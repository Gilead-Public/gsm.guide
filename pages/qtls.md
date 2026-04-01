---
title: Quality Tolerance Limits
layout: default
nav_order: 6
---

# Quality Tolerance Limits

As noted in the [Analysis Types overview]({% link pages/analysis-types.md %}#qtls), QTLs are study level parameters used to monitor for systematic issues that could ultimately impact the reliability of final study analysis or participant safety.

[{gsm}](https://github.com/Gilead-BioStats/gsm.core) currently has 2 QTL parameters:

| Parameter | Description |
|:----------|:------------|
| Inclusion/Exclusion | Proportion of enrolled subjects with any inclusion or exclusion criteria deviations. |
| Premature Study Discontinuation | Proportion of enrolled subjects that discontinue study prior to the expected timepoint. |

---

## Steps to Review QTLs

QTLs are reviewed at a set frequency (e.g., monthly, after x% of data accrual or enrollment, etc.) following the steps below regardless if there was a QTL deviation (i.e., parameter value exceeds the threshold).

1. Review QTL results to confirm if the QTL value exceeded the threshold (i.e., there was a QTL deviation).

2. If no deviation, assess if there is a worsening trend, where the parameter value is increasing toward the upper threshold. If so, consider if root cause investigation is still warranted despite no deviation.

3. If there was a deviation, the cross-functional study team should perform Deviation Root Cause Analysis and Mitigation planning.

4. Following RCA and Mitigation action agreement (as applicable), the Risk Advisor updates the CM Action Log and ensures the report is filed as required.
