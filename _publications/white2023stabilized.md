---
title: "Stabilized Neural Differential Equations for Learning Dynamics with Explicit Constraints"
authors: "Alistair White, Niki Kilbertus, Maximilian Gelbrecht, Niklas Boers"
collection: publications
permalink: /publications/stabilization
excerpt: 'Many successful methods to learn dynamical systems from data have recently been introduced. However, ensuring that the inferred dynamics preserve known constraints, such as conservation laws or restrictions on the allowed system states, remains challenging. We propose stabilized neural differential equations (SNDEs), a method to enforce arbitrary manifold constraints for neural differential equations.'
date: 2023-12-01
venue: 'Advances in Neural Information Processing Systems'
paperurl: 'https://arxiv.org/abs/2306.09739'
---
Many successful methods to learn dynamical systems from data have recently been introduced. However, ensuring that the inferred dynamics preserve known constraints, such as conservation laws or restrictions on the allowed system states, remains challenging. We propose stabilized neural differential equations (SNDEs), a method to enforce arbitrary manifold constraints for neural differential equations. Our approach is based on a stabilization term that, when added to the original dynamics, renders the constraint manifold provably asymptotically stable. Due to its simplicity, our method is compatible with all common neural differential equation (NDE) models and broadly applicable. In extensive empirical evaluations, we demonstrate that SNDEs outperform existing methods while broadening the types of constraints that can be incorporated into NDE training.
