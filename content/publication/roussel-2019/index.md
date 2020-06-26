---
title: "Designing chain reaction contraptions from causal graphs"
date: 2019-07-01
authors: ["Robin Roussel", "Marie-Paule Cani", "Jean-Claude Léon", "Niloy J. Mitra"]
publication_types: ["2"]
abstract: "Chain reaction contraptions, commonly referred to as Rube Goldberg machines, achieve simple tasks in an intentionally complex fashion via a cascading sequence of events. They are fun, engaging and satisfying to watch. Physically realizing them, however, involves hours or even days of manual trial-and-error effort. The main difficulties lie in predicting failure factors over long chains of events and robustly enforcing an expected causality between parallel chains, especially under perturbations of the layout. We present a computational framework to help design the layout of such contraptions by optimizing their robustness to possible assembly errors. Inspired by the active learning paradigm in machine learning, we propose a generic sampling-based method to progressively approximate the success probability distribution of a given scenario over the design space of possible scene layouts. The success or failure of any given simulation is determined from a user-specified causal graph enforcing a time ordering between expected events. Our method scales to complex causal graphs and high dimensional design spaces by dividing the graph and scene into simpler sub-scenarios. The aggregated success probability distribution is subsequently used to optimize the entire layout. We demonstrate the use of our framework through a range of real world examples of increasing complexity, and report significant improvements over alternative approaches."
featured: false
publication: "*ACM Transactions on Graphics (SIGGRAPH '19)*"
tags: ["success probability distribution", "computational design", "causal graphs", "robust design", "chain reactions"]
doi: "10.1145/3306346.3322977"
url_project: "http://geometry.cs.ucl.ac.uk/projects/2019/causal-graphs/"
url_pdf: "http://geometry.cs.ucl.ac.uk/projects/2019/causal-graphs/paper_docs/Roussel_causalGraphs_siggraph19_authorVersion.pdf"
url_video: "https://youtu.be/aBH-iPAR92c"
image:
  preview_only: true

---
This publication also appeared in the French newspaper [Le Monde](https://www.lemonde.fr/sciences/article/2019/08/19/l-art-de-fabriquer-des-machines-infernales_5500719_1650684.html). 
