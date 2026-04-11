# Workforce Capacity & Retention Analytics
#### Public Health Sector | Clinical Talent Retention | Sentiment Distribution Modeling

[![Power Query](https://img.shields.io/badge/Power_Query-Excel-217346.svg)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Methodology](https://img.shields.io/badge/Methodology-Sentiment_Distribution-blue.svg)](https://en.wikipedia.org/wiki/Likert_scale)
[![Domain](https://img.shields.io/badge/Domain-Public_Health_Workforce-0D6EFD.svg)](https://www.cdc.gov/publichealthgateway/index.html)

> [!IMPORTANT]
> **Executive Summary:** This project transforms qualitative workforce feedback from the **Seattle Department of Public Health** into a quantitative risk mitigation roadmap. By engineering an automated Power Query pipeline to replace deceptive blended averages with full Sentiment Distribution analysis, the analysis isolated a specific **"Appreciation Gap"** driving a systemic retention crisis among specialized clinical staff — enabling HR leadership to intervene before talent churned.

**Strategic Asset:**
- **Capacity Model:** [HR Survey Analysis Dashboard](./HR%20Survey%20Analysis.xlsx)

---

> [!NOTE]
> **Healthcare Analytics Connection:** This is a healthcare workforce analytics project grounded in real public health sector data. The methodology — Likert sentiment distribution, Job Clarity Index, and clinical talent retention modeling — maps directly to HR analytics in hospital systems, health plan operations, and public health agencies where specialized workforce attrition carries direct patient care implications. Clinical talent is hard to replace; the cost of losing a specialized public health worker is measured in program continuity, not just recruitment fees.

---

## The Problem

The Seattle Department of Public Health was facing a looming retention crisis among specialized clinical staff. Legacy VBA pipelines were returning blended average satisfaction scores that completely concealed immediate flight risks. An employee rating Compensation a "5" but Peer Support a "1" produces a healthy-looking average of "3" — while being a high-probability churn candidate. The analytical architecture was hiding the problem.

**Description:** Built a Workforce Capacity & Retention model using Excel and Power Query to identify exact points of sentiment friction before turnover occurs in a public health department context.

**Objective:** Transition from anecdotal exit interviews to data-driven proactive retention, stopping the loss of hard-to-replace specialized clinical talent.

## Data Sources

1. **Primary Datasets:** Qualitative HR survey responses from Seattle Department of Public Health employees, mapped to a quantitative Likert scale across hundreds of respondents.
2. **Additional Data:** Departmental mapping and baseline retention metrics to track aggregate churn probability by clinical unit.

## Process

- Standardized raw survey responses and handled data nulls via a robust Power Query ETL pipeline, retiring fragile legacy VBA macros.
- Calculated full Sentiment Distributions (100% Stacked) across 12 unique workforce parameters rather than relying on average scores.
- Quantified a Job Clarity Index to measure the alignment between clinical role expectations and operational reality for frontline health workers.
- Measured the Appreciation Gap by charting the variance between supervisor support scores and peer recognition scores across departments.

## Technical Pivot

**Rejecting the "Average Score" Trap**

Legacy reporting relied on calculating the mean Likert score per department. The blended average approach was rejected at the architecture level. By pivoting to full Sentiment Distribution analysis — measuring the exact spread from "Strongly Agree" to "Strongly Disagree" — hidden polarity was exposed. A department averaging 3.0 could contain both highly engaged staff and imminent churners simultaneously. Mean scores destroy that critical signal.

## Key Insights

- **The Appreciation Gap Isolated:** Clinical employees reported strong job clarity and solid management support — but critically low levels of peer connection and valued recognition. These specific dimensions are most predictive of voluntary turnover in specialized healthcare roles.
- **Emotional Friction Drives Churn:** Cross-referencing job clarity against appreciation scores proved that lack of peer recognition — not compensation or clinical workload — was the dominant driver of long-term churn probability.
- **Legacy VBA Caused Analytical Delays:** The fragile nature of existing VBA macros meant HR leaders lacked the agility to respond to real-time sentiment shifts in clinical units, waiting months between baseline measurements before acting.

## Recommendations

- **Democratize Peer Recognition:** Deploy peer-to-peer recognition initiatives specifically designed to bridge the Appreciation Gap, focusing on lateral connections between frontline clinical staff.
- **Reallocate Culture Budgets:** Shift funding away from generic organization-wide culture programs toward localized, unit-level connection initiatives aligned to identified sentiment friction clusters.
- **Retire VBA Pipelines:** Sunset legacy VBA reporting entirely in favor of the automated Power Query process to eliminate data handling delays.

## Next Steps

- **Pulse-Check Monitoring:** Integrate rapid 3-question survey cycles into the data pipeline for real-time sentiment tracking month-over-month across clinical departments.
- **Predictive Churn Alerts:** Establish a monthly executive review of the Appreciation Index to proactively address emerging retention risks long before formal exit interviews reach HR desks.