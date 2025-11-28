---
layout: page
title: DiRe Research Universe
subtitle: D.R.U.
---

<sup><sub>Disclaimer: Any similarity or resemblance of the project’s name to a certain cinematic universe is purely non-coincidental. 
  That said, I acknowledge that I personally have no idea about what goes on in MCU or DCU. 
  I use this analogy to stress that research is as fun as watching a DCU or an MCU movie (assuming most people love watching these movies). 
  </sub></sup>


The DiRe Research Universe (DiRe - Diversity and Representation) is a research project that uses insights from theoretical computer science to delineate the notions of diversity and representation. Currently, in the context of multiwinner elections, we observe that:
* just like correlation does not imply causation, diversity does not imply representation (and vice-versa).
* on the surface, diversity and representation in multiwinner elections may seem mathematically equivalent just like the vertex cover problem on *d*-regular hypergraphs and on *k*-uniform hypergraphs, respectively. However, on zooming in, these are as different as the vertex cover problem on *d*-regular hypergraphs and on *k*-uniform hypergraphs, respectively. 

Overall, the vision is to extrapolate this understanding to a more general setting and, more importantly, understand the origins of DRU.

#### Why care about DRU?
The need to reduce inequality is ubiquitous. At least three of the United Nations’ Sustainable Development Goals directly focus on this aim. However, the incorrect conflation of diversity and representation may be doing more harm than good. For instance, a [paper](https://www.nature.com/articles/s41586-021-03788-6) published in Nature and a [resolution](https://web.archive.org/web/20241107192559/https://www.brown.senate.gov/newsroom/press/release/brown-portman-introduce-rooney-rule-resolution-to-increase-minority-representation-in-the-private-sector) presented in the United States Senate incorrectly conflate these two terms. Hence, in the pursuit to reduce inequality, DRU intends to highlight the importance of delineating diversity and representation. Overall, if you care about reducing inequality or fair AI or responsible AI, this universe will interest you. (If you are a technical geek, it may be an added reason!!)

---
## 1. Development
---
The evolution of DRU can be classified into the following phases.

#### 1.1 Phase One - The Ideation
The DiRe committee paper [1], initially planned as a standalone release, eventually led to the creation of DRU and, hence, constitutes the Phase One. In this paper, we motivated the need for constraints on the selection of committee members from candidate groups *and* voter populations. This use of constraints eventually resulted in the delineation between diversity and representation.  

#### 1.2 Phase Two - The Realization
At a high level, Phase Two of DRU extended the DiRe committee paper [1] from two perspectives: fairness [2] and theoretical [3]. The former aimed to showcase the systematic unfairness that may be caused by a diverse and representative outcome, and the latter aimed to study the existence of DiRe outcomes and its corresponding complexity (read: is finding a diverse *and* representative outcome (of a certain size) PPAD( or PPA)-complete (under certain realistic assumptions)?). Moreover, an interesting consequence of the latter aim was the establishment of an equivalence between DiRe Committees and the vertex cover problem.

#### 1.3 Phase Three - A Result
Having established the relationship between DiRe Committees and the vertex cover problem in Phase Two, DRU evolves towards exploiting this relationship to overcome barriers that delay our progress in reaching the goal of finding DiRe committees and, broadly, reducing inequality. 

Specifically, what sort of barriers are we talking about? How can we overcome such barriers? Does a solution here have an impact on domains not related to reducing inequality? The first segment of a **new** release [4.1] moves towards answering these and more such questions by discovering a new data structure (termed "represents table") whose unique properties, in turn, are helping in the discovery of an unconditional deterministic polynomial-time algorithm for an NP-complete problem, namely the vertex cover problem on cubic bridgeless graphs [4.2].

#### 1.4 Future Plan

**Phase ZERO - The Origin**: 
Even before the work on Phase Three nears its completion, DRU's fourth phase, being labeled as Phase ZERO, is already in the pipeline. Releasing the papers in the previous phases, especially Phase 3, was like putting the cart before the horse. This means that Phase ZERO, a prequel, will propose a theory (with potentially some empirical backing, if needed) that highlights the reasons why DRU exists. Stay tuned for updates on this Big Bang of DRU!


*A ~17-minute video that provides a brief overview of the phase-wise evolution of DRU and, in particular, the development of Phase Three, can be found [here](https://www.youtube.com/watch?v=UY-EEAB1tMI) (recorded: August 16, 2024).*

---
## 2. Releases
---

**[1]** *DiRe Committee*: Diversity and Representation Constraints in Multiwinner Elections. <br/>
***K. Relia.*** <br/>
Proceedings of the Thirty-First International Joint Conference on Artificial Intelligence, IJCAI-22. [link](https://doi.org/10.24963/ijcai.2022/714)

**[2]** Fairly Allocating Utility in Constrained Multiwinner Elections.  <br/>
***K. Relia.*** <br/>
Pre-print, 2022. [link](https://arxiv.org/pdf/2211.12820.pdf)

**[3]** On the Complexity of Finding a Diverse and Representative Committee using a Monotone, Separable Positional Multiwinner Voting Rule.  <br/>
***K. Relia.*** <br/>
Pre-print, 2022. [link](https://arxiv.org/pdf/2211.13217.pdf)

**[4.1]** On Efficient Computation of DiRe Committees. <br/>
***K. Relia.*** <br/>
Pre-print, 2024. [link](https://arxiv.org/pdf/2402.19365.pdf), [Slides 1](https://docs.google.com/presentation/d/1FJscULC9PZA4am6KJJgP6V1v2YPTrrPB/edit?usp=sharing&ouid=116854247679466528662&rtpof=true&sd=true), [Slides 2](https://docs.google.com/presentation/d/10bKCa4lX0fwvEVpaDMJ_YGmcVDFO_kqb/edit?usp=sharing&ouid=116854247679466528662&rtpof=true&sd=true). <br/>

**[4.2]** On the Computational Complexity of the Vertex Cover Problem on Cubic Bridgeless Graphs. <br/>
***K. Relia.*** <br/>
*We discover that VC-CBG (also called VCCBG but not VCBG) is (i) NP-complete and (ii) in P.* <br/>
Pre-print, 2025. [link](https://kunalrelia.github.io/img/VCBG.pdf) <br/>

**[5]** Unnamed Phase ZERO release. <br/>
AY 2025-26

---
## 3. Acknowledgment
---
The universe was co-produced by (a.k.a. research was generously co-supported by) Julia Stoyanovich’s NSF grants. 

<sup><sub>(Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation or the PI.)</sub></sup>
