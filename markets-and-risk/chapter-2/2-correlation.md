# Correlation

## One-line intuition
Correlation answers:
> “Do two things tend to move together?”

---

## Simple interpretation
- Correlation ≈ +1 → move together
- Correlation ≈ −1 → move opposite
- Correlation ≈ 0 → independent

In practice, correlation is **context-dependent**.

---

## Why correlation matters for risk
If two positions:
- Move together in bad times

Then:
- Losses stack
- Exposure is understated
- Margin is insufficient

Correlation determines whether diversification actually works.

---

## Calm markets vs stressed markets
In normal times:
- Many assets appear weakly correlated

In stress:
- Fear synchronizes behavior
- Correlations increase
- Assets move together

This shift is the real danger.

---

## Correlation is not a constant
A common modeling mistake:
> “Correlation is stable.”

Reality:
- Correlation depends on regime
- Calm ≠ crisis

Risk systems must assume correlation increases under stress.

---

## Engineering analogy
Many microservices:
- Look independent
- Share the same database

Normal load → fine  
Outage → everything fails

Correlation was hidden.

---

## Common misunderstandings
❌ Correlation = causation  
❌ Historical correlation = future safety  

✅ Correlation is a stress-time phenomenon

---

## How this connects to other concepts
Correlation explains:
- Why dispersion fails
- Why stress losses stack
- Why worst gap feels unfair
