# Policy Gradient

This repository contains a draft document on Policy Gradient in Reinforcement Learning by Pedram Rabiee.

## Table of Contents

1. [Introduction](#introduction)
   1. [Why Policy Gradient?](#why-policy-gradient)
2. [Raw Policy Gradient](#raw-policy-gradient)
   1. [Definitions and Notations](#definitions-and-notations)
   2. [Policy Gradient Derivation](#policy-gradient-derivation)
   3. [REINFORCE](#reinforce)
   4. [State-Based Baseline](#state-based-baseline)
   5. [Vanilla Policy Gradient](#vanilla-policy-gradient)
   6. [Off-Policy Policy Gradient Using Importance Sampling](#off-policy-policy-gradient-using-importance-sampling)
3. [Actor-Critic](#actor-critic)
   1. [Actor-Critic Derivation](#actor-critic-derivation)
   2. [Discount Factor](#discount-factor)
   3. [Off-Policy Actor-Critic](#off-policy-actor-critic)
   4. [Actor-critic implementation notes](#actor-critic-implementation-notes)
4. [On-Policy Algorithms](#on-policy-algorithms)
   1. [GAE: Generalized Advantage Estimation](#gae-generalized-advantage-estimation)
5. [Off-Policy Algorithms](#off-policy-algorithms)
   1. [DDPG: Deep Deterministic Policy Gradient](#ddpg-deep-deterministic-policy-gradient)
   2. [SAC: Soft Actor-Critic](#sac-soft-actor-critic)
6. [Appendix I: Basic Statistics](#appendix-i-basic-statistics)
7. [Appendix II: Maximum Entropy Principle](#appendix-ii-maximum-entropy-principle)


## Citation

If you find this work useful and would like to cite it, please use the following BibTeX entry:

```bibtex
@misc{pedramrabiee-policy-gradient,
  author       = {Pedram Rabiee},
  title        = {Policy Gradient in Reinforcement Learning},
  year         = {2023},
  publisher    = {GitHub},
  journal      = {GitHub Repository},
  howpublished = {\url{https://github.com/pedramrabiee/Policy-Gradient}},
}
