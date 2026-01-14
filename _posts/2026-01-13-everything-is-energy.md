---
layout: post
title: "Everything Is Energy"
date: 2026-01-13
---

# Everything Is Energy
### (Including the Parts You Already Paid For)

*Last updated: January 2026*

Most discussions about energy stop at **usage**.
This post is about **accounting**.

Specifically: the difference between **embedded energy** and **amortized energy**, with numbers.

All calculations below are *order-of-magnitude*.
That is intentional. If the conclusion survives rough math, it survives precision.

---

## 1. Toast (direct, visible energy)

**Device:** 800–1,200 W toaster
**Time:** ~90 seconds

**Calculation**

Energy = Power × Time
= 1000 W × 90 s
= 90,000 J

Convert to kWh:
90,000 J ÷ 3,600,000 = **0.025 kWh**

![Toast energy visualization](/epistevid/assets/images/energy-toast.svg)

**Interpretation**
- Cost at \$0.15/kWh ≈ **\$0.004**
- 100% operational energy
- No ambiguity

This is the reference case: **energy you notice**.

---

## 2. Hot water (energy + timing)

**Scenario:** 10-minute shower
**Flow:** 9.5 L/min
**Temperature rise (ΔT):** 25 °C

**Calculation**

Mass of water:
9.5 L/min × 10 min ≈ 95 kg

Thermal energy:
Q = m × c × ΔT
= 95 × 4.18 × 25
≈ **9,930 kJ**

Convert to kWh:
9,930 kJ ÷ 3,600 = **2.76 kWh**

![Hot water energy visualization](/epistevid/assets/images/energy-shower.svg)

**Interpretation**
- Two orders of magnitude more than toast
- Still mostly operational
- Already sensitive to *when* energy is available

---

## 3. Refrigerator (amortization begins)

**Typical modern refrigerator**
- ~400 kWh/year
- Lifetime: 12–15 years

**Operational energy**
- 400 × 15 ≈ **6,000 kWh**

**Embedded (manufacturing) energy**
Life-cycle assessments estimate:
- **1,500–2,000 kWh** per unit
  (steel, plastics, compressor, transport)

**Ratio**
- Embedded ≈ **25–30%** of lifetime energy

![Refrigerator energy breakdown](/epistevid/assets/images/energy-fridge.svg)

**Interpretation**
You are already paying for past energy.
Efficiency labels mostly describe the *tail*, not the *head*.

---

## 4. Consumer electronics (energy moves upstream)

### Laptop

**Embedded energy**
- ~300–600 kWh
  (semiconductors dominate)

**Operational energy**
- ~60 W average
- 4 h/day → ~90 kWh/year
- 5 years → ~450 kWh

**Result**
Embedded energy ≈ operational energy.

![Laptop energy breakdown](/epistevid/assets/images/energy-laptop.svg)

---

### Smartphone

**Embedded energy**
- ~70–100 kWh

**Operational energy**
- ~5 kWh/year
- 2 years → ~10 kWh

**Result**
Embedded energy ≈ **85–90%** of total.

![Smartphone energy breakdown](/epistevid/assets/images/energy-phone.svg)

Calling phones "low-power devices" is an accounting illusion.

---

## 5. Electric vehicles (where intuition fails)

**Manufacturing energy**
Multiple LCAs converge on:
- **50–70 MWh** per vehicle
  (battery + aluminum + steel)

**Operational energy**
- ~18 kWh / 100 km
- 15,000 km/year → ~2,700 kWh/year
- 15 years → ~40 MWh

**Ratio**
Embedded energy ≈ lifetime operational energy.

![EV energy breakdown](/epistevid/assets/images/energy-ev.svg)

Debates that ignore either side are incomplete.

---

## The aggregation (the gotcha)

Across categories, a pattern appears:

| Category | Embedded Energy Share |
|--------|----------------------|
| Heating appliances | ~5–15% |
| Refrigeration | ~25–35% |
| Laptops | ~40–60% |
| Smartphones | ~85–90% |
| Electric vehicles | ~45–55% |

![Summary of embedded energy by category](/epistevid/assets/images/energy-summary.svg)

As operational energy gets cheaper:
- Replacement cycles shorten
- Embedded energy dominates
- Total system energy may increase, not decrease

This is **Jevons Paradox**, expressed through supply chains.

---

## The compression

There are only two energy buckets:

1. **Embedded energy**
   Paid once, upstream, invisible

2. **Amortized energy**
   Paid slowly, visible on bills

Most public debate tracks only the second.
Physics tracks both.

---

## Quiet conclusion

If energy generation keeps getting cheaper,
efficiency alone will not save energy.

Only **longer lifetimes, higher utilization, and better temporal coordination** will.

The rest is just moving joules around on a calendar.

---

## References (non-exhaustive)

- International Energy Agency (IEA), *Global Energy Outlook*, *Global EV Outlook*
- IVL Swedish Environmental Research Institute, EV life-cycle assessments
- Malmodin & Lundén (2018), *Journal of Industrial Ecology* – ICT life-cycle energy
- European Commission JRC, Ecodesign Preparatory Studies
- Ecoinvent Life Cycle Inventory Database (summaries)
- ASHRAE Residential Energy Handbooks

*All numerical values are order-of-magnitude estimates intended for system-level reasoning, not device-specific claims.*
