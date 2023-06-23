---
title: "Optimism and Adaptivity in Policy Optimization"
date: 2023-01-01
# publishDate: 2023-06-10T20:23:40.732811Z
authors: ["Veronica Chelu", "Tom Zahavy", "Arthur Guez", "Doina Precup", "Sebastian Flennerhag"]
publication_types: ["3"]
abstract: "We work towards a unifying paradigm for accelerating policy optimization methods in reinforcement learning (RL) through optimism & adaptivity. Leveraging the deep connection between policy iteration and policy gradient methods, we recast seemingly unrelated policy optimization algorithms as the repeated application of two interleaving steps (i) an optimistic policy improvement operator maps a prior policy πt to a hypothesis π_t+1 using a gradient ascent prediction, followed by (ii) a hindsight adaptation of the optimistic prediction based on a partial evaluation of the performance of π_t+1. We use this shared lens to jointly express other well-known algorithms, including soft and optimistic policy iteration, natural actor-critic methods, model-based policy improvement based on forward search, and meta-learning algorithms. By doing so, we shed light on collective theoretical properties related to acceleration via optimism & adaptivity. Building on these insights, we design an adaptive & optimistic policy gradient algorithm via meta-gradient learning, and empirically highlight several design choices pertaining to optimism, in an illustrative task."
featured: true
publication: "*arXiv preprint*"
url_pdf: "https://arxiv.org/pdf/2202.09699.pdf"
---
