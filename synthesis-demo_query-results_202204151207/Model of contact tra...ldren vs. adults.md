---
title: [[EVD]] - Model of contact tracing data from Hunan CDC estimates ~30 percent lower risk of infection for children vs. adults - [[@zhangChangesContactPatterns2020]]
url: https://roamresearch.com/#/app/roam-synthesis/page/qOe_I_-hH
author: Joel Chan
foo: bar
date: Mon Jun 14 2021 16:06:07 GMT-0400 (Eastern Daylight Time)
Location: China
Testing: 
---

- ## Summary::

    - fitted a [generalized linear mixed model regression](((au-LWQV8h))) to contact-tracing data for 7375 [close contacts](((EDPb9ARd_))) of 136 [index cases](((JJZ0C_t_m))) from the [Hunan](((DC6GQTVJK))) CDC, and estimated that young individuals (aged 0 to 14 years) had a [lower risk of infection](((L78oLtyVO))) compared to individuals aged 15-64 years ([odds ratio.md](odds ratio.md)

        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fjoel-covid19%2FZkClb3yUo6.png?alt=media&token=af46e2b1-244e-4e33-af36-1c7ab26d0779) (p. 29, SI)

        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fjoel-covid19%2FVoCLZAMXv-.png?alt=media&token=30fdc588-23c3-4025-83e3-8601fd8772f5) (p. 368)

        - relevant for [How susceptible are ...valent exposure?.md](How susceptible are ...valent exposure?.md)
- ## Grounding Context:: ((how might we reproduce this observation?))

    - setting: Hunan, China, between [January 16, 2020.md](January 16, 2020.md)

        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fjoel-covid19%2FmIOmFncDpc.png?alt=media&token=329f3ec5-c0bd-49aa-9b20-c2840056e2f0)

    - Location:: [China.md](China.md)

    - index case: symptom-based, travel-based, or contact-based

        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fjoel-covid19%2FqBJHCGQTwA.png?alt=media&token=11efb787-006b-40eb-9c06-fc9137d7e54a)

    - secondary cases were identified through exhaustive testing of all known close contacts, using official guidelines of Hunan province

        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fjoel-covid19%2FZ3pPbCOGME.png?alt=media&token=d14be215-5f50-4cbd-9422-e0b05d3fcc90)

    - independent variable: age: 0-14 years, 15-64 years, 65% years, and unknown age

        - ((OmsJcd2Mf))

    - dependent variable: binary outcome of infection or not

    - control variables: gender, type of contact with index case, exposure before/after strict social distancing, whether traveled to/from Wuhan/Hubei

        - ((OmsJcd2Mf))

    - statistical model: generalized linear mixed-effects model with a binary outcome (logit link), predicting [infection status](((WHG6hd9ae))) as a function of [age](((Vaay6GGbf))), and [controlling for various covariates](((vKWqUA7o6))); also cross-checked with fixed-effects logit and cluster-stratified Cox model

        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fjoel-covid19%2FBM_Xh1w9k0.png?alt=media&token=b5129f64-6bdb-4b9f-8c9e-31c39041d3d4)

    - Location:: [China.md](China.md)

###### Discourse Context

- **Informs::** How susceptible are ...valent exposure?.md
- **Supports::** Children are less li...ivalent exposure.md
- **ConsistentWith::** prevalence of COVID ...mpared to adults.md
- **ConsistentWith::** Model of PCR data in...ldren vs. adults.md
- **ConsistentWith::** Better model fit to ...ower than adults.md
- **SourcedBy::** zhangChangesContactPatterns2020.md

###### References

June 14th, 2021.md

- [Model of contact tra...ldren vs. adults.md](Model of contact tra...ldren vs. adults.md)

    - From: E - Model of contact tracing data from Hunan CDC estimates _30 percent lower risk of infection for children vs. adults - @zhangChangesContactPatterns2020.json
