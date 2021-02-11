---
layout: post
title: Polyp bailout update
author: Hannah Reich
date: 02/02/2021
tags: polyp bailout, Micropropagule, Pocillopora, synthetic coral, Putnam lab, NSF HDR, phenotype, survivorship
---

# Overview
This entry describes the results of the polyp bailout trials run during november 2020- january 2021. *Pocillopora acuta* fragments (n=4 treatment; n=4 control) were used for all trials.

# Relevant links
- [detailed protocol for inducing Pocillopora acuta polyp bailout via hyperosmotic stress](https://github.com/thesyntheticcoral/SynCoral_Protocols/blob/master/Polyp_Bailout/PUTNAM_LAB_POLYP_BAILOUT_PROTOCOL.md)
- [lab notebook post on Micropropagule phenotyping](https://github.com/hgreich/HGRlabnotebook/blob/master/_posts/20210120_micropropagule_phenotyping.Md)
- [Rmarkdown file with code for figures and stats](https://github.com/thesyntheticcoral/PolypBailoutExpt/blob/main/scripts/PolypBailoutTrialFigs.Rmd)

## Optimizing the salinity ramp
The initial trials in nov 2020 did not elicit sufficient hyperosmotic stress to induce bailout after ~48hr of gradual salinity increase to ~54psu. Though exposure to ~53-55psu has resulted in *P. damicornis* bailout at ~48hr in other studies [overview of literature in protocol](https://github.com/thesyntheticcoral/SynCoral_Protocols/blob/master/Polyp_Bailout/PUTNAM_LAB_POLYP_BAILOUT_PROTOCOL.md), It took 4-5days of exposure to ~53-55psu for our *P. acuta* fragments to bailout.

Following trials increased salinity to ~58-60psu over a 48hr period. This resulted in polyp bailout of all colonies after the salinity ramp. The majority of all colonies (50+%) released Micropropagules. **It is best to program salinity ramps so that one can be in lab within an hour of the control tank reaching ~58-60psu**

## Settlement rates remain at 0%
Thus far, no Micropropagules have settled. Some settlement substrates used are aragonite plugs, microscope slide coverslips, and small petri dishes. We have provided these settlement substrates in "pre-conditioned" form (exposed to water tables for 1+ week prior to experimentation) and "not-preconditioned" (i.e., right out of the bag). Future efforts to increase settlement rates will include using waterproof paper (non-preconditioned, pers comm from ASHuffmyer), and pre-conditioned petri dishes and microscope coverslips with red tape on them.

It is unsurprising settlement has not occurred given the "small" size of the *P. acuta* fragments used. In the literature, settlement rates are <5%. We hope that as we "scale-up" these experiments settlement will increase (i.e., using larger fragments which results in more Micropropagules).

## Micropropagule (MP) 'abundance' is highest immediately following bailout
![Micropropagule abundance by day and trial](https://github.com/thesyntheticcoral/PolypBailoutExpt/blob/main/figures/MP_survival_all_trials.png)

## There is some consistency between proportions of MP phenotypes between trials but less so by 'day-of-trial'
![fig](https://github.com/thesyntheticcoral/PolypBailoutExpt/blob/main/figures/mp_pheno_pct_all_trials.png)
The percentage of degenerated polyps (DPs) are often twice as frequent as recovered polyps (RPs). This disparity increases over time (DP Kruskal-Wallis chi-squared = 9.6544, df = 4, p-value = 0.04667; RP Kruskal-Wallis chi-squared = 8.8022, df = 4, p-value = 0.06624). There were no significant differences between trials.

## Percent Survivorship is higher in more recent trials (with 'optimized' salinity ramps) but varies by day of trial
![fig](https://github.com/thesyntheticcoral/PolypBailoutExpt/blob/main/figures/survivorship_alltrials.png)
Survivorship on trial day 3 (1 day post bailout) was highest (86%) when corals/Micropropagules were removed from ~60psu within an hour of reaching the salinity level (trial started 20210118). Trials where the corals/Micropropagules were left in ~58-60psu for more than an hour had lower survivorship (~24-66% survivorship). Overall, survivorship varied significantly by trial (Kruskal-Wallis chi-squared = 10.733, df = 3, p-value = 0.01326) but not within trial. Survivorship significantly decreased through time during each trial (Kruskal-Wallis chi-squared = 20.99, df = 4, p-value = 0.0003181).

## "Recovered" Micropropagules (RP) are larger than "degenerated" Micropropagules (DP)
![fig](https://github.com/thesyntheticcoral/PolypBailoutExpt/blob/main/figures/mp_size_by_pheno.png)
Data from the 20210112 trial demonstrate how DP's are significantly smaller than RP's (Kruskal-Wallis chi-squared = 40.464, df = 1, p-value = 2.003e-10). The surface area of RP's are nearly 4x larger (average 0.35 mm2) larger than DP's (average 0.010 mm2). MP size did not vary significantly by day (Kruskal-Wallis chi-squared = 3.2425, df = 3, p-value = 0.3557).

![fig](https://github.com/thesyntheticcoral/PolypBailoutExpt/blob/main/figures/mp_size_by_pheno_AND_fragid.png)
MP size did not vary by coral fragment (Kruskal-Wallis chi-squared = 1.1922, df = 3, p-value = 0.7549)
