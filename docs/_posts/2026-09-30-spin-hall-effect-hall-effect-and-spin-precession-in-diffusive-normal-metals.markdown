---
layout: posts
title:  "Spin Hall effect, Hall effect and spin precession in diffusive normal metals"
category: "A paper a day"
date: 2026-09-30
tags: 
    - hall effect
    - electromagnetism
    - condensed matter
---

## A paper a day: day 20
Today's [paper](https://arxiv.org/abs/cond-mat/0409130) I read trying to find where the value for spin-orbit coupling constant in aluminum $$\alpha=0.006$$ comes from (question arose while reading [another paper](https://arxiv.org/abs/cond-mat/0605423), where there was an aluminum Hall cross, and there was a tiny but measurable spin Hall transverse voltage). That question is stil unanswered, I've still no clue who's measurements produced that value, but this paper explained a bit of theory I had troubles with. As, for instance the precise nature of the dimensionless coupling constant $$\alpha$$ itself. It is the coefficient before the anomalous current caused by the spin-orbit interaction: $$v_{so} =\frac{\alpha}{\hbar k_F^2}(\bf{\hat{\sigma}} \times \bf{\nabla} V_{imp})$$. The gradient in the potential due to impurities results in scattering, or at least that's how I understand it. 

The paper is really a classic kind of theoretical paper: introduce a Hamiltonian, talk a little about what each potential term means, and then do a bunch of calculations. They derive diffusion equations for charge and spin in a metal, and solve them for two "easy" useful cases: a thin strip of metal between two reservoirs, and a thin strip of metal between two tunneling contacts (current incoming from a ferromagnet and going out into a normal metal). For the most part everything is expanded in terms of $$\alpha$$, which is posited to be small (if we're talking about stuff like Al or Cu, it is very much a reasonable approximation). 