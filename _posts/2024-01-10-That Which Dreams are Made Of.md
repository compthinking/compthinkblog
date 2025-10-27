---
title: That Which Dreams are Made Of
tags:
  - machine-learning
  - artificial-inteligence
  - ai4truth
  - generative-models
  - large-language-models
show_tags: true
status: published
date: 2024-01-10
toc: true
---
In William Shakespeare's *Tempest*, the old wizard Prospero at one point famously opines...

>Our revels now are ended. These our actors,
 As I foretold you, were all spirits and
 Are melted into air, into thin air;
 And – like the baseless fabric of this vision –
 The cloud-capped towers, the gorgeous palaces,
 The solemn temples, the great globe itself,
 Yea, all which it inherit, shall dissolve,
 And like this insubstantial pageant faded,
 Leave not a rack behind. We are such stuff
 As dreams are made on, and our little life
 Is rounded with a sleep.
  	-- Prospero in *The Tempest* by William Shakespeare  `(4.1.146-158)`

I wonder, do our current Wonders of the Modern Age, Large Language Models (LLM) and Generative AI Systems, see the world like a dream, are we the dreamer, or are they?

There's no real answer to that, but it was prompted much more concrete news raising questions we really should be able to answer if we think with a clear head.

My thoughts on two recent articles about LLMs and OpenAI's ChatGPT in particular.

## "Solving" the "Hallucination" "Problem" 

I have seen some people being quite optimistic about future uses of LLMs along the lines of  this article on the topic: https://www.fastcompany.com/91006321/how-ai-companies-are-trying-to-solve-the-llm-hallucination-problem

Some free advice, if you are betting your business on quickly "solving the hallucination problem" so you can fully integrate LLMs, then you might want to find out what hallucination really is. 

I think that's the wrong message to take from it.

*To wit...*

## Dream Machines
> Earlier this month, Andrej Karpathy, the former head of AI at Tesla and now at OpenAI, tweeted similar remarks. 
> > “I always struggle a bit when I’m asked about the ‘hallucination problem’ in LLMs. Because, in some sense, hallucination is all LLMs do. They are dream machines.”  
> > -- [Andrej Karpathy @karpathy on Twitter Dec 8, 2023](https://x.com/karpathy/status/1733299213503787018)

Andrej is right on point here, of course. Hallucination isn't actually a problem with LLMs, it's *how they work*. We just happen to like it when they hallucinate something we agree with. Mathematically "hallucination" is identical to "regression" or "prediction". 

Apparently, there is a whole industry of companies, like Vectara, trying to find ways to only make true predictions and not false ones.

> Ahmad (from Vectara), for his part, believes hallucinations will largely be solved in roughly 12-18 months, a timeline Altman has also suggested might be feasible. “When I say solved, I mean, it’s going to be that these models will be hallucinating less than less than a person would be,” Ahmad adds. “I don’t mean zero.”

I would suggest, to avoid confusion with normal people with little patience for arguing the meaning of common words, that you *don't call this "solved"* if that's not what you mean. In Computer Science and AI, solved usually means it can be performed optimally in all situations. Even if you soften it to mean "nearly optimally" I don't think most people actually wants advanced computer systems that *only lie or confabulate as much as humans do*. People commonly assume a machine or service should be really good at  something, better than average, otherwise why do we need it?

I'm sure these companies are doing great work. I also agree that building these systems in ways *that produce verifiable, true statements is an important goal*. However,  it's also a **very challenging** research goal that *no one knows the answer to yet*. The answer, probably isn't going to be tuning a bit for a year, or human's coaching it with lots of special cases (which is already the only reason ChatGPT is already coherent and polite). It's probably going to require *entirely new ideas* about language, data, learning, and more. 


## Dreams Built on "Borrowed" Stories?
Other troubles with OpenAI's approach to LLMs right now are the accusations of improper use of intellectual property (ie. stealing). 

[I think their latest argument here is completely circular](https://www.theguardian.com/technology/2024/jan/08/ai-tools-chatgpt-copyrighted-material-openai?utm_source=flipboard&utm_content=compthink%2Fmagazine%2FAI "https://www.theguardian.com/technology/2024/jan/08/ai-tools-chatgpt-copyrighted-material-openai?utm_source=flipboard&utm_content=compthink%2Fmagazine%2FAI"). They used the broadest understanding of "fair use" for data to train it, then when it worked so well they argue that it couldn't have been done any other way. Others have been using this data for research but once you turn it into a product you need to check your legal support of what you've done.

So I would say that one thing a corporation needs to do at that point is consider retraining, or talking to the content creators and negotiating usage, etc. 

> “Limiting training data to public domain books and drawings created more than a century ago might yield an interesting experiment, but would not provide AI systems that meet the needs of today’s citizens.” -- OpenAI Legal Submission

OpenAI's dismissal of some possibly "interesting experiments" is particularly troubling though. Using smaller, controlled datasets could have other benefits such as reducing the need to coach LLMs to avoid harmful outputs. Or if they are trained only on trusted, validated sources, there will be less ways for false statements to be generated

On Mastodon, [Dr. Holly Waters noted a valid irony](https://mastodon.social/@Manigarm/111721703349367950) about this as well:
> ![Mastodon Post from Dr. Holly Walters. Content: Honestly, the real story should be about billionaires conducting a plagiarism panic against non-white, female university presidents all the while they remain completely invested in the Plagiarism Machine.](/assets/images/manigarm-mastodon-2024-01-09.png)

