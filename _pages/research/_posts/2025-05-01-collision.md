---
layout: project
category: past-projects
title: Polyhedral Collision Detection via Vertex Enumeration
arxiv: https://arxiv.org/abs/2501.13201
authors: Andrew Cinar, Yue Zhao, Forrest Laine
image: collision.png
venue: ICRA2025
permalink: 'projects/collision'
date: 2025-05-01
abstract: "Collision detection is a critical functionality for
robotics. The degree to which objects collide cannot be repre-
sented as a continuously differentiable function for any shapes
other than spheres. This paper proposes a framework for
handling collision detection between polyhedral shapes. We
frame the signed distance between two polyhedral bodies as
the optimal value of a convex optimization, and consider
constraining the signed distance in a bilevel optimization
problem. To avoid relying on specialized bilevel solvers, our
method exploits the fact that the signed distance is the minimal
point of a convex region related to the two bodies. Our
method enumerates the values obtained at all extreme points
of this region and lists them as constraints in the higher-level
problem. We compare our formulation to existing methods in
terms of reliability and speed when solved using the same
mixed complementarity problem solver. We demonstrate that
our approach more reliably solves difficult collision detection
problems with multiple obstacles than other methods, and is
faster than existing methods in some cases."
---

In this work we develop a novel bilevel optimization approach to handling polytope collision detection problem, and we show that it may offer reliability and computational benefits in scenarios where contact between two polytope primitives are expected and desired.