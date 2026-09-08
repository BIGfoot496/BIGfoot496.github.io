---
layout: posts
title:  "A simple derivation for the skin effect in a round wire"
category: "A paper a day"
date: 2026-09-06
tags: 
    - electromagnetism
---

## A paper a day: day 3
Today's [paper](https://doi.org/10.1088/0143-0807/35/2/025002) is my admission of defeat. First, I tried reading Horace Lamb's original 1883 paper, but after like four pages I had to drop it. Not only does he operate in components of vectors, and writes triples of equations for everything, rather than use vector identities, like a *sane person*, he also gives *each component a SEPARATE LETTER*... I'm not fuming, you're fuming!

Anyway, this paper is from the European counterpart to yesterday's journal, so the derivation is meant to be comprehensible by an undergraduate student. I'm kinda disappointed in that, because the author decided that an undergraduate student should be more familiar with the integral formulations of Maxwell equations than the differential ones, and that solving an integral equation would be easier for them than a PDE... I'm sure for some people that is indeed the case, but I've always found the differential forms (yes, pun intended) cleaner and easier work with. And yes, this derivation is nice, yielding an equation for current in terms of its own double integral, which is solved by iteratively plugging J into the expression for J. But the resulting solution is a series, and I don't have the analysis prowess required to recognise the Bessel function in that mess. Dunno why the author thought it would be simpler than using vector identities...