# MSc Thesis project

## Last week's summary

- [x] Learned the 'copy' feature in R-INLA
- [x] Built a joint model of longitudinal measurements and time-to-event process (standard way in INLA to convert Cox to Poisson)
- [x] Copied random effects in longitudinal part to survival part
- [ ] Copied fixed effects in the longitudinal part while failing to incorporate them into the survival part.


## Weekly summary table

| Timeline | Description | Tasks & Feedback & suggections |
| --- | --- | --- |
| 6 Dec 2022 | First meeting with Dr. Bardia and supervisors | Meeting summary, understand research questions |
| 15 Dec 2022 | Weekly meeting | Read papers, prepare proposal |
| 22 Dec 2022 | Weekly meeting | Read papers, finish proposal, review LMM and survival analysis |
| 12 Jan 2023 | Weekly meeting | Access to LUMC account, try LMM and Cox model with INLA on two case studies, revised proposal based on feedback |
| 19 Jan 2023 | Weekly meeting | Specify prior, check label information in SPSS, apply LMM, Cox model to the real data set, initial data analysis |
| 26 Jan 2023 | Weekly meeting | Find patients whose AR grade dropped, find outliers, Access the HPC environment, and Try to add more random effects to the LMM |
| 2 Feb 2023 | Weekly meeting | Residual analysis (focus on the gradient), Cox regression (Include time-dependent covariates) |
| 7 Feb 2023 | Weekly meeting | Prepare for client meeting: defining the data |
| 10 Feb 2023 | Client meeting | Receive updated data, reconstruct the dataset, exploratory data analysis |
| 17 Feb 2023 | Weekly meeting | Reconstruct the dataset in R, Exploratory data analysis, Exploring joint modeling with INLA (Time-dependent cox regression?) |
| 24 Feb 2023 | Weekly meeting | Currently parametric model for the survival part makes too strong an assumption on baseline hazard; try cox regression in joint model |
| 2 Mar 2023 | Weekly meeting | Try the 'copy' feature in R-INLA to build a joint model, start with a joint of two models with normal outcomes |

## History (Finished tasks before the meeting)

2 Mar 2023
- [x] Fined joint models with INLA (Semi-parametric model for survival part)
- [x] Inference based on time-dependent cox model
- [x] Inference based on linear mixed model

24 Feb 2023
- [x] Built several joint models with INLA (only consider reoperation as the event);
- [x] Built several joint models with INLAjoint (reoperation and death, regarded as competing events)
- [x] Built several joint models with JMbayes2.
- [x] Summarise problems during data reconstruction.

17 Feb 2023
- [x] Reconstruct the dataset in R
- [x] Exploratory data analysis
- [x] Exploring joint modeling with INLA (Time-dependent cox regression?)

7 Feb 2023
- [x] Access the Research LUMC platform.
- [x] LMM: a residual analysis based on the full model (including two-way interactions).
- [x] Time-dependent cox regression (survival package).
- [ ] Time-dependent cox regression (INLA)

2 Feb 2023
- [x] Find patients whose AR grade dropped during follow-up.
- [x] Find outliers of each variable.
- [x] Fix errors when using 'xyplot'.
- [x] Residual analysis for LMM.
- [x] Build summary table on GitHub.
- [ ] Tried joint modeling in the JM package. - Failed due to NAs.
- [ ] Tried to build a LMM with ideal marginal residuals. - Linear trend in residuals at this moment.
