---
layout: single
title: "Limited-Lookahead Deadlock-Free Control"
permalink: /softwares/ll_ctrl_deadlockfree
author_profile: true
redirect_from:
  - /softwares/LL_Ctrl_DeadlockFree
  - /softwares/LL_DeadlockFree_Ctrl
  - /softwares/limited-lookahead
  - /softwares/limited-lookahead-deadlock-free-control
---

Website: [https://github.com/trigger1996/des_common/tree/master/limited_lookahead_deadlock_free](https://github.com/trigger1996/des_common/tree/master/limited_lookahead_deadlock_free)

**Supplementary material for the experimental results is [here](https://github.com/trigger1996/des_common/blob/master/limited_lookahead_deadlock_free/supplementary_material.pdf).**

Brief introduction:

`Limited-Lookahead Deadlock-Free Control` provides a Python implementation of limited-lookahead supervisory control for partially observed discrete-event systems modeled as deterministic finite automata. It constructs and prunes limited-lookahead bipartite transition systems (LL-BTS) to synthesize deadlock-free control policies, updating the lookahead window after observations.

The software includes closed-loop verification, supervisor and transition-system visualization, and reproducible case studies. Experimental tools compare limited-lookahead synthesis with full offline BTS construction and other limited-lookahead methods, reporting construction size, runtime, and memory use.
