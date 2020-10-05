---
layout: default
title: UCD Prop 17 Data Challenge
---

Prop 17 is a California constitutional amendment on the ballot, November 3, 2020, for restoring the voting rights of persons on parole. 

A **yes** on the ballot would restore the parolees right to vote, while a **no** will do the opposite. Here are few graphics we have put together to illuminate the prop 17 ballot.

## About
In order to get a better sense for the disenfranchisement of parolees in california we hope to paint a better picture of who parolees might be, and which communities might see the most new votes if parolees are allowed to vote. Additionally some interesting analysis has been done in other states that have allowed parole votes and there is some interesting analysis regarding the attitudes towards this proposition. 

## Parolee Demographics

### Parolee age distribution
{% include parole_age.html %}
**Fig 1.** Parole age distribution

### Parolee agent caseload distribution
{% include parole_agent_caseload.html %}
**Fig 2.** Parole-agent caseload distribution

### Parolee ethnicities
{% include parole_ethnicity.html %}
**Fig 3.** Parole ethnicity distribution

## California major parole populations and county partisanship
{% include parolees_vs_partisan_counties.html %}
**Fig 4.** The color scheme represents majority partisan party, red and blue colors are associated with the republican and democratic parties respectively.

This illustration does not represent the entire parolee population by county map, missing is 17,914 "others" [1]. It would be greatly appreciated if our primary source [1] could enumerate the entire list of counties and parole population in a complete table.

[1] California Department of Corrections and Rehabilitation (CDCR). (2018) "OFFENDER DEMOGRAPHICS FOR THE 24-MONTH PERIOD ENDING DECEMBER 2018", Retrieved from <https://www.cdcr.ca.gov/research/offender-outcomes-characteristics/offender-data-points/>

[2] Report of Registration. Retrieved from <https://www.sos.ca.gov/elections/report-registration/15-day-gen-2018>

{% include ratio_parole.html %}
**Fig 5.** 

## Infering Attitudes Towards Prop 17 Over The Years
{% include s_and_o.html %}
**Fig 6.** Gauging proponents and opponents of prop 17 from YouTube API data.

## Other States After Approving Prop 17
![p1](/assets/MD_Voter_Turnout.png)
**Fig 7.** Maryland voter turn out after parolees allowed to vote.

![p2](/assets/RI_Voter_Turnout.png)
**Fig 8.** Rhode Island voter turn out after parolees allowed to vote.
