---
layout: page
title: InvariantOODG
description: Invariant feature learning for 3D point cloud OOD generalization (ICASSP 2024)
importance: 2
category: research
related_publications: true
---

**InvariantOODG** addresses the domain gap between synthetic and real 3D point clouds for out-of-distribution generalization.

The method uses a two-branch network to extract local-to-global features from original and augmented point clouds. A set of learnable anchor points identifies useful local regions, and two augmentation transformations improve invariant representation learning.

Experiments on 3D domain generalization benchmarks show strong robustness on unseen scenes.

{% cite zhang2024invariantoodg %}
