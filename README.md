# Loan Default Risk by Credit Band & Loan Size Category  
*Simulated Fintech Lending Data*

This Power BI dashboard analyzes how default rates vary across credit bands (Fair, Good, Excellent, Poor) and loan size tiers (<$50K, $50K–$150K, >$150K) in a simulated fintech loan dataset. It offers insights that can inform credit strategy, risk modeling, and mid-ticket loan segmentation.

## 📊 Key Metrics Displayed
- **Overall Default Rate**: 49.4%
- **Total Loans Analyzed**: 500
- **Visuals**: Grouped bar chart, slicer filter, KPI cards

## 🔍 Business Insights
- Default rates are consistently highest in the **$50K–$150K** loan range across *all* credit bands.
- Even borrowers with **"Excellent" credit** have elevated risk in this range, suggesting that credit band alone may not be an effective risk differentiator in mid-sized loans.
- Smaller (<$50K) and larger (> $150K) loans show relatively lower default rates across most bands.

## 🧠 Strategic Implications
- Reassess mid-tier loan underwriting criteria or introduce layered risk models.
- Consider adjusting pricing or reserves for $50K–$150K loans regardless of credit score.
- Opportunity to improve decision-making through multi-variable risk segmentation.

## ⚙️ Technical Summary
- **SQL (PostgreSQL)**: Used to segment and calculate default rates by credit band and loan size category.
- **Power BI**: 
  - KPI cards (Default Rate %, Total Loans)
  - Grouped bar chart by credit band + loan size
  - Slicer filter to isolate loan size categories
  - DAX calculated measure for accurate percentage formatting

## 🧪 Tools Used
- pgAdmin4 (PostgreSQL)
- Power BI Desktop
- DAX for custom measure formatting

## 📁 Dataset
- Simulated fintech lending data (500 rows)

## 👤 Author
Jonathan Rebecca 
Aspiring Fintech Analyst | SQL & Power BI | Credit Strategy & Risk Insights  

---

> This dashboard was created to simulate real-world lending strategy problems and demonstrate skills in credit segmentation and default risk visualization.
