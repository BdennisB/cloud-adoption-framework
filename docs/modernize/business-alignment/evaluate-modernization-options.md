---
title: Evaluate cloud modernization readiness
description: Learn how to evaluate your technical and financial cloud readiness to determine which workloads you want to modernize during cloud adoption.
author: stephen-sumner
ms.author: ssumner
ms.date: 09/07/2022
ms.topic: conceptual
ms.service: cloud-adoption-framework
ms.subservice: modernize
ms.custom: internal, seo-caf-modernize
keywords: evaluate, technical, financial indicators, workloads, modernize, cloud adoption framework
---
# Evaluate cloud modernization readiness

Once you've envisioned your cloud modernization possibilities, evaluate whether you're ready to modernize in the cloud.

Evaluating your readiness for modernization has two components. You need to assess your financial readiness and technical readiness.

- *Financial readiness assessment* - helps you determine if you need more time to review your applications.
- *Technical readiness assessment* - helps you determine if you need to choose a different adoption path other than modernize.

## Step 1 - Evaluate the financial readiness of each workload

A financial readiness assessment helps you determine if it makes business sense to modernize your workload. Financial motivations are the key drivers of cloud modernization. Cloud modernizations can improve margins through efficiencies and generate new revenue streams. To realize those benefits, you need to evaluate the financial aspects of the effort.

For each workload you want to modernize, answer the following questions to assess your financial readiness.

- *Can you quantify the business value of modernizing the workload?*
- *Do you know what your modernization cost will be?*
- *Are these workloads business-critical?*
- *Does the cost of modernization meet your desired cost savings?*

Answering *yes* to all questions means you're likely ready to modernize. If you answered *no* to any of the questions, we recommend you conduct an [Azure Well-Architected Review](/assessments/?mode=pre-assessment&session=local) of your workload

The next step, [technical readiness evaluation](#step-2---evaluate-the-technical-readiness-of-each-workload), will help you determine if you're ready to modernize or find another adoption path.

## Step 2 - Evaluate the technical readiness of each workload

A technical readiness assessment helps you determine if your workload is ready for modernization or is better fit for a different cloud adoption strategy.

For each workload you want to modernize, answer the following questions to begin assess your technical readiness.

|Question|Yes|No|
|--|--|--|
|*Do you have enough control over the workload to modernize it?*|Modernize| Migrate|
|*Is your business actively investing<br> in these workloads?*|Modernize|Replace|
|*Will these modernized workloads <br>need to operate in hybrid or<br> multicloud environment?* |Modernize|Migrate|
|*Are your workloads portable?*|Modernize|Migrate|
|*Do you plan to keep the current architecture?*|Modernize|Conduct Azure Well-Architected Review|

If you answered *yes* to all the technical-readiness questions, you're likely ready to modernize the workload.

## Next steps

You've [envisioned](envision-cloud-modernization.md) and [evaluated](evaluate-modernization-options.md). It's time to commit to a modernization path.

> [!div class="nextstepaction"]
> [Commit to modernization](commit-to-modernization-plan.md)
