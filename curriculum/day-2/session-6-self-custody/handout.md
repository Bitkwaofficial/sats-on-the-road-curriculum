<p align="center"><img src="../../../media/brand/sotr-logo.png" alt="Sats On The Road" width="300"></p>

# How Bitcoin works

A one-page plain-language explainer. You do not need to know all of this to use Bitcoin, just as you do not need to know how the internet works to send a message. But an ambassador should be able to explain the basics.

## A shared record, kept by many

Bitcoin is a ledger: a record of every transaction since 3 January 2009. The record is not kept by one bank. It is copied on thousands of computers around the world, called **nodes**. The record shows addresses and amounts, not names.

## A fixed supply

There will only ever be **21 million bitcoins**. No one can make more. One bitcoin divides into 100,000,000 small units called **satoshis**, or "sats", which is what we use day to day. Because the supply is fixed and public, no one can quietly print more and weaken it.

## New coins arrive slowly: mining and the halving

New bitcoins are released a little at a time to the people who secure the network, called **miners**. Miners use computers and electricity to compete to add the next block of transactions. The winner adds the block and earns new bitcoins plus the fees in that block. This is **proof of work**: real effort that makes cheating too expensive to be worth it.

About every four years, the reward for mining is cut in half. This is the **halving**. It keeps new supply slowing down on a schedule everyone can see in advance.

## Blocks and the blockchain

Transactions are gathered into a **block** roughly every ten minutes. Each block carries a fingerprint (a **hash**) of the block before it, linking them into a chain: the **blockchain**. Change one old detail and every later fingerprint breaks, so the other nodes reject it. That is what makes old transactions practically impossible to alter.

## The mempool: the waiting room

When you send a payment, it first goes to the **mempool**, a waiting room of unconfirmed transactions. Miners pick transactions from it, usually preferring those that include a higher fee. Once a transaction is placed in a block, it is **confirmed**. More blocks on top mean more confirmations and more certainty.

## UTXOs: like notes and coins in a wallet

Your balance is really made of chunks called **UTXOs** (unspent transaction outputs), like the different notes and coins in a purse. To pay someone, you spend whole chunks: part goes to them, and the leftover comes back to you as **change** in a new chunk. Keep your UTXOs private, because anyone who knows them can guess how much you hold.

## How keys fit in

To receive, you share a public address, like sharing an email address. To spend, you sign with your **private key**, which only you hold, like the password to that email. This is why the seed phrase (which rebuilds your private keys) must stay private and backed up.

---

*Condensed from the BitKwa Bitcoin Diploma, Chapter 5. Want more depth? See the BitKwa Bitcoin Diploma, the [PlanB Network](https://planb.network), and [My First Bitcoin](https://myfirstbitcoin.io).*
