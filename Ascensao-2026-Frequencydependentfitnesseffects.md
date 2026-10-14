---
title: Frequency-dependent fitness effects are ubiquitous in rapidly adapting microbial populations
authors: Joao A. Ascensao, Keon D. Abedi, Aditya N. Prasad, Oskar Hallatschek
year: "2026"
publication: ""
DOI: 10.1101/2025.08.18.670924
urgl: https://www.biorxiv.org/content/10.1101/2025.08.18.670924v3
tags:
  - organism/bacteria/e-coli
  - evolution
  - genetics
  - ecology/competition
Topic: micro
notes: true
---

###### Abstract
**In simple microbial populations, the fitness effects of selected mutations are typically assumed to be constant, regardless of mutant frequency.** This assumption underpins predictions about evolutionary dynamics, epistasis, and the maintenance of genetic diversity. Here, we systematically test this assumption using beneficial mutations from early generations of the Escherichia coli Long-Term Evolution Experiment (LTEE). Using flow cytometry-based competition assays, **we find that frequency-dependent fitness effects are the norm rather than the exception, occurring in approximately 80% of strain pairs tested.** Most competitions exhibit negative frequency-dependence, **where fitness advantages decline as mutant frequency increases.** We demonstrate that the strength of frequency-dependence is predictable from invasion fitness measurements, which explain approximately half of the biological variation in frequency-dependent slopes. We also observe violations of **fitness transitivity** in several strain combinations, **indicating that competitive outcomes cannot always be predicted from fitness measured against a single reference strain**. High-resolution measurements reveal that frequency-dependence changes substantially within the growth cycle, with the net per-cycle effect reflecting the balance of opposing dynamics at different growth phases. **Our results demonstrate that even in a model system designed to minimize ecological complexity, subtle interactions between closely related genotypes create frequency-dependent selection that can fundamentally alter evolutionary trajectories.**

### Summary 
- frequency dependent fitness effects very common 
- negative frequency dependence - fitness advantage decline as frequency increase
- can be explained by invasion fitness
- frequency dependence changes with growth cycle 
### related 
- [[frequency-dependent selection]]
- [[E. coli]]
- 

--- 
### Detailed notes

#### Introduction 
- fitness effects assumed to follow classical population genetic dynamics 
- "evolutionary outcomes determined heavily by the rank order of fitness advantages"
	- selection depends on competition
- environmental heterogeneity not constructed but created by evolving population
	- eg excreted metabolites --> niche construction 
- "stable negatively frequency dependent polymorphisms arose in glucose limited chemostats founded by a single e. coli clone"
	- cross feeding on secondary metabolites 
	- "frequency dependent competition among spatial niche specialists"

Eschericia Coli Long-Term Evolution experiment (LTEE)

assumed that in populations with the same ecotype single point mutations have negligble effects on resource usage - do not generate FDFE
- eg invasion fitness of pykF knockout was higher then at higher frequency
- idea of a 'unconditionally beneficial effects'

- resource competition is common target
- could explain persistence of genetic diversity in lab populations 

#### Results 
##### Beneficial mutations exhibit pervasive frequency-dependent fitness effect

5 beneficial mutations
- G  - SNP - glmUS
- R - deletion of rbs
- P -  deletion of pykF 
- S - SNP - spoT
- T - SNP - topA

fluorescent protein tagging - integrated into a neutral intergenic genomic site via Tn7 transposon system 

4 initial starting frequencies - .01, .2, .8, .99 (equally spaces on log axis)
frequency f measured over 2 24 hour growth cycles 
fitness effects of focal strain relative to competitive 

 frequency dependent effects in most strain pairs 
- most had positive mean fitness effects relative to ancestor - magntitude varied with f

frequency dependent fitness relationship crossed 0 - potential for stable coexistance 
- some double mutants had lower fitness then single mutant ancestors 
	- sign of epistatis 

- negative frequency dependence 
	- would cause fixation dynamis to slow - beneficial mutations approach fixation 
	- wright-fisher-like simulation - increased mutant fixation time by hundreds of generations (???????)
- some had positive FDE 
- FDE more common in double mutants then single mutants 

##### Predictable patterns emerge in frequency dependent fitness effects
- fitness effects higher when focal strain less then .5 instead of greater then .5 
- "Moreover, the relationship between sinv and shigh  99  100 shows a slight curvature at higher absolute invasion fitness effects. This curvature is reflective of a general negative 101 dependence of the slope (βs) of the frequency-dependence on sinv (Figure 3b). This negative correlation is quite 102 strong, with absolute correlation coefficients around 50-60%. We find similar patterns when considering Malthusian 103 fitness (Figure S9)."
- ANOVA to partition varience = invasion fitness, biological idiosyncrasy, measurement error
	- measurement error can explain .4 percent variance
	- bio and fitness explain .3
##### fitness relationships violate transitivity assumptions
- evo theory assumes fitness effects transitive + additive 
	- "Under this assumption, if 113 we measure fitness effects sik of strain i relative to strain k and sjk of strain j relative to strain k, we should be able 114 to predict the fitness effect of strain i relative to strain j, sij = sik − sjk."
- if deviated = context important - fitness non-transitivity 
- test by comparing observed vs predicted fitness effects 
	- violations = observed fitness approx .2 
	- under different deffinitions higher number 
##### niche construction drives frequency dependent fitness effects
- frequency dependence changes within growth cycle 
- three phases 1) mutants slower then ancestor but higher fitness when minority 2) gained fitness advatnage 3-6 hours, stronger advantage when   majority, 3) 6-10 hours better when in minority 

difference in growth rate between mutant and ancestor = fitness effect
- ∂t logit( f ) = ∂t log(nmut) − ∂t log(nwt).
- "Both REL606 and mutant growth rates depend on population composition, with both strain types achieving higher 150 growth rates when REL606 dominates, particularly at the beginning and end of exponential phase."
- FDE in late exponential phase account for 10-40 % of fitness
- "We assume that wild-type and mutant 157 strains grow by consuming a single, exhaustible resource, with strain-specific growth rates (rwt, rmut) and resource 158 conversion factors (awt, amut). Analyzing the dynamics in the high- and low-frequency limits, we show that resource 159 depletion time T scales inversely with the growth rate of the dominant strain, and is thus frequency-dependent:  T ∝ r−1  160 major."
- resource depletion dynamics explain 10-50% of FDFE 

#### Discussion
- "It is worth emphasizing that the LTEE, and our assays, use daily batch transfers rather than continuous culture. 197 Batch dynamics impose a natural cycle of feast and famine, with successive temporal niches (lag, exponential, 198 transition, stationary) over which strains can differ"
