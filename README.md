# Case Study: NC Pricing Trends & Market Attractiveness

## Overview of the Case Study

This dashboard analyzes housing market trends across North Carolina using Zillow’s datasets. The focus is on identifying KPIs that builders and investors can easily understand, such as median prices, regional year-over-year (YoY) growth, and long-term price appreciation, in order to support real estate decision-making and track market trends in the North Carolina region.

Dashboard Link: 

---

## Business Questions & Challenges

* How is the median home price trending across the state & regions?
* Which regions are experiencing the fastest YoY growth in home values?
* What are the long-term growth trends (CAGR) across North Carolina?
* How can builders, investors, and policymakers use these insights to prioritize markets?

---

## Tools and Tech

* **Data Source**: Zillow ZHVI (Zillow Home Value Index) ([https://www.zillow.com/research/data/](https://www.zillow.com/research/data/))
* **Tools**: Tableau for visualization & KPI dashboards, Excel & Python for data cleaning
* **Metrics Used**: Median price, YoY % change, CAGR (3 years)

---

## Analysis Process

**Data Cleaning & Prep:**

* Used a custom Python script (*RealEstateDashboardNC.ipynb*) to clean and preprocess Zillow ZHVI data.
* Steps included handling missing values, ensuring consistent date formatting, filtering North Carolina-specific data, and reshaping the dataset into a Tableau-ready format.
* Added derived columns (e.g., YoY % change, CAGR) before exporting the dataset for visualization.

**KPI Creation:**

* Built calculations in Tableau for Median Price, YoY % Change, and CAGR (3 years).

**Visualizations:**

* KPI tiles for Median Price, YoY Growth, CAGR
* Map of YoY % (Year-on-Year) growth by region
* Line chart of Price Trends (2016–2025)

---

## Key Insights

* **Median Home Price:** Across North Carolina, the median home value is around \$310K, with a consistent upward trend.
* **Regional Differences:** Certain counties show above-average YoY growth (like Sunbury), while others lag behind, creating clear winners and underperforming regions.
* **Sustained Growth:** Most regions are on a positive trajectory, indicating stable demand and limited risk of price decline in the near term.
* **Long-Term CAGR (Compound Annual Growth Rate):** Over the last 3 years, some regions (like Aberdeen) demonstrate a CAGR of 5–7%, suggesting sustained appreciation and long-term investment value.

---

## Business Recommendations

* **Target High-Growth Regions:** By observing the YoY price growth per region, we can see certain regions in North Carolina showing sharp upward trends. Builders and investors should prioritize these regions, as strong YoY appreciation indicates robust demand and higher resale potential.
* **Spot Emerging Growth Areas:** Regions with lower base prices but strong YoY growth represent “up-and-coming” regions. Investors can enter early at lower costs, while builders can develop mid-market housing to capture rising demand.
* **Stabilize Through Long-Term Investments:** Counties with steady CAGR growth (not just recent spikes) show resilience. These areas are less risky and ideal for long-term rental portfolios or institutional investments.
* **Long-Term Value Creation:** Using CAGR insights from the dashboard, we can identify counties that have not only grown recently but also sustained long-term appreciation. These regions provide the strongest case for long-term ROI, making them ideal for buy-and-hold strategies.
* **Capitalize on Premium Markets:** Regions consistently above the state median price of \$310K (from pricing trend data) are strong premium markets. Builders can target these areas for luxury housing, while investors can focus on high-margin resale opportunities.
* **Regional Diversification:** Instead of overconcentrating in high-price areas, investors should spread portfolios across counties with different growth profiles (high YoY vs. stable CAGR) to balance short-term gains and long-term security.

---

## Business Risks

* **Regional Demand Volatility:** Markets with strong YoY but weak long-term CAGR could signal short-term spikes (possibly driven by temporary migration or economic shocks). Such volatility can result in unstable returns.
* **Affordability Risk:** With the median price at \~\$310K, continued upward trends could price out first-time buyers. Builders may face reduced demand for entry-level housing, while policymakers face affordability crises.
* **Supply Chain & Construction Costs:** High-growth counties attract more builders → increased demand for land, labor, and materials. This can inflate costs, squeeze margins, and delay project timelines.

---

## Conclusion

This dashboard provides a clear snapshot of North Carolina’s housing market by analyzing median prices, year-over-year growth, and long-term appreciation trends (CAGR). The insights help builders, investors, and policymakers identify where opportunities lie — from high-growth counties that signal strong demand to more affordable regions that balance risk and return.

At the same time, the analysis highlights important risks such as potential overvaluation in fast-growing markets, affordability pressures, and external shocks like interest rate changes or policy shifts.

Ultimately, this dashboard transforms raw real estate data into actionable insights, enabling smarter investments, balanced risk management, and more sustainable housing development in North Carolina.
