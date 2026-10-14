---
title: Effectiveness of predator satiation in masting oaks is negatively affected by conspecific density
authors: Michał Bogdziewicz, Josep M. Espelta, Alberto Muñoz, Jose M. Aparicio, Raul Bonal
year: "2018"
publication: Oecologia
DOI: 10.1007/s00442-018-4069-7
urgl: https://pmc.ncbi.nlm.nih.gov/articles/PMC5859101/
tags:
  - project/acorn-weevil
Topic: acorn-weevil
notes: true
---

###### Abstract
Variation in seed availability shapes plant communities, and is strongly affected by seed predation. In some plant species, temporal variation in seed production is especially high and synchronized over large areas, which is called ‘mast seeding’. One selective advantage of this phenomenon is predator satiation which posits that masting helps plants escape seed predation through starvation of predators in lean years, and satiation in mast years. However, even though seed predation can be predicted to have a strong spatial component and depend on plant densities, whether the effectiveness of predator satiation in masting plants changes according to the Janzen-Connell effect has been barely investigated. We studied, over an 8-year period, the seed production, the spatiotemporal patters of weevil seed predation, and the abundance of adult weevils in a holm oak (Quercus ilex) population that consists of trees interspersed at patches covering a continuum of conspecific density. Isolated oaks effectively satiate predators, but this is trumped by increasing conspecific plant density. Lack of predator satiation in trees growing in dense patches was caused by re-distribution of insects among plants that likely attenuated them against food shortage in lean years, and changed the type of weevil functional response from type II in isolated trees to type III in trees growing in dense patches. This study provides the first empirical evaluation of the notion that masting and predator satiation should be more important in populations that start to dominate their communities, and is consistent with the observation that masting is less frequent and less intense in diverse forests.


## Notes

> [!summary] Isolated holm oaks satiate weevils (type II response, strong lagged numerical response). In dense conspecific patches both components of predator satiation break down: weevils redistribute among neighbouring trees, the functional response becomes type III with no decline at high crops, and past crop size no longer predicts predation. First empirical test of the idea that PSH effectiveness depends on focal plant density (PSH × Janzen-Connell).

### Introduction

- PSH has two components:
    - **Functional**: proportion of seeds eaten falls as crop rises (type II, or the declining arm of type III).
    - **Numerical**: lean years starve predators, so fewer are around in mast years.
- JC effect and PSH have mostly been studied separately (exception: Xiao et al. 2016).
- Argument: in dense patches, low-mobility predators can move between trees, which buffers them in lean years and lets them aggregate on resource-rich trees.
- Predictions: type II in isolated trees, type III in dense patches; weaker dependence on previous crops in dense patches.

### Methods

- **Site**: Huecas, Toledo, central Spain. _Quercus ilex_ scattered in a cereal matrix.
- **System**: _Curculio elephas_, specialist, low mobility (~600 m dispersal), extended diapause (66 / 30 / 4% emerge after 1 / 2 / 3 yr).
- **Sampling**: 24 trees. Acorn crop and infestation 2008–2015 (seed traps, 1.5–2% of canopy). Adult weevil emergence traps on trunks 2008–2013.
- **Density**: modified Hanski connectivity index, then dichotomised using the 600 m dispersal distance.
    - Isolated: n = 15, mean connectivity 63, mean spacing 1726 m
    - Dense: n = 9, mean connectivity 641, mean spacing 220 m
    - Continuous-connectivity versions are in Table S1.
- **Models** (binomial GLMMs, tree ID random, AICc selection):
    1. Predation ~ crop + crop² × density → functional response. Year deliberately not a random effect.
    2. Predation ~ log imago emerged under tree × density → test for between-tree migration.
    3. Predation ~ summed crop of previous 2 yr × density → numerical response.
    4. Imago count ~ log crop of previous 2 yr × density (zero-inflated neg. binomial, tree + year random, trap number as offset).
- Functional response rule: type I = no significant terms; type II = negative linear; type III = positive linear + negative quadratic.

### Results

||Isolated|Dense|
|---|---|---|
|CVp|0.55|0.49|
|CVi|1.00|0.91|
|Synchrony (r)|0.14|0.37|
|Mean crop / tree|5850|2108|
|Imago index / tree|1.37|1.52|
|Imago per acorn|119 × 10⁻⁵|278 × 10⁻⁵|
|Mean predation rate|0.38|0.42|

- **Functional response**: isolated = type II (linear z = −12.54, quadratic z = 9.90). Dense = type III (linear z = 4.62, quadratic z = −3.01), but predation plateaus and never declines.
- **Migration test**: predation tracks locally emerged imagos in isolated trees (z = 5.56) but not in dense patches (z = 0.45, p = 0.65).
- **Numerical response, predation**: depends on previous 2-yr crop in isolated trees (z = 11.50), not in dense (z = −0.23, p = 0.83).
- **Numerical response, imagos**: positive in both; steeper in dense (interaction z = 3.44). Interaction is not significant with continuous connectivity.
- Previous-year crop alone did not predict imago abundance (Fig. S1), hence the 2-yr sum.

### Discussion

- Dense patches: satiation fails on both the functional and the numerical side.
- Two proposed mechanisms for the missing starvation effect: (1) microclimate in dense stands buffers larvae against drought and fungal attack; (2) relocation among asynchronous neighbours.
- Implication: masting intensity should scale with species dominance or local density, moderated by predator mobility. Consistent with weaker masting in diverse tropical forests.
- Synchrony matters even for a relatively immobile specialist insect, contra the older view that such predators select for variability only.
- Higher predation in dense patches = JC effect at the pre-dispersal stage, though it may be offset later (disperser attraction, nurse effects under drought).
- Focal plant density may reconcile conflicting PSH results across species and sites.


## Relevant literature

### Masting: concepts and reviews

- Kelly 1994 — Evolutionary ecology of mast seeding (_TREE_)
- Kelly & Sork 2002 — Mast seeding in perennial plants: why, how, where? (_Annu Rev Ecol Syst_)
- Herrera et al. 1998 — Annual variability in seed production and the masting concept (_Am Nat_)
- Koenig et al. 2003 — Components of population-level variation in seed production (_Oikos_)
- Crone et al. 2011 — What defines mast seeding? (_J Ecol_)
- Pearse et al. 2016 — Mechanisms of mast seeding (_New Phytol_)
- Silvertown 1980 — Evolutionary ecology of mast seeding in trees (_Biol J Linn Soc_)

### Predator satiation hypothesis: empirical tests

- Kelly & Sullivan 1997 — Benefits of masting in _Chionochloa pallens_ (_Oikos_)
- Kelly et al. 2000 — Predator satiation in 11 _Chionochloa_ species (_Oikos_)
- Crawley & Long 1995 — Alternate bearing and satiation in _Quercus robur_ (_J Ecol_)
- Bonal et al. 2007 — Satiation at plant and seed levels (_Evol Ecol_)
- Espelta et al. 2008 — Drought-mediated masting reduces acorn predation (_Ecology_)
- Xiao et al. 2013 — Predator satiation vs predator dispersal hypotheses (_J Ecol_)
- Żywiec et al. 2013 — Individual fruiting patterns and PSH (_Oecologia_)
- Linhart et al. 2014 — Cone production and seed predator response (_J Ecol_)
- Zwolak et al. 2016 — Granivore satiation timing in European beech (_Oecologia_)
- Bogdziewicz et al. 2017a — N deposition and masting benefits (_J Ecol_)
- Wright et al. 2005 — Seedfall and recruitment in a Neotropical forest (_Ecology_)

### Functional and numerical responses

- Holling 1965 — Functional response of predators to prey density (_Mem Entomol Soc Can_)
- Fletcher et al. 2010 — Functional response of a hoarding seed predator to masting (_Ecology_)
- Klinger & Rejmánek 2009 — Numerical and functional responses of a granivorous rodent (_Ecology_)
- Moreira et al. 2016 — Masting alters seed predator selection in a pine (_Plant Biol_)
- Moreira et al. 2017 — Contrasting predator guilds, two Mediterranean oaks (_Oikos_)
- Ostfeld & Keesing 2000 — Pulsed resources and consumer dynamics (_TREE_)
- Bogdziewicz et al. 2016 — Vertebrate responses to mast seeding (_Oikos_)

### Janzen-Connell and density-dependent seed fate

- Janzen 1970 — Herbivores and tree species number in tropical forests (_Am Nat_)
- Connell 1971 — Natural enemies and competitive exclusion (in _Dynamics of Populations_)
- Wright 2002 — Plant diversity in tropical forests, review (_Oecologia_)
- Comita et al. 2014 — JC meta-analysis (_J Ecol_)
- Xiao et al. 2016 — Satiation and JC effects vary with spatial scale (_Ann Bot_)
- Visser et al. 2011 — Tri-trophic interactions and density dependence (_Ecol Lett_)
- Wyatt & Silman 2004 — Distance dependence in two Amazonian palms (_Oecologia_)
- Yamazaki et al. 2009 — Density-dependent seedling mortality, temperate forest (_Plant Ecol_)
- Bell & Clark 2016 — Seed predation and climate, SE USA (_Oecologia_)

### Plant density, predator mobility and synchrony

- Janzen 1971 — Seed predation by animals (_Annu Rev Ecol Syst_)
- Janzen 1978 — Seeding patterns in tropical trees (book chapter)
- Ims 1990 — Ecology and evolution of reproductive synchrony (_TREE_)
- Platt et al. 1974 — Seed predation and plant density in _Astragalus_ (_Oecologia_)
- Curran & Leighton 2000 — Vertebrate responses to dipterocarp masting (_Ecol Monogr_)
- Curran & Webb 2000 — Spatiotemporal scale of dipterocarp seed predation (_Ecol Monogr_)
- Crone & Lesica 2004 — Synchronous flowering in _Astragalus scaphoides_ (_Ecology_)

### _Curculio elephas_ biology

- Venner et al. 2011 — Coexistence on a pulsed resource; diapause fractions (_PLoS ONE_)
- Pélisson et al. 2013a — Income vs capital breeding (_PLoS ONE_)
- Pélisson et al. 2013b — Dispersal and dormancy strategies; 600 m figure (_Ecol Entomol_)
- Desouhant et al. 2000 — Clutch size manipulation (_Oecologia_)
- Menu & Desouhant 2002 — Bet-hedging and prolonged diapause (_Oecologia_)
- Bonal & Muñoz 2009 — Body size conflicts in _Curculio_ larvae (_Ecol Entomol_)
- Bonal et al. 2012 — Fragmentation effects on acorn weevils (_Insect Conserv Div_)
- Bonal et al. 2015 — Late summer rain and weevil sex ratio (_R Soc Open Sci_)
- Espelta et al. 2017 — Rainfall stochasticity and acorn predation (_Ecosphere_)


### Connectivity and landscape structure

- Hanski 1999 — _Metapopulation Ecology_
- Puerta-Piñero et al. 2012 — Landscape effects on _Q. ilex_ regeneration (_Oecologia_)
- Ruiz-Carbayo et al. 2017 — Community assembly in a savannah-like landscape (_Insect Conserv Div_)

### Statistical methods

- Burnham & Anderson 2002 — Model selection and multimodel inference
- Arnold 2010 — Uninformative parameters and AIC (_J Wildl Manage_)
- Fournier et al. 2012 — AD Model Builder / glmmADMB (_Optim Methods Softw_)

