---
id: 2028
title: '[FYI] KAIST Theory Day (May 31, 2015)'
postdate: 2015-05-11T13:41:41+09:00
author: sangil
layout: post
guid: http://mathsci.kaist.ac.kr/~sangil/seminar/?p=2028
permalink: /kaist-theory-day-2015/
categories:
  - "2015"
  - KAIST Discrete Math Seminar
tags:
  - DanielStefankovic
  - EricVigoda
  - MartinZiegler
  - YitongYin
  - 신진우
  - 오세웅
  - 이의웅
date: 2015-05-31
---
FYI: (KAIST Theory Day organized by [Jinwoo Shin](https://sites.google.com/site/mijirim/) and [Eric Vigoda](http://www.cc.gatech.edu/~vigoda/))

<div class="talk">
  KAIST Theory Day
</div>

<div class="date">
  2015/5/31 Sun 10AM-5PM (Building N1, room 102, KAIST)
</div>

<table>
  <tr>
    <td width="15%">
      9:30 &#8211;
    </td>
    
    <td width="85%">
      Coffee and refreshments
    </td>
  </tr>
  
  <tr>
    <td>
      10:00 &#8211;
    </td>
    
    <td>
      <b><a href="https://www.cs.rochester.edu/~stefanko/">Daniel Stefankovic (Rochester)</a></b>:  <a href="http://www.cc.gatech.edu/~vigoda/KAIST/Daniel.html">Spin models: connections between complexity, phase transition, belief propagation, and induced matrix norms</a>
    </td>
  </tr>
  
  <tr>
    <td>
      11:00 &#8211;
    </td>
    
    <td>
      <a href="http://tcs.nju.edu.cn/yinyt/Yitong_Yin_homepage.html"><b>Yitong Yin (Nanjing)</b></a>: <a href="http://www.cc.gatech.edu/~vigoda/KAIST/Yitong.html">Phase transition of hypergraph matchings</a>
    </td>
  </tr>
  
  <tr>
    <td>
      12:00 &#8211;
    </td>
    
    <td>
      Lunch break
    </td>
  </tr>
  
  <tr>
    <td>
      1:30 &#8211;
    </td>
    
    <td>
      <a href="http://www.cs.cmu.edu/~euiwoonl/"><b>Euiwoong Lee (CMU)</b></a>:  <a href="http://www.cc.gatech.edu/~vigoda/KAIST/Euiwoong.html">Hardness of Graph Pricing through Generalized Max-Dicut</a>
    </td>
  </tr>
  
  <tr>
    <td>
      2:30 &#8211;
    </td>
    
    <td>
      <a href="http://web.engr.illinois.edu/~swoh/"><b>Sewoong Oh (UIUC)</b></a>:  <a href="http://www.cc.gatech.edu/~vigoda/KAIST/Sewoong.html">Data processing inequality for differential privacy and applications</a>
    </td>
  </tr>
  
  <tr>
    <td>
      3:30 &#8211;
    </td>
    
    <td>
      Coffee break
    </td>
  </tr>
  
  <tr>
    <td>
      4:00 &#8211;
    </td>
    
    <td>
      <a href="http://m.zie.de/"><b>Martin Ziegler (TU Darmstadt)</b></a>:  <a href="http://www.cc.gatech.edu/~vigoda/KAIST/Martin.html">Algebraic Complexity Theory and Quantum Logic</a>
    </td>
  </tr>
</table>

<span style="line-height: 1.5;">Speaker: Daniel Stefankovic</span>

Title: Spin models: connections between complexity, phase transition, belief propagation, and induced matrix norms

> <span style="line-height: 1.5;">What are the typical configurations of a spin model (for example, Ising model, or Potts model) on a random regular graph? We show that the answer to this question is characterized by tree recursions (belief propagation) and p->q operator matrix norms.</span>
> 
> Understanding the typical configurations allows us to show hardness of approximating the partition function for certain multispin models (for example, Potts model) on d-regular graphs in the non-uniqueness regime (that is, when the Gibbs measure on infinite d-regular tree is not unique). Joint work with Andreas Galanis, and Eric Vigoda.

Speaker: Yitong Yin

Title: Phase transition of hypergraph matchings

> We study the problem of approximately counting weighted matchings in hypergraphs of bounded maximum edge size and maximum degree. The problem is expressed as evaluating the partition function, which is the weighted sum of all macthings in a hypergraph where each macthing M is assigned a weight λ|M| in terms of a fixed activity parameter λ. This model unifies two important problems in approximate counting arising from statistical physics: counting independent set (the hardcore model) and counting matchings (the monomer-dimer model).
> 
> We show that for hypergraph matchings, the critical activity λc= dd/k(d-1)(d+1) is the uniqueness threshold for the Gibbs measure on (d+1)-uniform (k+1)-regular hyper-tree, and when λ<λc, the hypergraphs of maximum edge size at most d+1 and maximum degree at most k+1 exhibit strong spatial mixing. As a consequence, there is an FPTAS for counting matchings in hypergraphs of bounded maximum edge size at most and bounded maximum degree as long as the uniqueness condition is satisfied.
> 
> As for the inapproximability, it can be easily shown that there is no FPRAS for the problem when λ>2λc, unless NP=RP. This left an intriguing gap between λc and 2λc. A key step towards tight inapproximability result is the local weak convergence from a sequence of finite graphs to the extremal measures for the uniqueness threshold on the infinite tree. For hypergraph matchings, we discover that such local weak convergence does not exist for any sequence of finite hypergraphs, which indicates that approximate counting on hypergraphs (or general CSPs) contains much richer structure yet to be understood.

Speaker: Euiwoong Lee

Title: Hardness of Graph Pricing through Generalized Max-Dicut

> <span style="line-height: 1.5;">The Graph Pricing problem is among the fundamental problems whose approximability is not well-understood. While there is a simple combinatorial ¼-approximation algorithm, the best hardness result remains at ½ assuming the Unique Games Conjecture (UGC). We show that it is NP-hard to approximate within a factor better than ¼ under the UGC, so that the simple combinatorial algorithm might be the best possible.</span>
> 
> This work is based on the effort to view the Graph Pricing problem as a Constraint Satisfaction Problem (CSP) simpler than the standard and complicated formulation. We propose the problem called Generalized Max-Dicut(T), which has a domain size T + 1 for every T ≥ 1 . Generalized Max-Dicut(1) is well-known Max-Dicut. Besides its connection to Graph Pricing, the hardness of Generalized Max-Dicut is interesting in its own right since in most arity two CSPs studied in the literature, SDP-based algorithms perform better than LP-based or combinatorial algorithms &#8212; for this arity two CSP, a simple combinatorial algorithm does the best.

Speaker: Sewoong Oh

Title: Data processing inequality for differential privacy and applications

> <span style="line-height: 1.5;">We provide a hypothesis testing interpretation to differential privacy and derive natural forward and reverse data processing inequalities. These inequalities are very useful in deriving tight impossibility results, as demonstrated by the following two applications: composing multiple queries and multi-party computation. The impossibility results hold for arbitrary parameter settings (privacy levels, number of queries, etc) and for both standard and approximate differential privacy settings. Further, these impossibility results cannot be improved upon.</span>

Speaker: Martin Ziegler

Title: Algebraic Complexity Theory and Quantum Logic

> <span style="line-height: 1.5;">Algebraic models of computation (like register machines) make one operation per step regardless of the value processed. They underly algorithms for sorting or in computational geometry. As opposed to bit models, algebraic methods permit to establish non-trivial lower bounds:</span>
> 
> We recall Morgenstern&#8217;s elegant proof that the fast fourier transform is optimal; then proceed to the structural complexity theory and prove the quantum satisfiability problem complete for NP_R^0: a well-known discrete complexity class between NP and PSPACE. (Joint work with Christian Herrmann.)