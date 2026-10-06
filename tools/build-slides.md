<p align="center"><img src="../media/brand/sotr-logo.png" alt="Sats On The Road" width="300"></p>

# Building the slides

Every session's slides are written as **`slides.md`** in
[Marp](https://marp.app) markdown. Markdown slides are easy to read, easy to
translate, and version-controlled, so anyone can fix a typo or translate a deck
with a pull request. You render them to PDF, PowerPoint or HTML only when you need
to project them.

## Why markdown instead of a .pptx file

- Translators and reviewers can edit one plain-text file, from a phone if needed.
- Changes show up clearly in pull requests (unlike binary slide files).
- One source renders to PDF (for projecting or printing), PPTX (to edit in
  PowerPoint), or HTML (to present in a browser).

## Render one deck

You need [Node.js](https://nodejs.org). No install step is required; `npx` fetches
Marp on first use.

```bash
# PDF (best for projecting or printing)
npx @marp-team/marp-cli@latest curriculum/day-1/session-1-money/slides.md --pdf

# PowerPoint (to edit in PowerPoint or Google Slides)
npx @marp-team/marp-cli@latest curriculum/day-1/session-1-money/slides.md --pptx

# HTML (to present from a browser, offline)
npx @marp-team/marp-cli@latest curriculum/day-1/session-1-money/slides.md --html
```

The output file is written next to the `slides.md` (for example `slides.pdf`).

## Render every deck at once

From the repository root:

```bash
# PDF for every slides.md in the repo
find . -name "slides.md" -print0 | xargs -0 -I {} npx @marp-team/marp-cli@latest {} --pdf
```

On Windows PowerShell:

```powershell
Get-ChildItem -Recurse -Filter slides.md | ForEach-Object {
  npx @marp-team/marp-cli@latest $_.FullName --pdf
}
```

## Present live

```bash
npx @marp-team/marp-cli@latest curriculum/day-1/session-1-money/slides.md --preview
```

## House style for slides

- Keep slides sparse: a title and a few bullets. The depth lives in the
  facilitator guide, not on the slide.
- Put teacher notes in an HTML comment: `<!-- notes: ... -->`.
- Follow the project [style rules](../CONTRIBUTING.md): no em-dashes, and only the
  functional symbols ₿, ⚡ and ♪.
- **A branded, ready-to-present `slides.pptx` already ships in every session
  folder** (cream canvas, orange accents, the logo, real trip photography on the
  title slide). Open and edit it in PowerPoint or Google Slides, translate it, or
  project it as-is. The `slides.md` here is the plain-text source for diffs and
  translation; regenerate the PPTX from it when the content changes.
- Each `slides.md` also carries the brand: the logo is on the title slide and as a
  small footer on every slide, set with the `footer:` front-matter pointing at the
  logo in `media/brand/`. Keep that when you edit a deck.
- To theme the decks further with SOTR colours (orange #F7931A, near-black #0D0D0D,
  cream #F6EFE3), add a Marp theme CSS and reference it in the front-matter.

## A note on committing PDFs

Rendered `slides.pdf` files are optional and can be large. You can either commit
them for people without Node, or keep only the `slides.md` source and render on
demand. If you commit them, run the "render every deck" command before tagging a
release.
