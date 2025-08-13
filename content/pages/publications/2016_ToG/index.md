---
title: "Parallel Inverse Kinematics for Multithreaded Architectures (ToG 2016)"
date: 2016-08-01
draft: false
description: "Parallel Inverse Kinematics for Multithreaded Architectures"
tags: ["Moka Studio", "Publications", "Computer Animation", "Inverse Kinematics", "Parallel Computing"]
authors : ["Pawan Kumar Harish", "Mentar Mahmudi", "Benoit Le Callennec", "Ronan Boulic"]
---

{{% columns ratio="3:1" class="space-x-4" %}} <!-- begin columns block -->

**In ACM Transactions on Graphics, vol. 35, num. 2, 2016. Presented at SIGGRAPH 2016.**

In this article, we present a parallel prioritized Jacobian-based inverse kinematics algorithm for multithreaded architectures. We solve damped least squares inverse kinematics using a parallel line search by identifying and sampling critical input parameters. Parallel competing execution paths are spawned for each parameter in order to select the optimum that minimizes the error criteria. Our algorithm is highly scalable and can handle complex articulated bodies at interactive frame rates. We show results on complex skeletons consisting of more than 600 degrees of freedom while being controlled using multiple end effectors. We implement the algorithm both on multicore and GPU architectures and demonstrate how the GPU can further exploit fine-grain parallelism not directly available on a multicore processor. Our implementations are 10 to 150 times faster compared to a state-of-the-art serial implementation while providing higher accuracy. We also demonstrate the scalability of the algorithm over multiple scenarios and explore the GPU implementation in detail.

{{< youtubeLite id="DAeP8nI6340" label="ToG (2016)" >}}

<---> <!-- magic separator, between columns -->

<div class="[&>figure]:my-4">
</div>

[Related project]({{< relref "/pages/projects/2016_rnd_Mosketch/" >}})

[View at publisher](https://dl.acm.org/doi/10.1145/2887740)

{{% /columns %}}
