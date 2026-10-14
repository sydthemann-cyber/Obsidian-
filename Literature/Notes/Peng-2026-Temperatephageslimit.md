---
title: Temperate phages limit their own propagation under spatial constraint in biofilms on chitin | bioRxiv
authors: Yixuan Peng, Jacob D. Holt, Triana N. Dalia, Daniel Schultz, Ankur B. Dalia,  Carey D. Nadell
year: pending
publication: biorx
DOI: https://doi.org/10.1101/2025.11.26.690769
url: https://www.biorxiv.org/content/10.1101/2025.11.26.690769v2
tags:
  - organism/phage
  - organism/bacteria/vibrio
  - interaction
Topic: vibrio-phage
notes: true
PDF:
---
###### Abstract
Biofilm growth and phage exposure are common to diverse bacterial species. Studying phage-host interaction and population dynamics in biofilms with cellular resolution remains a significant challenge, especially when attempting to recapitulate the natural environments that microbes occupy. Here we study the population dynamics of phage K139 lysogenized and non-lysogenized _Vibrio cholerae_ when growing in biofilms on the surface of chitin particles in seawater, replicating key features of _V. cholerae_ ecology in the marine environment. We find that lysogenized _V. cholerae_, via spontaneous lytic induction and phage release, kill and displace non-lysogenized bacteria on chitin surfaces. After lysogens become common, however, they can no longer displace remaining non-lysogenized cells. Using a combination of modeling approaches and microscopy experiments, we show that the lysogens’ capacity to displace non-lysogens depends on the ability of phages released by spontaneous induction to reach susceptible non-lysogens. Phage access to non-lysogenized bacterial hosts declines once lysogens become common, and this occurs due to the spatial constraints inherent to biofilm growth as well as to superinfection immunity, which neutralizes phage particles adsorbed to lysogens. Once lysogens comprise the majority of the host population, they can be selected against, because they still incur the cost of spontaneous induction without gaining the benefit of killing non-lysogen cells via phage release. The cost of lytic induction, phage-mediated killing of non-lysogens, and constraints on phage mobility within host bacterial biofilms together yield population dynamics that are consistent with negative frequency dependent selection for lysogenized cells under physiologically realistic growth conditions.

###### Related
-  [[frequency-dependent selection]]
- [[NFD]]
- [[CTXφ]]
- [[V cholerae]]
- [[Phage Life Cycle]]
- [[frequency-dependent selection]]

###### Referenced Papers 
- 


### Detailed notes
#### Introduction
phage K139 lysogenixes and non-lysogenix V cholerae 
- " lysogenized _V. cholerae_, via spontaneous lytic induction and phage release, kill and displace non-lysogenized bacteria on chitin surfaces"
	- lysogens become common -> no longer displace remaining cells 
	- capacity to displace non lysogens depends on ability to be released by [[spontaneous induction]] 
	- [[superinfection immunity]]
	- lysogens in majority --> can be selected against --> still have COST of spontaenous induction without the benefit killing non lysogens through phage release
		- #question -> do non lysogen cells that become infected lyse?
- [[Temperate Phage]] - production of new [[virion]] --> [[lytic cycle]]
	- or vertical genome propogation (genome replication occurs when host divides) --> [[lysogenic cycle]]
- reversion from lysogenic to lytic cycles
	- environmental exposures
	- DNA damage, high host cell density 
	- --> burst of new phages 
- [[lytic induction]] - spontaneously at low rates 
	- dont affect lysogens due to [[superinfection immunity]]
	- may kill non lysogens during lytic infection or integraton into genome to make new lysogens 
	- killing them = realives intraspecific competition 
 >[!quote] "In this manner, temperate phages can displace susceptible cells either by converting them to new lysogens, or by killing them, which not only releases bursts of phage virions but also relieves intraspecific competition for limiting space and growth substrates for other lysogens that have not been induced to the lytic cycle."

access + exploitation --> receptor compatibility, avoidance of phage defense systems
community scale: physical structure 
- biofilm environments 

fundamental perspective: phage biofilm interactions common in nature 
applied: constraints of phage infection --> [[Phage Therapy]]

>[!info] For example, little is known about how well phages released from biofilm-embedded lysogens can propagate through the rest of the host population, particularly in physiologically realistic conditions.

artificial seawater + chitin --> marine snow simulation 

spatial constraint + superinfection immunity promote coexistance of lysogenixed and non-lysogenized

#### Results
##### Mini methods
- [[PDMS]]
- see: [[Peng Methods]]
- k139 lysogens --> superinfection immunitiy --> phages adsorb and inject genome, but does not result in lytic infection 
	- 'sinks' for unproductive phage adsorption 
- parental lysogen - parental non-lysogen (phage susceptible) subpopulations
- mKate22 mKOk - neutral site in cholera genome !!!
- lysogens + non lysogens --> indistinguishable growth in monoculture + fluorescent protein doesnt influence competiton 
##### Population dynamics of lysogens and non lysogens in marine snow conditions 
- rare lysogen = increase in frequency 
	- selective advantage 
- intermediate lysogen = also increase
	- higher variance in per day change in lysogen fraction --> variation in biofilm size and spatial distribution across replicates 
- lysogen : non-lyogen parity = less consistent 

![[Jack Figure 1.png]]

majority: no change o decrease

>[!quote] "population dynamics across experimental runs implied the operation of negative frequency-dependent selection for lysogens in competition with susceptible cells, with lysogens approaching an equilibrium frequency of ∼0.88"

phage released by spontaneous induction --> benefit lysogens by removing non lysogens from surface --> benefit is dependent on frequency 
- effect specific to biofilm environment --> lysogens "positively selected regardless of initial frequency"

frequency of newly produce lysogens: 0.015
de novo resistant mutants: 0.015 
- deltak139 which removes prophage in non lysogen --> also removes attP site where k139 integrates when lysogenizing --> reduced potential for phage susceptible cells to become lysogenized -- most infection lytic 
- growth of lysogen - outgrowth of previously existing lysogens - not novel lysogenization 
- selective pressure for resistance low - cant explain why non lysogens remain at the end 

lysogens -> frequency dependent advantage --> local phage release that selectively removes susceptible competitors --> limitted by spatial constraint and lysogen abundance 
- lysogens adsorb + neutralize phages #question (isnt this self limitting)

##### Lysogens block phage access to susceptible cells in a simple percolation model 
- rare / moderate - benefit of partial lytic induction exceeds cost of induction 
	- benefit of partial lytic induction: removal of competing non lysogens
	- cost of induction: death of fraction of lysogen population 
- [[superinfection immunity]] --> non productive adsorption 
- percolation model 
	- fixed cells - uninfected non lysogens, infected non lysogens, lysogens (phage adsorbing, immune) #question is rate of spontaneous induction and adsorption balanced? 
	- random distribution of L and NL --> assumed infection origin at center 
	- model tracks fraction of suceptible cells within continuos contact with each other from initial site of phage infection --> lysogens are barrier to phage propogation 
		- did not include phage replication and diffusion, cell growth, division, or movement 
	- increasing lysogen frequency restricts infection spread 

![[Jack Figure 2.png]]

even with differences in clustering (eg larger patches less even distribution) and open space (that can / cannot be traversed by phage) --> similar relationship between L and LN frequency 
- ecll infection declined at a slightly lower frequency relatibe to random simulation 
- can have.0 infection due to clusters of lysogens trapping infection propagation at point of origin
- 'herd immunity'
reaction-diffusion model 
- recapitulate tendency towards L NL coexistence with spatial constraints
lysogens only have fitness advantage when actively elinating susceptible cells (not in majority)
- net fitness disadvantage when competing with NL
##### Lytic induction cost imposes a fitness defect in the absence of phage-mediated killing
- test assumption that phage release is responsible for NL cell death + cost of prophage induction sufficient to explain selection against L 
- measure degree of cell death in susceptible strain in presence of lysogens that produce functional pahges after induction 
	- visualization: SYTOX green 
- pervasive phage suscpetible cell death when lysogens initiated at low frequency 
![[Jack figure 3.png]]

isolating killling effects 
- two K139 derived strains w/ capsid GFP translational fusions -> spontaenous lytic induction from host lysogens at the same rate as parental K139. 
	- GFP-K139 virions that reatin infectivity - used strain wirth orf18-GFP translationfusion at ectopic locus
	- allsows incorporation of subset of GFP tagged proteins into wild type K139 capsis --> flourescent labeled phages 
	- GFP-K139-D - GFP and orf18 at native locus in prophage genome (no ectopic constructO --> virions unable to cuse new infectio
		- --> no observed cell death 
- cost of lytic induction is constant, but killing abaility different 
>[!Quote] "By monitoring the competitive dynamics of susceptible non-lysogens in co-culture with lysogens that release infectious phages, versus lysogens that release non-infectious phages, we could assess the assumption that the cost of spontaneous lytic induction yields a net fitness defect to lysogens when the phages they release cannot kill susceptible hosts."
- when repeated NFD expirement from figure 1 with the two toggle strains non infectious phage producer eliminated day 6 / no increase even when low starting population 

#### Discussion 

>[!Tip] "Another important consideration is that our study does not address the fact that many natural biofilm systems are thought to contain dozens or hundreds of different species ([88](https://www.biorxiv.org/content/10.1101/2025.11.26.690769v2.full#ref-88)–[90](https://www.biorxiv.org/content/10.1101/2025.11.26.690769v2.full#ref-90)). The presence of numerous other species that are not susceptible to a given phage, for example, could impose additional barriers to phage diffusion that would limit the ability of spontaneously induced prophages to alter the community composition ([44](https://www.biorxiv.org/content/10.1101/2025.11.26.690769v2.full#ref-44), [91](https://www.biorxiv.org/content/10.1101/2025.11.26.690769v2.full#ref-91), [92](https://www.biorxiv.org/content/10.1101/2025.11.26.690769v2.full#ref-92)). Further increases to ecological realism in the design of future experiments will be important to assess the generality of the results reported here."

- "Our results also corroborate prior theoretical work in the biofilm literature, which has found that refugia in which some bacterial cells remain unexposed to phages are crucial to coexistence of phages and susceptible hosts ([36](https://www.biorxiv.org/content/10.1101/2025.11.26.690769v2.full#ref-36), [41](https://www.biorxiv.org/content/10.1101/2025.11.26.690769v2.full#ref-41), [82](https://www.biorxiv.org/content/10.1101/2025.11.26.690769v2.full#ref-82)). These refugia can emerge spontaneously due to biofilm architecture that limits phage diffusion, but in the instance described here, refuge from phage exposure emerges when lysogens become common enough to prevent access to susceptible hosts by phages released by spontaneous induction."

[[superinfection exclusion]] --> mechanism that some temperate phages use to prevent attachment of released virvions to the surface of other lysogens 
- eg pilZ interacting protein Zip --> reduction in [[Type IV Pili]] length + count --> prevents phage adsorption into binding site 