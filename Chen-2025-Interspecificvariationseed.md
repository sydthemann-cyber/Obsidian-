---
title: Interspecific variation in seed traits facilitates divergent pre-dispersal seed predation among five stone oak species
authors: Xi Chen, Xingyue Li, Qian Li
year: "2025"
publication: Ecological Processes
DOI: 10.1186/s13717-025-00607-y
urgl: https://doi.org/10.1186/s13717-025-00607-y
tags:
  - project/acorn-weevil
Topic: acorn-weevil
notes: true
---

###### Abstract
Seed traits, including size, nutrient content, mechanical and chemical defenses, are important factors influencing seed-animal interactions. Representing insect-seed antagonism, pre-dispersal seed predation (PSP) has a significant negative impact on plant reproductive success. However, empirical studies examining the influence of multiple seed traits on PSP are scarce. As dominant canopy tree species in evergreen forests of East Asia, Lithocarpus species serve as ideal models for investigating how seed traits affect PSP.

## Notes 

> [!summary] Five co-occurring stone oaks in Yunnan differ in both seed traits and pre-dispersal seed predation (PSP). Mechanical defense (husk + cupule mass relative to seed) is associated with lower PSP; chemical defenses are not. The one enclosed-receptacle species, _L. corneus_, had zero predation. Weevils were the main predators. PSP was low overall (0–21%) in the single study year.

### Introduction

- PSP = insect–seed antagonism with knock-on effects for dispersal and recruitment; understudied as a coexistence mechanism.
- Trait effects are unclear or contradictory, especially seed size (smaller seeds escape vs larger seeds satiate larvae). Most studies look at one or two traits.
- _Lithocarpus_ has two fruit types:
    - **Acorn (AC)**: smaller seed, thin husk, more chemical defense.
    - **Enclosed receptacle (ER)**: larger, nutrient-rich seed in a thick lignified husk.
- **Predation selection hypothesis** (Chen et al. 2018, 2023b): AC fruits attract more dispersers but suffer more PSP; ER fruits block PSP but limit dispersal to large vertebrates. Not previously tested.

### Methods

- **Site**: Laoshan Natural Forest Reserve, Malipo, SE Yunnan; old-growth forest at 1200–1400 m, ~0.5 ha.
- **Species**: _L. corneus_ (ER); _L. truncatus_, _L. echinophorus_, _L. pseudovestitus_, _L. talangensis_ (all AC). The five that masted in late Oct 2020.
- **Sampling**: 400 fallen mature fruits per species from 5–8 trees, pooled.
- **Seed status** (200 fruits/species): sound, infested (larva present), larva-escaped, aborted. Larvae identified to family from morphology; rearing to adults failed.
- **Traits** (from the other 200; 2 measurements per species):
    - Seed size = fresh mass
    - Mechanical defense = (husk + cupule fresh mass) / seed fresh mass
    - Macronutrients: starch + non-starch polysaccharides (TNC − FSS), crude protein, lipids, free simple sugars
    - Antifeedants: tannin, lignin, hemicellulose, cellulose
- **Analysis**: multinomial regression of species on status counts; ANOVA / Kruskal–Wallis per trait; binomial GLMM of predation (1) vs sound (0) on each trait, species as random effect, aborted seeds excluded (n = 802), AIC selection.

### Results

|Species|Type|Aborted|Sound|Weevil|Moth|Escaped|Predation|
|---|---|---|---|---|---|---|---|
|_L. corneus_|ER|19|181|0|0|0|0%|
|_L. echinophorus_|AC|20|164|7|0|9|8%|
|_L. pseudovestitus_|AC|64|118|0|2|16|9%|
|_L. truncatus_|AC|18|160|0|0|22|11%|
|_L. talangensis_|AC|77|80|22|1|20|21%|

- Predators: weevils (Curculionidae) and moths (Lepidoptera); weevils dominant. Predators of _L. truncatus_ unidentified (all had left).
- Multiple larvae per seed: 14 of 23 infested _L. talangensis_ seeds; 1 in _L. echinophorus_; none elsewhere.
- Trait variation significant for seed size, starch + NSP, protein, tannin, lignin, hemicellulose, mechanical defense. Not for lipid, FSS, cellulose.
- Approximate species means: mechanical defense _corneus_ 11 > _echinophorus_ 5.6 > _talangensis_ 2.9 > _truncatus_ 2.3 > _pseudovestitus_ 0.3. Seed mass _talangensis_ 3.7 g > _corneus_ 2.35 > _truncatus_ 2.0 > _echinophorus_ 1.2 > _pseudovestitus_ 1.0.
- GLMM (Table 4): mechanical defense −0.42 (p = 0.013); crude protein −1.00 (p = 0.009); cellulose +1.09. Seed size, starch, tannin, lignin, hemicellulose not retained.
- Tannin is low throughout (1–3%); fibre is the main antifeedant investment (31–45%).
- Abortion: ~35% in the two species with the highest starch + NSP (_pseudovestitus_, _talangensis_), ~10% in the rest.

### Discussion

- Mechanical defense outweighs chemical defense against PSP. Proposed mechanism: thick husk stops larvae exiting, so insects have evolved to avoid ovipositing in _L. corneus_; the cupule may also block oviposition early on.
- Chemical defense: tannin is well below the ~10% typical of _Quercus_; insects tolerate it. May matter more for vertebrates.
- Seed size: no overall association, but the largest-seeded species had the most multi-larva infestation, which could undermine within-seed satiation.
- Larva-escaped seeds may involve different species from those found inside, so predator diversity is probably underestimated.
- Some aborted seeds may be PSP-related (oviposition-triggered abortion), so true PSP may be higher.
- Results support the ER side of the predation selection hypothesis, based on one ER species.
- Trait divergence → PSP divergence, offered as a natural-enemy route to congeneric coexistence.

### Things to check against my annotations

- Protein direction: Results and Table 4 give a negative association with PSP; the Discussion says PSP increased with protein.
- Cellulose showed no significant interspecific variation and Methods say only the seven varying traits were modelled, yet cellulose appears in Table 4 with a very small SE.
- Traits are species-level values (five species), so the 802-seed GLMM effectively has five distinct predictor values per trait; mechanical defense and protein are both highest in _L. corneus_ and hard to separate.
- One year, one mast event, one ER species, fruits collected from the ground and pooled across trees.
- The "larger seeds → multiple larvae" point rests on _L. talangensis_ alone.
- Text gives 1 of 16 infested _L. echinophorus_ seeds with multiple larvae, but Table 3 shows 7 with larvae (16 is total predation).

## Relevant literature

### Pre-dispersal seed predation: general and consequences

- Janzen 1969 — Seed-eaters vs seed size, number, toxicity, dispersal (_Evolution_)
- Janzen 1971 — Seed predation by animals (_Annu Rev Ecol Syst_)
- Crawley 2000 — Seed predators and plant population dynamics (in _Seeds_)
- Crawley & Long 1995 — Alternate bearing and satiation in _Quercus robur_ (_J Ecol_)
- Harper 1967 — A Darwinian approach to plant ecology (_J Ecol_)
- Leiva & Fernández-Alés 2005 — Holm oak acorn infestation in dehesas (_For Ecol Manage_)
- Louda & Potvin 1995 — Inflorescence-feeding insects and plant fitness (_Ecology_)
- Fukumoto & Kajimura 2000 — Insect predation and _Q. variabilis_ germination (_J For Res_)
- Fukumoto & Kajimura 2003 — Seed-insect fauna in pre-dispersal acorns (IUFRO proc.)
- Ueda 2000 — Pre- and post-dispersal acorn damage, two oaks (_J For Res_)
- Higaki 2016 — Prolonged diapause and masting, _Curculio robustus_ (_Entomol Exp Appl_)
- Perea et al. 2012 — Insect infestation and rodent seed dispersal (_Oecologia_)
- Wang et al. 2021 — Masting, infestation and rodent dispersal of _Castanea_ (_For Ecol Manage_)

### Chemical defense and tannins

- Weckerly et al. 1989 — Acorn germination, insect predation and tannins (_Can J For Res_)
- Xiao et al. 2007 — Acorn defenses: resistance, tolerance, escape (_For Ecol Manage_)
- Muñoz et al. 2014 — Acorn–weevil interactions in a mixed-oak forest (_For Ecol Manage_)
- Mezquida et al. 2021 — Acorn crop, seed size and chemical defenses (_Insects_)
- Barbehenn & Constabel 2011 — Tannins in plant–herbivore interactions (_Phytochemistry_)
- Chen et al. 2012 — Physical vs chemical defense trade-off in stone oak seeds (_PLoS ONE_)

### Mechanical defense

- Toju & Sota 2006 — Predator–prey armament clines, camellia weevil (_Am Nat_)
- Toju 2008 — Weevil mouthpart length and pericarp thickness (_Evolution_)
- Toju 2009 — Fine-scale divergence in a coevolutionary arms race (_BMC Evol Biol_)
- Nakagawa & Nakashizuka 2004 — Physical and chemical traits of dipterocarp seeds (_Seed Sci Res_)
- Espelta et al. 2009 — Acorn predation: phenology, seed size, predator size (_J Ecol_)
- Vander Wall 2010 — How plants manipulate scatter-hoarders (_Phil Trans R Soc B_)
- Brett 1964 — Evolution of the Fagaceae cupule (_New Phytol_)

### Seed size and predation

- Palmer et al. 2022 — Seed size predicts pre-dispersal seed loss in forbs (_Ecosphere_)
- Bonal & Muñoz 2008 — Premature abscission limits _Curculio elephas_ larval size (_Ecol Entomol_)
- Bonal & Muñoz 2009 — Body size conflicts in _Curculio_ larvae (_Ecol Entomol_)
- Mucunguzi 1995 — Bruchids and _Acacia_ seed survival (_Afr J Ecol_)
- Mack 1998 — Large seeds tolerate predators (_Biotropica_)
- Yi & Yang 2010 — Large acorns satiate weevil larvae in _Q. aliena_ (_Plant Ecol_)
- Bogdziewicz et al. 2019 — Seed-size-mediated tolerance across latitude (_Ann Bot_)
- Perea et al. 2020 — Embryo damage location and partial seed predation (_Oikos_)
- Gibson 1971 — Insects of bur oak acorns (_Ann Entomol Soc Am_)

### Seed nutrients and insect preference

- Sallabanks & Courtney 1992 — Frugivory, seed predation, insect–vertebrate interactions (_Annu Rev Entomol_)
- Hana et al. 2020 — Seed properties and carabid preferences (_Insects_)
- Vander Wall 2001 — Evolutionary ecology of nut dispersal (_Bot Rev_)

### Seed abortion

- Östergård et al. 2007 — Fruit abortion and selective oviposition (_Ecology_)
- Severino & Auld 2013 — Growth and development framework, castor (_Ind Crops Prod_)
- Brink & Cooper 1947 — The endosperm in seed development (_Bot Rev_)
- Barnabás et al. 2008 — Drought and heat stress on cereal reproduction (_Plant Cell Environ_)
- Liu et al. 2013 — Sugars as nutrients and signals under heat and drought (_Front Plant Sci_)
- Tonnabel et al. 2021 — Postmating sexual selection in plants (_TREE_)
- Baskin 2022 — Climate change and annual crops (book chapter)

### Coexistence and natural enemies

- Chesson 2000 — Mechanisms of maintenance of species diversity (_Annu Rev Ecol Syst_)
- Chesson 2018 — Updates on diversity maintenance mechanisms (_J Ecol_)
- Comita et al. 2014 — JC meta-analysis (_J Ecol_)
- Bartomeus & Godoy 2018 — Biotic controls of plant coexistence (_J Ecol_)
- Chen et al. 2023a — Fruit size, physical defense and dispersal in three oaks (_For Ecol Manage_)
- Greig 1993 — Pre-dispersal seed predation on five _Piper_ species (_Oecologia_)
- Stowe et al. 2000 — Evolutionary ecology of tolerance to consumer damage (_Annu Rev Ecol Syst_)
