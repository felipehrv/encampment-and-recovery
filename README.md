# Encampment, Self-Settlement and the Recovery of Displaced Households

**Syrian refugees in Jordan: what each of two support packages let a household do with what it had brought from Syria.**

In 2016, five years into the Syrian war, a household that had fled to Jordan lived under one of two support packages. In Zaatari camp it had a caravan, water, schooling, most health care and a food voucher of fixed value; in the towns of the north it rented a dwelling, paid utilities, worked mostly without a permit and received assistance in tiers that depended on an assessment of need. This page reads an original survey of 391 Syrian refugee households, 257 interviewed in Zaatari and 134 in Irbid, Ramtha, Jerash, Zarqa and three other governorates, to ask what each package let a household do. It does not estimate the effect of living in a camp, and it does not say which package is better: where a household ended up was not assigned, and the households that reached the towns had been, before the war, more often urban, more often savers and more often owners of a business.

**[Read the brief](https://felipehrv.github.io/encampment-and-recovery/)** · **[Leer el resumen en español](https://felipehrv.github.io/encampment-and-recovery/index_espanol.html)** · **[Technical note](https://felipehrv.github.io/encampment-and-recovery/encampment_technical_note.html)**

The brief summarizes a working paper under the same title.

## What the page shows

The brief runs in nine chapters. Five of its graphics are scrolling sequences: the text advances in steps beside a graphic that keeps its place and changes state, and every chart carries a "Show the table" control with the figures it draws.

1. **Two support packages.** What a household had inside Zaatari and outside it in the summer of 2016, and the cut in assistance of August 2015 that fell on the households outside the camps.
2. **What the households brought.** Where the households came from and where they were interviewed (a flow map from governorate of origin to place of interview), and how the two groups differed before the war: liquid resources and urban ties, not the level of income.
3. **Comparing like with like.** The twelve outcomes of the main family among households with the same nine pre-war traits, with the tier each difference earns under checks fixed in advance: robust, fragile or null.
4. **What comes in, what has to be paid, and the gap.** Income and its sources, assistance, rent, spending by category and the gap between spending and income.
5. **When income fell.** How often income fell in each group, the causes named, and the eleven responses households used, from eating less to sending a child to work.
6. **Health as a factor.** Households with a member with a medical condition against the rest, under either package.
7. **A refrigerator, a stove, and feeling at home.** The two basic living conditions, security, whom the household would turn to first, and the scales of self-rated integration, optimism and happiness.
8. **Over the years in Jordan.** Households that arrived in 2012 or earlier against those that arrived later, within each group.
9. **What the evidence supports, and what it cannot say.**

A closing section, "About this page", gives the survey, the research design, the verification and the protection of the households, and lists the files of the review.

## What the evidence supports

Households that could leave Zaatari, or never entered it, were more often those with liquid resources and urban ties before the war; where a household lives in Jordan is a selection on what it brought. Among households that looked alike before the war, households under the two support packages live differently in seven respects that clear every check of the tier rule: towns households more often have income from work, spend about twice as much per person, hold a refrigerator and a stove far more often, faced a fall in income less often and used savings less often, and their members rate their own integration about 3 points lower on a scale of 10, in Irbid, Ramtha and Jerash alike. On the gap between spending and income, on security and on happiness the two packages do not differ in ways the sample can detect. Under either package, a household in which a member has a medical condition reports having done more to get by.

The reading the page gives is this. The camp package is a floor, which most households live on; under it, when income fell, the gap was closed with loans and savings. The towns package is tiered assistance plus work, out of which the household pays a rent that takes close to half of its reported income at the median; under it a household more often has the basic living conditions and, when its income falls, closes the gap with the plate rather than with credit. Neither is a choice households made freely.

What the survey cannot say matters as much: it did not ask which documents a household held, when and why it decided where to live, or whom it knew in Jordan; the towns group was reached through networks and does not stand for Amman; the data are one cross-section; and the smallest difference the design can detect is about 20 to 25 points for a yes or no outcome. Nothing on the page is the effect of moving a household from one place to the other.

## The survey

The survey was designed and conducted by the author between June and August 2016 for a master's thesis at the University of San Francisco (2017): 391 households, 257 selected at random within the twelve districts of Zaatari camp and 134 reached by referral within groups set beforehand (a stratified snowball design) in the northern towns, interviewed by day and at home. The questionnaire had 153 questions in 21 blocks: income and its sources, spending by category, assets, savings and debt, work, assistance, security, community and morale, the responses to a fall in income, and the same items for life in Syria before the war.

## Methods in brief

The analysis was rebuilt from the ground up in October 2026, in five steps, each declared in writing before it ran: what each of the 275 variables of the household file measures; whom the sample represents, against 54 published figures; a theory of change in nine parts, with the literature; a research design; and a verdict table that reads every claim of the page against the rebuilt evidence.

The research design estimates the average difference between towns households and camp households with the same nine pre-war traits, within a common support, under five estimators (augmented inverse probability weighting as the main one; inverse probability weights, entropy balancing, bias-adjusted nearest-neighbour matching and OLS as checks), with a bootstrap that resamples households within the strata of the sampling design, a Romano and Wolf correction within each family of outcomes, sensitivity analyses in the manner of Oster and of Cinelli and Hazlett, minimum detectable differences, an eight-trait specification, five rules of inference, a double machine learning check and the reproduction of the thesis table. Every family of results was replicated blind by a separate instance of the AI assistant that prepared the review, from the written declaration alone, and the finished files were read by further instances as a reader receives them. The technical note walks through every step with its tables and figures.

## Files in this repository

| File | What it holds |
|---|---|
| `index.html` | The brief, in English |
| `index_espanol.html` | The brief, in Spanish |
| `encampment_technical_note.html` | The technical note: the analysis step by step, with every table and figure |
| `encampment_variable_audit.xlsx` | Step 1. What each of the 275 variables measures, and its verdict |
| `encampment_sample_and_benchmarks.xlsx` | Step 2. The sample against 54 published figures |
| `encampment_design_diagnostics.xlsx` | Step 4. The research design: estimates, inference, sensitivity, health as a factor, blind replication |
| `encampment_verdict_table.xlsx` | Step 5. The verdict table: 68 claims read against the evidence, with their verdicts and new wording |

The step 3 workbook, `encampment_theory_of_change.xlsx` (the chain in nine parts, with the literature and the full cuts by subgroup), will be added in its next edition, once the scales by subgroup are printed with fewer digits; until then the link to it on the page does not resolve. The pages are self-contained HTML files with no build step and no external dependency beyond web fonts; the two language versions draw every figure from the same embedded data. The household file and the scripts are not published. The working paper is not published in this repository at this stage.

## Protection of the households

Participants are refugees, and in 2016 many Syrians outside the camps lacked valid residence documents. The material is handled accordingly.

- Before each interview, households were told the purpose of the study, academic and nothing else, that nothing that could identify them would be asked, that they could decline any question or end the interview at any time, and that there was no payment for answering and no penalty for declining. The survey had no institutional review. The household file holds no names, addresses or contact details.
- Every figure published is an aggregate; no household-level record is embedded in any file. No count below ten households is printed, and no count below ten can be worked out from what is printed: a cell reads "fewer than 10", "nearly all" or "withheld" when showing it would give another cell away. Blind readings tried the subtractions across tables and files that could recover a masked cell, and what they found was corrected.
- Places are given at the level of governorate of origin, town of interview and camp district. The map draws only Syria and Jordan; its lines follow a rule of five households, stated under the map, and counts are printed for two flows only.
- Health enters through two yes or no items, never crossed with a town, a district or a route out of the camp. Open answers appear only as coded categories; no respondent is quoted. The people who helped reach households are not named.
- The household file and the scripts stay on the author's computer; only aggregates leave it, verified by checksum. The file is not public at this stage; any future release would be de-identified, reviewed for disclosure risk and distributed through a repository with access controls.

If you believe any content on the page could identify a participant, please open an issue; it will be reviewed and removed.

## Citation

Rodríguez Villalta, F. H. (2026). *Encampment, Self-Settlement and the Recovery of Displaced Households: Syrian Refugees in Jordan*. Brief and technical note of a working paper. https://felipehrv.github.io/encampment-and-recovery/

## License

Text and figures are licensed under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/). The map draws only Syria and Jordan; their outlines are simplified, from Natural Earth (public domain, through the world-atlas distribution), and the boundaries shown do not imply endorsement or acceptance.
