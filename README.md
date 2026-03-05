# Workforce Capacity Planning

## **Project Overview**

**The Chaos on the Ground:** The Seattle Department of Public Health faced a looming retention crisis. Unstructured, qualitative employee surveys were sitting in spreadsheets, leaving HR blind to the specific operational frictions driving turnover.
**The Solution:** I engineered a unified analytical "Control Tower" using Power Query and Excel. By normalizing Likert scale data and cross-referencing sentiment drivers, I quantified a critical "Appreciation Gap"—giving leadership a precise, data-backed roadmap to halt turnover through targeted operational adjustments.

## **Data Sources**

- **HR Employee Survey Responses:** Raw, unstructured workforce feedback data encompassing over 12 parameters of job satisfaction, supervisor support, and role clarity.

## **Process**

- **Data Engineering (Power Query):** Replaced manual data cleansing by automating the extraction and normalization of raw survey data—handling nulls, trailing spaces, and standardizing categories.
- **Likert Distribution Architecture:** Engineered 100% stacked bar charts to mathematically visualize the distribution of sentiment across all operational parameters.
- **Root Cause Analytics:** Cross-referenced core job alignment scores against supervisor support scores to isolate the primary and secondary risk factors for employee churn.

## **Key Findings**

- **The Appreciation Gap:** Revealed the primary bottleneck: employees reported exceptionally high clarity on _what_ their job was, but suffered from critically low feelings of appreciation for doing it.
- **Supervisor Support Stability:** Confirmed that structural management was functioning well, identifying "Strong Supervisor Support" as the current anchor preventing mass attrition.
- **Cultural Friction:** Identified a distinct lack of peer-to-peer connection as a secondary vulnerability threatening long-term operational stability.

## **Recommendations (Operational Scripts)**

- **Targeted Recognition Protocols:** Immediately pivot HR strategy to deploy highly visible, structured recognition programs that directly address the "Appreciation Gap."
- **Team-Building Roadmap:** Launch operational initiatives explicitly localized around peer-to-peer connection and team-building to fuse fragmented departments.
- **Refine Entry Operations:** Double down on the current onboarding processes to maintain the high "Job Clarity" scores that are currently stabilizing the workforce.

## **Next Steps**

- **Proactive Pulse Checks:** Implement high-frequency, automated pulse-check surveys to track sentiment recovery in real-time, moving away from reactive annual analytics.
- **Golden Pipeline Maintenance:** Automate the survey data ingestion via `HR Survey Analysis.xlsx` to ensure leadership always has a live view of workforce capacity risk.
