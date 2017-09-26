---
title: "Limiting Bias From Test-Control Interference in Online Marketplace Experiments"
collection: publications
permalink: /publication/2016_wise_gcr
excerpt: 'Many internet firms use A/B tests to make product decisions. When running an A/B test, the typical objective is to measure the average treatment effect (ATE), i.e. the difference between the average outcome in the counterfactual situation where 100% of users are exposed to the treatment and the average outcome in the status quo situation (in which 100% of users are exposed to the control). However, a simple difference-in-means estimator will give a biased estimate of the ATE when outcomes of units in the control depend on the behavior or outcomes of units in the treatment - a case referred to in this work as test-control interference. Both Blake and Coey [2] and Fradkin [6] find evidence of bias due to test-control interference in online marketplace experiments. This paper considers the use of experimental designs and ATE estimators discussed by Eckles et al [5], which reduce bias in the presence of peer effects, in online marketplace experimentation. In order to do so, I model the marketplace as a network in which an edge exists between two sellers if their goods substitute for one another. Using data scraped from Airbnb [16], I create an agent-based simulation to model seller outcomes, both under the status quo and subject to “treatments” that force hosts to lower their price. Having estimated hosts’ baseline outcomes and their outcomes when 100% of hosts are subject to the treatment, I use the same simulation framework to approximate ATE distributions obtained when various network experiment design and analysis techniques are used. I find that graph cluster randomization leads to bias reductions of as much as 62%. Unfortunately, the variance of ATE estimators also increases significantly. Replacing the simple difference-in-means estimator with more sophisticated ATE estimators can lead to mixed results. While some methods (i.e., exposure models) provide (small) additional reductions in bias and small reductions in variance, others (i.e., the Hajek estimator for the ATE) lead to increased bias and variance. Although further work is needed, current results suggest that experiment de- sign and analysis techniques from the network experimentation literature are promising tools for for reducing bias due to test-control interference in marketplace experiments.'
date: 2016-12-06
venue: 'Workshop on Information Systems and Economics (WISE 2016), Dublin, Ireland'
paperurl: 
citation: 'Holtz, David. “Limiting Bias From Test-Control Interference in Online Marketplace Experiments.” Workshop on Information Systems and Economics (WISE 2016), Dublin, Ireland. 2016.'
---
Many internet firms use A/B tests to make product decisions. When running an A/B test, the typical objective is to measure the average treatment effect (ATE), i.e. the difference between the average outcome in the counterfactual situation where 100% of users are exposed to the treatment and the average outcome in the status quo situation (in which 100% of users are exposed to the control). However, a simple difference-in-means estimator will give a biased estimate of the ATE when outcomes of units in the control depend on the behavior or outcomes of units in the treatment - a case referred to in this work as test-control interference. Both Blake and Coey [2] and Fradkin [6] find evidence of bias due to test-control interference in online marketplace experiments. This paper considers the use of experimental designs and ATE estimators discussed by Eckles et al [5], which reduce bias in the presence of peer effects, in online marketplace experimentation. In order to do so, I model the marketplace as a network in which an edge exists between two sellers if their goods substitute for one another. Using data scraped from Airbnb [16], I create an agent-based simulation to model seller outcomes, both under the status quo and subject to “treatments” that force hosts to lower their price. Having estimated hosts’ baseline outcomes and their outcomes when 100% of hosts are subject to the treatment, I use the same simulation framework to approximate ATE distributions obtained when various network experiment design and analysis techniques are used. I find that graph cluster randomization leads to bias reductions of as much as 62%. Unfortunately, the variance of ATE estimators also increases significantly. Replacing the simple difference-in-means estimator with more sophisticated ATE estimators can lead to mixed results. While some methods (i.e., exposure models) provide (small) additional reductions in bias and small reductions in variance, others (i.e., the Hajek estimator for the ATE) lead to increased bias and variance. Although further work is needed, current results suggest that experiment de- sign and analysis techniques from the network experimentation literature are promising tools for for reducing bias due to test-control interference in marketplace experiments.

[Download paper here](https://daveholtz.github.io/files/Holtz_WISE_Manuscript.pdf)