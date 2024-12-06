# Habitat-as-a-trait
Honors Project

Title: Modelling the Coexistence of Phenotypic Plasticity and Habitat Choice Using
Multivariate Mixed Models, Double-Hierarchical Generalised Linear Mixed Models and
Causal Structure Models.

Background and rationale:
Understanding the basis of habitat choice is important to answer questions that relate to
conservation and evolution of populations. More recent papers have looked at how genetic
factors could lead to different individual preferences regarding habitat choice. It is known
that many animals actively choose a habitat that will maximize their fitness (Morris, 2003).
Phenotypic plasticity is another well studied mechanism that animals can use to increase their
fitness, physiologically, morphologically or behaviourally, based on the habitat that is
available to them (Edelaar & Bolnick 2019). These two mechanisms have generally been
studied independently. Some papers have looked at the interactions between phenotypic
plasticity and matching habitat choice, and which strategy might be best in terms of fitness
(Edelaar et al. 2017). There is still limited knowledge in this area, and we would like to create
and test a framework to describe the differences at the individual level in habitat choice and
phenotypic plasticity. This will help us to better understand if and how these two strategies
coexist given their respective costs. This topic warrants discussion because we will gain a
better understanding of adaptive strategies and how they can coevolve and contribute to
phenotypic differentiation.

Purpose and specific objectives:
The purpose of this project is to test the different models that are proposed. The models will
be compared in their abilities to retrieve parameters and potential bias/error. In comparing the
models, we want to know which model is optimal in the trade-off between accuracy and
simplicity. We would also like to know how much data will be required to run such models
effectively and if they can estimate the covariance between an individual’s traits and habitat
features given different scenarios.
Materials and methods:
The data used to test these models will be simulated using R and generated from a
multivariate normal distribution. The models will use this data to retrieve the parameters, and
then we will be able to determine potential bias and error estimates. We will conduct residual
analysis to check for normality and other assumptions and calculate goodness-of-fit criteria to
compare models. Finally, we will use power analysis to determine the minimum sample size
that would be necessary to detect such effects.

Expected results:
We expect to see a more complex model, like the causal structure model, have more accurate
estimations for the parameters when compared to a simple model like the multivariate mixed
model. The trade off in this case is that the more complex model should require more data to
effectively run but the simpler models may have more bias/error. This project will advance
the field by providing a better understanding of how plasticity and habitat choice function
together as adaptive strategies.

Literature cited:
Edelaar et al. (2017). Should I Change or Should I Go? Phenotypic Plasticity and Matching
Habitat Choice in the Adaptation to Environmental Heterogeneity
https://www.journals.uchicago.edu/doi/abs/10.1086/693345
Edelaar and Bolnick (2019) Appreciating the multiple processes increasing individual or
population fitness. Trends in Ecology and Evolution 34, 435–446.
Morris, D. W. 2003. Toward an ecological synthesis: a case for habitat selection.
Oecologia 136:1—13. https://link.springer.com/article/10.1007/s00442-003-1241-4
