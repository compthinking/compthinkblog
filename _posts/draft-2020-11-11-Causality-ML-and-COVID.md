---
title: Causality, ML and COVID-19

date: '2020-11-11'
description: 'Blog post on a topic of a presentation on in December 2020.'
tags: causality machine-learning
show_tags: true
aside: 
    toc: true
---

## Using Machine Learning for Prediction and Causal Reasoning for COVID-19

The global response to covid in each country, region and city is like a thousand different experiments being carried out at once on the same problem. 

These are not **controlled experiments** in the statistical sense. I don't mean they are *uncontrolled experiemnts*, they are, of course, controlled by each region. 
But a "controlled experiment" in statistics means that you attempt to determine a causal link by *controlling* the input population to be identical, or to be sampled from a from a known, common distribution. 

***Note:*** "Identical" here only means "identical for all *relevant* variables". So, for example, if you know age does not have any impact on the question being studied then you would not need everyone in your data to belong to the same age group.

An experiment being "controlled" also, critically, means that **interventions** are taken, which you could also actions. The whole goal of the experiment is to determine if an intervention has a notable effect which cannot be explained by any other factors.

## Vaccine Testing
We have all recently become experts on the process of vaccine validation and safety trials (ok, some of the attendees here actually are:) ). (Expert comic?)
We all knod deeply as our friends explain the importance of the sanctity of stage 3 trials to be maintained.

Note: I'm not mocking this, it's been a great education in basic epidemiology and drug studies for the past year.

**Essential Causal Questions:** Does the vaccine work? Do masks work? Should we close restaurants and gyms? Or should we close schools? Or both?

Well, this is of course a perfect example of a *controlled **causal** experiment*.
- Guardian Article about Human Trials (https://www.theguardian.com/world/2020/sep/24/uk-covid-19-vaccine-trial-set-to-infect-healthy-volunteers-with-virus)




## Current ML Approaches
AI and ML should be, and are being, used for very practical, on-the-ground tasks. 
- *Spread Prediction:* Improve prediction spread models in one region given model of disease auelprian in-region data. 
- Analyse genetic variation patterns in the disease as it mutates.
- *Logistics:* Predict and manage shortfalls and of hosptital supplies such as PPE, cleaning supplies and basic medicines. 
- *Anti-viral drug discovery:* aiding the search for promising chemicals to test in various stages of druge development to speed up the process.

Since this is a privacy, data and COVID conference, I'll focus on the possibilities for using ML to predict and understand the spread of the disease using data about people, government interventions and policies etc. 

## Antiviral Discovery
- Mila doing projects on learning relationships between drugs, chemicals, proteins on the outcome for good drugs.
- Use machine learning models to propose new candidates, test them in large experimental setups (robotic drug labs). 
- Data from these tests feed back into the ML models
- Eventually try out clinical trials at the best candidates
- In future, use more interactive approaches, like Reinforcement Learning, to design new molecules which could be useful drugs.

## A Note on the SIR Model
The classic approaches for epidemiological study and practice are models such as the *susceptible-infected-removed (SIR)* model for spread of a virus in a community. I'm sure Prof. Tuite and others will talk about this and richer models that are actually used, much better than I can. These are ODE models that capture the essential, *statistical* behaviour of a virus and how it spreads across the population. 

My emphasis on statistical is in contrast to *conditional* or *individual* which would be some approach that looks at the actual known effects of indivduals, when available, and makes inferences.

Now these ODEs are, in a sense, causal. They define how we understand disease to spread from in a population and how distance, risk profilesm viral load and recovery/death rates. 

But they are also *very simple* models, they cannot **learn** what these relationships should be from data? They do not **include**  specific information such as gyms vs. restaurants vs. schools, or masks vs. none.

### SIR Model Details
At it's core, SIR Models are a set of equations modelling how three simple variables change over time during an outbreak.

The number of susceptibale people $S(t)$:
$S(t) = -\Beta S I$
TODO check formulation, not as differential equation

The number of infected people :
$I(t) = \Beta S I - \gamma I$

And the number of people who have recovered $R(t)$.
Where $\Beta$ is the *infection rate* and $\gamma$ is the *recovery rate*.

The *epidemiological threshold* determines the dynamics of the system
$R_0 = \frac{\Beta S}{\gamma}$
which is the number of other infections that one infected person is expected to cause before they recover.


### Types of SIR Models
There are many other models and forms of this, [SEIR](https://www.frontiersin.org/articles/10.3389/fpubh.2020.00230/full) is another.  

The SEIR model adds infromation such as birth and death rate, specific fatality rate caused by the virus directly or indirectly. Probability of transiion for every contact between two people, rates of disease incubation progress and recovery for individuals.


### The Original SIR Model
> The Kermack-McKendrick model is an SIR model for the number of people infected with a contagious illness in a closed population over time. It was proposed to explain the rapid rise and fall in the number of infected patients observed in epidemics such as the plague (London 1665-1666, Bombay 1906) and cholera (London 1865). It assumes that the population size is fixed (i.e., no births, deaths due to disease, or deaths by natural causes), incubation period of the infectious agent is instantaneous, and duration of infectivity is same as length of the disease. It also assumes a completely homogeneous population with no age, spatial, or social structure. - wolfram - https://mathworld.wolfram.com/Kermack-McKendrickModel.html

It makes many simplifying assumptions about the world. And that is necessary for any model. But at what cost?


## What is COVID-19 and Why is it so Hard to Handle?
There are many reasons, but in essence, 





## Let a Thousand Experiments Bloom
The global response to COVID in each country, region and city is like a thousand different experiments being carried out at once on the same problem. 

These experiments are, of course, controlled by each region, 
but they are not *controlled experiments* in the statistical sense. 

A "controlled experiment" in statistics, and generally in science, means that you attempt to determine a _causal link_ by *controlling the input population to be "identical", or more commonly, from a known distribution. 

Note: "Identical" here only means "identical for all relevant variables". So, for example, if you know that hair colour does not have any impact on the question being studied then you would not need everyone in your data to belong to the same hair-colour group.

An experiment being "controlled" also, critically, means that  *interventions* are taken, which you might also call *actions*. The whole goal of the experiment is to determine if the intervention has a notable effect which cannot be explained by anything else.

## Different ways to Learn a Causal Relation
### Significance Tests / Hypothesis Testing
- this is the bread and butter of much of science
- but it's also highly restrictive
- it's results can also be very easily misunderstood, or worse, purposely misused

### The Causal Hierarchy (Judea Pearl, 2018)
Pearl describes three levels of machine learning at the highest level given the relationship to data, labels, knowledge and causality 
1. Association – passive observation
2. Intervention – active experiments, interventions
3. Counterfactuals – retrospective analysis, what-if scenarios

***AND*** you need to be Bayesian about incoming data, how you build knowledge and what probabilities * are *.


## Using the Experiment we Have
So, as far as determining what we can learn from existing COVID-19 spread data, and how we can leverage ML, this is one of the biggest new things we could hope for.

**Challenge**: 
> Can we collect together all the data about interventions, in different countries and regions? Can we combine all the demographic, economic, even socio-political information we have and then learn a useful model that explains the differences? 


## Possible Influencing Factors:
These are difficult to define and measure. But they are real, societal factors that could explain why the same control policies don't have the same effect in different regions.
- demographic factors
- age distribution 
- health care system setup 
- systemic racism 
- size of minority groups
- local temperature, season, weather
- wealth disparity in general
- general education levels (woman, men, age of children, ethnic groups, wealth gap)
- dominance of anti-establishment feelings, resistance to strict central rules
- anti-vaccine culture 
- religious control of state?

## What ML is Actually Good at vs. What we Need
- TODO example for not knowing the causal direction 

