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

It should go without saying, but for the revamped version of my simulations/plotting, I want to forego generating any code at all. I already have my working project as a reference and the boilerplate I'd like generated I can just yank from there. Dag gummit you can't build muscle when a robot does the exercise for you.

### Available Tutorials
<table>
  <tr>
    <th>Platform</th>
    <th>Title</th>
    <th>Summary</th>
    <th>AI Usage</th>
  </tr>
  <tr>
    <td>Orekit</td>
    <td>Hohmann Transfer</td>
    <td>Create a simulation of a simple Hohmann transfer. Calculate timing and magnitude of burns analytically. Attach <code>ImpulseManeuver</code>s to propagator and plot resulting trajectory. Notes on all imported Orekit objects and their purposes.</td>
    <td>Python code aside from timing of burns.</td>
  </tr>
</table>

### Upcoming
<table>
  <tr>
    <th>Platform</th>
    <th>Title</th>
    <th>Summary</th>
  </tr>
  <tr>
    <td>Orekit</td>
    <td>Propagator Comparisons</td>
    <td>Propagate the same, very low Earth, orbit to demonstrate how different propagators handle aerocapture. Notes on use cases for each category of propagator. </td>
  </tr>
  <tr>
    <td>Orekit</td>
    <td>Stationkeeping</td>
    <td>Stationkeeping demonstrated for spacecraft in LEO. Notes on different atmospheric models</td>
  </tr>
  <tr>
    <td>Orekit</td>
    <td>Trajectory Optimization</td>
    <td>Interplanetary trajectory and burn optimization using YAPSS.</td>
  </tr>
</table>

Early in this project, I will be leaning on AI tools more to generate code snippets for me to study and explain, but I will write my own analyses and **never** push AI-generated explanations. It doesn't help me, or anyone else, learn if the available references are peppered with hallucinated references and tools. Furthermore, unless I cite it explicitly in the AI column, the presented work can be assumed as my own.
