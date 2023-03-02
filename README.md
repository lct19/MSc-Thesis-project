# MSc Thesis project

## Last week's summary

- [x] Fined joint models with INLA (Semi-parametric model for survival part)
- [x] Inference based on time-dependent cox model
- [x] Inference based on linear mixed model


## Weekly summary table

| Timeline | Description | Tasks & Feedback & suggections |
| --- | --- | --- |
| 6 Dec 2022 | First meeting with Dr. Bardia and supervisors | Meeting summary, understand research questions |
| 15 Dec 2022 | Weekly meeting | Read papers, prepare proposal |
| 22 Dec 2022 | Weekly meeting | Read papers, finish proposal, review LMM and survival analysis |
| 12 Jan 2023 | Weekly meeting | Access to LUMC account, try LMM and Cox model with INLA on two case studies, revised proposal based on feedback |
| 19 Jan 2023 | Weekly meeting | Specify prior, check label information in SPSS, apply LMM, Cox model to the real data set, initial data analysis |
| 26 Jan 2023 | Weekly meeting | Find patients whose AR grade dropped, find outliers, Access to the HPC environment, Try to add more random effects to the LMM |
| 2 Feb 2023 | Weekly meeting | Residual analysis (focus on the gradient), Cox regression (Include time dependent covariates) |
| 7 Feb 2023 | Weekly meeting | Prepare for client meeting: defining the data |
| 10 Feb 2023 | Client meeting | Receive updated data, reconstruct the dataset, explortory data analysis |
| 17 Feb 2023 | Weekly meeting | Reconstruct the dataset in R, Explortory data analysis, Exploring joint modeling with INLA (Time dependent cox regression?) |
| 24 Feb 2023 | Weekly meeting | Built several joint models with INLA, Built several joint models with INLAjoint, Built several joint models with JMbayes2 |

## History

24 Feb 2023
- [x] Built several joint models with INLA (only consider reoperation as the event);
- [x] Built several joint models with INLAjoint (reoperation and death, regarded as competing events)
- [x] Built several joint models with JMbayes2.
- [x] Summarise problems during data reconstruction.

17 Feb 2023
- [x] Reconstruct the dataset in R
- [x] Explortory data analysis
- [x] Exploring joint modeling with INLA (Time dependent cox regression?)

7 Feb 2023
- [x] Access the Research LUMC platform.
- [x] LMM: residual analysis based on full model (include two-way interactions).
- [x] Time dependent cox regression (survival package).
- [ ] Time dependent cox regression (INLA)

2 Feb 2023
- [x] Find patients whose AR grade dropped during follow-up.
- [x] Find outliers of each variable.
- [x] Fix errors when using 'xyplot'.
- [x] Residual analysis for LMM.
- [x] Build summary table on GitHub.
- [ ] Tried joint modeling in the JM package. - Failed due to NAs.
- [ ] Tried to build a LMM with ideal marginal residuals. - Linear trend in residuals at this moment.
