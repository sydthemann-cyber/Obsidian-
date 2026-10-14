---
title: Geometric ordering in bacterial communities
authors: Melika Gorgi, Summer J. Kasallis, Calvin Trinh, Lizett Ortiz de Ora, Travis J. Wiles, Albert Siryaporn
year: "2026"
publication: Proceedings of the National Academy of Sciences
DOI: 10.1073/pnas.2526643123
urgl: https://www.pnas.org/doi/10.1073/pnas.2526643123
tags:
  - process/biofilm
  - ecology/community
Topic: biofilm
notes: true
---

###### Abstract
The organization of bacteria has a central role in shaping interactions, dynamics, and composition within communities and microbiomes. Bacteria form distinct spatial patterns that have often been attributed to microbial processes such as chemotaxis, nutrient transport, and signaling. However, common patterns are observed across distinct bacteria and conditions, suggesting that a general organizing principle could direct bacterial organization. Here, we find that the organization of bacteria is explained by geometric ordering that promotes space-filling efficiency, giving rise to geometric patterns known as Voronoi tessellations. We find that the Voronoi Growth Model accurately predicts bacterial pattern formation in diverse conditions including in biofilms at the liquid–air interface, swimming populations, the zebrafish gut, and conditions that promote swarming. The patterns are observed in two and three dimensions, at the cm and mm length scales, across diverse species (Vibrio cholerae, Pseudomonas aeruginosa, Escherichia coli), arise solely from the principles of Voronoi tessellation, and require no detailed knowledge of microbial processes. Entropic considerations show that bacteria provide little or no information about the pattern formation, which is determined solely by their initial positions and environmental conditions. These findings demonstrate that bacterial communities achieve robust, reproducible organization through a universal geometric principle, linking microbial patterning to the broader biological context of multicellular organization.

### Summary

This paper demonstrates that large-scale bacterial spatial organization can often be explained by **geometric ordering** rather than species-specific biological mechanisms. Across *Vibrio cholerae*, *Pseudomonas aeruginosa*, *Escherichia coli*, and mixed-species communities, bacterial populations self-organize into **Voronoi tessellations** through two simple rules: radial expansion and growth arrest upon contact. The resulting spatial patterns are highly predictable using a parameter-free Radial Growth Model (RGM), suggesting that physical constraints can dominate community organization across diverse environments, including swimming populations, biofilms, swarms, and the zebrafish gut. :contentReference[oaicite:0]{index=0}

### Related

- [[Biofilm]]
- [[Biofilm Development]]
- [[Competition Sensing]]
- [[Flagellum]]


### Detailed Notes

#### Central hypothesis

- bacterial spatial organization may arise from universal geometric rules rather than species-specific signaling pathways
- physical constraints alone can generate reproducible community architecture
- Voronoi tessellations maximize space-filling efficiency

---

#### Radial Growth Model (RGM)

Simple rules:

1. populations begin from fixed positions
2. expand radially in all directions
3. all populations grow at equal rate (unless modified)
4. expansion stops upon contact with neighboring population
5. expansion also stops at physical boundaries

No incorporation of

- chemotaxis
- quorum sensing
- nutrient diffusion
- signaling gradients
- gene regulation

Despite this, RGM accurately predicts experimental organization.

---

#### Voronoi tessellations

Definition

- geometric partition of space
- each region contains points closest to one founder population

Properties

- efficient space filling
- boundaries determined solely by founder positions
- independent of microbial physiology

---

#### Swimming V. cholerae

Conditions

- 0.2% agar
- flagellar motility

Observations

- colonies expand radially
- collision produces sharp linear boundary
- populations remain segregated
- non-colliding fronts continue expanding

Model agreement

- Jaccard similarity ≈0.95

---

#### Biofilm organization

Conditions

- ΔpomAB mutants
- liquid-air pellicle
- viscoelastic medium

Observations

- radial pellicle expansion
- collision transforms circular colonies into hexagonal Voronoi domains
- wrinkles appear after collision due to compressive forces

Implication

- motility is not required
- geometry also governs biofilm organization

---

#### Swarming P. aeruginosa

- Voronoi boundaries emerge before dendritic swarming develops
- dendrites form only at expanding fronts
- collision boundaries remain stable

---

#### Mixed-species communities

Species

- Plesiomonas
- Aeromonas

Different growth rates produce

- curved interfaces
- weighted Voronoi tessellations
- faster species occupy larger territory

Growth rate influences geometry but not underlying organizational principle.

---

#### Zebrafish gut

Two fluorescent E. coli strains

Observations

- distinct clonal territories
- linear and curved interfaces
- RGM reproduces 3D organization

Suggests

- gut mucus restricts mixing
- bacterial aggregates expand clonally
- host-associated communities also follow Voronoi geometry

---

#### Colony growth

Firm agar

- expanding colonies produce sectors
- founder position determines sector boundaries
- unequal growth rates generate sector dominance

---

#### Requirements for Voronoi organization

Required

- radial clonal expansion
- contact inhibition between neighboring populations

Disrupted by

- flow
- mixing
- asymmetric growth
- strong mechanical perturbation
- low cell density

---

#### Entropy

Pattern contains essentially no new configurational information

Information required

- initial founder positions

Pattern formation

- determined by geometry
- not by molecular details

---

#### Biological implications

Physical organization

- may emerge independently of signaling
- conserved across bacteria and multicellular organisms
- provides efficient partitioning of space and resources

Potential applications

- engineered microbial consortia
- synthetic communities
- prediction of biofilm architecture
