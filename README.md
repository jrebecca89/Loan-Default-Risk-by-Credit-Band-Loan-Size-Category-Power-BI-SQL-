# Loan Default Risk Analysis by Credit Band & Loan Size Category

**Created:** May 01, 2025  
**Tooling:** PostgreSQL + Power BI  
**Data:** Simulated fintech lending data

## Project Summary

This project explores loan default risk by analyzing how **credit bands** (Fair, Good, Excellent, Poor) interact with **loan size categories** (`<50K`, `50K–150K`, `>150K`). The goal is to uncover which borrower profiles carry the highest default risk—and whether higher credit score bands truly translate to lower risk at all loan sizes.

---

## Key Findings

- **Default rates are highest in the $50K–$150K loan size category**, regardless of credit band.
- **Borrowers in the "Excellent" credit band** still show high default rates when borrowing in this mid-size range.
- This suggests **loan amount** may be a stronger risk signal than credit rating alone for certain borrower segments.

---

## Technologies Used

- **PostgreSQL**: Data cleaning, transformation, and group-by queries to calculate total loans, defaults, and default rate percentages.
- **Power BI**: Dynamic bar chart visualizations, slicers, KPI cards (total loans, default rate), and formatting logic for presentation clarity.

---

## Dashboard Preview

*(Loan Default Risk.dashboard.pdf)*

---

## How to Reproduce

1. Import the `loan_funnel_data.csv` into PostgreSQL.
2. Run the SQL query provided in `loan_default_rate_by_band.sql` to generate the aggregate results.
3. Load the resulting CSV summary into Power BI.
4. Use the default rate % measure and credit_band/loan_size_category to create a clustered column chart.
5. Add KPIs: Total Loan Count and Overall Default Rate.
6. Add a slicer by Loan Size Category for interactivity.
7. Add insights as a text box on the dashboard.

---

## Insight Statement

> "Default rates are highest in the $50K–$150K range across all credit bands.  
> 'Excellent' credit does not significantly reduce risk in this segment."

---

## Author

Jonathan Rebecco  
Data-Driven Fintech Strategist | Aspiring Analytics Leader  

---

## License

This project uses **simulated data** for demonstration purposes only.  
No proprietary or confidential data is included.

