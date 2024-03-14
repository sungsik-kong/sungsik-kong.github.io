---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

I am a **computational evolutionary biologist** who focuses on developing methods that quantitatively analyze large genomic data to answer questions arising in biology, using techniques and concepts from statistics and computer science. The overarching theme of my research topics is to infer hybridization and phylogenetic networks using genomic data.

## Inferring phylogenetic networks from the sequence data

While phylogenetic networks can model more complex biological histories that the bifurcating trees cannot, the use of networks in evolutionary investigations is limited by the inability of existing methods to handle large datasets due to their algorithmic complexity. I propose a novel method, **PhyNEST** (Phylogenetic Network Estimation using SiTe Patterns), for inferring phylogenetic networks directly from sequence data. **PhyNEST** achieves computational efficiency by employing the composite likelihood framework in the network setting and accuracy by incorporating all sources of variability in genome data through quartet site pattern frequencies. Composite likelihood approximates the likelihood; however, it has been shown to be extremely useful in phylogenetic context and may offer a promising direction to alleviate the computational burden required to compute the full likelihood. The method is implemented in publicly available, open-source software [[download at github]](https://github.com/sungsik-kong/PhyNEST.jl).

### Relevant publications
- [Inference of phylogenetic networks from sequence data using composite likelihood](https://doi.org/10.1101/2022.11.14.516468)
- [Classes of explicit phylogenetic networks and their biological and mathematical significance](https://doi.org/10.1007/s00285-022-01746-y)
- [Digest: Frequent hybridization in *Darevskia* rarely leads to the evolution of asexuality](https://doi.org/10.1111/evo.14587)

## Expanding the network space

## Application of phylogenies to the real-world problems

## Detecting hybridization using genomic data

## Advancement of machine learning in evolutionary biology

## Theoretical evaluation of abstract networks in evolutionary investigations

Median-joining (MJ) was proposed as a method for phylogeographical analysis and is enjoying increasing popularity. Herein, we evaluate the efficacy of the approach as originally intended. We show that median-joining networks (MJNs) are theoretically untenable for evolutionary inference, and that confusion has afflicted their use for over 15 years. The approach has two obvious shortcomings: its reliance on distance-based phenetics (overall similarity instead of character transformations) and the lack of rooting (no direction or history). Given that evolution involves both change and time, and the absence of rooting removes time (ancestor–descendant relationships) from the equation, the approach cannot yield defensible evolutionary interpretations. We also examine the impact of MJ analyses on evolutionary biology via an analysis of citations and conclude that the spread of MJNs through the literature is difficult to explain, especially given the availability of character-based analyses.

### Publications
 <a href="https://doi.org/10.1111/cla.12147">On the use of median-joining networks in evolutionary biology</a><br>
 <a href="https://doi.org/10.1073/pnas.2007062117">Median-joining network analysis of SARS-CoV-2 genomes is neither phylogenetic nor evolutionary</a>




## Methods for hybrid detection using genomic dataset

We used simulated data to comparatively evaluate the performance of four tools that are commonly used to infer hybridization events: HyDe, the D-statistic, structure and ADMIXTURE. We consider single hybridization scenarios that vary in the time of hybridization and the amount of incomplete lineage sorting (ILS) for different proportions of parental contributions (⁠γ⁠); introgressive hybridization; multiple hybridization scenarios; and a mixture of ancestral and recent hybridization scenarios. We focus on the statistical power to detect hybridization and the false discovery rate (FDR) for comparisons of the D-statistic and HyDe, and the accuracy of the estimates of γ as measured by the mean squared error for HyDe, structure, and ADMIXTURE. Both HyDe and the D-statistic are powerful for detecting hybridization in all scenarios except those with high ILS, although the D-statistic often has an unacceptably high FDR. The estimates of γ in HyDe are impressively robust and accurate whereas structure and ADMIXTURE sometimes fail to identify hybrids, particularly when the proportional parental contributions are asymmetric. Moreover, the posterior distribution estimated using structure exhibits multimodality in many scenarios, making interpretation difficult. 

### Publications
 <a href="https://doi.org/10.1093/sysbio/syaa092">Comparative Performance of Popular Methods for Hybrid Detection using Genomic Data</a>
