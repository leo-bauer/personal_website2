---
layout: default
is_contact: true
---

## Data

### Published Datasets

* **Mediation in Self-Determination Disputes Dataset**

Th Mediation in Self-Determination Disputes Dataset (MSDD) provides original mediation event data for a global sample of self-determination disputes between 1991 and 2015, both during and outside of civil conflict. We record three types of mediation events: bilateral mediation with only one side of the dispute and a mediator present, direct mediation with both sides and a mediator present as well as shuttle diplomacy. We sampled disputes randomly and the MSDD contains 1,285 mediation events for 51 disputes spanning 1,131 dispute-years. The MSDD allows us to test theoretical expectations about the use of mediation to prevent civil war. Access the data [here](https://doi.org/10.7910/DVN/SA4KYD){:target="_blank"}{:rel="noopener noreferrer"}.

Cite as: Cunningham, David E., Leo Bauer, Sloan Lansdale, and Megan Lloyd. "Under What Conditions Does Preventive Mediation Occur in Self-Determination Disputes?" 2026. *Journal of Peace Research*, online first. [doi:10.1093/jopres/xjaf033](https://doi.org/10.1093/jopres/xjaf033){:target="_blank"}{:rel="noopener noreferrer"}.

* **SRDP to UCDP Conversion Dataset**

This dataset contains all Strategies of Resistance Data Project (SRDP) faction IDs that match an Uppsala Conflict Data Program (UCDP) actor ID and thus allows for merging SRDP with UCDP data. To construct the dataset, I matched SRDP factions with UCDP non-state actors engaged in state-based conflict via both an automated string matching technique and manual matching. As SRDP factions are sometimes more disaggregated than UCDP actors, several SRDP factions may match with the same UCDP actor but not the other way around. The dataset contains 230 SRDP factions and 141 UCDP non-state actors. Access the data [here](https://leo-bauer.com/files/srdp-ucdp_conversion.csv).

Cite as: Bauer, Leo, and Kathleen Gallagher Cunningham. "The Nonviolent Legacies of Rebel Group Origins." 2026. *Journal of Peace Research*, 63(3): 309--320. [doi:10.1093/jopres/xjaf024](https://doi.org/10.1093/jopres/xjaf024){:target="_blank"}{:rel="noopener noreferrer"}.

### Datasets in Progress

* **Rebel-Civilian Social Ties Dataset**

This dataset records the existence of social ties between rebels and civilians at the outset of conflict. Social ties between rebels and civilians are present if at conflict onset (1) the majority of a rebel group’s members and leadership originate from a delimited geographical location such as an urban neighborhood, village, town, or a cluster of such localities that is smaller than a first-order administrative boundary and (2) the group is based in and challenges the state in this area. I record social ties as a binary variable for all UCDP non-state actors engaged in state-based conflict active between 1990 and 2018, resulting in a dataset comprising 358 dyads. 

* **Non-State Actors in Armed Conflict Dataset Update**

The Non-State Actor Data (NSA) Update builds on the original NSA by Cunningham, Gleditsch and Salehyan, whose coverage ends in 2011. We code all variables that record information on rebel characteristics for dyads active between 2012 and 2024, excluding external support variables. With the update we add more than 250 dyad spells to the original NSA and make the NSA fully compatible with v24.1 of the UCDP Armed Conflict Dataset. The dataset allows us to explore trends in rebel organizational characteristics and capabilities over time for a comprehensive sample of rebel groups.

### Data Collection Scripts

* **Peaceful Revolution Protest Data Scraper**

This webscraper allows for the collection of protest event data on the 1989--1990 Peaceful Revolution in the German Democratic Republic from the most comprehensive publicly available archive. The webscraper is written in Python. Access the webscraper [here](https://github.com/leo-bauer/gdr-protest-scraper){:target="_blank"}{:rel="noopener noreferrer"}.

* **Junge Freiheit News Archive Scraper**

This webscraper allows for the collection of text data for all articles published between 1997 and 2019 in *Junge Freiheit*, Germany’s biggest weekly far-right newspaper. The webscraper is written in Python. Access the webscraper [here](https://github.com/leo-bauer/junge-freiheit-scraper){:target="_blank"}{:rel="noopener noreferrer"}.
