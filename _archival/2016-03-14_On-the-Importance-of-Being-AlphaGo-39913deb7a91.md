---
title: On the Importance of Being AlphaGo
description: ''
date: '2016-03-14T17:55:00.000Z'

tags: []
---

Victory for #teammachine! Plus a very informative consolation prize for #teamhuman.   
  
This is a response to a couple articles ([Beautiful AI and Go](http://nayrb.org/~blog/2016/03/13/beautiful-ai-and-go/), [Go and Weakness of Decision Trees](http://nayrb.org/~blog/2016/03/14/go-and-weaknesses-of-decision-trees/)) from my friend over at “SE,AG” about the recent match between [DeepMind’s AlphaGo](http://beautiful%20ai%20and%20go%20and%20go%20and%20weakness%20of%20decision%20trees./) and World Champion Go player Lee Sedol.:

> **“Is the Horizon effect something you can just throw more machine learning at? Isn’t this what humans do?”**

That’s what I was going to say in response, but you beat me to it.   
  
Obviously, you could build deeper trees. But the reason these games, even chess, are hard to handle is you can’t build larger trees indefinitely. And would it be really satisfying if AlphaGo built ridiculously deep trees, peering into the future more than any human could, in order to defeat a human’s uncanny ability to built compact trees using heuristics?  
  
That was why the DeepBlue victory felt a little hollow, as far as I remember, it was mostly tree search with lots of tricks. But AlphaGo uses treesearch, a database of amateur games it has watched and Reinforcement Learning. This means it can really learn from each game it plays, even from playing itself (enter player 0). This is the most exciting thing for me about this victory, that it’s a powerful use of RL with deep learning to solve something no one thought would be possible for another decade or two using compute power alone.  
  
Also, on a more pedantic point, AlphaGo doesn’t use [Decision Trees](https://en.wikipedia.org/wiki/Decision_tree), which are good for learning how to classify or predict data. Rather it uses [Monte Carlo Tree Search](https://en.wikipedia.org/wiki/Monte_Carlo_tree_search), which is an area of research in decision making that simulates forward different scenarios based on the current policy to evaluate how good it is. In many algorithms these trees can be throw away and the policy is updated to take the actual action forward. I think this is what goes on people’s head when they play a game like chess or Go. But humans are very good and intuitively picking just the branches with the most promise.   
  
I haven’t looked into it in detail yet but I image that part of the [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning) element that Alpha Go uses is for building this kind of intuition, so that it doesn’t treat all possible choices equally.
