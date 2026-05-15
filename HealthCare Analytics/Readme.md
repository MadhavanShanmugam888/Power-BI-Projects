# Healthcare Analytics Dashboard (2020–2025)
# Project Overview

The Healthcare Analytics Dashboard is an end-to-end Power BI report developed using a synthetic hospital dataset containing 9,742 patient records between 2020 and 2025. The objective of this project is to analyze hospital operations, patient demographics, financial performance, and clinical trends to support data-driven healthcare decision-making.
The report is structured into two analytical layers:
* Patient Demographics
* Clinical & Operational Insights
Through interactive visuals and DAX-driven KPIs, the dashboard transforms raw patient data into meaningful insights that can support hospital administrators, operations managers, and healthcare analysts.

# Data Overview

The dataset includes structured information related to:
* Patient demographics
* Admission and discharge details
* Hospital stay duration
* Medical conditions
* Billing information
* Doctor assignment
* Test outcomes
* Patient satisfaction ratings
The data was cleaned and validated in Microsoft Excel before being modeled in Power BI using relationships, calculated columns, and measures.

# Data Modeling & Preparation
To ensure accurate and dynamic analysis, the following steps were implemented:

# Data Modeling

* A dedicated Date table was created to enable time intelligence analysis.
* Relationships were established between patient records and time attributes.
* A separate measures table was created for KPI calculations.

# Calculated Columns

* Age groups were derived for demographic segmentation.
* Length of stay was calculated using admission and discharge dates.
* Time-based fields (Year, Month) were extracted for trend analysis.
* Additional logical groupings were created for deeper segmentation.

# DAX Measures
Key performance indicators were developed using DAX, including:

* Total Patients
* Average Age
* Average Length of Stay
* Average Billing Cost
* Patient Satisfaction Score
* Admission Distribution
* Monthly Admission Trends
* Doctor Performance Metrics

# Dashboard Section 1: Patient Demographics
This section focuses on understanding the characteristics of the hospital’s patient population.

🔹 Population Overview

The dashboard displays total patient count along with gender distribution, offering a quick snapshot of patient volume and demographic balance.

🔹 Age Distribution Analysis

Patients are segmented into meaningful age groups to identify which population contributes most to hospital admissions.
The analysis reveals that middle-aged and elderly patients represent the majority of hospital visits, indicating higher healthcare dependency in those age segments.

🔹 Admission Pattern Analysis

Admission types are analyzed to understand operational pressure and emergency handling capacity.
The distribution helps assess whether hospital inflow is primarily planned or emergency-driven.

🔹 Test Result Analysis

The dashboard evaluates patient test outcomes to monitor clinical severity levels and risk distribution within the patient population.

🔹 Blood Group & Demographic Patterns

Demographic segmentation allows identification of population trends that may support targeted healthcare services and preparedness planning.

🔹 Monthly Admission Trends

Time-based visualizations identify patterns in patient inflow, peak admission periods, and seasonal fluctuations.

This section enables administrators to better understand who their patients are and how patient volume evolves over time.

# Dashboard Section 2: Clinical & Operational Insights
This section shifts focus toward hospital performance, treatment trends, and financial metrics.

🔹 Medical Condition Distribution
The dashboard analyzes the distribution of major medical conditions across age groups.
This helps identify:
* Which conditions are most prevalent
* Which age segments are more vulnerable
* Potential areas requiring preventive strategies
The condition spread is relatively balanced, ensuring no single category dominates hospital resources disproportionately.

🔹 Length of Stay Analysis
Hospital stay duration is calculated dynamically to evaluate:
* Average patient hospitalization period
* Resource occupancy patterns
* Potential efficiency gaps
Understanding stay duration helps optimize bed utilization and operational planning.

🔹 Billing & Revenue Insights
Financial analysis includes:
* Average billing cost per patient
* Cost variation across treatment outcomes
* Revenue distribution trends
Billing is influenced by treatment duration and condition severity, offering insight into hospital revenue drivers.
This section helps evaluate financial sustainability and cost management effectiveness.

🔹 Medication Utilization Trends
The report analyzes prescription frequency to understand treatment patterns and medication demand.
This enables:
* Supply chain optimization
* Inventory planning
* Identification of high-demand treatments

🔹 Doctor Performance Evaluation
Doctor-level analysis includes:
* Total patients handled
* Average patient satisfaction rating
This provides insight into service quality and supports performance recognition or improvement strategies.

🔹 Room Utilization Analysis
Room allocation trends are studied across different patient segments to understand infrastructure usage and optimize space planning.

# Key Business Questions Answered
This dashboard addresses several strategic healthcare questions:
* What does our patient population look like?
* Which age groups require more medical attention?
* How long do patients typically stay in the hospital?
* How are admissions distributed across different categories?
* What drives hospital revenue?
* Are patients satisfied with their treatment experience?
* Which doctors are performing consistently well?
* Are there observable seasonal patterns in admissions?

# Key Insights
* Adults and elderly patients form the largest admission segment.
* Average hospital stay duration reflects moderate treatment complexity.
* Patient satisfaction remains stable around mid-level ratings.
* Billing averages indicate consistent revenue distribution.
* Admission patterns show steady inflow across months without extreme spikes.
* Clinical case severity is evenly distributed across categories.

# Conclusion

The Healthcare Analytics Dashboard demonstrates how structured data modeling, DAX calculations, and visual storytelling can transform raw hospital records into strategic insights.
This project highlights practical skills in:
* Data Cleaning & Transformation
* Data Modeling
* DAX Calculations
* KPI Design
* Healthcare Data Analysis
* Interactive Dashboard Development
By integrating demographic, clinical, financial, and operational metrics into a unified analytical framework, the dashboard provides a 360-degree view of hospital performance and patient care outcomes.


## 👤 Author

**Madhavan Shanmugam**

*Data Analyst | Python | Power BI | SQL | Advanced Excel*
