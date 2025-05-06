---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

{% include base_path %}

## Open-Source Projects

### [PhyNEST.jl](https://github.com/sungsik-kong/PhyNEST.jl)
**Phylogenetic Network Estimation using Site Patterns (Julia)**  
`PhyNEST.jl` is a Julia package for inferring phylogenetic networks from sequence alignments using site pattern-based methods. It enables robust estimation of complex reticulate evolutionary histories under the multispecies network coalescent model.

- Written in pure Julia for speed and flexibility
- Accepts data in Nexus and Phylip formats
- Supports hybridization and incomplete lineage sorting
- Includes utilities for visualizing and analyzing networks
- Integrates with [PhyloNetworks.jl](https://github.com/crsl4/PhyloNetworks.jl)

> **Status**: Actively developed | **License**: MIT  
> 🔗 [View on GitHub](https://github.com/sungsik-kong/PhyNEST.jl)

---

### [SymbolicQuartetNetworkCoal.jl](https://github.com/sungsik-kong/SymbolicQuartetNetworkCoal.jl)
**Symbolic Computation of Expected Quartet Concordance Factors**  
`SymbolicQuartetNetworkCoal.jl` is a Julia package for symbolically computing expected concordance factors under the network multispecies coalescent model. It supports exact symbolic derivations and is ideal for theoretical work and benchmarking.

- Derives closed-form expressions for concordance factors
- Supports both tree and reticulate topologies
- Symbolic manipulation of coalescent probabilities
- Built using Julia’s symbolic computation libraries

> **Status**: Research-ready | **License**: MIT  
> 🔗 [View on GitHub](https://github.com/sungsik-kong/SymbolicQuartetNetworkCoal.jl)

---

If you use these tools in your research, please cite the relevant software or publications (see [Research](/research/)). Contributions and feedback are welcome!
