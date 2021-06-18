---
abstract: >-
  We explore the use of policy approximations to reduce the computational cost
  of learning Nash equilibria in zero-sum stochastic games. We propose a new
  Q-learning type algorithm that uses a sequence of entropy-regularized soft
  policies to approximate the Nash policy during the Q-function updates. We
  prove that under certain conditions, by updating the entropy regularization,
  the algorithm converges to a Nash equilibrium. 

  We also demonstrate the proposed algorithm's ability to transfer previous training experiences, enabling the agents to adapt quickly to new environments. We provide a dynamic hyper-parameter schedule scheme to further expedite convergence. Empirical results applied to a number of stochastic games verify that the proposed algorithm converges to a Nash equilibrium, while exhibiting a major speed-up over existing algorithms.
slides: SNQ2
url_pdf: ""
publication_types:
  - "1"
authors:
  - Yue Guan
  - Qifan Zhang
  - Panagiotis Tsiotras
author_notes:
  - Equal contribution
  - Equal contribution
publication: In *International Joint Conference on Artificial Intelligence*
summary: We use entropy-regulated policy approximations to expedite learning
  Nash equilibrium in zero-sum stochastic games.
url_dataset: ""
url_project: ""
publication_short: In *IJCAI-21*
url_source: ""
url_video: ""
title: Learning Nash Equilibria via Entropy-Regularized Policy Approximation
subtitle: ""
doi: ""
featured: true
tags: []
projects:
  - Multi-Agent Reinforcement Learning
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
date: 2013-07-01T00:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
