[![DOI](https://zenodo.org/badge/591360037.svg)](https://zenodo.org/badge/latestdoi/591360037)

# Experience, Ownership, and Code Quality Study 2023

This repo contains a complete replication package, including raw data and scripts for the statistical analysis, for the paper "U Owns the Code That Changes and How Marginal Owners Resolve Issues Slower in Low-Quality Source Code" accepted for the EASIER Track at the [27th International Conference on Evaluation and Assessment in Software Engineering (EASE)](https://conf.researchr.org/home/ease-2023), Oulu, Finland, June 14-16, 2023.

## Authors

Markus Borg, Adam Tornhill, and Enys Mones

## Abstract

[Context] Accurate time estimation is a critical aspect of predictable software engineering. Previous work shows that low source code quality increases the uncertainty in issue resolution times.
[Objective] Our goal is to evaluate how developers' project experience and file ownership are related to issue resolution times. [Method] We mine 40 proprietary software repositories and conduct an observational study. Using CodeScene, we measure source code quality and active development time connected to Jira issues.  [Results] Most source code changes are made by either a marginal or dominant code owner. Also, most changes to low-quality source code are made by developers with low levels of ownership. In low-quality source code, marginal owners need 45% more time for small changes, and 93% more time for large changes. [Conclusions] Collective code ownership is a popular target, but industry practice results in many dominant and marginal owners. Marginal owners are particularly hampered when working with low-quality source code, which leads to productivity losses. In codebases plagued by technical debt, newly onboarded developers will require more time to complete tasks.

## Repository Content
- A Jupyter Notebook. The number of dependencies is limited and all imports are in the first cell.
- Anonomous data in a csv-file.
