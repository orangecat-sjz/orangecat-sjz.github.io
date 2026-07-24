---
layout: page
title: Representative Functional Dependencies
description: Discovering compact, non-redundant functional dependencies efficiently.
importance: 2
category: research
---

The number of valid functional dependencies can grow dramatically with dataset dimensionality, producing large collections with substantial duplication. This project asks how to discover a representative subset directly rather than filtering a fully materialized result.

We integrate representativeness verification into lattice traversal and use nearest indexes for pruning, dynamic stripped partitions for validation, and a compressed FD-tree to preserve minimality.

This work was presented at the **42nd IEEE International Conference on Data Engineering (ICDE 2026)**.

[ICDE 2026 program](https://icde2026.github.io/program_details.html)
