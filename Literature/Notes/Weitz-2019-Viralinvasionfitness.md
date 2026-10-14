---
title: Viral invasion fitness across a continuum from lysis to latency
authors: Joshua S Weitz, Guanlin Li, Hayriye Gulbudak, Michael H Cortez, Rachel J Whitaker
year: "2019"
publication: Virus Evolution
DOI: 10.1093/ve/vez006
urgl: https://doi.org/10.1093/ve/vez006
tags:
  - organism/phage
  - organism/bacteria/vibrio
  - interaction
Topic: vibrio-phage
---

###### Abstract
The prevailing paradigm in ecological studies of viruses and their microbial hosts is that the reproductive success of viruses depends on the proliferation of the ‘predator’, that is, the virus particle. Yet, viruses are obligate intracellular parasites, and the virus genome—the actual unit of selection—can persist and proliferate from one cell generation to the next without lysis or the production of new virus particles. <mark style="background: #FFF3A3A6;">Here, we propose a theoretical framework to quantify the invasion fitness of viruses using an epidemiological cell-centric metric that focuses on the proliferation of viral genomes inside cells instead of virus particles outside cells.</mark> This cell-centric metric enables <mark style="background: #FFF3A3A6;">direct comparison of viral strategies characterized by obligate killing of hosts (e.g. via lysis), persistence of viral genomes inside hosts (e.g. via lysogeny), and strategies along a continuum between these extremes (e.g. via chronic infections).</mark> As a result, we can identify environmental drivers, life history traits, and key feedbacks that govern variation in viral propagation in nonlinear population models. For example, we identify threshold conditions given relatively <mark style="background: #FFF3A3A6;">low densities of susceptible cells and relatively high growth rates of infected cells in which lysogenic and other chronic strategies have higher potential viral reproduction than lytic strategies</mark>. Altogether, the theoretical framework helps unify the ongoing study of eco-evolutionary drivers of viral strategies in natural environments.

##### Related
- [[Peng-2026-Temperatephageslimit]]
- [[Lysogeny]]
- [[lytic cycle]]
- [[lytic phages]]
- [[lytic induction]]
- [[lysogenic cycle]]

### Detailed Notes
#### Introduction 
- infection --> interaction between [[virion]] and host cell 
- ultimately [[lysis]] 
- driver of cell death --> large focus of studies 
- [[phage λ]] - [[Temperate Phage]]
	- integrate genome with host -- integrated viral DNA = [[prophage]]
- chronic viruses [[filamentous phage]] [[M13]] 
	- episomal persistance 
	- genome replication, package inparticle + released without cell washout #question 
		- same system exist in archaeal virus-host system
- marine hydrotherm and soil environments -> uggested lysogeny more common than assumed 
- [[viral dark matter]] - integrated and extrachromosomal viral sequence in microbial genomes
stewart and levin 1984
- temperate phage could persist as long term prophages if integration enhanced host fitness or enhanced resistance to infections by other lytic phage - [[superinfection immunity]]
- change sin host abundance --> niche 
	- favorability of lysogeny over lysis at low abundances doesnt perclude lysis being favored strategy 
game theory 
- [[game theory]]
- temperate strategy = rapid expansion during stability for host, mitigates risk of population collapse during unstable
	- long term favorability does not mean it is favorable for the virus at specific moment in time 
mathematical epidemiology
- quantify viral fitness measured in terms of proliferation of inected cells 
- change to [[R0]]
- lytic, latent, chronic 
- purely lytic phage: phage reproductive number


--- skipped methods -------

#### Results 
##### Cell-centric metric of viral fitness
predator prey dynamics vs infectious spread 
- R0 = basic reproduction number
	- >1 pathogen increases abundance 
revised R0 for virus-microbe dynamics
- <mark style="background: #BBFABBA6;"> average number of new infected cells produced by a single infected cell and its progeny virions in an otherwise susceptible population </mark>
- [[virocell]]
- comparison of vertical transmission infection versus horizontal transmission infection - [[HGT]]
- does not account for feedback between viral population growth and environment - see discussion 

##### Obligately lytic viral strategies: a baseline for comparison
- dynamics represented with nonlinear differential equations 
- [[NGM]] approach 

![[viral invasion schema.png]]![[fitness of lytic phage.png]]
B = burst size, O = adsorption rate, m = decay rate of virions, 1/n is latent period, d' is loss rate of infected cells, and S* is equilibrium density of susceptible cells 
= threshold of the horizontal contributions to basic reproduction number 
- first factor = probability of adsorbtion before decay
- second factor = fraction of infected cells that lyse before being washed out of system 
- multiply probabilities by burst size --> number of new virions released --> yields average number of new infections by single virions = Rhor (reproductive phage number)
	- [[Rhor]]
- viral proliferation varies with life history traits - burst size + ecological context - initial cell density (figure 2 [[fitness of lytic phage.png]])
- can do same calculation but with cell producing newly infected cells
##### latent viral strategies
vertical and horizontal transmission - but not both simulatenously 
- exclusive integration case 
	- b' division rate of infected cells, K density of suceptible cells in absence of virus, other paremters same as obligate lytic 
	- Ro = vertical transmission of viral genomes
		- birth rate of lisogen - decreases with increasing cells 
		- average lifespan of individua lysogen 
	- Ro = average number of newly infectious cells produced in the lifetime of the original infection 
	
higher lysogen production when lower competiton m - [[S*]] < K
- lysogens have advantageous life history = spread exclusievly thorugh vertical transmission 
- lysogeny cost = vertical transmission not enough for Rver > 1
	- monotonically decreasing function = population increase decreades advantage of VT

Rhor and Rver cross at a critical value Sc 
- S > Sc = horizontal, S < Sc = vertical 
- induction = rare --> R0 converged to maximum of Rver and Rhor 
	- critical cell density 

##### chronic viral strategies 
- concurrent vertical and horizontal transmission 
- 
