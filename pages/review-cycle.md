---
title: CM Review Cycle
layout: default
nav_order: 4
---

# General CM Review Cycle Steps

The following is a high-level overview of the steps recommended to perform a Centralized Monitoring review cycle. Detailed/specific steps for each KRI, CSM, etc. are provided in the [KRI Review]({% link pages/kri-review.md %}) section.

---

## If Signals Were Raised During Prior CM Review Cycle(s)

For any signals (study, country, site) that were previously raised for action and remain an outlier/signal in a subsequent review cycle, the Central Monitor should evaluate what action was previously taken and current data to assess if additional action is warranted.

{: .example }
> - Site was an outlier with significantly low AE rate in a prior cycle and this was escalated for investigation
> - Site remains a low outlier in the current review without significant worsening
> - Review the action taken to determine if the CRA thoroughly evaluated site process. If they did and no process gaps or other issues were identified, and this is adequately documented by the CRA, then the CM signal for the current cycle should be closed with a comment, e.g., "CRA evaluated site process per prior escalation and no process gaps or issues were identified. As the signal has not worsened, no further action required at this time."

---

## Review KRI Reports

### Study Level Review

1. Detailed steps for each KRI are provided in the [KRI Review]({% link pages/kri-review.md %}) section. However, the **Central Monitor is to begin the review by first assessing signals across study to gain a broad picture of the overall risks**. This can be performed by reviewing the Summary charts at the top of the Site KRI Overview report. Subset the sites for All (highlighted in screenshot) then review for KRIs with a high proportion of flags (amber or red). For example, in the screenshot below there may be a study level trend related to AE under-reporting.

   ![Study overview screenshot]({{ site.baseurl }}/assets/images/image9.png)

2. **The total number of sites relative to the number of sites with risk signals must be taken into consideration when deciding to escalate a study level trend.**

   {: .example }
   > If 60% of sites are outliers in high query rate, this is a study level trend that would require investigation and action at the study level by the study team (e.g., CDM to confirm any trends in specific queries that may be contributing and potentially evaluate eCRF Guidelines to ensure the requirements for the associated data is clear; Clin Ops to determine retraining or site level actions to support the mitigations). However, if there are 10 outlier sites in an analysis, but there are 100 sites active on study, this is not a study level trend.

   If identified, study level risks can be escalated via a manually entered signal in the ADO CM Action Log.

### Country and Site Level Review

**After reviewing for any study level trends, the next steps will be to review signals at the site and country level.**

![Note icon]({{ site.baseurl }}/assets/images/image10.png){: .d-inline-block style="width: 50px; vertical-align: middle;" }

{: .note }
> +/- 1 outliers (amber, where color is denoted) should be investigated just like +/- 2 outliers (red). However, amber outliers should generally be considered in the context of other signals for the site. This is because amber signals are not as strong/are less likely to indicate a true issue than red outliers are (amber outliers should still be investigated and may warrant escalation for action in and of themselves, this note is simply to ensure the strength of the signal(s) is considered). Similarly, some KRIs represent higher risk than others e.g., AE/SAE under-reporting and high IPD rates are more critical to investigate and action than others e.g., a single flag for query rate or data entry delay.

{: .example }
> In the screenshot below, site 30888 has 1 amber flag on query rate, which likely does not warrant escalation, while site 10141 has 5 amber flags that together may indicate a broader site risk related to data integrity.

![Site flags comparison]({{ site.baseurl }}/assets/images/image12.png)

{: .important }
> If a site has multiple KRIs flagged amber, together these signals may warrant escalation whereas a single amber flag may not merit action e.g., 15 non-important deviations across 937 days on study (amber) may not be as high a risk as a site with 37 non-important deviations across 714 days on study (red). However, if the amber site has other signals of risk such as high query rate, delayed data entry, etc. this is a much stronger indicator of a true underlying issue and should be escalated for investigation by the site's CRA. These signals can be combined into a single signal describing the overall risk for the site across domains.
>
> An exception to this is low AE rate outliers flagged as amber which may warrant escalation in and of itself due to the higher risk related to unreported AEs.

The Central Monitor will perform an initial investigation into each signal to confirm if escalation to the appropriate function for action is warranted (e.g., CRA, MM, CDM, etc.).

**When evaluating each country or site signal, the CM will:**

1. **Confirm if there are additional findings for the same country/site** to assess for connections.

   {: .example }
   > If there is a low AE reporting rate site and the site also is at risk due to data entry lags, the two signals could be related (data entry lag in AE data would result in a low AE rate).

   In the Study Overview section of the KRI Report by Site, subset sites for 1+ flag. For example, site 21897 has 5 flags across safety, deviation, query, and data entry lag categories. Bear in mind that not all flags will warrant action so this should be considered when evaluating.

   ![Site with multiple flags]({{ site.baseurl }}/assets/images/image13.png)

   In these cases, the signals can be combined to create a comprehensive signal describing the overall risk. The goal would be to provide as complete a picture as possible rather than separate more granular signals. This will allow the responsible action owner to better evaluate root cause.

   {: .example }
   > Site is an outlier with a significantly lower AE incidence rate than other sites on study and has significantly higher deviation and query rates. The site also has a trend in delayed data entry. Together these signals indicate a broader data integrity risk including potentially unreported safety data.

2. **Assess if the signal is a new/emerging risk.** New risks (i.e., signals not previously flagged for the site) are also important to identify and flag to the study team to ensure we take action early, to mitigate potential issues.

   In the KRI reports by Country and Site, below the Study Summary Charts, is the "Flags Changes" list. This compares the current snapshot data to the prior snapshot data.

   ![Flag changes list]({{ site.baseurl }}/assets/images/image14.png)

   Each bullet can be expanded to show details of how the metric flag changed since the prior review. Note, improving flags are also shown as the new green flags. In some cases new amber flags will be improvements (change from red to amber) or worsening (change from amber to red).

   {: .example }
   > In the case below, there is a new signal for site 28688 for IPD Rate. The expanded view shows that since the last snapshot (~1 month) there were 12 new IPDs reported for this site (numerator increase +12), up from only 1 reported in the prior snapshot.

   ![Expanded flag change details]({{ site.baseurl }}/assets/images/image15.png)

3. **Note:** when reviewing country level trends, evaluate the number of sites contributing to the country level trend. For example, if there is a single site in a country, a country level trend may be flagged that is truly just a site level signal. Likewise, if there is a single country on study, country level trends would not be applicable; in this case, consider if there is a study level trend, based on the proportion of sites contributing to the signal.

4. As an example, in the screenshot below, Great Britain is an outlier in IPD rate, but if this is only based on a small proportion of sites in the country, or if there are only a small number of sites in the country, this is likely a site level trend and not a country level trend.

   ![Country level IPD rate]({{ site.baseurl }}/assets/images/image16.png)

5. Another method for investigating a site of interest across KRIs is to select the site in one visualization using the "Select Group" drop down and then review the other KRI visualizations -- the same site will be highlighted across KRIs.

   ![Cross-KRI site highlighting]({{ site.baseurl }}/assets/images/image17.png)

6. Perform initial investigation into the signals using any additional tools and visualizations available. Detailed steps are provided for each KRI in the [KRI Review]({% link pages/kri-review.md %}) section.

7. Ensure to review for prior signals for the same site/KRI to assess if the new signal is a worsening, if action has been taken, and if a new escalation is required.

8. Following the expected process, the Central Monitor raises signals for action to the appropriate functional team member.
