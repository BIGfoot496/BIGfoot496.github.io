---
layout: posts
title:  "Spin-polarized electron transport for the altermagnet CrSb"
category: "A paper a day"
date: 2026-09-30
tags: 
    - hall effect
    - electromagnetism
    - condensed matter
---

## A paper a day: day 20
Today's [paper](https://arxiv.org/abs/2607.07334) is yet another work-related one, but now in a slightly different way: it was written by my advisor's group. It is related to what I'll be doing, though, so it was doubly useful (to be fair, my advisor was the one who sent it to me, so that was a gimme). 

The object under study -- chromium antimonide -- is altermagnetic. That means, among other things, that it does not have a net magnetic moment (like antiferromagnets), but the spin degeneracy is broken in most of the Brillouin zone (except for momenta that are time-reversal invariant by themselves). The absense of net magnetisation means there shouldn't be much anomalous Hall effect to speak of. And indeed there isn't: when a CrSb flake was placed on gold leads, and AC current passed through it, there was no measurable transverse voltage. However, when nickel leads were used instead, and the whole assembly placed inside a magnetic field, there was a measurable, albeit very noisy, AHE signal. Why? Because Ni is ferromagnetic, and the current passed through it is thus spin-polarised.

Nonlinear Hall effect arises from broken inversion symmetry just as anomalous Hall effect arises from broken time-reversal symmetry. I am not quite up to speed on the theory of all this (and seems likely some of the future papers here will come from me struggling to understand it), but from what I gathered so far, the equation for electron's velocity in a crystal has a term $$\dot{\textbf{k}} \times \textbf{\Omega}_k$$, and a bunch of mathemagic later you get that if inversion symmetry is broken, there is a transverse current at twice the frequency. CrSb is inversion symmetric, so there should not be much second harmonic transverse voltage if the sample is placed onto gold leads. There is _some_, for reasons unclear to me, and not really explained in the paper (I've seen other papers that claim detection of NLHE in inversion symmetric materials, but I haven't yet read any), but regardless, with ferromagnetic leads the measured second harmonic response is much more pronounced.

The thing I find sorely lacking in this paper is a _quantitative_ description of what the various curves they measured are expected to look like. So far it is only qualitative. I guess, if I'm gonna be doing related work, I'll find a friendly theoretical physicist that would explain (or produce?) models for this sort of stuff for me.