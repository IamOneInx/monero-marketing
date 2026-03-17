---
layout: fr
title: "MoneroPay + Monero Marketing Site — making XMR usable at everyday merchants"
author: IamOneInx
date: 2026-03-16
amount: 65
milestones:
  - name: Marketing site live + MoneroPay MVP
    funds: 30
    done:
    status: unfinished
  - name: MoneroPay merchant mode + mobile polish
    funds: 20
    done:
    status: unfinished
  - name: Outreach campaign + merchant onboarding guide
    funds: 15
    done:
    status: unfinished
paymentid:
---

## What

Two deliverables that address Monero's biggest adoption gap: **discoverability** and **point-of-sale usability**.

### 1. Monero Marketing Site

A plain-language website explaining Monero to people who have never heard of it — written like Cash App explains itself, not like a whitepaper. No jargon. No crypto maximalism. Just honest, human answers to "what is this and why should I care."

**Live demo:** https://monero-site-3hq.pages.dev (permanent domain TBD)

Key sections:
- Why financial privacy matters (without framing it as criminal)
- How Monero compares to banks, Venmo, wire transfers
- How to get started in under 5 minutes
- MoneroPay — how to use XMR at local merchants

Open source, MIT licensed, free for any community member to fork, translate, or improve.

### 2. MoneroPay — QR-based point-of-sale PWA

A mobile-first web app (Progressive Web App, no download required) that solves the "coffee shop problem" — using XMR for everyday in-person purchases.

**Merchant flow:**
1. Open moneropay.app on phone
2. Enter your XMR address once (saved locally)
3. Type in the amount (USD, EUR, or XMR)
4. Show the QR to the customer

**Customer flow:**
1. Open camera or any XMR wallet
2. Scan the QR
3. Confirm payment
4. Done in ~2 minutes

**Technical approach:**
- Pure PWA — works on any phone browser, no app store
- No backend, no server, no accounts
- Live XMR/USD price via CoinGecko API (free tier)
- Payment detection via customer's own wallet or a configurable public node
- Subaddress generation so every transaction gets a unique address (privacy preserved)
- Open source, MIT licensed

**What it is NOT:** a custodial service, an exchange, a wallet. It is purely a payment request generator + QR display tool. The money goes directly from buyer's wallet to merchant's wallet. We touch nothing.

---

## Why this matters

Monero has the best privacy technology of any cryptocurrency. It is arguably the only coin that actually delivers on the promise of digital cash. And yet:

- Most people have never heard of it
- Those who have associate it with dark markets (due to media framing we have not countered)
- There is no simple "pay at a store" tool for everyday use
- The existing wallets are excellent but targeted at users who already know what they are doing

Bitcoin had this same problem from 2011–2015. The community built BitPay, Coinbase, and a thousand explainer sites. Those tools drove adoption. Monero needs the same — but with the privacy ethos intact.

The marketing site and MoneroPay are not about compromising Monero's values. They are about communicating those values in language that normal people understand, and giving them a tool to act on it immediately.

---

## Who

Community developer with working shipped code:
- GitHub: https://github.com/IamOneInx
- Monero GUI i2p integration PR: https://github.com/monero-project/monero-gui/pull/4574
- p2pool-splitter utility: https://github.com/IamOneInx/p2pool-splitter

---

## Milestones

### Milestone 1 — 30 XMR
**Marketing site + MoneroPay MVP live**

Deliverables:
- Marketing site deployed at public domain, open source on GitHub
- MoneroPay MVP: merchant QR generation, live XMR/USD price, basic payment detection
- Mobile-tested on iOS and Android
- README and self-hosting guide

Timeline: 3 weeks from funding

### Milestone 2 — 20 XMR
**MoneroPay merchant mode + polish**

Deliverables:
- Unique subaddress per transaction (via monero-wallet-rpc or public node)
- Transaction history (local storage, never leaves device)
- USD/EUR/GBP amount input with live conversion
- Print-friendly QR for physical display at counter
- Accessibility audit + dark mode

Timeline: 3 weeks after M1

### Milestone 3 — 15 XMR
**Outreach + merchant onboarding**

Deliverables:
- "Accept Monero at your business" guide (PDF + web)
- Outreach to 50 small businesses in crypto-friendly cities
- r/Monero, Twitter/X, and Nostr campaign with the marketing site
- Translation starter kit (i18n structure, EN complete, template for other langs)
- Video walkthrough (< 3 min) showing the full merchant + customer flow

Timeline: 4 weeks after M2

---

## Total: 65 XMR

Both deliverables are MIT licensed. Everything built is owned by the Monero community.

---

## Expiry

6 months from funding date.
