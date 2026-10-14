---
title: Eco-evolutionary responses to plasmid-dependent phage constrain the spread of multidrug-resistance plasmids
authors: Daniel Cazares, Eliza Rayner, Adrian Cazares, Wendy Figueroa, David Goulding, Samuel T E Greenrod, Adam J Mulkern, Michelle Y Y Yin, Tao He, Nick Thomson, Michael A Brockhurst, R Craig MacLean
year: "2026"
publication: The ISME Journal
DOI: 10.1093/ismejo/wrag113
urgl: https://academic.oup.com/ismej/article/doi/10.1093/ismejo/wrag113/8673213
tags:
  - genetics/plasmid
  - interaction/resistance
  - organism/bacteria/e-coli
  - organism/phage
  - genetics/HGT
  - evolution
Topic: Phage
notes: true
---

###### Abstract
Phage therapy offers an alternative to antibiotics for treating multidrug-resistant infections. Plasmid-dependent phages (PDPs) are promising therapeutics as they can kill targeted pathogens and prevent the spread of plasmid-encoded antibiotic resistance genes. However, the evolutionary trajectories of multidrug-resistance (MDR) plasmids under the selective pressure of PDPs remain poorly understood, particularly in eco-evolutionary contexts that remain permissive to plasmid conjugation. We experimentally evolved populations of Escherichia coli carrying the MDR plasmid RP4 in the presence of the plasmid-dependent phage PRD1 under conditions where the benefits of conjugation were either strong or weak. When opportunities for conjugation were rare, PRD1 only transiently suppressed the conjugative plasmid population due to the rapid evolution of phage-resistant plasmids lacking conjugative ability. Increasing ecological opportunities for conjugation enhanced plasmid suppression and delayed the evolution of phage-resistant plasmids. PRD1 resistance was associated with plasmid loss and reduced conjugative ability, though this trade-off was complex because resistance mutations caused heterogeneous effects on pilus production and conjugation. Mutations and insertion sequence (IS)-mediated inactivation in conjugation genes generated a spectrum of resistance phenotypes, from partial (trbB, trbL) to complete (virB4/trbE) resistance. Bioinformatic analysis of publicly available IncP plasmids revealed frequent truncations of the VirB4/TrbE protein, suggesting that plasmid-dependent phages may represent an important selective pressure shaping plasmid evolution in natural populations. Our results demonstrate an evolutionary trade-off between conjugative ability and phage resistance that plasmids cannot easily circumvent. Targeting multidrug-resistance plasmids with PDPs is likely to drive loss of conjugation, limiting the transfer of antibiotic resistance genes in microbial communities.

### Summary

This paper investigates how **plasmid-dependent phages (PDPs)** influence the evolution and spread of multidrug resistance (MDR) plasmids. Using experimental evolution of *E. coli* carrying the conjugative RP4 plasmid and challenged with phage PRD1, the authors demonstrate that phage pressure selects against conjugative pili, producing plasmids that are resistant to infection but poor at horizontal transfer. Increasing ecological opportunities for conjugation (continuous influx of plasmid-free recipients) slows resistance evolution because conjugation becomes more beneficial. The study reveals a strong evolutionary trade-off between phage resistance and plasmid mobility, suggesting PDPs could both eliminate resistant bacteria and reduce dissemination of AMR genes. :contentReference[oaicite:0]{index=0}

### Related

- [[Mobile Genetic Elements]]
- [[HGT]]
- [[Conjugation]]
- [[Phage Therapy]]
- [[Antimicrobial Resistance]]
- [[Defense Islands]]
- [[Restriction-Modification Systems]]
- [[Phage–Host Arms Race]]
- [[T4SS]]
- [[Conjugative Pili]]

### Detailed Notes

#### Experimental system

- donor = *E. coli* MG1655 carrying RP4::GFP
- recipient = plasmid-free *E. coli* J53
- plasmid = RP4 (broad host range IncP MDR plasmid)
- phage = PRD1 (plasmid-dependent phage)
- PRD1 receptor = conjugative pilus
- evolution = 12 day serial passage (~43–56 generations)
- treatments:
  - no phage
  - phage
  - immigration
  - phage + immigration

---

#### Ecological manipulation

Immigration treatment

- daily addition of plasmid-free recipient cells
- increases opportunity for conjugation
- increases selective benefit of maintaining conjugative pili

---

#### Main ecological result

Without immigration

- phage rapidly suppresses plasmid population
- resistant plasmids evolve quickly
- plasmid abundance recovers

With immigration

- suppression lasts much longer
- resistance evolves more slowly
- conjugative plasmids maintained longer

→ ecological context changes evolutionary trajectory.

---

#### Mechanism of suppression

PRD1

- infects conjugative donor cells
- suppresses donor population
- suppresses transconjugants
- reduces plasmid transfer
- selects for complete plasmid loss in many cells (~50%)

---

#### Evolutionary trade-off

Selection favors mutations that

- reduce pilus function
- prevent PRD1 infection

but simultaneously

- reduce conjugation
- reduce plasmid spread

Therefore

greater phage resistance

↓

lower horizontal transfer.

---

#### Genes repeatedly mutated

Most mutations occurred in Tra2 region

Genes

- trbE (VirB4 ATPase)
- trbI
- trbJ
- trbB
- trbL
- trbG

These encode components of the T4SS / conjugation machinery.

---

#### trbE

Most common evolutionary target.

Functions

- ATPase
- powers T4SS assembly
- pilus biogenesis
- substrate translocation

Mutations

- SNPs
- indels
- IS421 insertions
- truncations

Effects

- strong PRD1 resistance
- reduced conjugation
- pilus loss

---

#### Partial vs complete resistance

Partial resistance

- trbB
- trbL

↓

reduced but retained conjugation

Complete resistance

- trbE
- trbI
- trbJ

↓

minimal conjugation

---

#### TEM observations

PRD1 binds

- sides of conjugative pilus

Susceptible cells

- abundant phage binding
- rapid lysis

trbI mutants

- reduced binding
- retain pilus remnants

trbE mutants

- almost no pili
- minimal binding

---

#### Evolutionary implications

Conjugation creates benefit

↓

selection maintains pili

↓

selection against phage resistance

When conjugation provides little benefit

↓

loss of pili is favored

↓

rapid resistance evolution

---

#### Natural populations

Public IncP plasmids

~13%

contain truncated TrbE/VirB4 proteins.

Suggests

selection against conjugation

may occur naturally,

possibly due to plasmid-dependent phages.

---

#### Applications

Plasmid-dependent phages

- suppress MDR plasmids
- prevent conjugation
- reduce AMR spread
- may select for plasmids with poor mobility instead of improved resistance

Potential therapeutic strategy

↓

push plasmids toward evolutionary dead ends rather than simply killing bacteria.
