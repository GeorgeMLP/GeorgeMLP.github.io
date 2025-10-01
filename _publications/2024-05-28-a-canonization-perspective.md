---
title: "A Canonicalization Perspective on Invariant and Equivariant Learning"
collection: publications
permalink: /publication/2024-05-28-a-canonization-perspective
excerpt: 'We analysed the efficiency and expressiveness of invariant and equivariant networks from a canonicalization perspective.'
date: 2024-09-25
venue: 'NeurIPS'
paperurl: 'https://openreview.net/forum?id=jjcY92FX4R&noteId=jjcY92FX4R'
citation: 'George Ma, Yifei Wang, Derek Lim, Stefanie Jegelka, Yisen Wang (2024). A Canonicalization Perspective on Invariant and Equivariant Learning. In <i>Thirty-eighth Conference on Neural Information Processing Systems</i>.'
---
In many applications, we desire neural networks to exhibit invariance or equivariance to certain groups due to symmetries inherent in the data. Recently, frame-averaging methods emerged to be a unified framework for attaining symmetries efficiently by averaging over input-dependent subsets of the group, i.e., frames. What we currently lack is a principled understanding of the design of frames. In this work, we introduce a canonicalization perspective that provides an essential and complete view of the design of frames. Canonicalization is a classic approach for attaining invariance by mapping inputs to their canonical forms. We show that there exists an inherent connection between frames and canonical forms. Leveraging this connection, we can efficiently compare the complexity of frames as well as determine the optimality of certain frames. Guided by this principle, we design novel frames for eigenvectors that are strictly superior to existing methods --- some are even optimal --- both theoretically and empirically. The reduction to the canonicalization perspective further uncovers equivalences between previous methods. These observations suggest that canonicalization provides a fundamental understanding of existing frame-averaging methods and unifies existing equivariant and invariant learning methods.