# RetailPulse Nigeria — End-to-End Retail Analytics Project

**An Excel-based data analysis project for a simulated Nigerian omni-channel retailer, covering 3 years of sales, operations, and customer performance data.**

Built by [Obiekwe Emmanuel C.](https://github.com/obiekwe-emmanuel) using the **JTG Six-Phase Data Analysis Process**.

---

## 📌 Business Context

RetailPulse Nigeria Limited is a simulated omni-channel retailer selling across 8 product categories (Electronics, Clothing & Fashion, Food & Beverages, etc.) through 4 sales channels (In-Store, Online, Phone Order, WhatsApp Commerce), across 5 Nigerian regions, from 2022–2024.

This project answers 15 core business questions across revenue, profitability, operations, and customer performance — the kind of questions a retail business owner would actually ask.

## 🔍 Process

Following the JTG Six-Phase Data Analysis Process:
1. **Define** — Scoped business questions and KPIs
2. **Collect** — Built a synthetic 3-year transactional dataset
3. **Structure & Transform** — Cleaned and modeled data for analysis
4. **Analyze** — Answered 15 business questions using pivot tables, formulas, and calculated metrics
5. **Visualize** — Built 4 interactive dashboards with slicers, VBA flip-card macros, and dynamic insight text boxes
6. **Report** — Delivered written findings and social media summaries

## 📊 Dashboards

### Revenue & Profitability Dashboard
Tracks total net revenue, profit, average order value, margin, and orders — broken down by product category, region, sales channel, sales rep performance, and monthly trends.

**Key finding:** ₦555M generated over 3 years but effectively flat, carried almost entirely by Electronics. VIP customers aren't spending more despite discounts, and 25% of orders aren't completing.

![Revenue Dashboard 1](dashboards/Revenue_and_Profitability_1.jpg)
![Revenue Dashboard 2](dashboards/Revenue_and_Profitability_2.jpg)

### Operations & Customer Performance Dashboard
Tracks order completion, return rate, delivery performance, customer ratings, and customer segment movement over time.

**Key finding:** RetailPulse completes 74% of orders but loses 26% to returns, cancellations, and pending status — a systemic operations issue, not a category-specific one. The VIP segment has stayed flat for 2 of 3 years, meaning the business retains customers at "Returning" level but fails to graduate them upward.

![Operations Dashboard 1](dashboards/Operations_and_Customer_Performance_1.jpg)
![Operations Dashboard 2](dashboards/Operations_and_Customer_Performance_2.jpg)

## 🛠️ Tools Used
- Microsoft Excel (Pivot Tables, Power Query, advanced formulas)
- VBA (flip-card navigation macros, dynamic insight text boxes)
- Slicer-connected interactive dashboards

## 📁 Files
- `RetailPulse_NG.xlsm` — Full macro-enabled workbook with dashboards
- `/dashboards` — Dashboard screenshots
