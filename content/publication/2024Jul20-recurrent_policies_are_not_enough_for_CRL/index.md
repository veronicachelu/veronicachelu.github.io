---
title: "Recurrent Policies Are Not Enough for Continual Reinforcement Learningt"
date: 2024-07-20
authors: ["Nathan de Lara", "Veronica Chelu", "Doina Precup"]
publication_types: ["3"]
abstract: "Continual Reinforcement Learning (CRL) aims to develop algorithms that adapt to
non-stationary sequences of tasks. A promising recent approach utilizes Recurrent
Neural Networks (RNNs) to learn contextual Markov Decision Process (MDP)
embeddings. This enables a reinforcement learning (RL) agent to discern the
optimality of actions across diverse tasks. In this study, we examine two critical
failure modes in the learning of these contextual MDP embeddings. Specifically, we
find that RNNs are prone to catastrophic forgetting, manifesting in two distinct ways:
(i) embedding collapse—where agents initially learn a contextual task structure that
later collapses to a single task, and (ii) embedding drift—where learning embeddings
for new MDPs interferes with embeddings the RNN outputs for previous MDPs in
the sequence, leading to suboptimal performance of downstream policy networks
conditioned on stale embeddings. We explore the effects of various objective functions
and network architectures concerning these failure modes, revealing that one of these
modes consistently emerges across different setups."
featured: true
publication: "*preprint*"
url_pdf: "https://drive.google.com/file/d/1scdul85AzCyGUEh0xWQyWos-eAVqKq_8/view?usp=sharing"
---
