# 📊 Business Insights — Pharma Supply Chain Optimization

> **Prepared by:** Supply Chain Analytics Division  
> **Dataset:** 2,000 transactions · 20 drug SKUs · 5 regions · 24 months

---

## Executive Summary

Analysis reveals critical supply-demand imbalances: **42.4% stockout risk** and **24.6% overstock burden** across all records — together costing an estimated ₹3.2 Cr annually in opportunity loss and carrying cost.

---

## Insight 1 — Cardiovascular Drugs Face Systemic Stockout Risk

Cardiovascular drugs (Lisinopril, Losartan, Atorvastatin, Metoprolol, Amlodipine) represent the highest demand category at **194,371 units** yet consistently show stockout events across all five regions. These are chronic-disease medications with inelastic demand — a stockout is a patient safety event, not merely a missed sale.

**Recommendation:** Increase safety stock for cardiovascular SKUs by 25%. Prioritize as Class A in replenishment scheduling.

---

## Insight 2 — Psychiatric Category Shows Severe Overstock Pattern

Psychiatric medications show the widest inventory-demand gap: 113,669 units stocked against 87,828 demanded — a **29% overstock ratio**. Carrying cost on excess units generates ~₹34 lakh in avoidable annual cost.

**Recommendation:** Reduce order quantities for psychiatric SKUs by 15–20%. Implement rolling 30-day demand forecasts.

---

## Insight 3 — EOQ Model Reduces Ordering Inefficiency by ~18%

Current order quantities deviate from optimal EOQ by an average of 22%. Low-cost analgesics (Ibuprofen, Paracetamol) warrant high EOQ values (~3,500 units) due to low holding cost — bulk procurement is advantageous. High-cost drugs require tighter, more frequent ordering.

**Recommendation:** Implement dynamic EOQ recalculation quarterly. Automate purchase orders for Class A drugs.

---

## Insight 4 — Delivery Delays Compound Antibiotic Stockout Risk

Antibiotics face the highest delivery delays (Amoxicillin: 3.8 days avg). For acute-care drugs with unpredictable demand spikes, delayed replenishment creates a compounding risk cascade.

**Recommendation:** Establish emergency supplier agreements with 48-hour SLAs for antibiotic SKUs. Maintain 14-day safety buffer.

---

## Insight 5 — Regional Distribution Is Structurally Imbalanced

All five regions carry excess inventory yet simultaneously record stockout events — indicating misallocation, not shortage. West India has the highest surplus (+29,490 units) while East India has the most stockout events (175). This is a distribution routing problem.

**Recommendation:** Implement inter-regional redistribution protocol. Cross-check cross-region inventory before new purchase orders. This alone could resolve 30–40% of stockouts.

---

## Insight 6 — ABC Classification Should Drive Priority Tiering

- **Class A (848 records):** Cardiovascular, Antidiabetic, Psychiatric — tight control, frequent ordering, real-time monitoring.
- **Class B (412 records):** Analgesics, Respiratory — periodic review with EOQ guidance.
- **Class C (740 records):** Antiallergic, niche SKUs — annual review, bulk procurement.

---

## Priority Action Table

| Priority | Action | Expected Impact |
|----------|--------|-----------------|
| P1 | Increase cardiovascular safety stock 25% | Reduce stockouts ~35% |
| P1 | Inter-regional redistribution protocol | Resolve 30–40% of stockouts |
| P2 | Apply EOQ to all Class A SKUs | Reduce ordering cost ~18% |
| P2 | Reduce psychiatric overstock 15–20% | Save ~₹34 lakh/year |
| P3 | 48-hr SLA for antibiotic suppliers | Cut delay-driven stockouts ~50% |
