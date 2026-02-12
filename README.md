# 📦 Supply Chain SLA & Profitability Analysis
Operational Degradation Investigation | January 2025
--- 
# 📌 Project Overview
This project analyzes a mid-sized Central European e-commerce company operating in: Slovakia, Czechia, Hungary, Poland.
The company operates 2 warehouses (WH_A, WH_B) and processes ~2,200 orders per month.

# 🚨 Business Problem
In January 2025 the company experienced:

1) Increased delivery delays,
2) Higher Lead Time,
3) Declining OTD (On-Time Delivery),
4) Falling Service Level (SLA),
5) While logistics costs remained stable.

The objective was to identify whether the issue was operational, financial, or structural.

# 🔎 Investigation Framework
The analysis followed a structured root-cause approach:

Detection of structural break in performance,
Pre/Post January 15 comparison,
Lead Time and OTD decomposition,
Volume stress testing,
Pareto analysis (Route + WH + Country + Category),
SKU-level profitability review,
Order-level profitability segmentation,
Volume vs price sensitivity analysis.

---

# 📉 Key Findings – Operational Side

1) A structural break occurred after January 15, 2025,
2) Lead Time increased system-wide,
3) OTD declined across all segments,
4) No single warehouse, route, or category acted as a bottleneck,
5) Order volume remained stable → no overload effect detected.

# Conclusion:
The SLA degradation is systemic, not localized. The issue likely stems from process-level changes rather than isolated operational failures.

---

# 💰 Key Findings – Profitability Side

Unprofitable orders were driven by:
Low Net Price per unit,
Medium order volume (4–6 units),
High fixed & logistics cost allocation.

Insights:
Orders with 1–2 units had only 7–46% profitability probability
Profitability improves significantly at 4–6 units (>70%)
However, volume alone does not guarantee profitability
Low price + medium volume still leads to losses

Core Insight:
Profitability is determined by the combination of:
Order volume,
Unit price,
Cost allocation structure,
The key driver is increasing average order value, not just quantity.

---

🛠 Business Recommendations
1. Discount Policy:
Restrict discounts for 1–2 unit orders,
Introduce minimum order value for discount eligibility.

2. Logistics Model:
Add handling fee for small orders,
Introduce paid shipping below threshold.

3. Cost Structure:
Review fixed cost allocation,
Convert part of fixed cost into variable structure.

---
📊 Deliverables

⁕ Python analytical notebook,
⁕ Interactive Excel dashboard (pre/post structural break comparison),
⁕ Operational & financial root cause summary.
