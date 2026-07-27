---
layout: articles
title: Astrodynamics Tutorials
cover: https://archive.gps.gov/multimedia/images/GPS-III-A.jpg
date: 2026-07-27
articles:
  type: brief
---

### [Repo Link](https://github.com/GeostationaryBeaver/astro-tutorials/tree/main)

Astrodynamics tools like Orekit don't have beginner-to-intermediate-friendly tutorials lying around the internet. After [fighting for my life](/2026/07/25/new-repo-idea.html) with Orekit last spring, I figured I'd make references that I wish I had as I learn more about Orekit and other computational astrodynamics software. As of when I first start this repo, my goal is to recreate my [astrodynamics final project](https://github.com/GeostationaryBeaver/16.346-Astrodynamics/tree/main), while significantly improving the performance and (ideally) accuracy.

It should go without saying, but for the revamped version of my simulations/plotting, I want to forego generating any code at all. I already have my working project as a reference and the boilerplate I'd like generated I can just yank from there. Dag gummit you can't build muscle when a robot does the exercise for you. With the tutorials, I'll point out 

Presently, the only tutorial is on a simple Hohmann transfer in Orekit. For now, I'd like to remain focused on Orekit, adding in tutorials on:

- creating custom force models
- creating and propagating satellite constellations
- applying maneuvers for station-keeping
- tracking solar incidence
- performing low-thrust maneuvers (and comparing/contrasting them with impulsive maneuvers)

### For the future, I should probably make a table of the tutorials I have made and then another table of the upcoming ones I want to make.

I think I'll format it like:

| Tutorial Type | Title of Tutorial | Learning Outcome | AI Usage |
|---------------|---|---|---|
| Orekit | Hohmann Transfer | Create and propagate a spacecraft which performs a Hohmann transfer | All Python Code |

And w.r.t. AI usage, anything I don't say explicitly as written by AI can be assumed to be my own, original work. Regardless of what I use AI for, I'll always present code that I have revised/vetted. I will ***not*** be posting up code haphazardly. I should also probably put in a references part to the table. Yeah, academic honesty, I like that.