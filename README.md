# Conjoint Analysis — Product Feature Valuation

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-Product%20Analytics%20%7C%20Consumer%20Research-8A2BE2?style=flat)
![Method](https://img.shields.io/badge/Method-Conjoint%20Analysis-0078D4?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-2ea44f?style=flat)

## Overview

Conjoint analysis is the gold standard for quantifying how consumers make trade-offs between product features. This project applies conjoint methodology to two business cases — **Rhiney Custom Apparel** and **Natural Soap Company** — to determine which product attributes drive purchase decisions and how to design optimal product offerings.

The same technique is used by Apple to decide which iPhone features justify premium pricing, by Netflix to test subscription tier design, and by healthcare companies to optimize drug formulary options.

---

## Business Cases

### Case 1 — Rhiney Custom Apparel
**Question:** Which product customization features matter most to customers, and how should Rhiney price and configure their product lineup?

**Attributes analyzed:**
- Customization options (fabric, fit, color)
- Price tiers
- Delivery time
- Brand/label visibility

### Case 2 — Natural Soap Company (Exam)
**Question:** Among scent, ingredients, packaging, and price — what do soap buyers value most, and what is the optimal product configuration?

---

## Methodology

**Step 1 — Profile Design**
Constructed product profiles (combinations of attribute levels) using orthogonal design to minimize correlation between attributes.

**Step 2 — Preference Data Collection**
Used simulated customer preference rankings across product profiles.

**Step 3 — Utility Estimation (Part-Worth Analysis)**
- Ran regression of preference scores on attribute dummies
- Extracted **part-worth utilities** — the marginal value of each attribute level
- Calculated **relative importance** of each attribute as % of total utility range

**Step 4 — Optimal Product Design**
- Identified the attribute combination with maximum total utility
- Simulated market share for proposed product configurations vs. competitors

---

## Key Outputs

| Output | What It Tells You |
|--------|-------------------|
| Part-worth utilities | How much each feature level is worth to customers |
| Attribute importance scores | Which features drive decisions most |
| Optimal product profile | The configuration that maximizes appeal |
| Market share simulation | Expected share given competitor offerings |

---

## Sample Finding

> For the Natural Soap case, **ingredients (natural/organic)** accounted for ~38% of purchase utility — more than scent (~27%) and packaging (~19%) combined. This means investing in organic ingredient sourcing has 2× the ROI of premium packaging redesign for this target customer.

---

## Skills Demonstrated

- Conjoint analysis design and execution
- Part-worth utility calculation via regression
- Attribute importance scoring
- Market share simulation
- Excel: regression, dummy variable coding, utility scoring
- Business translation: converting statistical outputs into product strategy

---

## Tools Used

- Microsoft Excel (regression, dummy coding, utility calculations)

---

## Related Projects

- [Customer Segmentation — Cluster Analysis & MDS](#)
- [Price Optimization Models](#)
