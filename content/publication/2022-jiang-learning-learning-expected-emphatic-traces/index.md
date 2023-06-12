---
title: "Learning Expected Emphatic Traces for Deep RL"
date: 2021-01-01
# publishDate: 2023-06-10T20:23:40.734521Z
authors: ["Ray Jiang", "Shangtong Zhang", "Veronica Chelu", "Adam White", "Hado van Hasselt"]
publication_types: ["1"]
abstract: "Off-policy sampling and experience replay are key for improving sample efficiency
and scaling model-free temporal difference learning methods. When combined
with function approximation, such as neural networks, this combination is known
as the deadly triad and is potentially unstable. Recently, it has been shown that
stability and good performance at scale can be achieved by combining emphatic
weightings and multi-step updates. This approach, however, is generally limited
to sampling complete trajectories in order, to compute the required emphatic
weighting. In this paper we investigate how to combine emphatic weightings with
non-sequential, off-line data sampled from a replay buffer. We develop a multi-step
emphatic weighting that can be combined with replay, and a time-reversed n-step
TD learning algorithm to learn the required emphatic weighting. We show that
these state weightings reduce variance compared with prior approaches, while
providing convergence guarantees. We tested the approach at scale on Atari 2600
video games, and observed that the new X-ETD(n) agent improved over baseline
agents, highlighting both the scalability and broad applicability of our approach."
featured: false
publication: "*AAAI Conference on Artificial Intelligence*"
url_pdf: "https://arxiv.org/pdf/2107.05405.pdf"
---

