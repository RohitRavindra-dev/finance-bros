# Signals and Venues (HFT Context)

## One-line intuition
- **Signals** decide *when* to trade
- **Venues** decide *where* the trade happens

They are hidden sources of correlation.

---

## Signals (what drives trades)
A signal is:
> A rule or pattern that triggers buy/sell decisions

Examples:
- Price mean reversion
- Order book imbalance
- Cross-market movements

Many positions may be driven by the **same signal**.

---

## Why signals matter for risk
If one signal fails:
- Many positions unwind together
- Micro dispersion collapses

Signal concentration = hidden correlation.

---

## Venues (where trades execute)
Venues include:
- Exchanges
- Dark pools
- Alternative trading systems

Each venue has:
- Different liquidity
- Different latency
- Different failure modes

---

## Why venues matter in stress
In stress:
- Some venues halt
- Some dry up
- Some become unusable

Positions that looked diversified:
- Across assets
- But on the same venue

→ Gap together.

---

## Risk takeaway
Signals and venues create:
- Structural correlation
- Liquidity clustering

Risk systems must account for this.

---

## How this connects to other concepts
Signals and venues explain:
- Why HFT portfolios gap together
- Why correlation spikes
- Why worst gap feels sudden
