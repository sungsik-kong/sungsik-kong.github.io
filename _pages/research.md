---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}

I am a computational evolutionary biologist who is interested in statistical and computational problems surrounding phylogenetic network estimation, and their applications in practice in understanding complex evolutionary histories including hybrid speciation, introgression, and gene flow. GOOGLE SCHOLR

### Inferring phylogenetic networks and hybridization

Reconstructing the 'tree of life' is the central goal in phylogenetics, however, the true relationship of taxa can never be inferred unless reticulate processes, such as hybridization, are taken into account. The network inference methods available today are largely categorized by their purposes, either to exhibit conflicting signals within data (i.e., abstract networks) or to model reticulate evolution (i.e., explicit networks), although the distinction often is vague in practice. It must be stressed that the former does not narrate evolutionary histories whereas the latter does, while being rarely used in practice due to excessive computational requirements. Because network inference using the explicit methods is NP-hard, only one or two individuals per subpopulation are included in the analysis which can result in insufficient signal to infer a relationship that is representative of the entire population. The objective for this aim is to develop a computational tool that infers phylogenetic networks with hybrid speciation using multi-locus data from multiple individuals per population with a feasible computational cost. 


### Applications of computational methods in evolutionary biology








### Detecting hybridization in nature















### Assessing appropriateness of computational tools for theirs uses in evolutionary biology

Tracking the spread of pandemics and the evolution of the underlying pathogens are effective tools for managing deadly outbreaks. Forster et al.(1) use a median-joining (MJ) network (MJN) and its Steinerization process to investigate the evolution of severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2), which causes coronavirus disease 2019 (COVID-19) within humans. They claim to “assist in tracing infection pathways and designing preventive strategies” by analyzing 160 genomes sampled worldwide. However, their assertation that “this method can contribute to an understanding of coronavirus evolution” is based on a misunderstanding of both the method and its interpretation. Because their work may have profound implications for understanding and managing the COVID-19 global pandemic, scrutiny is necessary. MJNs are not an appropriate representation of viral evolution. Although Forster et al …

Median‐joining (MJ) was proposed as a method for phylogeographical analysis and is enjoying increasing popularity. Herein, we evaluate the efficacy of the approach as originally intended. We show that median‐joining networks (MJNs) are theoretically untenable for evolutionary inference, and that confusion has afflicted their use for over 15 years. The approach has two obvious shortcomings: its reliance on distance‐based phenetics (overall similarity instead of character transformations) and the lack of rooting (no direction or history). Given that evolution involves both change and time, and the absence of rooting removes time (ancestor–descendant relationships) from the equation, the approach cannot yield defensible evolutionary interpretations. We also examine the impact of MJ analyses on evolutionary biology via an analysis of citations and conclude that the spread of MJNs through the literature is difficult …

Interspecific hybridization is an important evolutionary phenomenon that generates genetic variability in a population and fosters species diversity in nature. The availability of large genome scale datasets has revolutionized hybridization studies to shift from the examination of the presence or absence of hybrids in nature to the investigation of the genomic constitution of hybrids and their genome-specific evolutionary dynamics. Although a handful of methods have been proposed in an attempt to identify hybrids, accurate detection of hybridization from genomic data remains a challenging task. The available methods can be classified broadly as site pattern frequency based and population genetic clustering approaches, though the performance of the two classes of methods under different hybridization scenarios has not been extensively examined. Here, we use simulated data to comparatively evaluate the performance of four tools that are commonly used to infer hybridization events: the site pattern frequency based methods HyDe and the D-statistic (i.e., the ABBA-BABA test), and the population clustering approaches structure and ADMIXTURE. We consider single hybridization scenarios that vary in the time of hybridization and the amount of incomplete lineage sorting (ILS) for different proportions of parental contributions (γ ); introgressive hybridization; multiple hybridization scenarios; and a mixture of ancestral and recent hybridization scenarios. We focus on the statistical power to detect hybridization, the false discovery rate (FDR) for the D-statistic and HyDe, and the accuracy of the estimates of γ as measured by the mean squared error for …
