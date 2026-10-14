---
title: Rapid aggregative and reproductive responses of weevils to masting of North American oaks counteract predator satiation
authors: Michał Bogdziewicz, Shealyn Marino, Raul Bonal, Rafał Zwolak, Michael A. Steele
year: "2018"
publication: Ecology
DOI: 10.1002/ecy.2510
urgl: https://onlinelibrary.wiley.com/doi/abs/10.1002/ecy.2510
tags:
  - project/acorn-weevil
Topic: acorn-weevil
notes: true
---

#### Abstract
The predator satiation hypothesis posits that masting helps plants escape seed predation through starvation of predators in lean years, followed by satiation of predators in mast years. Importantly, successful satiation requires sufficiently delayed bottom-up effects of seed availability on seed consumers. However, some seed consumers may be capable of quick aggregative and reproductive responses to masting, which may jeopardize positive density dependence of seed survival. We used a 17-yr data set on seed production and insect (Curculio weevils) infestation of three North American oaks species (northern red Quercus rubra, white Q. alba, and chestnut oak Q. montana) to test predictions of the predation satiation hypothesis. Furthermore, we tested for the unlagged numerical response of Curculio to acorn production. We found that masting results in a bottom-up effect on the insect population; both through increased reproductive output and aggregation at seed-rich trees. Consequently, mast seeding in two out of three studied oaks (white and chestnut oak) did not help to escape insect seed predation, whereas, in the red oak, the escape depended on the synchronization of mast crops within the population. Bottom-up effects of masting on seed consumer populations are assumed to be delayed, and therefore to have negligible effects on seed survival in mast years. Our research suggests that insect populations may be able to mount rapid reproductive and aggregative responses when seed availability increases, possibly hindering satiation effects of masting. Many insect species are able to quickly benefit from pulsed resources, making mechanisms described here potentially relevant in many other systems.

#### Related

## Introduction
- perennial plant species - fluctuating + synchronized seed production
[[masting]]
- "fitness benefit to plants through decreased costs of reproduction per surviving offspring" - economies of scale
	- pollination efficiency
	- seed dispersal
	- <mark style="background: #FF5582A6;">satiation of seed predators </mark>
[[Predator satiation]] 
- seed consumers controlled by resources --> bottum up 
	- scarcity = decrease in abundance <mark style="background: #FFF3A3A6;">*but on what time frame - reproductive cycle / abundance time lags*</mark>
	- "Consequently, consumers are relatively rare in mast years, and therefore easily satiated, which results in a decrease in the proportion of damaged seeds when seed production is high (Kelly et al. 2000, Fletcher et al. 2010, Z_ ywiec et al. 2013, Linhart et al. 2014)." - how strong is this relationship - are weevils always lower at the onset of a mast year in our specific model?
- Ostfeld 
- "Immediate bottom-up effects of masting on seed consumers may be driven by behavioral aggregation in resource-rich habitats, rapid reproductive responses, or a combination of both"
	- need to know how [[weevil life history]] and [[weevil reproduction]] and [[weevil sensing]] play into this 
- models - assume insects have limitted dispersal + cannot have aggregative responses to masting 
	- <mark style="background: #FFB8EBA6;">could their be a secondary means of aggregation (ie they are not sending the food but they are sensing x organism that is, or x factor that also corresponds with masting?)</mark>
- if masting impacts population in future years (delay), but not for seed survival in current year --> masting = PSH

exceptions
- [[endoparasitic seed predator]] 
	- adults = short lifespan 
	- increased abundance = increase in realized fecundity
		- lower questing 
		- lower competition 
	- impacts infestation rate --> even if not yet more adults 
	- eg: higher number of seeds with larvae, even though number of adult seed predators is the same
		- <mark style="background: #FFB8EBA6;">functionally does this correspond with how adult weevil reproduction works? - check citations</mark>
	- [[curculio sp.]]
	- [[quercus rubra]]
		- 1) evaluate PSH
		- 2) ability of weevils to numerically respond to masting 
	- <mark style="background: #FFB8EBA6;">“The second component of the PSH involves invertebrate starvation, i.e., lean seed years followed by mast years should favor increased seed survival (Kelly and Sullivan 1997, Z_ ywiec et al. 2013, Espelta et al. 2017). Thus, past acorn production should positively correlate with current predation rates (prediction 2).” (Bogdziewicz et al., 2018, p. 2576)
	- “In that case, seed damage rate should be negatively correlated with the change in reproductive effort of plants between subsequent years (prediction 3).” (Bogdziewicz et al., 2018, p. 2576)</mark>
	- **COME BACK TO**
numeric response of weevils to acorn production
- aggregation
- reproductive output 
- per tree larvae counts <mark style="background: #ADCCFFA6;">methods</mark>
- relationship between crop size and acorn production (ambient - local area - sending question once again)
- predict arrival at productive trees during lean years 
	- if aggregative affect contributes to correlation then there should be an increase in effect of aggregation at tree level during lean years
- [[weevil life history]] traits
	- disperse only with complete seed failure of host tree
	- if also effecr of fecundity then correlation between population level larval abundance and population level crop size 

## Materials + Methods
### Study system
[[quercus rubra]] - red oak 
- widespread hardwoods with masting behavior 
- [[univoltine]] insect - curculio
	- one brood of offspring per years
- preforate seed with rostrum and oviposit 
- larva then exit dropped acorn and bury into ground --> pupate --> adulthood 
	-  overwinter in soil 
	- [[diapuse]]
	- climb the tree they emere under --> canopy --> reproduction 
- poor dispersal 
egg laying ability 
- 40 / lifetime, realized fecundity < 20 / female (shorter lifespan)

### seed production and infestation 
-<!--c:rxzb3--> 17 years, 3 sites 
- acorn production by individual oak tree 
	- seed traps under 15 
	- crop size per tree = summed acorn count from two seed traps 
	- biweekly collection august - november 
- insect larvae counts - 1 weevil per exit hole<!--/c:rxzb3-->
### statistical analysis
binomial family, logit link, generalized linear mixed models 
- [[GLMMs]]
- acorn infestation (1 = infested, 0 = not infested) as response
- <!--c:3tn4r-->fixed effect = tree level crop size as interaction term with population level crop size <!--/c:3tn4r-->
<!--co:3tn4r by:Sydney at:2026-09-17T23:44:24.791Z status:open quote:"fixed effect = tree level crop size as interaction term with population level crop size"
Sydney (2026-09-17T23:44:24.791Z): "We used acorn infestation (1, infested; 0, not infested) as a response, while the fixed effect included tree-level crop size as an interaction term with the population-level crop size (summed crop per site per year)"
-->
<!--co:rxzb3 by:Sydney at:2026-09-17T23:45:46.272Z status:open quote:"17 years, 3 sites - acorn production by individual oak tree - seed traps under 15 - crop size per tree = summed acorn count from two seed traps - biweekly collection august - november - insect larvae counts - 1 weevil per exit hole"
Sydney (2026-09-17T23:45:46.272Z): In other words, if aggregation of weevils at highly productive trees contributes to the positive correlation between weevil larval abundance and the tree-level crop size, the numerical increase at highly productive trees should be stronger in low-crop years. This is based on weevil life history traits; these insects are expected to disperse only when faced with almost complete seed failure of the host tree (Venner et al. 2011, Pelisson et al. 2012). Moreover, if the increased larval abundance at productive trees is not only an outcome of a re-distribution of weevils in space, but also of increased realized fecundity, we should see a positive correlation between population-level larval abundance and population-level crop size (prediction 6).
-->
	- test effect of background crop production on infestation rate 
	- <!--c:styib-->aggregation at large crops not in synchrony - negative interaction term --> satiation only efficient if the whole population masts<!--/c:styib-->
<mark style="background: #ABF7F7A6;">	- **COME BACK TO **</mark>
<!--co:styib by:Sydney at:2026-09-17T23:47:24.289Z status:open quote:"aggregation at large crops not in sy chrony - negative interaction term --​> satiation only efficient if the whole population masts"
Sydney (2026-09-17T23:47:24.289Z): "The interaction term allowed us to test for the effect of background crop production on the infestation rate of each tree. If weevils aggregate at trees producing large crops out of synchrony with the rest of the population, we should see a negative interaction term, i.e., satiation is only efficient if the whole population masts."
Sydney (2026-09-18T00:26:29.002Z): The response was summed larval abundance per year, per site, while the fixed effect included the summed crop size per year, per site. Site was included as a covariate.
-->
- dont include years since it would restrict to in year variation - it is among year variation that is most importantly

starvation component of [[Predator satiation]] with 4 models<!--c:sngtx--> / species <!--/c:sngtx-->
<!--co:sngtx by:Sydney at:2026-09-17T23:48:59.105Z status:open quote:"/ species"
Sydney (2026-09-17T23:48:59.105Z): why include species as a factor in GLMM
-->
- test if curent predation rate related to previos year crop size or sum of <!--c:qmgqq-->past two years <!--/c:qmgqq-->
<!--co:qmgqq by:Sydney at:2026-09-17T23:49:36.639Z status:open quote:"past two years"
Sydney (2026-09-17T23:49:36.639Z): ostfeld connection
-->
- seed damage rate as related to ratio of crop in year to year previous (t v t-1)
"To test for the link in larval abundance between subsequent years (prediction 4) we regressed current year larval abundance per tree to the larval abundance at that tree in the previous year." - <mark style="background: #FF5582A6;">Question</mark>
determining cause of change in abundance - reproduction vs aggregation / redistribution 

## Results
low predation rates - between 10-30 
2 species with no decrease in infestation at tree level with increasing crop size 
- IFD?
red oak - tree level predation decrease with crop size 
- dependent on population level seed production 
	- suggesting it is masting dependent?
predictions 2-4 not support
	no relationship between previous year crop and current predation, or summed past two years or current to previous ratio 
		chstnut oak - current rate higher if previous year was higher
	no relationship between current and previous larvae abundance either
predictions 5-6
- increasing in larval abundance in response to seed production
- abundance positively related to crop size 
	- stronger when crop size was small(would suggest not masting...)
## Discussion
- assumed time delay --> insect population immediate response to increase resource --> both aggregative and reproductive response 
	- sstiation effect not realized 
- not effective to against seed predation in 2 species --><!--c:k7m4y--> escape depended on synchronicity of mast crops in population<!--/c:k7m4y-->
<!--co:k7m4y by:Sydney at:2026-09-18T00:33:56.509Z status:open quote:"escape depended on synchronicity of mast crops in population"
Sydney (2026-09-18T00:33:56.509Z): but where is this supported in the data/results
-->
- increased affect of aggregation when low crop 
- because populations not affected by past variability --? aggregative effect also due to dispersion (or mortality)

>[!info] "In the case of univoltine insects, like Curculio, the reproductive response should be most important in systems where one female is able to infest multiple seeds, and the effect size will depend on maximum potential fecundity of females. In turn, an aggregative response will likely depend on mobility of the species, and is likely to be important, as the Curculio are considered limited in their dispersal ability yet capable of redistributing among trees in reaction to seed production" 
>

limited bottom up effects on population --> corresponding increase in top-down control 
-<!--c:u8khv--> resource pulses = sequential effects<!--/c:u8khv-->
- aggregation of large mammals and birds --> predation after seed is dropped 
<!--co:u8khv by:Sydney at:2026-09-18T00:38:41.175Z status:open quote:"resource pulses = sequential effects"
Sydney (2026-09-18T00:38:41.175Z): “(Yang et al. 2008).” ([Bogdziewicz et al., 2018, p. 2578](zotero://select/groups/6676006/items/8N55YX67)) ([pdf](zotero://open-pdf/groups/6676006/items/TT9WDWZU?page=4&annotation=RITQNYWN))
-->+ larvae
- small mammals --> peak population after seed depletion --> increased rodent predation on invertebrates
	- pressure on overwintering larvae 
failed predator satiation --> lack of density dependence on infestation rates 
theoretical models - predator satiation may not have been needed to evolve ( eg improved pollination)
- lack of response / satiation in 2 species does not account for potential post-dispersal satiation 
- in red oaks population level crop size had to be high enough --> synchrony 
	- both syncrhony AND variation important for [[Predator satiation]]
- 
