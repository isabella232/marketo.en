---
unique-page-id: 7504676
description: Understanding Period Costs - Marketo Docs - Product Documentation
title: Understanding Period Costs
---

# Understanding Period Costs {#understanding-period-costs}

Understanding Period Costs - Marketo Docs - Product Documentation

#### Overview {#understandingperiodcosts-overview}

Period costs refer to the money you spend in a specific month on a program.

>[!NOTE]
>
>**Example**
>
>If you spend $1000 to hire an illustrator for an eBook that launches in July - the eBook program would have a period cost of $1000 in July.
>
>If you spend $200 per month on Google Adwords - the Google Adwords program would have a period cost of $200 **every month**.

>[!NOTE]
>
>**Deep Dive**
>
>[Understanding Programs](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)
>
>[Understanding Program Membership](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)

#### How Period Costs are Calculated {#understandingperiodcosts-howperiodcostsarecalculated}

Imagine an event, like a webinar, that occurs in March. New people are acquired beforehand from advertising in January and February. New contacts are also acquired after the event, when people download the webinar in the months of April and May.

##### 1. With a single period cost attributed to March... {#understandingperiodcosts-withasingleperiodcostattributedtomarch...}

![](assets/graph1.png)

...contacts added in the months before and after will *only* count towards March.

![](assets/graph2.png)

##### 2. With period costs attributed to January, February, and March... {#understandingperiodcosts-withperiodcostsattributedtojanuary-february-andmarch...}

![](assets/graph3.png)

...contacts added only in the months after March will count towards March.

![](assets/graph4.png)

##### 3. With period costs attributed to January and April... {#understandingperiodcosts-withperiodcostsattributedtojanuaryandapril...}

![](assets/graph5.png)

...contacts added in the months January through March will count towards January. Contacts added in the months April and May will count towards April.

![](assets/graph6.png)

>[!NOTE]
>
>**Reminder**
>
>In summary - months with no defined period costs will roll "backwards" to the last one that was defined. If there is no prior period cost, the months will be rolled "forward" to the next one that has been defined. If a period cost has not been defined for *any* months, reporting in RCE will not be available for the program.

>[!NOTE]
>
>**Related Articles**
>
>* [Using Period Costs in a Program](using-period-costs-in-a-program.md)
>* [Filter a Program Report by Period Cost](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/programs/program-performance-report/filter-a-program-report-by-period-cost.md)
>
