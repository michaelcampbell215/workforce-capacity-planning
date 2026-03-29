# Workforce Capacity & Retention

[![Power Query](https://img.shields.io/badge/Power_Query-Excel-217346.svg)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Data Visualization](https://img.shields.io/badge/Visualization-Sentiment_Distribution-blue.svg)](https://www.microsoft.com/en-us/microsoft-365/excel)

> [!IMPORTANT]
> **Executive Summary:** This project transforms qualitative workforce feedback into a quantitative risk mitigation roadmap. By engineering an automated Power Query pipeline to replace deceptive "blended averages," we isolated a specific "Appreciation Gap" driving a systemic retention crisis within the public health sector, allowing HR to intervene before talent churned.

**Strategic Asset:** 
*   **Capacity Model:** [HR Survey Analysis Dashboard](./HR%20Survey%20Analysis.xlsx)

---

## Project Overview

The Seattle Department of Public Health was facing a looming retention crisis. Legacy VBA pipelines were returning "blended average" satisfaction scores that completely concealed immediate flight risks. For example, an employee rating Compensation a "5" but Peer Support a "1" produces a healthy-looking average of "3" while technically being a high-probability churn candidate.

1. **Description:** We built a Workforce Capacity & Retention model using Excel and Power Query to identify exact points of sentiment friction *before* turnover occurs.
2. **Objective:** Transition from anecdotal exit interviews to data-driven proactive retention, stopping the loss of specialized clinical talent.

## Data Sources

1. **Primary Datasets:** Qualitative HR survey responses mapped to a quantitative Likert scale across hundreds of employees.
2. **Additional Data:** Departmental mapping and baseline retention metrics to track aggregate churn probability.

## Process

*   Standardized raw survey responses and handled data nulls via a robust Power Query ETL pipeline.
*   Calculated exact Sentiment Distributions (100% Stacked) across 12 unique parameters rather than relying on standard average scores.
*   Quantified the Job Clarity Index to measure the alignment between role expectations and operational reality.
*   Measured the Appreciation Gap by charting the variance between supervisor support and peer recognition.

## Technical Pivot

*   **Rejecting the "Average Score" Trap:** Initial legacy reporting methods relied on calculating the mean Likert score for a department. We firmly rejected this blended reporting at the architecture level. By pivoting to a Sentiment Distribution (measuring the exact spread from "Strongly Agree" to "Strongly Disagree"), we exposed hidden polarity. We proved that calculating an average mathematically destroys the signal needed to save an at-risk employee.

## Key Insights

*   **The Appreciation Gap Isolated:** By separating specific survey categories, we revealed that while employees reported high job clarity and strong management support, they felt critically low levels of value and peer connection.
*   **Emotional Friction Drives Churn:** Cross-referencing job clarity against appreciation scores proved that this lack of emotional connection not compensation or clinical workload was actually the dominant driver of long-term churn probability among the staff.
*   **Legacy VBA Caused Analytical Delays:** The fragile nature of the existing VBA macros meant HR lacked the agility to respond to real-time sentiment shifts, forcing them to wait months to compile baseline metrics before acting.

## Recommendations

*   **Democratize Peer Recognition:** Deploy peer-to-peer recognition initiatives specifically designed to bridge the Appreciation Gap, focusing heavily on lateral connections between frontline staff.
*   **Reallocate Culture Budgets:** Shift funding away from generic, organization-wide "culture programs" and redirect it to localized, department-level connection initiatives based strictly on the identified friction clusters.
*   **Retire VBA Pipelines:** Completely sunset legacy VBA reporting in favor of the automated Power Query process to eliminate data handling bottlenecks.

## Next Steps & Action Plan

*   **Pulse-Check Monitoring:** Integrate rapid 3-question survey cycles into the data pipeline to track real-time sentiment recovery month-over-month.
*   **Predictive Churn Alerts:** Establish a monthly executive review of the specialized Appreciation Index to proactively address emerging retention risks long before formal exit interviews fall onto HR's desk.
