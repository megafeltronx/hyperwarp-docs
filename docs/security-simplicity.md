---
title: Security & Simplicity
---

## Security & Simplicity

HyperWarp prioritizes security and simplicity by supporting a **limited set of whitelisted assets**:

* **NFTs**: Only **veKitten** is currently supported
* **Tokens**: All purchases are made using **Kitten**, the native token of the ecosystem

Restricting the tradable assets minimizes attack surface and ensures consistency in the marketplace logic.

## FAQ: Why only Kitten?

Pricing in a single native token like **Kitten** keeps things simple and predictable. Allowing listings in volatile tokens like **HYPE** introduces unnecessary complexity— keeping things consistent and easy to understand.

### Here's what can go wrong with volatile pricing:

Let's say:
* 1 **HYPE** = **$15**
* 1 **veKitten** = **$1**
* A seller lists **10,000 veKitten** for **500 HYPE**

At the time of listing, this makes sense:
> 500 HYPE × $15 = $7,500
> 10,000 veKitten × $1 = $10,000
> → Buyer is getting a 25% discount

But now imagine HYPE drops to $10:
> 500 HYPE × $10 = $5,000
> → The same listing now offers a **50% discount** instead of 25%

Or HYPE pumps to $20:
> 500 HYPE × $20 = $10,000
> → No discount at all — maybe even overpriced

*By listing everything in **Kitten**, the price is stable within the protocol. No guessing. No recalculating discounts based on token volatility. Buyers and sellers stay aligned.*
