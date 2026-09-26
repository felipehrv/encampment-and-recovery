# Encampment, Self-Settlement and the Recovery of Displaced Households

**Syrian refugees in Jordan: what the camp protected and what living outside it cost.**

A visual essay built from an original household survey. Between May and July 2016, 391 Syrian refugee households were interviewed in Jordan, 257 in Zaatari camp and 134 in Irbid, Ramtha, Jerash, Zarqa and nearby towns. Every household answered the same questionnaire twice over: about its life in Jordan, and about its life in Syria before displacement. That second module turns a cross-section into a two-period panel of the same families, and it is what lets the essay separate what living outside the camp did from who chose to leave it.

**[Read the visual essay](https://felipehrv.github.io/encampment-and-recovery/index.html)**

## What the page shows

The essay runs in five chapters, each built around an interactive graphic that changes as you scroll.

1. **The households.** A flow map from governorate of origin to place of interview, and a unit chart of the 391 households: camp and town, routes out of the camp, UNHCR registration, who answered the questionnaire, and who reduced food intake after a fall in income.
2. **Before and after.** Household income in Syria and in Jordan under three currency conversions (a fixed pre-crisis rate, the rate of the year each family left, purchasing power parity), and the before-and-after of assets, savings, debt and work.
3. **Who left the camp.** Standardised differences in pre-displacement characteristics between the two groups: liquidity and origin, not earning capacity, separated those who left from those who stayed.
4. **After adjustment.** The effect of living outside the camp on seven domain indices once camp households are reweighted to match the pre-displacement profile of those outside, with a placebo on life in Syria, four estimators side by side, the minimum detectable effect and robustness to hidden bias.
5. **Why.** Rent, the WFP voucher cut of August 2015 that fell on refugees outside the camps, registration as the gate to assistance, and how respondents describe an average day.

Every figure and table on the page is generated from the survey file by three scripts, and the numbers quoted in the text are taken from the same files. Each chart has a "Show the numbers" table and a hover layer.

## The survey

Fieldwork took place from May to July 2016, inside Zaatari camp (twelve districts) and in the towns of northern Jordan. Out-of-camp households were reached through the towns rather than through agency files, so the sample includes families that surveys of registered refugees cannot see. The questionnaire covered income and its sources, spending by category, assets, savings and debt, work, assistance, security, wellbeing and social ties, coping with income shocks, and the same items for Syria before the war. The survey was carried out for a master's thesis (University of San Francisco, 2017); the analysis on this page rebuilds and extends that work.

## Methods in brief

Two-period household panel by recall. Pre-displacement values serve as balancing covariates and as placebo outcomes. The estimand is the effect of living outside the camp for the households that did (ATT), under selection on pre-displacement observables. Entropy balancing on first moments is the main estimator, with augmented inverse probability weighting, nearest-neighbour matching on the propensity score and OLS alongside; robust and stratified-bootstrap standard errors; Rosenbaum bounds, Cinelli and Hazlett robustness values and Benjamini and Hochberg q-values. Syrian pounds are converted at a fixed pre-crisis rate in the main results, at purchasing power parity in the welfare version, and at the rate of the year each family left in an appendix. The page states its limits: overlap between the groups is thin, the minimum detectable effect is about 0.30 standard deviations, and subjective outcomes are answered by different people in the two groups.

## Data protection

Participants are refugees, and in 2016 many Syrians outside the camps lacked valid residence documents. The material is handled accordingly.

- Before each interview, households were told the purpose of the study, which was purely academic, that nothing that could identify them would be asked, that they could decline any question or end the interview at any time, and that there was no reward for taking part and no consequence for declining. The household file holds no names, addresses or contact details.
- The page publishes aggregates only. No household-level record is embedded in it, no statistic is reported for a subgroup of fewer than ten households, and flows on the map are drawn only for origin and destination pairs with at least five households.
- Places are given at the level of governorate of origin, town of interview and camp district. Open-ended answers appear only as coded categories and no respondent is quoted. The people who helped reach households are not named.
- The household file is not in this repository and is kept encrypted, off line. It is not public at this stage; any future release would be de-identified, reviewed for disclosure risk and distributed through a repository with access controls.
- The survey was carried out for a master's thesis in 2016 and was not reviewed by an institutional review board. What is published here is a secondary analysis of de-identified data.

If you believe any content on the page could identify a participant, please open an issue; it will be reviewed and removed.

## Status and reproducibility

This repository holds the essay itself, a single self-contained HTML file with no build step and no external dependencies beyond web fonts, in English (`index.html`) and in Spanish (`es/index.html`); the two versions draw every figure from the same embedded data. The three scripts that produce every figure (derived variables and conversions; indices, balancing and sensitivity; budget, assistance, registration and time use) are not published at this stage. A working paper under the same title is in progress.

## Citation

Rodríguez Villalta, F. H. (2026). *Encampment, Self-Settlement and the Recovery of Displaced Households: Syrian Refugees in Jordan*. Visual essay. [https://USERNAME.github.io/encampment-and-recovery/]

A `CITATION.cff` file is included; GitHub renders it under "Cite this repository".

## License

Text and figures are licensed under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/). The map draws only Syria and Jordan; their outlines are simplified, from Natural Earth (public domain, through the world-atlas distribution), and the boundaries shown do not imply endorsement or acceptance.
