# Fit GLMM with R package brms

I regularly give [a course on Bayesian statistics with `R` for non-specialists](https://oliviergimenez.github.io/bayesian-stats-with-R/). 
To illustrate the course, we analyse data with [generalized linear, often mixed, models or GLMMs](https://bbolker.github.io/mixedmodels-misc/glmmFAQ.html).

So far, I've been using `Jags` to fit these models. This requires some programming skills, like e.g. coding a loop, 
to be able to write down the model likelihood. Although students learn a lot from going through that process, it can be daunting. 

This year, I thought I'd show them the [`R` package `brms`](https://paul-buerkner.github.io/brms/) developed by 
[Paul-Christian Bürkner](https://paul-buerkner.github.io/). In brief, `brms` allows fitting GLMMs (but not only) in 
a `lme4`-like syntax within the Bayesian framework and MCMC methods with Stan.

In this repo I go through the course examples and fit the models with `glm()` and `(g)lmer()` functions, `Jags` and `brms`. 
