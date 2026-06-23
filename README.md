# Uplift-Modelling-to-estimate-CATE

## Overview
This project implements uplift modelling to estimate Conditional Average Treatment Effect (CATE) on the Criteo uplift dataset. The main goal is to identify the top persuadable users who benefit most from treatment, then target the top 20% of users by predicted uplift to maximize conversion lift while keeping marketing spend efficient.

## Objectives 
- Train uplift models that estimate individual treatment effect
- Compare S-Learner and NonParamDML (R-learner)
- Tune each model for uplift performance on validation data
- Evaluate models using:
   - Qini AUC
   - Uplift@K%
   - Average Treatment Effect (ATE)
   - Decile uplift analysis
   - CATE distribution