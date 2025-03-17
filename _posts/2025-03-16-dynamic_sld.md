---
title: "Practical and Parallel Dynamic Tree Contraction"
categories: "project"
---

Dynamic tree contraction has proven to be a powerful technique to solve the dynamic trees problem, since it is amenable to parallelism, and supports a large suite of queries. However it suffers from the requirement that the input tree is degree bounded. Because of this, data structures require ternarization of the input tree which hurts the performance in many ways. We describe a new dynamic tree contraction data structure called UFO tree, which does not require ternarization. We show that this allows for an extremely effective implementation that is on par with link/cut trees, which has been the best performing sequential dynamic tree data structure for decades.
