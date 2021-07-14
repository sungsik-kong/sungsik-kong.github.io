---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

I am a computational evolutionary biologist who is interested in statistical and computational problems surrounding phylogenetic network estimation, and their applications in practice in understanding complex evolutionary histories including hybrid speciation, introgression, and gene flow. 


## Inferring phylogenetic networks and hybridization

Reconstructing the 'tree of life' is the central goal in phylogenetics, however, the true relationship of taxa can never be inferred unless reticulate processes, such as hybridization, are taken into account. The network inference methods available today are largely categorized by their purposes, either to exhibit conflicting signals within data (i.e., abstract networks) or to model reticulate evolution (i.e., explicit networks), although the distinction often is vague in practice. It must be stressed that the former does not narrate evolutionary histories whereas the latter does, while being rarely used in practice due to excessive computational requirements. Because network inference using the explicit methods is NP-hard, only one or two individuals per subpopulation are included in the analysis which can result in insufficient signal to infer a relationship that is representative of the entire population. The objective for this aim is to develop a computational tool that infers phylogenetic networks with hybrid speciation using multi-locus data from multiple individuals per population with a feasible computational cost. 




## Use of abstract networks in evolutionary biology

Median-joining (MJ) was proposed as a method for phylogeographical analysis and is enjoying increasing popularity. Herein, we evaluate the efficacy of the approach as originally intended. We show that median-joining networks (MJNs) are theoretically untenable for evolutionary inference, and that confusion has afflicted their use for over 15 years. The approach has two obvious shortcomings: its reliance on distance-based phenetics (overall similarity instead of character transformations) and the lack of rooting (no direction or history). Given that evolution involves both change and time, and the absence of rooting removes time (ancestor–descendant relationships) from the equation, the approach cannot yield defensible evolutionary interpretations. We also examine the impact of MJ analyses on evolutionary biology via an analysis of citations and conclude that the spread of MJNs through the literature is difficult to explain, especially given the availability of character-based analyses.

###Publications
 <a href="https://doi.org/10.1111/cla.12147">On the use of median-joining networks in evolutionary biology</a><br>
 <a href="https://doi.org/10.1073/pnas.2007062117">Median-joining network analysis of SARS-CoV-2 genomes is neither phylogenetic nor evolutionary</a>




## Methods for hybrid detection using genomic dataset

We used simulated data to comparatively evaluate the performance of four tools that are commonly used to infer hybridization events: HyDe, the D-statistic, structure and ADMIXTURE. We consider single hybridization scenarios that vary in the time of hybridization and the amount of incomplete lineage sorting (ILS) for different proportions of parental contributions (⁠γ⁠); introgressive hybridization; multiple hybridization scenarios; and a mixture of ancestral and recent hybridization scenarios. We focus on the statistical power to detect hybridization and the false discovery rate (FDR) for comparisons of the D-statistic and HyDe, and the accuracy of the estimates of γ as measured by the mean squared error for HyDe, structure, and ADMIXTURE. Both HyDe and the D-statistic are powerful for detecting hybridization in all scenarios except those with high ILS, although the D-statistic often has an unacceptably high FDR. The estimates of γ in HyDe are impressively robust and accurate whereas structure and ADMIXTURE sometimes fail to identify hybrids, particularly when the proportional parental contributions are asymmetric. Moreover, the posterior distribution estimated using structure exhibits multimodality in many scenarios, making interpretation difficult. 

###Publications
 <a href="https://doi.org/10.1093/sysbio/syaa092">Comparative Performance of Popular Methods for Hybrid Detection using Genomic Data</a>
