# Thomas Holland

Earth scientist with interests in inverse problems and statistical geophysics. I am currently working on my MSci in Earth Sciences, having completed my project.

## Research Interests

- Bayesian inverse problems and uncertainty quantification  
- Dynamical systems and equation discovery  
- (Geophysical) inverse problems  

## Selected Projects

### MSci Dissertation — Bayesian Inversion for Sea Level and Ice Sheet Signals

A research project investigating the application of Bayesian inversion methods to estimate sea level change from satellite altimetry observations, incorporating sea level physics to improve upon traditional spatial averaging approaches.

Application of a infinite-dimensional Bayesian inversion framework to recover ice thickness change directly from sea surface height altimetry. Priors are defined as Gaussian measures over Sobolev spaces on the sphere, encoding physically motivated beliefs. The posterior is obtained in closed form and propagated through the full sea level physics without discretisation artefacts. Direct empirical evidence of well-calibrated and improved uncertainty quantification over traditional methods.

The methods developed here offer technical advances over other existing approaches: principled uncertainty propagation through the full modelled physics; full recovery of posteriors whose structure is inherited from physically motivated priors; and joint inference over competing signals with formal uncertainty quantification on the trade-offs between them.

[View project](https://github.com/0thomasholland/Part_III_Project)

<p align="center">
  <img src="https://github.com/0thomasholland/0thomasholland/blob/main/imgs/Screenshot%202026-04-13%20at%2013.06.41.png?raw=true" width="49%">
  <img src="https://github.com/0thomasholland/0thomasholland/blob/main/imgs/Screenshot%202026-04-13%20at%2013.07.08.png?raw=true" width="49%">
</p>

### Nonlinear Dynamics and Data Assimilation — Spring-Slider Study

Analysis of a two-state-variable quasi-static spring-slider exhibiting chaotic stick-slip dynamics. Covers Lyapunov spectrum computation (QR method), Grassberger-Procaccia correlation dimension, bifurcation diagrams over the dimensionless stiffness ratio, SDE ensemble analysis, and grid-based exact Bayesian data assimilation with reanalysis and EnKF comparison. Implemented in Julia.

[View project](https://github.com/0thomasholland/nldc-coursework)

<p align="center">
  <img src="https://github.com/0thomasholland/nldc-coursework/blob/main/.figures/code_example.png?raw=true" width="49%">
  <img src="https://github.com/0thomasholland/nldc-coursework/blob/main/figures/fig5_bayes_sde_assimilation_x123.png?raw=true" width="49%">
</p>

### Seismic Wave Forward Modeller (Rust)

2D elastic wave propagation on a staggered grid using finite differences, with Ricker wavelet sources, harmonic-averaged material properties, and parallel time-stepping via rayon. Configurable via TOML.

[View project](https://github.com/0thomasholland/computational-science-fun/tree/main/seismic-wave-modeller)

<p align="center">
  <img src="https://github.com/0thomasholland/computational-science-fun/raw/main/seismic-wave-modeller/output/1.gif" width="80%">
</p>

### Camdram Connected

Web app for finding shortest collaboration paths between any two people in Cambridge theatre using public Camdram data. Built as static HTML, CSS, and JavaScript on Cloudflare Pages, with a Pages Function proxy to handle Camdram API CORS restrictions.

- Solves manual digging through theatre credits by showing how any two people in Cambridge theatre are connected, using Camdram role data to recover shortest collaboration paths.
- Built as static HTML, CSS, and JavaScript on Cloudflare Pages, with a Pages Function proxy to handle Camdram API CORS restrictions without adding a build step.
- Uses a rate-limited, cache-backed breadth-first search that lazily expands person and show roles to keep external API usage under control.
- Adds debounced autocomplete, role-type filters, shareable URL state, PNG export, and a vis.js graph plus step-by-step details panel for each discovered path.

[View project](https://github.com/0thomasholland/camdram-connected)

### Critical Cellular Automaton (Fortran + Python)

A 3D self-organised criticality model written in Fortran: grains are added to a grid and redistribute when a threshold is exceeded, producing avalanche dynamics. Accompanied by a Python visualiser that renders rotating 3D animations of the evolving grid.

[View project](https://github.com/0thomasholland/computational-science-fun/tree/main/critical_cell)

### Website Development

I also do the occasional website development, for both [my own website at thomasholland.uk](https://thomasholland.uk) and the [Cambridge University Astronomical Society website](https://cuastronomy.co.uk).

## Languages

Python, Julia, Rust, Fortran, Bash, LaTeX
