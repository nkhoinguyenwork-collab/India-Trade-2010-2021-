# India Merchandise Trade Dynamics & Deficit Analysis (2010 - 2021) 

## Project Overview
This project delivers a macroeconomic and structural assessment of India's merchandise trade flows from 2010 to 2021. It examines commodity concentration across global Harmonized System (HS) chapters, bilateral dependency dynamics, and the underlying drivers behind India's structural trade deficit (-36%).

---

## 🛠 Tech Stack & Tools
- **Data Transformation & Querying:** SQL (Data cleaning, aggregation, HS-code mapping, and trade balance formatting)
- **Data Modeling & Visualization:** Microsoft Power BI (`India Trade.pbix`)
- **Raw Dataset (2010–2021):** [Download Full Raw Data from Google Drive](https://drive.google.com/drive/folders/150qTXoeKV9__D085T9pIEaBOIvfOOKMT?usp=sharing)
- **Metrics & DAX:** Measures for Trade Deficit (-36%), YoY Growth, and Market Share Decomposition
- **Analytical Competencies:** Value-chain trade analysis, supply chain decoupling, macro trade profiling

---

## Key Business Questions & Strategic Scope
- How does India's import-to-export processing model operate across core commodities (Mineral Fuels and Gems/Jewellery)?
- What does the asymmetric dependency between upstream supply (China) and downstream demand (United States) reveal about India's trade exposure?
- What are the primary deficit drivers, and which specialized industries provide structural trade surpluses?
- How did the 2020 pandemic disrupt bilateral volumes, and what was the pace of subsequent recovery?

---

## Key Strategic Findings & Analytical Breakdown

### 1. Commodity Processing & Two-Way Trade Structure
- **Mineral Fuels (HS 27):** Dominates both import and export flows. India heavily imports unrefined crude oil, refines it domestically, and re-exports high-value distillates and refined petroleum products.
- **Gems & Jewellery (HS 71):** Ranks #2 in both trade directions. India serves as the global cutting and polishing hub (notably Surat) for raw rough diamonds and precious stones before exporting finished jewellery.
- **Structural Deficit ("Spend to Grow"):** Across critical industrial lines, imports consistently outstrip exports, reflecting high domestic capital investment and machinery demand to fuel internal economic expansion.

### 2. Market Footprint: Upstream Dependency vs. Downstream Markets
- **Export Destinations:** The **United States** stands as the largest export destination (~$456k baseline), followed by the **UAE, Hong Kong, China, and Singapore**.
- **Import Sources:** **China** dominates inbound trade volumes (~$623k), trailed by the **UAE, Saudi Arabia, the US, and Switzerland**.
- **Strategic Exposure:** India relies heavily on China for low-cost upstream intermediate manufacturing inputs, while relying predominantly on the US and Western partners as final consumer absorption markets.

### 3. Bilateral Dynamics: India – Vietnam Trade Flow
- **Net Exporter to Vietnam:** Vietnam ranks among India's **Top 7 export destinations**.
- **Trade Surplus:** India maintains a consistent merchandise trade surplus with Vietnam (~47k export turnover vs. ~20k import value), making Vietnam a key net absorber of Indian raw commodities and manufactured inputs.

### 4. Shock Resilience & Post-COVID Rebound
- **2020 Contraction:** Severe downturn across both inbound and outbound trade volumes driven by COVID-19 logistics disruptions and nationwide lockdowns.
- **V-Shaped Recovery:** Rapid rebound immediately post-2020, scaling to multi-year peaks driven by pent-up demand and elevated global commodity price environments.

### 5. Trade Balance Decomposition (Overall: -36%)
- **Major Deficit Contributors (Net Outflows):**
  - *Mineral Fuels & Distillation (HS 27):* Deficit of **-US$1.13M**
  - *Electrical Machinery & Equipment (HS 85):* Deficit of **-US$364k**
  - *Gems & Precious Metals (HS 71):* Net deficit of **-US$292k** (bulk rough import value exceeds processed export margin)
  - *Mechanical Appliances & Reactors (HS 84):* Deficit of **-US$279k**
- **Competitive Structural Surpluses (India's "Golden Sectors"):**
  - *Pharmaceuticals:* High global export footprint in generic formulations.
  - *Fisheries & Marine Products:* Substantial agricultural net surplus.
  - *Textiles & Cotton:* Core competitive edge across knitted and non-knitted apparel.

---

## 📁 Repository Structure
- `queries/`: SQL scripts used for data cleaning, commodity slicing, and trade balance aggregations (`india_trade_cleaning.sql`).
- `India Trade.pbix`: Interactive Power BI dashboard with full DAX measures and visualizations.
- `README.md`: Executive summary and strategic trade breakdown.
