---
layout: page
title: PhD Project
subtitle: Assurance Methods for Adaptive Clinical Trials
---

My PhD project combines two separate notions from clinical trials: assurance and being adaptive.

*Assurance methods* are becoming increasingly popular when planning clinical trials. Assurance methods work by specifying prior distributions for the parameters in the trial (the treatment effect, for example). These prior distributions are then sampled from and clinical trials are simulated using these values. The percentage of these trials that are 'successful' is equivalent to the assurance.

*Adaptive clinical trials* come in many forms. Being adaptive is advantageous for many reasons and there are different decision-rules that one can implement at an interim analysis. At the interim analysis, we can calculate the *conditional power* - the power expected to be seen at the end of the trial. We can use the value of the conditional power to help us make decisions at this interim analysis. Three of the most commonly used adaptions are:

* Stopping for futility
* Stopping for efficacy
* Sample size re-estimation

We can combine these two ideas: assurance and adaptive and calculate the Bayesian Posterior Predictive probability - that is, given the prior and the data accrued so far, we can calculate the probability that the trial will be 'successful'.