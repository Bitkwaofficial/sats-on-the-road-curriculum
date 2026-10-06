<p align="center"><img src="../../../media/brand/sotr-logo.png" alt="Sats On The Road" width="300"></p>

# Facilitator Guide, Session 3: Hands-on wallet setup, seed phrase, first sats

**Duration:** 90 minutes (the core of Day 1)
**Audience:** Day 1, everyone. This is the hands-on heart of the day. Everyone leaves with a working wallet.
**Objectives:**
1. Learners can explain the difference between a custodial and a self-custodial wallet.
2. Learners can install a wallet and create a new one on their own phone.
3. Learners can write down and protect a seed phrase, and explain why it must never be photographed or typed into a website.
4. Learners can receive their first sats and send sats to another person.

**Materials:**
- Each learner needs a phone. For smartphones, a wallet app. For feature phones, a USSD option like Machankura may be used. [CONFIRM: which options work in this country.]
- A reliable internet connection or data for the room.
- One pen and one sheet or card per learner for writing the seed phrase. Plain paper is fine.
- A small amount of sats to send to each learner for their first receive. [CONFIRM: funding source and amount per learner.]
- Board or flip chart.
- Printed handouts and the checklist in `exercise.md`.

**Diploma source:** BitKwa Bitcoin Diploma, Chapter 3 (Bitcoin: introduction and how to use it), the wallet and transactions sections.

---

## Before you start
- Decide the teaching wallet for your country ahead of time: `[primary wallet, e.g. Blink or Phoenix]`. Teach one wallet to the whole room so everyone follows the same screens.
- Keep instructions wallet-agnostic in your words, so learners can repeat them with any good wallet later.
- Have a helper or two ready to move around the room. Some learners will be slower, and that is fine.

---

## Minute by minute

### 0 to 8, What a wallet really is (8 min)
Talking points:
- A Bitcoin wallet does not hold coins inside it. The coins live on the network. The wallet holds your **keys**, which prove the coins are yours.
- Think of two parts:
  - A **receive address**, like your email address. You share it so people can send you sats.
  - A **private key and seed phrase**, like the password to your email. You never share this. Whoever has it controls the money.
- Repeat the saying: "Not your keys, not your coins."

### 8 to 20, Custodial vs self-custodial (12 min)
Draw a simple two-column table on the board.

Talking points:
- **Custodial wallet:** a company holds your keys for you. It is easy to start, and they can help you recover access. But they control your money. They can freeze it, and if they fail, your sats are at risk. It is like money in someone else's safe.
- **Self-custodial wallet:** you hold your own keys. No one can freeze or confiscate your sats, and no one needs to approve your payments. But you carry full responsibility. If you lose your seed phrase, no one can recover it for you.
- Be honest: a custodial wallet can be fine for small amounts and for a first taste. For holding savings, self-custody is the goal.
- Name real options neutrally, without claiming which is best or legal in this country:
  - **Blink:** easy to start, good for a first experience with Lightning. [CONFIRM availability.]
  - **Phoenix:** self-custodial Lightning wallet. [CONFIRM availability.]
  - **Machankura:** lets you use Lightning over USSD on a basic feature phone, with no smartphone needed. [CONFIRM availability.]
  - Hardware or seed-phrase wallets: for savings, mentioned generally.
- Tell the room which wallet you will all use today and why.

### 20 to 30, Choosing a wallet (10 min)
Talking points, framed as what to look for:
- **Self-custody:** do you hold your own keys?
- **Open source:** the code is open for the community to check.
- **Ease of use:** simple screens, especially for beginners.
- **Good reputation:** known and trusted, not a random app.
- Remind learners: never download a wallet from a link someone sends you. Use the official app store and check the maker's name. [CONFIRM: exact app name and publisher for your chosen wallet.]

### 30 to 45, Install and create a wallet (15 min)
Walk the room through it together, step by step. Keep pace so no one is left behind.

1. Open the App Store (iPhone) or Google Play Store (Android).
2. Search for `[primary wallet]` and check the publisher name carefully.
3. Install the app.
4. Open it and choose "Create a new wallet" (wording varies by app).
5. Let the app create your keys. Your first receive address is made for you automatically.
6. If the app offers an extra passcode or PIN, set one. This protects the app on your phone.

Facilitator note: for feature-phone learners using USSD, follow the provider's dial-in steps instead. [CONFIRM: the exact USSD steps for your country.]

### 45 to 60, Write down the seed phrase (15 min, the most important part)
Slow right down here. This is the single most important skill of the day.

Talking points, say them clearly and more than once:
- The app will show you a list of words, usually 12 or 24. This is your **seed phrase**, also called a recovery phrase.
- These words are the master key to all your sats. Anyone who gets them can take everything.
- **Write them on paper, by hand, in the exact order shown.** Number each word.
- **Never take a photo of them.** Photos can sync to the cloud and be stolen.
- **Never type them into any website.** No real wallet or support person will ever ask for your seed phrase. Anyone who asks is trying to rob you.
- **Never store them in notes, messages, or email.**
- Keep the paper somewhere safe and dry that only you can reach. For larger savings, people keep a second copy in a separate safe place.
- If you lose both your phone and your seed phrase, your sats are gone for good. No one can recover them.

Then have each learner:
1. Copy the words onto their paper, numbered and in order.
2. Confirm the words in the app when it asks (the app checks you wrote them correctly).
3. Fold the paper and keep it on their person for now.

Walk the room and check that everyone has actually written the words down before moving on. Do not rush this.

### 60 to 72, Receive your first sats (12 min)
Talking points:
- To receive, you share your address or a QR code.
- In the app, tap "Receive." It shows a QR code and an address.
- Explain: your address is safe to share. It is like your email address. Sharing it does not give anyone control of your money.
- Send each learner a small amount of sats to their displayed code. [CONFIRM: amount per learner and funding source.]
- Have them watch the balance update. Celebrate the first sats calmly and warmly.
- Note: a Lightning payment usually arrives in seconds. We cover Lightning properly in Session 4.

### 72 to 84, Send sats (12 min)
Pair learners up so they can send to each other.

Talking points and steps:
1. Tap "Send."
2. Scan the other person's QR code, or paste their address or invoice.
3. Enter the amount in sats.
4. **Double-check the amount and the recipient before confirming.** Payments cannot be reversed.
5. Confirm and send. Watch it arrive on the other phone.
- Have each pair send a small amount back and forth once or twice.
- Stress again: always check the amount and the recipient first. There is no undo.

### 84 to 90, Wrap and common mistakes (6 min)
Recap the three things that matter most:
1. You hold your own keys. Not your keys, not your coins.
2. Your seed phrase is written on paper, never photographed, never typed into a website.
3. You can receive and send sats, and you always check before you confirm.

Point to Session 4, where we go deeper into Lightning for fast, cheap payments.

---

## Common questions

**"I lost my phone. Are my sats gone?"**
If you have your seed phrase written down, you can restore your wallet on a new phone and your sats are safe. That is exactly why the seed phrase matters.

**"Someone online says they are support and need my seed phrase to help me. Should I give it?"**
Never. No real support ever needs your seed phrase. Anyone who asks for it is trying to steal from you.

**"Can I just take a quick photo of the words, to be safe?"**
No. Photos can sync to the cloud and be stolen. Paper only, by hand.

**"What if I only have a basic phone?"**
There are options that work over USSD without a smartphone, such as Machankura. [CONFIRM availability in this country.]

**"Is it safe to share my receive address?"**
Yes. Your address is like your email address. Sharing it lets people pay you. It does not give them any control of your money.

**"How much should I keep in a phone wallet?"**
Keep everyday spending money on your phone. Keep larger savings in a more secure setup, which Day 2 covers for ambassadors.

See the shared glossary: `../../../translations/GLOSSARY.md`.
