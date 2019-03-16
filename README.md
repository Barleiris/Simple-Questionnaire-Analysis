# Simple-Questionnaire-Analysis

In survey data, variables often ordinal with missing values. And the normaility assumption doesn't always hold. Every vairable is related to the goal you want to achieve but no one is specific enough to be the only responce variable Y. Therefore you will have to explore the relationship betweem a metrix of X with a metrix of Y, sometimes another confounding matrix Z should also be taken into consideration.

Here, a questionnaire containing 40+ questions is given to hundreds of people, who are interviewed about their feelings and hobbies with a goal to find the causal relationship between depression and cognitive impairment. Some questions are related to depression, some to cognitive impairment, while others are confounding.  

This repository provides a workflow of analyzing the correlation among multiple frames of survey data using R. The main analysis method used are Iverse Propensity Score Weighting, a classical causal inference approach, and Conditioning Probability, which is a adapted version of Copula I invented.
