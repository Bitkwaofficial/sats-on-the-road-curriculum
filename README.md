<p align="center">
  <img src="./media/brand/sotr-logo.png" alt="Sats On The Road" width="220"/>
</p>

<h1 align="center">Sats On The Road, Field Curriculum</h1>

<p align="center"><em>Driving Bitcoin across the African continent.</em></p>

<p align="center">
  <a href="https://satsontheroad.africa">Website</a> ·
  <a href="./curriculum">Curriculum</a> ·
  <a href="./playbook/ambassador-playbook.md">Ambassador Playbook</a> ·
  <a href="./merchant-kit">Merchant Kit</a> ·
  <a href="./translations">Translations</a>
</p>

---

**Sats On The Road** is a grassroots Bitcoin road trip across Africa, run by
BitKwa. A wrapped vehicle drives from town to town teaching people to hold their
own Bitcoin, use it over the Lightning Network, and spend it with real merchants.
So far the trip has covered roughly **[CONFIRM: km] km** across
**[CONFIRM: number] countries**, onboarded **[CONFIRM: number] people** and
**[CONFIRM: number] merchants** (see the [live dashboard](./data/dashboard.csv)).
**Phase 1A** takes the trip through **[CONFIRM: Ghana, Benin, Togo, Burkina Faso,
Côte d'Ivoire, Liberia, Sierra Leone]** between **[CONFIRM: start month]** and
**[CONFIRM: end month] 2026**.

This repository is the **teaching engine** of the trip: a **two-day course** that
a local educator can run in their own town, plus the playbook, merchant kit,
safety material and translations that make each stop work. It is condensed from
the [BitKwa Bitcoin Diploma](https://github.com/Bitkwa/bitkwa-bitcoin-diploma)
(see [`ATTRIBUTION.md`](./ATTRIBUTION.md)).

## The two days at a glance

| Day | Session | Time | For |
|----:|---------|-----:|-----|
| **1** | 1. Money and why ours fails | 45 min | Everyone |
| **1** | 2. What Bitcoin is, in plain words | 45 min | Everyone |
| **1** | 3. Hands-on wallet setup, seed phrase, first sats | 90 min | Everyone |
| **1** | 4. Lightning: paying and getting paid | 60 min | Everyone |
| **1** | 5. Market practice: buy something real in sats | 60 min | Everyone |
| **2** | 6. Self-custody deeper: backups, recovery, what not to do | 60 min | Ambassadors |
| **2** | 7. Bitcoin for activists and journalists: privacy and opsec | 90 min | Ambassadors |
| **2** | 8. How to teach this | 60 min | Ambassadors |
| **2** | 9. Onboarding a merchant, step by step | 60 min | Ambassadors |
| **2** | 10. The ambassador commitment | 45 min | Ambassadors |

Day 1 is open to anyone. Day 2 is for the people who will keep the work going
after the vehicle leaves. Short on time? Run the
[one-session version](./curriculum/one-session) (the 2-hour market or school
session we ran in Lomé).

## Who this is for

- **Local educators** who will be trained in two days and become **ambassadors**:
  they teach their communities and onboard merchants after the trip moves on.
- **The people they teach**: traders, students, workers and community members who
  want to hold and use Bitcoin, and activists and journalists who need to receive
  support safely.

No prior Bitcoin knowledge is assumed. A basic smartphone is enough for most of
the course; feature-phone options are included.

## How to run this in your own town

1. **Find a country lead or partner community** and read the
   [country lead guide](./playbook/country-lead-guide.md). Pick a venue, a date,
   and a nearby market with willing merchants.
2. **Localise it**: set the local currency and examples, choose the teaching
   wallet, and translate the Day 1 handouts, merchant sign and consent form
   (see [translations](./translations)).
3. **Gather materials**: phones or a feature-phone option, printed handouts, the
   [merchant kit](./merchant-kit), and a small amount of sats to seed first
   transactions.
4. **Teach Day 1** for everyone, then **Day 2** for your future ambassadors.
   Each session has a [facilitator guide](./curriculum), slides, a handout, an
   exercise and a short quiz.
5. **Report back**: fill in the [monthly report](./playbook/monthly-report-template.md)
   and add a row to the [dashboard](./data/dashboard.csv) so the next town learns
   from yours.

## How to translate

1. Open [`translations/`](./translations) and read
   [`TRANSLATION-GUIDE.md`](./translations/TRANSLATION-GUIDE.md).
2. Start with the [glossary](./translations/GLOSSARY.md), then the Day 1 handouts,
   the merchant sign and the consent form.
3. Submit a pull request (you can do it from a phone), or open a
   ["Offer a translation"](./.github/ISSUE_TEMPLATE) issue and we will help.

## What is in this repository

| Folder | What it holds |
|--------|---------------|
| [`curriculum/`](./curriculum) | The two days, session by session, plus the one-session version |
| [`playbook/`](./playbook) | Ambassador selection, stipend and verification, reporting, country lead guide, code of conduct |
| [`merchant-kit/`](./merchant-kit) | Printable "Bitcoin accepted here" sign, QR stand, merchant guide, cash-out options |
| [`safety/`](./safety) | Opsec for activists and journalists, team safety protocol, consent forms |
| [`translations/`](./translations) | Glossary and one folder per language |
| [`data/`](./data) | The dashboard, pilot lessons, and per-country reports |
| [`media/`](./media) | Footage archive, episode templates, brand files, and how to credit them |

## Links

- Website: https://satsontheroad.africa
- Upstream curriculum: https://github.com/Bitkwa/bitkwa-bitcoin-diploma
- Footage archive: [CONFIRM: Internet Archive URL]
- Live dashboard: https://satsontheroad.africa (and [`data/dashboard.csv`](./data/dashboard.csv))
- Soundtrack: *Sats On The Road Vol 1* on Audiomack

## License

Code and scaffolding: [MIT](./LICENSE). Teaching material, images, video and
audio: [CC BY 4.0](./LICENSE-CONTENT.md). Please keep the credit line when you
reuse or adapt. See [`ATTRIBUTION.md`](./ATTRIBUTION.md).
