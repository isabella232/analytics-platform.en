---
title: Calculated metrics overview
description: Learn about 
---

# Calculated metrics overview

>[!NOTE]
>
>You are viewing the documentation for Analysis Workspace in Customer Journey Analytics. Its feature set differs slightly from [Analysis Workspace in traditional Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/home.html). [Learn more...](/help/getting-started/cja-aa.md)

Calculated and Advanced Calculated (or Derived) Metrics are custom metrics that you can create from existing metrics. Our Calculated Metrics tools offer a highly flexible way of building, managing and curating metrics. They allow you as marketers, product managers and analysts to ask questions of the data without having to change your [!DNL Analytics] implementation.

You can

* Create filtered metrics that are derived at report run time, [without having to change the implementation](https://youtu.be/CuQTm9RaUpY). These can be viewed historically because they are based on filters.
* Share metrics across report suites. This means that all newly created metrics apply to all reports suites in the same login company.
* (Advanced Calculated Metrics only) Filter on metrics. For example, you can create a metric for "New visitors", with a count of people for whom this is the first session.
* (Advanced Calculated Metrics only) Incorporate statistical functions to help you better describe your data. For example, you can count the number of items in a report or add in the number of standard deviations for each item.

## Calculated metrics versus advanced calculated metrics

Here is a comparison of Calculated Metrics and Advanced Calculated Metrics capabilities: 

|  Builder Options  | Calculated Metrics  | Advanced Calculated (Derived) Metrics  |
|---|---|---|
| Format types (decimal, time, percent, currency  | Yes  | Yes  |
| Attribution changes (default, linear, participation, etc.  | Yes  | Yes  |
| Metric types (standard, total | Yes  | Yes  |
|  Basic operators (add, subtract, multiply, divide)  | Yes  | Yes  |
| Apply filters | No  | Yes  |
| [Basic functions (count, abs value, mean, etc)](/help/components/calc-metrics/cm-functions.md)  | No  | Yes  |
| [Advanced functions (regression, if/then, t-score, etc)](/help/components/calc-metrics/cm-adv-functions.md)  | No  | Yes  |

## Tools

| Tool | Capabilities |
|--- |--- |
|Calculated Metric Builder|<ul><li>Create calculated and advanced calculated metrics using advanced allocation models.</li><li>Add filters inline to metric formulas.</li><li>Compare filters in the same report. For example, compare local visitors vs. international visitors.</li><li>Use statistical functions.</li><li> Provide detailed metric descriptions (show what it does, where to use it, where NOT to use it).</li><li>Copy definitions into new metrics.</li><li>Provide an inline metric preview.</li><li>Set metric polarity, which indicates whether it's good or bad if a given custom event (metric) goes up.</li><li>Tag metrics.</li></ul>|
|Calculated Metric Manager|<ul><li>Share metrics with others.</li><li>Approve and curate metrics.</li><li>Organize (tag) your metrics so people can find them.</li><li>Delete metrics.</li><li>Rename metrics.</li></ul>|
|API for Calculated Metrics|Part of the Adobe Analytics 2.0 API set.|

