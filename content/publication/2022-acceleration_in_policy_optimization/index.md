---
title: "Acceleration in Policy Optimization"
date: 2023-06-18
# publishDate: 2023-06-10T20:23:40.732811Z
authors: ["Veronica Chelu", "Tom Zahavy", "Arthur Guez", "Doina Precup", "Sebastian Flennerhag"]
publication_types: ["3"]
abstract: "We work towards a unifying paradigm for accelerating policy optimization methods in reinforcement learning (RL) by integrating foresight in the policy improvement step via optimistic and adaptive updates. Leveraging the connection between policy iteration and policy gradient methods, we view policy optimization algorithms as iteratively solving a sequence of surrogate objectives, local lower bounds on the original objective. We define optimism as predictive modelling of the future behavior of a policy, and adaptivity as taking immediate and anticipatory corrective actions to mitigate accumulating errors from overshooting predictions or delayed responses to change. We use this shared lens to jointly express other well-known algorithms, including model-based policy improvement based on forward search, and optimistic meta-learning algorithms. We analyze properties of this formulation, and show connections to other accelerated optimization algorithms. Then, we design an optimistic policy gradient algorithm, adaptive via meta-gradient learning, and empirically highlight several design choices pertaining to acceleration, in an illustrative task."
featured: true
publication: "*arXiv preprint*"
url_pdf: "https://arxiv.org/abs/2306.10587"
---
