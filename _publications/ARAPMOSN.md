---
title: "A Random Algorithm for Profit Maximization in Online Social Networks"
collection: publications
permalink: /publications/ARAPMOSN
venue: "Theoretical Computer Science (TCS)"
date: 2019-3-26
citation: '<b>Tiantian Chen</b>, Bin Liu, Wenjing Liu, Qizhi Fang, Jing Yuan, Weili Wu.<i> Theoretical Computer Science (TCS), vol. 803, pp. 36-47, 2020</i>.'
---

[[PDF]](https://arxiv.org/abs/2101.06239)

## Abstract
Online social networks have been one of the most effective platforms for marketing and advertising. Through "word of mouth" effects, information or product
adoption could spread from some influential individuals to millions of users in social networks. Given a social network G and a constant k, the influence 
maximization problem seeks for k nodes in G that can influence the largest number of nodes. This problem has found important applications, and a large 
amount of works have been devoted to identifying the few most influential users. But most of existing works only focus on the diffusion of a single idea 
or product in social networks. However, in reality, one company may produce multiple kinds of products and one user may also have multiple adoptions. 
Given multiple kinds of different products with different activation costs and profits, it is crucial for the company to distribute the limited budget 
among multiple products in order to achieve profit maximization. Profit Maximization with Multiple Adoptions (PM2A) problem aims to seek for a seed set 
within the budget to maximize the overall profit. In this paper, a Randomized Modified Greedy (RMG) algorithm based on the Reverse Influence Sampling 
(RIS) technique is presented for the PM2A problem, which could achieve a (1−1/e−ε)-approximate solution with high probability. Compared with the algorithm 
proposed in [16] that achieves a (1−1/e^2)/2-approximate solution, our algorithm provides a better performance ratio which is also the best performance 
ratio of the PM2A problem. Comprehensive experiments on three real-world social networks are conducted, and the results demonstrate that our RMG algorithm 
outperforms the algorithm proposed in [16] and other heuristics in terms of profit maximization, and could better allocate the budget.
