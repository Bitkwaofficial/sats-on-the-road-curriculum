<p align="center"><img src="../media/brand/sotr-logo.png" alt="Sats On The Road" width="300"></p>

# Stipend and verification

This page explains how we confirm an ambassador's work and pay the stipend, in a way that respects the privacy of the people they teach and onboard.

## The core idea: count events, not people

We never ask for or store the names, phone numbers, or ID of the learners or merchants an ambassador works with. We confirm that **a thing happened**, not **who it happened to**. We count events, we do not build a list of people.

This protects ordinary people, and it especially protects activists, journalists, and traders who may have good reasons not to be on any list. It also keeps the ambassador's job simple: they report numbers and light proof, not personal data.

## What we verify

We verify two kinds of events:

- A **verified onboarding**: a person was taught and left able to send and receive sats on their own phone.
- A **verified merchant**: a shop, stall, or service that now accepts Bitcoin.

## How an event is verified (privacy-preserving proof)

An ambassador confirms an event with **one** of these, and never with a person's name or ID:

- **A signed confirmation from the ambassador.** The ambassador signs (digitally or on paper) a short statement: "On this date I onboarded N people and M merchants in this town." They are putting their name and reputation behind the count. No learner names appear.
- **A merchant's own confirmation message.** A short note or voice message from the merchant saying they now accept Bitcoin, sent in their own words. The merchant chooses to send this. We store the confirmation, not an identity file.
- **A photo of the signage, with consent.** A picture of a "Bitcoin accepted here" sticker or sign at the stall, taken with the merchant's agreement. Faces are not required and should be avoided unless the person clearly agrees to appear.
- **A hashed receipt or reference.** Where there is a natural reference (for example a payment reference), the ambassador can record a one-way **hash** of it rather than the raw detail. The hash lets us check the same event is not counted twice, without ever revealing who was involved.

Any one of these is enough. The goal is honest proof that is light to collect and safe to keep.

### What we never collect

- No learner names, phone numbers, wallet addresses, or ID numbers in any central list.
- No photos of people without their clear, specific consent.
- No central database that could be used to identify who uses Bitcoin in a town.

If a merchant or learner later asks to be left out of any photo or note, we remove it, no questions asked.

## The amounts

- Per verified onboarding: `[CONFIRM: amount in sats]`
- Per verified merchant onboarded: `[CONFIRM: amount in sats]`
- Any monthly base or cap: `[CONFIRM: amounts]`

All amounts are placeholders until confirmed. They may be reviewed over time.

## When payment happens

Payment follows the monthly rhythm, not each single event:

1. The ambassador submits the [monthly report](monthly-report-template.md) for the town.
2. They join the monthly call `[CONFIRM: call date and cadence]`.
3. A reviewer checks the report and the light proof against the counts.
4. Once the report is approved, the stipend for that month's verified events is paid in sats `[CONFIRM: payout timing after approval]`.

No report, no payment for that month. A late report can be picked up the next month.

## How disputes are handled

Mistakes and disagreements happen. Here is how we settle them.

- **If a count is questioned**, we look at the proof the ambassador already provided. The signed confirmation, the merchant message, or the photo settles most cases.
- **If proof is missing for some events**, only the unproven events are held back. The rest are still paid. The ambassador can add proof later and have those events counted in a following month.
- **If two ambassadors claim the same merchant or onboarding**, the hashed reference (where one exists) shows whether it is a duplicate. If there is no reference, a reviewer talks to both and the merchant's own confirmation decides it.
- **If an ambassador disagrees with a decision**, they can raise it on the monthly call or with `[CONFIRM: dispute contact]`. A second reviewer takes a fresh look.
- **Honest errors are not penalised.** We assume good faith. Repeated or deliberate false counts end the stipend arrangement.

Throughout, the rule holds: we resolve disputes using event proof, never by collecting the personal details of the people involved.

## A note on money

The stipend is a thank-you for real teaching work, not an investment return. Nothing here is financial advice, and Bitcoin's price can fall.
