---
title: Teaching & Software
---

## Teaching

- Anthropological Genomics (BIO/ANTH 351; CCNY, Fall 2026)
- Population Genomic Inference of Demographic History (CUNY Graduate Center, Fall 2025)
- Anthropological Genomics of Dogs (CCNY, Spring 2025)
- Ecology and Evolution (Bio 228; CCNY, Fall 2023)
- Modeling Biodiversity (CUNY Graduate Center, Spring 2022)
- Ecology and Evolution (Bio 228; CCNY, Fall 2021)
- Anthropological Genomics (CCNY, Spring 2020)
- Population Genomic Simulation and Inference (CUNY Graduate Center, Fall 2019)
- Ecology and Evolution (Bio 228; CCNY, Spring 2019)
- Anthropological Genomics (Spring 2014)
- Population Genetics (CUNY Graduate Center, Fall 2013)
- Ecology and Evolution (Bio 228; Spring 2013)
- Anthropological Genomics (Spring 2012)
- BioStatistics (Bio 230; Fall 2011)
- Frontiers in Phylogeography (CUNY Graduate Center, Spring 2011)
- Statistical Phylogeography (CUNY Graduate Center, Spring 2010)
- Model-based Phylogeography, with Bryan Carstens and Naoki Takebayashi (Southwest Research Station, 2009 and 2010)

## Software

**Phylodiet.** A web app that scores a meal by the phylogenetic diversity of what's on the plate, using a dated tree of about 3,300 edible species.  
[Try it](https://mjhickerson.github.io/phylodiet/app/phylodiet.html) · [Code and data](https://github.com/mjhickerson/phylodiet)

**MESS (Massive Eco-evolutionary Synthesis Simulations).** A model of community assembly that jointly predicts species abundances, genetic diversity, and trait values. Led by Isaac Overcast, with Megan Ruffley, Mike Hickerson, Andy Rominger, and collaborators.  
[Code](https://github.com/messDiv/MESS) · [Documentation](https://pymess.readthedocs.io/) · [Paper](https://doi.org/10.1111/1755-0998.13514)

**PTA (Phylogeographic Temporal Analysis).** Comparative phylogeography from whole-genome or SNP data across co-distributed species. By Isaac Overcast.  
[Code](https://github.com/isaacovercast/PTA) · [Documentation](https://pta.readthedocs.io/en/latest/)

### Older software

**msBayes.** Hierarchical approximate Bayesian computation (HABC) for comparative phylogeographic inference across many taxa. It tests hypotheses and estimates hyper-parameters describing how consistently co-distributed taxon pairs share divergence or colonization times and biogeographic histories. MTML-msBayes is the multi-taxa, multi-locus version, with rate heterogeneity across loci.  
[Download](http://msbayes.sourceforge.net/) · [Manual](https://docs.google.com/document/d/15heQlz60cGe6GWKcXqf1AIYMBZ6p2sKuGct-EoEHiNU/edit?usp=sharing) · [Installation guide](https://docs.google.com/document/d/1enMQaogxOs0RppAmE8KcGU3nNjzotuiycAl6I1s0KYg/edit?usp=sharing)  
Contributors: Isaac Overcast, Wen Huang, Yan Qi, Naoki Takebayashi, Eli Stahl, Xiaoou Xie, and Mike Hickerson.

**R scripts for generic or msBayes ABC** (Wen Huang and Mike Hickerson)

- [Simulation testing of generic ABC](https://docs.google.com/Doc?docid=0AVkCIu87W8ooZGNyc3M2ZDhfMzljYnJkNmhnag&hl=en) using pseudo-observed data sets (PODS)
- Simulation testing of MTML-msBayes using PODS: [shell script](https://docs.google.com/Doc?docid=0AVkCIu87W8ooZGNyc3M2ZDhfNDdwczh6MnFjNg&hl=en), run on the command line, and the [R script](https://docs.google.com/Doc?docid=0AVkCIu87W8ooZGNyc3M2ZDhfNDhjODZ4cHdoNQ&hl=en) that runs inside it
- [Categorical model choice with ABC](https://docs.google.com/Doc?docid=0AVkCIu87W8ooZGNyc3M2ZDhfNDZkc201OGhncw&hl=en), e.g. testing migration vs isolation across taxon pairs, or estimating any other discrete parameter
- [Plotting N-dimensional Euclidean distances](https://docs.google.com/Doc?docid=0AVkCIu87W8ooZGNyc3M2ZDhfMzNjYjM3MmJocQ&hl=en) between the observed summary statistic vector and the accepted simulated ones
