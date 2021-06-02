---
layout: post
title: 20210524_polyp_bailout_expt_planning
date: '2021-05-24'
categories: Goals, Protocols
tags: [polyp bailout, pocillopora, NSF HDR, Syn Coral, physiology, Putnam Lab]
---

Date started: 20210520

Date last revised: 20210601 HGR adding schedule updates, etc.

# Lab notebook post on experimental design for the polyp bailout work and timepoints for the response variables

*Project rationale:* determine the recovery dynamics of Pocillopora acuta (and endosymbiotic dinoflagellate) following hyperosmotic-induced polyp bailout. An understanding of how exposure to acute hyperosmotic stress influences coral/algal physiology and energy budgets will better inform best practices for future coral-on-a-chip experimental work.

# Table of response variable timepoints

| Timepoint | Rationale | Response variables |
| --- | --- | --- |
| T-0, 35 psu, start | examine physiology before hyperosmotic stress* | Host lipid, carbohydrate, protein, Symbiont PSII photochemical efficiency, density, cell size, chlorophyll content |
| T-1d, 48 psu, pre-bailout | examine physiology during hyperosmotic stress* | Host lipid, carbohydrate, protein, Symbiont PSII photochemical efficiency, density, cell size, chlorophyll content |
| T-2d, 60 psu, bailout | examine physiology of recently bailed out micropropagules | micropropagule size, micropropagule phenotype, corallite counts, Host lipid, carbohydrate, protein, Symbiont PSII photochemical efficiency, density, cell size, chlorophyll content |
| T-3d, 35 psu, pre-settlement*** | determine whether recovery occurs pre-settlement** | micropropagule surivivorship, micropropagule size, micropropagule phenotype, Host lipid, carbohydrate, Symbiont PSII photochemical efficiency, density, cell size, chlorophyll content |
| T-5d, 35 psu, post-settlement**** | determine how settlement alters energy dynamics and recovery | settlement success, secondary recruit size, Host lipid, carbohydrate, protein, Symbiont PSII photochemical efficiency, density, cell size, chlorophyll content |
| T-12d, 35 psu, juvenile growth | track recovery dynamics through time | secondary recruit survivorship, secondary recruit growth, Host lipid, carbohydrate, protein, Symbiont PSII photochemical efficiency, density, cell size, chlorophyll content |  
| T-26d, 35 psu, juvenile growth | track recovery dynamics through time | secondary recruit survivorship, secondary recruit growth, Host lipid, carbohydrate, protein, Symbiont PSII photochemical efficiency, density, cell size, chlorophyll content |
| T-1 month, 35 psu, juvenile growth | track recovery dynamics through time | secondary recruit survivorship, secondary recruit growth, Host lipid, carbohydrate, protein, Symbiont PSII photochemical efficiency, density, cell size, chlorophyll content |
| T-2 month, 35 psu, juvenile growth | track recovery dynamics through time | secondary recruit survivorship, secondary recruit growth, Host lipid, carbohydrate, protein, Symbiont PSII photochemical efficiency, density, cell size, chlorophyll content |

## points of consideration

- * The T-0 and T-1d timepoints will require airbrushing adults whereas the remaining timepoints will involve micropropagule/juvenile preservation.
- ** could consider preserving micropropagules by phenotype to determine differences in recovery dynamics between degenerated verses recovered polyps
- *** will want to evaluate settlement success rates with different settlement substrates (waterproof paper, fresh microscope slide cover slips, fresh microscope slide cover slips with red tape, pre-conditioned microscope slide cover slips, pre-conditioned microscope slide cover slips with red tape)
- **** this might fall on a weekend
- whether it would be feasible to study symbiont lipid:carb:prot as well as host (for a subset of samples).
- (20210527) removed TAC assay from list of response variables as it has not been particularly informative for some other coral work and is of lower priority for studying the effects of hyperosmotic stress.
- (20210527) incorporate a feeding treatment to see if it can hasten recovery

## Brief overview of experimental design (bailout and settlement)

- Start with control fragments and hyperosmotic stress fragments of *Pocillopora acuta* using the [detailed bailout protocol here](https://github.com/thesyntheticcoral/SynCoral_Protocols/blob/master/Polyp_Bailout/PUTNAM_LAB_POLYP_BAILOUT_PROTOCOL.md). Check for bailout everyday. Fragments will be housed in 153uM mesh chambers that allow water flow but prevent micropropagules from getting stuck in pumps. **NOTE1**: filter all seawater (control and high salinity) with a 0.2uM filter. Use all seawater from the mixing tank rather than water from the recirculating tank. **NOTE2** number of control & treatment fragments will vary by response variable objectives.
- Place polyp bailout mesh chambers in ambient seawater immediately following bailout. Use 6-well plates for settlement trials. Refill wells with 0.2uM filtered seawater 1-2x/week. see *** in 'points of consideration' about experiment to test settlement substrate. These forms of settlement substrate are ideal because they will allow for microscopy work downstream (relative to live rock fragments or skeleton)

## Brief overview of expermental design (coral physiology through time)

- Track suite of physiology parameters through time to monitor host and symbiont recovery. [Repo with links to protocols for assays of interest here](https://github.com/thesyntheticcoral/SynCoral_Protocols/tree/master/Polyp_Bailout)
- all assays will normalize to protein (chla, carb, lipid), corallite count (micropropagule count/ survival), or secondary recruit sizes
- will space out assays (chla, carb, lipid, P:R, PAM), ideally ~3 trials (weeks) with n=5-8 (control and treatment) adults each
- note from KHW & ASH: ~20 Past larvae (~0.5mm2) is enough material for chla/prot/tac extractions. Will likely need to pool recruits - ASH was able to get reliable chla measurements for ~1yr old Mcap recruits (5-7mm2)
- trial assays will determine # micropropagules needed, will want 3 reps of (15, 20, 25, 30, 40) pools of micropropagules for testing chla, prot, lipid, carb extraction protocols (390 per protocol, ~1560 total, will want a few extra for testing sym cell counts and size measurements, equates to ~200 mm2 adult tissue).
- Total micropropagules/ coral tissue needed… assuming 5mm of coral yields 30-40 MPs. Will want ~160 MPs per colony for measurements from at least 7 timepoints (~25 MP for host prot, host lipid, host carb, chla, ~5 for sym density & size). Will want to use colonies capable of rearing 960 MP+ (colony size around ~120 mm).


## proposed schedule (20210602 update - priorities by week for June, by month for Aug-Sept)

### JUNE priorities by week

**overall priorities for June:**
1. 3-4 bailout trials for settlment optimization, scale up sample size after 2
2. Intern onboarding: lab notebook & water quality (AT); executing bailout experiment in incubator (all); filtering seawater (all); diving pam (all); micropagule sizing + phenotyping (all); tracking of settlement success and secondary recruit growth (all); symbiont counts & sizing (all)

| Wk of | objective & primary tasks | intern training | notes |
| --- | --- | --- | --- |
| 6/7 | bailout trial (n=4 salinity, n=4 control) for training/ settlement checks | AT lab notebook & water quality onboarding; RB AT micropropagule counting + phenotyping, settlement checks | show RB AT tris curve cal in R |
| 6/14 | bailout trial (n=4 salinity, n=4 control) for training/ settlement checks | RB AT micropropagule counting + phenotyping, settlement checks, sizing in imageJ | if time - diving PAM  |
| 6/21 | bailout trial (n=6-8 salinity, n=6-8 control) for training/ settlement checks | diving PAM best practices |  try and separate DP and RP for PAM |
| 6/28 |  settlement checks | sym counting/sizing training^; continue diving PAM onboarding | ^ sym count/sizing training does not have to be with micropropagules |

### July - Sept priorities by month

| Month of | objective & primary tasks | intern training | notes |
| --- | --- | --- | --- |
| July | 3-4 bailout trials with larger sample sizes for settlement optimization and assay testing; SDR troubleshooting | P:R with SDR; colorimetric assays (after testing) | HR off with family 7/19-24; RB off 7/30 |
| August | **re-eval bailout plans based on assay testing, settlement success, & secondary recruit survivorship**; bailout trials for assay sampling; assay optimization | sample preservation, colorimetric assays | interns finish |  
| Sept | bailout trials for assay sampling; assay optimization | | |

- ^^ preserve pools of secondary recruits for assay testing (to determining # of recruits needed for each assay)
- SDR plate for P:R is in Hawaii until 20210630
- interested in incorporating feeding treatments

## reagants needed for phys protocols

updated table (20210528) on google drive [here](https://docs.google.com/spreadsheets/d/19jdKqWK7u9aPzEWbmwNnlPqc5GgtQM0Ljxeehmu2yuA/edit?usp=sharing), now includes reagents from Bove [lipid](https://www.protocols.io/view/coral-lipid-assay-for-96-well-plates-bvcfn2tn) and [carbohydrate](https://www.protocols.io/view/coral-carbohydrate-assay-for-96-well-plates-bvb9n2r6) protocols

| assay | chemical | amount per sample (units) | total samples^^^ (x # trials, # of assay tech reps) | total reagent needed |
| --- | --- | --- | --- | --- |
| chla | 100% acetone | 1 mL | 174, triplicate | ~600 mL |
| carb ^^ | 5/5 phenol in water (w/w) | 1 mL | 174, single tech rep | ~ 200 mL |
| carb ^^ | H2S04 | 5 mL | 174, single tech rep | ~ 1 L |
| carb ^^ | 10mL glass pipettes | 174, single tech rep | ~ 200 10mL glass pipettes |
| prot | 1M NaOH | 10 uL | 174, triplicate | ~ 6mL |
| prot |  0.1M HCL | 280 uL | 174, triplicate | ~150 mL |
| prot | bca working reagent (WR) | 200 uL | 174, triplicate | ~ 105 mL |
| lipid | | | | |
| symbiont cell size & counts | zfix |  |  |

- ^^ Wall protocol
- ^^^ math on # of reactions per assay type - tech reps accounted for above [assay testing(5 MP pools * 3 colonies) + (5 juvi pools * 3 colonies)] + [phys through time(6 time points * 3 trials * 8 colonies)] = 174
- **NOTE** will want to estimate plates per assay

### TAC assay reagents  

probably not running this assay but the estimates of reagents needed is listed below

| assay | chemical | amount per sample (units) | total samples^^^ (x # trials, # of assay tech reps) | total reagent needed |
| --- | --- | --- | --- | --- |
| TAC | uric acid standards | 10mg, duplicate | 10mg/plate | |
| TAC | 1:100 PBS or methanol for reaction buffer | 180uL | 174, duplicate | ~65 mL |
| TAC | 1:100 copper ion reagent | 50uL | 174, duplicate | ~18 mL |
| TAC | 1:10 stop solution | 50uL | 174, duplicate | ~18 mL |
