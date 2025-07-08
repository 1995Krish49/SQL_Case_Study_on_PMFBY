This project presents a structured SQL-based exploration of the Pradhan Mantri Fasal Bima Yojana (PMFBY) dataset to analyze the effectiveness and reach of agricultural insurance across Indian states and districts over multiple years.

**🧾 Project Overview**
The dataset includes key information about:

Insured Land Area

Sum Insured

Premium Contributions (by farmers, state, and central government)

Insurance Units and Farmer Participation

Across different states, districts, and years

The project uses SQL queries to perform trend analysis, identify coverage gaps, and assess the scheme's financial model, with the goal of uncovering actionable insights for stakeholders and policymakers.

**🔍 Key Insights**
Madhya Pradesh led with over 9 million farmers insured and the highest SumInsured values.

Districts like Thane, Jaipur, Allahabad showed high participation, while some like Bengaluru Urban had zero recorded premiums, hinting at data gaps or non-enrollment.

Kangra (Himachal Pradesh) in 2021 had multiple entries indicating localized or small-scale implementations.

A spike in InsuredLandArea in 2020 suggests the impact of government intervention during the COVID-19 period.

Haryana and Chhattisgarh reflected strong multi-party financial contributions.

**🛠️ Technologies Used**
SQL (MySQL) for data querying and analysis

MySQL Workbench for database management

CSV-based data ingestion

**✅ Assumptions and Data Handling**
No null values were found; no imputation was required.

Pattern matching for names (e.g., districts starting with 'A') used LIKE clauses.

No changes were made for case sensitivity in filters.

Focused on active records (InsuranceUnits > 10).

Financial figures (SumInsured, Premiums) were assumed to be pre-scaled correctly.

**📌 Conclusion**
This analysis highlights the uneven implementation of the PMFBY scheme across regions. While states like Madhya Pradesh and Uttar Pradesh show strong participation and funding support, others lag behind. The insights drawn can assist in refining policy execution and promoting broader insurance coverage for Indian farmers.
