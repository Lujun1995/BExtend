
# SimulationSetting
This file contains the simulation setting and reference of the poster.

X pretreatment covariates: X1 ~ N(1, 1); X2 ~ Pois(2); X3 ~ Unif(-1, 1)

A treatment assignment: A~Bernouli(0.5)

Y outcome: Y = X1 + X2 + X3 + A + AX1 - AX2 + epsilon

epsilon ~ N(0, 2)

The selection mechanism 

p = F(-5.087 + X1 + X2 + X3) where F(.) is the cumulative distribution function of the logistic distribution.

S ~ Bernouli(p)

The total sample n was set at 500, 1000, 2000, and 5000 to generate 1000 simulated datasets respectively.

# Reference
[1] Rothwell, Peter M. "External validity of randomised controlled trials:“to whom do the results of this trial apply?”." The Lancet 365.9453 (2005): 82-93.

[2] Nguyen, Ryan H., et al. "Race and Ethnicity Reporting and Enrollment Disparities in Clinical Trials Leading to FDA Approvals for Breast Cancer Between 2010 and 2020." Clinical Breast Cancer (2023).

[3] Dahabreh, Issa J., et al. "Generalizing causal inferences from individuals in randomized trials to all trial‐eligible individuals." Biometrics 75.2 (2019): 685-694.

[4] Stuart, Elizabeth A., et al. "The use of propensity scores to assess the generalizability of results from randomized trials." Journal of the Royal Statistical Society Series A: Statistics in Society 174.2 (2011): 369-386.

[5] Li, Fan, Hwanhee Hong, and Elizabeth A. Stuart. "A note on semiparametric efficient generalization of causal effects from randomized trials to target populations." Communications in Statistics-Theory and Methods 52.16 (2023): 5767-5798.

[6] Lee, Dasom, et al. "Improving trial generalizability using observational studies." Biometrics 79.2 (2023): 1213-1225.

[7] Rudolph, Kara E., and Mark J. Laan. "Robust estimation of encouragement design intervention effects transported across sites." Journal of the Royal Statistical Society Series B: Statistical Methodology 79.5 (2017): 1509-1525.

[8] Li, Fan, Ashley L. Buchanan, and Stephen R. Cole. "Generalizing trial evidence to target populations in non-nested designs: Applications to aids clinical trials." Journal of the Royal Statistical Society Series C: Applied Statistics 71.3 (2022): 669-697.

[9] Bissiri, Pier Giovanni, Chris C. Holmes, and Stephen G. Walker. "A general framework for updating belief distributions." Journal of the Royal Statistical Society Series B: Statistical Methodology 78.5 (2016): 1103-1130.
