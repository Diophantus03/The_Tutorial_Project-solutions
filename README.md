# The Tutorial Project - Solutions

This repository contains solutions to the exercises in Patrick Massot's tutorial (aka "the tutorial project). 

*Goal:* Prove a series of statements from undergraduate real analysis course in Lean 4, culminating in a proof of the intermediate value theorem. 

Let $f(a)$ and $f(b)$ be two continuous functions. 
 
**Theorem (IVT).** Let $u \in \mathbb{R}$ be such that 
$$\min (f(a), f(b)) < u < \max(f(a), f(b))$$
Then there exists $c \in (a, b)$ such that $f(c) = u$. 

To be simple, the above theorem states that if $f$ is a continuous function whose domain contains the interval $[a, b]$, then it takes on any given value between $f(a)$ and $f(b)$ at some point within the interval. 

The above theorem has two crucial corollaries. 

**Corollary (Bolzano's Theorem).** If a continuous function has values of opposite sign inside an interval, then it has a root in that interval

**Corollary.** The image of a continuous function over an interval is itself an interval.