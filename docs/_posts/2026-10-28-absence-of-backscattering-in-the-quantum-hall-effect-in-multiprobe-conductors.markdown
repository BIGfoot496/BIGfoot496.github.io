---
layout: posts
title:  "Absence of backscattering in the quantum Hall effect in multiprobe conductors"
category: "A paper a day"
date: 2026-10-28
tags: 
    - quantum mechanics
    - hall effect
    - condensed matter
    - electromagnetism
---

## A paper a day: day 26
I've returned, sorta. It turns out that reading a paper a day is much easier when reading papers is your main activity. Now I'm enrolled in a PhD programme (woohooo!), and... tbh, reading papers is still my main activity, so maybe I'm just whining. When I originally stopped posting, I did so because there was a conference that week, and my brain was too swamped by all the new info from presentations to read even more stuff and write even a single paragraph on it. I thought I'll return after the conference to cover papers mentioned during the talks, but I never did. I did read some stuff during the time -- textbooks, mostly. Dunno if I'll post daily again, but I'll try to keep it at least somewhat regular.

Anyways, today's [paper](https://doi.org/10.1103/PhysRevB.38.9375) is not from the conference. It's one I read yesterday. Once again, Hall effect, but now... *drumroll*... Quantum! It's one of the classics, pretty sure this paper is the reason Büttiker's name got attached to a generalisation of Landauer's formula.

Before this paper, Quantum Hall Effect was treated theoretically in closed conductors only. But the resistance quantization is actually detected in samples that have contacts! So this paper is answering the question of why dirty, disordered contacts don't destroy the effect. It first treats a perfect two-dimensional two terminal conductor in a high magnetic field, and gradually adds more and more disorder. It turns out that the only current-bearing states in a perfect conductor are the ones on the edges. These states are chiral (moving only right on the top edge, only left on the bottom), each edge is an equipotential line, and the two edges don't interact (no backscattering). Adding even high concentrations of elastic scatterers does not allow for backscattering. If one adds inelastic scattering, the conductor can be modeled as a number of coherent regions separated by phase randomising reservoirs. The edges, however, remain equipotential lines, and the resistance remains the same. Now add contacts that connect the QHE edge states to a region where 3D motion is allowed, characterized by their transmission and reflection coefficients. Turns out the resistance between these non-ideal contacts is now different from the resistance calculated in the ideal case, but the (quantized) Hall resistance between the edges of the sample (within a distance from the contacts larger than the inelastic scattering length) is exactly the same as before! The contacts lead to an initial nonequilibrium population in the edge states, but then the inelastic scatterings equilibrate them. What's more, if one adds several more disordered contacts between the current source and drain, they *still* don't affect the edge states in any way, if the sample is big enough. Which means every single pairwise resistance in the sample is completely determined by the transmission and reflection coefficients of the contacts, and the Hall resistance is *extremely* well quantized. 