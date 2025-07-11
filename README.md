# Efficient simulation of individual-based population models

[![build status](https://github.com/computorg/published-202412-giorgi-efficient/actions/workflows/build.yml/badge.svg)](https://github.com/computorg/published-202412-giorgi-efficient)
[![DOI:10.57750/sfxn-1t05](https://img.shields.io/badge/DOI-10.57750/sfxn--1t05-034E79.svg)](https://doi.org/10.57750/sfxn-1t05)
[![reviews](https://img.shields.io/badge/review-report%201-blue)](https://github.com/computorg/published-202412-giorgi-efficient/issues/2)
[![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/computorg/published-202412-giorgi-efficient/)](https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/computorg/published-202412-giorgi-efficient)
[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

Authors:

- Daphné Giorgi (Sorbonne Université, CNRS)
- Sarah Kaakai (Le Mans Université)
- Vincent Lemaire (Sorbonne Université, CNRS)

The `R` Package `IBMPopSim` aims to simulate the random evolution of
heterogeneous populations using stochastic Individual-Based Models (IBMs). The
package enables users to simulate population evolution, in which individuals
are characterized by their age and some characteristics, and the population is
modified by different types of events, including births/arrivals, death/exit
events, or changes of characteristics. The frequency at which an event can
occur to an individual can depend on their age and characteristics, but also
on the characteristics of other individuals (interactions). Such models have a
wide range of applications in fields including  actuarial science, biology,
ecology or epidemiology. `IBMPopSim` overcomes the limitations of
time-consuming IBMs simulations by implementing new efficient algorithms
based on thinning methods, which are compiled using the `Rcpp` package while
providing a user-friendly interface.`


