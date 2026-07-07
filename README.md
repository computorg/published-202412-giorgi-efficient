# Efficient simulation of individual-based population models
Daphné Giorgi, Sarah Kaakai, Vincent Lemaire
2025-01-27

### Citation

Daphné Giorgi, Sarah Kaakai and Vincent Lemaire (January 2025). Efficient simulation of individual-based population models. Computo.
<https://doi.org/10.57750/sfxn-1t05>

### Badges

[![build and
publish](https://github.com/computorg/published-202412-giorgi-efficient/actions/workflows/build.yml/badge.svg)](https://github.com/computorg/published-202412-giorgi-efficient/actions/workflows/build.yml)
[![reviews](https://img.shields.io/badge/review-report-blue)](https://github.com/computorg/published-202412-giorgi-efficient/issues?q=is%3Aopen+is%3Aissue+label%3Areview)
[![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/computorg/published-202412-giorgi-efficient)](https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/computorg/published-202412-giorgi-efficient)
[![DOI:10.57750/sfxn-1t05](https://img.shields.io/badge/DOI-10.57750%2Fsfxn--1t05-034E79.svg)](https://doi.org/10.57750/sfxn-1t05)
[![Creative Commons
License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

### Authors’ affiliations

- [Daphné Giorgi](https://perso.lpsm.paris/~giorgi/) (Sorbonne Université, CNRS)
- [Sarah Kaakai](https://www.math.univ-paris13.fr/~kaakai/) (Université Sorbonne Paris Nord, CNRS, Ecole Polytechnique, CNRS)
- [Vincent Lemaire](https://perso.lpsm.paris/~vlemaire/) (Sorbonne Université, CNRS)

### Abstract

The `R` Package `IBMPopSim` facilitates the simulation of the random
evolution of heterogeneous populations using stochastic Individual-Based
Models (IBMs). The package enables users to simulate population
evolution, in which individuals are characterized by their age and some
characteristics, and the population is modified by different types of
events, including births/arrivals, death/exit events, or changes of
characteristics. The frequency at which an event can occur to an
individual can depend on their age and characteristics, but also on the
characteristics of other individuals (interactions). Such models have a
wide range of applications in fields including actuarial science,
biology, ecology or epidemiology. `IBMPopSim` overcomes the limitations
of time-consuming IBMs simulations by implementing new efficient
algorithms based on thinning methods, which are compiled using the
`Rcpp` package while providing a user-friendly interface.
