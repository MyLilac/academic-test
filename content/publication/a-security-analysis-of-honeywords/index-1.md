---
title: A Security Analysis of Honeywords
publication_types:
  - "1"
authors:
  - Wang
  - Ding and Cheng
  - Haibo and Wang
  - Ping and Yan
  - Jeff and Huang
  - Xinyi
publication: NDSS 2018
abstract: "Proposed by Juels and Rivest at CCS'13, honeywords are decoy
  passwords associated with each user account, and they contribute a promising
  approach to detecting password leakage. This approach has been covered by
  hundreds of medias and also been adopted in various research domains. The idea
  of honeywords looks deceptively simple, but it is a deep and sophisticated
  challenge to automatically generate honeywords that are hard to differentiate
  from real passwords. In Juels-Rivest's work, four main honeyword-generation
  methods are suggested but only justiﬁed by heuristic security arguments. In
  this work, we for the ﬁrst time develop a series of experiments using 10
  large-scale password datasets, a total of 104 million real-world passwords, to
  evaluate the security that these four methods can provide. Our results reveal
  that they all fail to provide the expected security: real passwords can be
  distinguished with a success rate of 29.29%~32.62% by our basic
  trawling-guessing attacker, but not the claimed 5%, with just one guess (when
  each user account is associated with 19 honeywords as recommended). This ﬁgure
  reaches 34.21%~49.02% under the advanced trawling-guessing attackers who make
  use of various state-of-the-art probabilistic password models. We further
  evaluate the security of Juels-Rivest's methods under a targeted-guessing
  attacker who can exploit the victim'personal information, and the results are
  even more alarming: 56.81%~67.98%. Overall, our work resolves three open
  problems in honeyword research, as deﬁned by Juels and Rivest."
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-06-02T07:38:46.331Z
---
