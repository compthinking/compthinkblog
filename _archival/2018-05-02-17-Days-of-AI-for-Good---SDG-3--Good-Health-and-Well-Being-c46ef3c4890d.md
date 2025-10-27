---
title: 17 Days of AI for Good — SDG 3— Good Health and Well-Being

description: >-
  Each day up until the AI for Good Summit in Geneva on May 15 I’m writing up a
  thought on how Artificial Intelligence could impact on each…
date: '2018-05-02T12:51:00.972Z'

tags: []
---

**Goal:** Good Health and Well-being : Ensure healthy lives and promote well-being for all at all ages.

**AI XPRIZE Suggestion:** “Preventative healthcare programs and diagnostics are significantly improved through AI leading to new scientific breakthroughs. There are 8 billion mobile devices with smartphone cameras being used to diagnose heart, eye and blood disorders; microphone and motion sensors yielding insights into bone density and osteoporosis — and managing cancer, diabetes and chronic illness remote care.” — [AI XPRIZE](https://ai.xprize.org/AI-For-Good/sustainable-development-goals)

![](/assets/1__bBcYFZu64iqoZxhBqptoZQ.png)

#### Learning to Control Spatially Spreading Processes from Data

Infectious disease spread, urban sprawl, invasive species spread (see SDG 12) and forest wildfire. These are all examples of domains containing _Spatially Spreading Processes_ _(SSP)_ that have inherent dynamics which can be thought of as recursive, or agent based, systems acting on a landscape.  
Many researchers use hand tunes models to simulate these types of systems. Given such models, a variety of AI methods can be used for optimization of best policies to inhibit, encourage or alter growth of the SSP. More ambitiously, learning the dynamics of this spread from data would potentially allow us to find patterns no one has imagined yet. As mentioned in [SDG1](https://medium.com/computationallythinking/17-days-of-ai-for-good-4bed544f42f8) my lab has published work on learning such models [for forest wildfires](https://www.frontiersin.org/articles/10.3389/fict.2018.00006/full) using satellite images. Infectious disease is a more complex problem since the data is spread across many locations, not in a well defined set of images or agencies. Also, human movement is spatial in a physical sense, but not in any simple logical sense. People can board a plane and carry an infectious disease to the other side of a continent in hours. Thus, to learn the dynamics of spread we need combine spatial modelling with network analysis of travel locations. To go even further, human relationships surely need to be used, so social networks can provide rich data to guide learning about disease. Already researchers have used Twitter data from regional searches to predict outbreaks of flu and other diseases.

#### Getting the Numbers Right

Medical research, especially drug trials are in the midst of a reproducibility crisis based on different statistical standards and natural human biases. Some areas of Machine Learning has often been criticized for their own difficulty to be reproduced and the ease with which a solution can be overfit to training data.

But hope is not lost, improved tools and methodologies are constantly being developed to avoid these biases. Scaling these tools out to existing study data on infectious diseases, or using it to design new studies, could lead to great improvements in ability to fight future diseases.

#### Automating Medical Science

Even more ambitiously, some AI researchers look at using ontologies to model knowledge in the most general and complex human endeavour there is, science itself. By describing the various experimental conditions, hypotheses and raw data results in a standardized way could allow data mining on a large scale to find better drugs and medical treatments.

_Mark Crowley has no official affiliation with IBM, XPrize, ITU or the UN. The views and opinions expressed here are entirely his own._
