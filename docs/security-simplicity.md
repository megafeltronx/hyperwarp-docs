---
title: Security & Simplicity
---

## Security & Simplicity

HyperWarp prioritizes security and simplicity by supporting a **limited set of whitelisted assets**:

* **NFTs**: Only **veKitten** is currently supported
* **Tokens**: All purchases are made using **Kitten**, the native token of the ecosystem

Restricting the tradable assets minimizes attack surface and ensures consistency in the marketplace logic.

### Here's what can go wrong with volatile pricing:

Let’s say:  
- 1 **HYPE** = **$40**  
- 1 **veKitten** = **$1**  
- A seller lists **10,000 veKitten** for **250 HYPE**

At the time of listing, this makes sense:  
> 250 HYPE × $40 = $10,000  
> 10,000 veKitten × $1 = $10,000  
> → A fair deal

But now imagine HYPE drops to $20:  
> 250 HYPE × $20 = $5,000  
> → The same listing now offers a **50% discount**

Or HYPE pumps to $60:  
> 250 HYPE × $60 = $15,000  
> → Buyer overpays by 50% — maybe without realizing it

---

### Comparison Table

| Pricing Token | Market Movement | Buyer Pays (USD) | Outcome            |
|---------------|------------------|------------------|---------------------|
| **Kitten**    | Any              | $10,000          | Stable / Predictable |
| **HYPE**      | Drops to $20     | $5,000           | Buyer gets 50% discount |
| **HYPE**      | Rises to $60     | $15,000          | Buyer overpays by 50% |

---

*By listing everything in **Kitten**, the price is stable within the protocol, both buyers and sellers know exactly what to expect — no surprise discounts, no accidental overpays.*


