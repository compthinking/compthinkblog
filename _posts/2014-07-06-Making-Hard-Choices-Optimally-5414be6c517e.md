---
title: Making Hard Choices Optimally
description: ''
date: '2014-07-06T21:25:00.000Z'

tags: []
---

This [TED talk](https://youtube.googleapis.com/v/8GQZuzIdeQQ&source=uds) by [Ruth Chang](http://ruthchang.net/), a Philosopher at Rutgers University, is really thought provoking and useful. I disagree with some of her logic about non-numerical values being the reason we can’t make the choice, but I agree with her conclusion nonetheless. Hard choices are not just about choosing what will happen next, but about choosing which past we are willing to live with and be happy with.

[https://youtube.googleapis.com/v/8GQZuzIdeQQ&source=uds](https://youtube.googleapis.com/v/8GQZuzIdeQQ&source=uds)

#### Life is an Optimization Problem

![](/assets/0__mAoi5EehMA710bA5.png)

Myresearch focuses on understanding the mechanism for making optimal decisions, particularly in situations where there is uncertainty about the world and what will happen next. I look at this not from the context of what humans and animals actually do in their heads, but what a robot or other computer _should_ do for any given decision problem. It’s an area of Artificial Intelligence known as _Decision Making Under Uncertainty_.  
  
Chang is talking about the hard choices we all face in our lives at some point, choices where is seems impossible to come up with the “right” answer. The hardest choice Chang puts forward in her talk is between two very different jobs. One job is artistic, in the city, with various exciting benefits and pay. The other job is in law, in the country, with more pay and other benefits. These two choices have qualities and possible outcomes which are comparable; you may prefer the country to the city but prefer the city job artistic job more than the law job. So we can draw up our PROS vs CONS list and compare individual qualities of the jobs but the whole choice taken together still seems impossible to decide. Chang says this is because the two options are value choices and _are not numerically comparable_. One choice _could_ be clearly better or worse than the other, but they could also simply be “on par”. This means they are in the neighbourhood of being equal, but small movements in favour of one or the other won’t change things.

This is where I started shaking my head. I tend to agree with her conclusion, but the reason we cannot make a hard choice is not because the values are incomparable, it is because we lack information, and always will. Consider the hard choice between two jobs. In my field we would say that the value function for these two choices has many dimensions. One dimension is location, another is pay. Other dimensions quantify job satisfaction, health benefits, proximity to friends, the theatre or fresh country air. On each dimension it might be clear that one job is better than the other or they could be equal. Thus _they are numerically comparable_ on each dimension.  
  
The problem comes when you want to compare the entire choice at once. Assuming that there is a single number for each choice that is either less than, equal to or greater than the other, as Chang does, implies that you know how to combine all the numbers in each dimension into a single number. The fact is, we rarely know how to combine these numbers in real world problems.

The simplest solution would be to say that one dimension, salary for example, dominates all others and should be used alone. But this isn’t the reality we are faced with, if it were that easy we’d have made the choice already. The next simplest solution is to do a weighted sum of the dimensions. Assign a number _wi_ to each dimension _i_ indicating how important it is relative to the others. Think of it like a pie that needs to be given out to a group of people. You can decide the size of each slice but you only have one pie to apportion out. Each _wi_ is a slice that indicates the relative importance of salary, location, job satisfaction, proximity to friends. Once you have that you simply multiply each _wi_ weight by the value of that dimension and add them up. The weighted sum that is greater is the best option. That’s how classical economics and decision theory assume people make decisions.  
  
There is growing evidence in **behavioural economics** that in fact humans use a much richer formulation for weighting the dimensions of their values which depends on the _probability of events_ and the gain or loss each outcome would yield them _relative to what they currently have_. Unfortunately, this still doesn’t help us to make the choice. We’ve just shifted the problem, determining the slices of pie to give to each dimension is just as hard as the original choice itself. However, we _are_ still in the realm of an optimization problem that can be defined with numbers. Chang’s introduction of “on par” values which cannot be numerically compared is not necessary.

#### How to make the best decision

Given that we are still functioning in an optimization problem, the question is _what are we optimizing_? What these conundrums are avoiding is that when we make choices we are not really trying to optimize the outcomes of that choice. (_Huh?)_

When human beings make choices they are almost always really optimizing a single, much more mysterious and overarching value. We could call it contentment or we could it satisfaction, maybe we can just call it _happiness_.

We could be trying to optimize our short term happiness or long term happiness. The options available might directly influence our happiness, such as eating the doughnut; or they might indirectly influence it, such as taking a particular job or making someone else happy. It might be that the events that result from our choice only later lead to our happiness.

Ay, there’s the rub. Computing the expected happiness resulting from a choice requires _predicting the future_ and any number of other events or even other choices we will make in the future. Ruth Chang says the right strategy, when faced with these hard choices, is to _choose the one you can get behind_.

Psychologists and economists have been talking a lot in recent years about the importance of _rationalization_ in human thinking. Chang’s decision making strategy posits rationalization as a useful tool for navigating towards a happy life. When faced with an intractably hard choice, choose the one that you will be able to successfully rationalize yourself into enjoying the most. Given that, after the fact, you will rationalize your decisions to yourself anyways, it follows that eventually making the choices that will yield the best post-rationalization state will be the life where you are most likely to maximize your happiness. This kind of **counterfactual justification** may be the key to happiness by accepting your intense drive to rationalize your decisions and making it work for you.

I think strategy thisworks even though I don’t agree with Chang that value based choices are non-numerical. We _can_ compare them numerically, but because of the multi-dimensional nature of the choice and the uncertainty about the future we simply do not know, and cannot know, how best to combine all the information we have and compare them. Even if the future were fully determined we still wouldn’t know how best to weigh all the components of each choice. Is it better to live in a city or in the country? Is that part of the comparison more important than the satisfaction I’ll get from the job or from the proximity to loved ones? How _much_ more important…exactly? We simply can’t answer those questions, not because they aren’t comparable, but because we don’t know what our values are and every question implicitly requires knowing how the future will unfold.

So the conclusion is still that hard choices are hard because there is information we do not have and can never have about our own values and about the future. But there is hope, since _we’re not actually trying to make the best choice_ for it’s own sake. We are trying to maximize our own value function, our happiness, and doing that “only” requires making the choices we are most willing to live with, regardless of their outcome.

_— — This post has been revised and reposted from a few years ago. — —_
