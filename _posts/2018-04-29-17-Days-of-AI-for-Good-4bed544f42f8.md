---
title: 17 Days of AI for Good

description: >-
  In a couple weeks I will have the good fortune to be attending the second AI
  for Good Summit in Geneva. The summit is run through…
date: '2018-04-29T03:17:49.576Z'

tags: []
---

![](/assets/1____SXM4ufiw9W3s2boIyS8og.jpeg)

In a couple weeks I will have the good fortune to be attending the second [**AI for Good Summit**](https://www.itu.int/en/ITU-T/AI/2018/Pages/default.aspx) in Geneva. The summit is run through collaboration between the [XPRIZE Foundation](http://If%20you%20consider%20limiting%20the%20objectives%20to%20predicting%20just%20broad%20society-wide%20targets%20such%20as%20poverty%20levels%20you%20can%20just%20about%20imagine%20it’s%20possible%20for%20this%20kind%20of%20agent-based%20model%20learning%20to%20work.), [ACM](http://acm.org) and the [United Nations](https://www.itu.int/en/ITU-T/AI/2018/Pages/default.aspx). I will be attending as a result of being a judge/reviewer for the ongoing [IBM Watson AI XPrize](https://ai.xprize.org/) which incentivizes teams around the world to “develop and demonstrate how humans can collaborate with powerful AI technologies to tackle the world’s grand challenges.”

I got into this through connections in **Computational Sustainability** community which looks at applying Artificial Intelligence, Machine Learning and Optimization to real world sustainability problems which is quite related to the AI XPrize goals. In fact, the real focus of the AI XPrize and this summit is **how to bring about impactful AI solutions able to yield long-term benefits and help achieve the Sustainable Development Goals**.

There are 17 days to go until the summit starts on May 15. So I thought I’d try to give my thoughts on one SDG a day from the perspective of AI/ML/RL until then. Now, I’m not an expert on the UN Sustainable Development Goals (SDGs) at all, I’ve read a bit about them but that’s all. So please forgive me if I oversimplify or miss an important perspective, but more importantly, join the discussion! Part of the goal of this blog is to reach out with my approach to bringing AI and computational thinking in general to any and all important problems in society. So if I’m off base, reply and let’s talk about it.

#### Update During and After Summit

**Thursday May 16, 2018:** So I got a bit behind on these posts (as expected), however the summit is fascinating and I’ll be filling in my thoughts and updating the posts as I attend sessions and think about it in the coming weeks.

So with all that being said…

### Let’s start at the very beginning…

> **SDG #1 :** _End poverty in all its forms everywhere_

**Note:** _For each SDG the IBM Watson AI XPrize has this_ [_handy website_](https://ai.xprize.org/AI-For-Good/sustainable-development-goals) _giving a short idea of how AI could be or already is being brought to bear on the challenge. I’ll list that first before giving my own ideas._

**Even more resources:** This [AI Repository](https://www.itu.int/en/ITU-T/AI/Pages/ai-repository.aspx) provides an even more exciting resource, letting you search for projects and organizations around the world which are focusing on using AI for specific SDGs.

![](/assets/1__SyfUZxZh9o__aAhRUmZ0CzQ.jpeg)

> “AI will provide real-time resource allocation through satellite mapping and data analysis of poverty.” — [AI X-Prize](https://ai.xprize.org/AI-For-Good/sustainable-development-goals)

#### My Take

Well, no one can accuse them of not being ambitious can they? So how do we make this more concrete?

One standard way to approach this goal using AI would be to consider outcomes that can be achieved using AI technologies to improve the economy, improve access to information, food, education etc. The answer of Satellite data analysis is a very important one, and the Summit will have an entire session devoted to discussing that impact.

Looking through the later SDGs, many of these solutions could arise from those more goals. So, for this very ambitious, very high level goal, let’s think about a very ambitious, very high level AI response.

#### Defining Your Target

There’s a big question that every AI/ML researcher will hear, or ask, many times in their life when considering a problem that seems ill defined:

> _What’s the ground truth in your problem?_

This means, do you have any existing examples for your problem **where you know the correct answer**? This is important for checking the solutions you propose, for example. But it’s also useful for machine learning, in that you can often train a system to mimic existing data, and generalize to new situations.

So, do we have examples of societies that have achieved zero poverty, even on a small scale? By society here we could mean not just nations but cities, regions, historical periods. Maybe even within smaller communities or virtual societies. I’m not a historian or sociologist so other people can answer that better than me.

If the answer is yes, then we’d ask can we extract useful **features** from any and all data that we could use to generalize what worked? Even if limited examples exist for small societies as well as the policies and concrete actions that led them to eliminate poverty, then this could be used to try to mine patterns that could be helpful.

Unfortunately, I suspect that there are not very many examples of achieving this goal. That’s doesn’t mean it’s impossible, but it implies something else is needed.

#### Learning from Partial Data

For the goal of reducing poverty everywhere, let’s assume we want to build some kind of machine learning system that helps us find plausible strategies for moving society towards this goal. One idea which I know people in economics and other areas work on is building **agent based simulation models** of economy-scale and societal-scale dynamics. Models of people or groups of people and how they respond to different incentives or policies can help to predict which will lead to lower poverty.

Of course, people are too complex to predict with any sufficient level of detail. This is often done manually which makes it possible to do in a simple way but makes it hard to extract bias from the creators. It’s also hard to know if you’ve got it right or how to begin building the model.

One idea for very ambitious, high level AI contribution to this goal would be building systems that **use historical data about how people respond** at a societal level to different economic incentives to learn the **rules of agent based systems** directly. In this case, any situations where poverty could be seen to increase or decrease could be used as training examples. The resulting system would attempt to recreate those outcomes in simulations. The **objective function** would be a measure of how well the simulation predicted the outcome from historical data it had never seen.

We’ve had some success in using **Reinforcement Learning** to [learn a kind of agent based model of forest fire spread](https://uwaterloo.ca/scholar/mcrowley/publications/combining-mcts-and-a3c-prediction-spatially-spreading-processes-forest) from historical satellite data. People and societies are much more complex than fire, and zero-poverty s a much trickier objective than burned area, but the main idea holds. What would be needed is a base model of the interaction between relevant actors in the society/economy and some general actions that can be taken to influence change in the economy as a whole. Then using historical data you’d try to learn the rules which govern the interaction of these agents. If you consider limiting the objectives to predicting only broad society-wide targets such as poverty levels you can just about imagine it’s possible for this kind of agent-based model learning to work.

Now, I admit, learning such a model seems _almost_ impossible. But in a way that’s what Artificial Intelligence research is all about, exploring computational problems which seem almost impossible … and taming them.

You could say, it’s a moon shot. Which is literally what the XPrize’s are all about. Given the challenges facing the world these days, moon shot level ambition is the only way we might be able to actually bring about the sustainable future we all want.

So that’s my thought on SDG #1 …<_cracks knuckles>_…let’s do this.

1 down. 16 more to go.

_Mark Crowley has no official affiliation with IBM, XPrize, ITU or the UN. The views and opinions expressed here are entirely his own._
