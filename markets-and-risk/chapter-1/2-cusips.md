# CUSIP and Identifiers

## One-line intuition
A **CUSIP** is a unique ID for a financial instrument.

Just like:
- Aadhaar for people
- SKU for products
- UUID for objects

---

## Why names are not enough
“Apple stock” is ambiguous.

There are:
- Different share classes
- Different markets
- Different instruments

Banks don’t trust names.
They trust **IDs**.

---

## Financial meaning
A CUSIP uniquely defines:
- Issuer
- Instrument type
- Specific security

So instead of:
> “Apple stock”

Systems store:
> “CUSIP 037833100”

---

## How positions really look in systems

| Account | CUSIP | Quantity | Side |
|------|------|---------|------|
| A123 | 037833100 | 100,000 | Long |

This is the atomic unit of risk.

---

## Why CUSIPs matter for risk
Risk is calculated:
- Per CUSIP
- Aggregated upward

If a CUSIP has bad data:
- Exposure explodes
- Gap risk inflates
- Margin spikes

---

## Common misunderstandings
❌ CUSIP is just metadata  
❌ CUSIP doesn’t matter to risk  

✅ CUSIP is the **anchor of all calculations**

---

## How this connects to other concepts
CUSIPs are used in:
- Exposure calculation
- Stress scenarios
- Worst-gap attribution
