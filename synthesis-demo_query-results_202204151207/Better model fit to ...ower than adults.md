---
title: [[EVD]] - Better model fit to Wuhan case data with age-dependent susceptibility, with children ~2x lower than adults - [[@cmmidcovid-19workinggroupAgedependentEffectsTransmission2020]]
url: https://roamresearch.com/#/app/roam-synthesis/page/g00easazW
author: Joel Chan
foo: bar
date: Mon Jun 14 2021 16:06:07 GMT-0400 (Eastern Daylight Time)
Location: China
Testing: mixed
---

- # **Summary**

    - Better [model](((y3p62r0pE))) fit to case data in Wuhan from [early 2020](((EfARucwb2))) when model allowed susceptibility and clinical severity to [vary by age](((kixkpTWIB))). This model estimated that relative susceptibility of children aged 0-9 (0.4) was [approximately half](((_Ap8fPT7f))) that of adults over 20 (~0.8).

        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fjoel-covid19%2Frnfcgv2qs7.png?alt=media&token=67caf0db-a194-4011-8cc9-45f3df4fed1d)

        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fjoel-covid19%2FgjdTvllqwi.png?alt=media&token=f90af533-d4f6-4812-a582-9c373f7c209b)

    - Model fit is significantly better in terms of DIC than model with only age-varying susceptibility OR severity, or no age-varying factors.

        - > "Comparison using the deviance information criterion6 (DIC) showed that the age-varying susceptibility (DIC, 697) and age-varying clinical fraction (DIC, 663) model variants were preferred over the model with neither (DIC, 976)." ([CMMID COVID-19 working group et al 2020:2](zotero://open-pdf/groups/2451508/items/FCWP5YBA?page=2))

    - Note: I don't fully understand the susceptibility measure yet: says it relative, but.. relative to what?
- # **Grounding Context**

    - source:: [cmmidcovid-19working...Transmission2020.md](cmmidcovid-19working...Transmission2020.md)

    - Location:: [China.md](China.md)

    - Seemed to be early in the pandemic

        - > We assumed that initial cases were in adults, and accounted for school closures in the model by decreasing the school contacts of children starting on 12 January 2020, when schools were closed for the Lunar New Year holiday. We also estimated the effect of the Lunar New Year holiday period on non-school contact rates from 12 January to 22 January 2020, as well as the impact on transmission of travel and movement restrictions in Wuhan, which came into effect on 23 January 2020 (Fig. 1d)." ([CMMID COVID-19 working group et al 2020:2](zotero://open-pdf/groups/2451508/items/FCWP5YBA?page=2))

    - Used an age-structured deterministic compartmental model

        - > "age-structured deterministic compartmental model (Fig. 1a) stratified into 5-year age bands, with time approximated in discrete steps of 0.25 days. Compartments in the model are stratified by infection state (S, E, IP, IC, IS or R), age band and the number of time steps remaining before transition to the next infection state" ([CMMID COVID-19 working group et al 2020:8](zotero://open-pdf/groups/2451508/items/FCWP5YBA?page=8))

    - Model fitted to case data using Markov Chain Monte Carlo with negative binomial likelihood for incident cases and Dirichlet-multinomial likelihood for age-distribution of cases ([CMMID COVID-19 working group et al 2020:8](zotero://open-pdf/groups/2451508/items/FCWP5YBA?page=8))

    - Many assumptions are made in the model, but most seem defensible. The discussion of limitations highlights some questionable ones. Examples:

        - assume subclinical infections less infectious than clinically apparent infections by about 50% ([CMMID COVID-19 working group et al 2020:5](zotero://open-pdf/groups/2451508/items/FCWP5YBA?page=5))

        - assume a stationary distribution of cases over age, set from the early part of the epidemic (likely false: likely some variation in age distribution over the  course of the epidemic). see ([note on p.8](zotero://open-pdf/groups/2451508/items/FCWP5YBA?page=8))_

    - testingRegime:: mixed

        - Notably, I **did not detect any corrections made for possible reporting bias due to symptomatic testing** (e.g., if testing often symptom-based, and children less likely to be symptomatic, then their case data are likely undercounted by some amount)

    - Code and data available here: https://github.com/cmmid/covid-age

        - Data sources for case data:

            - Liu, Z., Xing, B. & Xue Za, Z. The epidemiological characteristics of an outbreak of 2019 novel coronavirus diseases (COVID-19) in China. Chin. J. Epidemiol. 41, 145–151 (2020).

            - Li, Q. et al. Early transmission dynamics in Wuhan, China, of novel coronavirus-infected pneumonia. N. Engl. J. Med. 382, 1199–1207 (2020).
- self-cite by [vinerSusceptibilityS...oV2Infection2020.md](vinerSusceptibilityS...oV2Infection2020.md)

###### Discourse Context

- **Informs::** How susceptible are ...valent exposure?.md
- **Supports::** Children are less li...ivalent exposure.md
- **ConsistentWith::** prevalence of COVID ...mpared to adults.md
- **ConsistentWith::** Model of PCR data in...ldren vs. adults.md
- **ConsistentWith::** Model of contact tra...ldren vs. adults.md
- **SourcedBy::** cmmidcovid-19working...Transmission2020.md

###### References

June 14th, 2021.md

- [Better model fit to ...ower than adults.md](Better model fit to ...ower than adults.md)

    - From: E - Better model fit to Wuhan case data with age-dependent susceptibility, with children _2x lower than adults - @cmmidcovid-19workinggroupAgedependentEffectsTransmission2020.json
How susceptible are ...valent exposure?.md

- [Better model fit to ...ower than adults.md](Better model fit to ...ower than adults.md)

    - this doesn't make sense!!
March 18th, 2022.md

- e.g., this one: [Better model fit to ...ower than adults.md](Better model fit to ...ower than adults.md)

    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froam-synthesis%2FQznIHB-xwh.28.08.png?alt=media&token=110869df-32c8-4989-86f2-3f7c23219d07)
