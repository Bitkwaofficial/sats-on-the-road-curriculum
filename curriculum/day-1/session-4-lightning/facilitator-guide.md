<p align="center"><img src="../../../media/brand/sotr-logo.png" alt="Sats On The Road" width="300"></p>

# Facilitator Guide, Session 4: Lightning, paying and getting paid

**Duration:** 60 minutes
**Audience:** Day 1, everyone. Builds directly on the wallet from Session 3.
**Objectives:**
1. Learners can explain what the Lightning Network is and why it exists, in plain words.
2. Learners can describe the difference between an on-chain payment and a Lightning payment.
3. Learners can create and pay a Lightning invoice, and recognise a Lightning address.
4. Learners can send and receive sats over Lightning quickly and with low fees.

**Materials:**
- Each learner's phone and wallet from Session 3.
- Internet or data for the room.
- A small amount of sats in each wallet to practice with (from Session 3, or top up). [OWNER TO FILL: amount.]
- A screen or large phone view for the live demonstration, if available.
- Board or flip chart, printed handouts.

**Diploma source:** BitKwa Bitcoin Diploma, Chapter 4 (The Lightning Network).

---

## Minute by minute

### 0 to 6, Recap and the problem (6 min)
Recap Session 3: everyone has a wallet, a seed phrase on paper, and has sent and received sats.

Talking points:
- Sending sats directly on the main Bitcoin network is called an **on-chain** payment. It is very secure, but it can take about ten minutes to confirm and can cost more in fees.
- For small, everyday payments like a coffee or a taxi fare, we want something faster and cheaper.
- That is what the Lightning Network is for.

### 6 to 16, What Lightning is and why (10 min)
Keep it plain. Use the café tab picture from the Diploma.

Talking points:
- Lightning is a fast layer built on top of Bitcoin. Think of it as a quick lane for small payments.
- The café tab picture: imagine you will be in a café all day. Instead of paying for each cup one by one, you open a tab, pay as you go, and settle the final total at the end. Lightning works in a similar way, so payments are instant and cheap.
- Payments arrive in seconds and usually cost only a tiny fee.
- You can pay anyone on the network, not only people you know. The payment finds its way across the network to the receiver.
- Bitcoin is the strong base layer. Lightning is the fast layer on top. You still hold your own keys in a self-custodial Lightning wallet.

### 16 to 26, On-chain vs Lightning (10 min)
Draw a simple two-column comparison on the board.

Talking points:
- **On-chain:**
  - Very secure.
  - Takes about ten minutes to confirm.
  - Better for larger amounts and for savings.
- **Lightning:**
  - Instant, in seconds.
  - Very low fees.
  - Best for small, everyday payments.
- Honest note: Lightning is excellent for daily spending. For large savings, on-chain and secure backups still matter. Use the right tool for the job.

### 26 to 38, Invoices and Lightning addresses (12 min)
This is the practical core. Show it on a screen if you can.

Talking points:
- A **Lightning invoice** is a request for a payment. The receiver creates it, often as a QR code. It can include a set amount. Once paid, it is used up.
- To get paid: tap "Receive," choose Lightning, enter the amount if asked, and show the invoice or QR code.
- To pay: tap "Send," scan the invoice or QR code, check the amount, and confirm.
- A **Lightning address** looks like an email address, for example `name@example.com`. It is reusable, so people can pay you again and again without a new invoice each time. [OWNER TO FILL: whether your chosen wallet gives each learner a Lightning address.]
- Note for fundraising context: the Sats On The Road fundraiser can receive Lightning to the address `satsontheroadafrica@geyser.fund`. This is a real example of a Lightning address in use.

### 38 to 52, Live demonstration (14 min)
Run the activity in `exercise.md`: a live relay where sats pass from one learner to the next across the room, then a simple pay-the-facilitator demonstration. Keep it hands-on and lively.

### 52 to 57, When to use which, honest caveats (5 min)
Talking points:
- Use Lightning for small daily payments. Use on-chain for larger amounts and moving savings.
- Keep only everyday spending money in a phone wallet.
- Repeat the safety basics from Session 3: your seed phrase stays on paper, never photographed, never typed into a website.
- No financial advice, no predictions. The price can fall.

### 57 to 60, Questions (3 min)
Take a few questions. Preview Session 5, where learners buy something real from a merchant in sats.

---

## Common questions

**"Is Lightning still Bitcoin?"**
Yes. It is a fast layer built on top of Bitcoin. The sats are the same sats.

**"Why is it so much cheaper than on-chain?"**
Because payments happen on the fast layer and only settle to the main network when needed. Many small payments do not each need to be recorded on the main chain.

**"What is the difference between an invoice and a Lightning address?"**
An invoice is a one-time request, often for a set amount. A Lightning address is reusable, like an email address, so people can pay you many times.

**"Can a Lightning payment fail?"**
Sometimes a payment does not go through, for example if there is no good route or the wallet is low on receiving capacity. If it fails, the sats stay with the sender. Just try again or use a different amount.

**"Is Lightning as secure as on-chain?"**
On-chain is the most secure for large amounts. Lightning is very good for everyday spending. Match the tool to the amount.

See the shared glossary: `../../../translations/GLOSSARY.md`.
