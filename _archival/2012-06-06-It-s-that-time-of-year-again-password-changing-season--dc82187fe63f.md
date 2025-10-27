---
title: It’s that time of year again…password changing season.
description: ''
date: '2012-06-06T21:30:00.000Z'

tags: []
---

If you use the popular professional social network LinkedIn you should go there right now and change your password to a new one, [apparently some russian hackers got a few million passwords off their systems](http://www.zdnet.com/blog/btl/646-million-linkedin-passwords-leaked-online/79290). Even if it’s a false alarm it’s a good idea to change your passwords every once in a while.  
  
I would suggest coming up with a new password entirely. Why? because [if you are like a lot of people you reuse a few passwords](http://arstechnica.com/security/2012/06/10-or-so-of-the-worst-passwords-exposed-by-the-linkedin-hack/) in many places, maybe even just one password. So the next thing you’ll want to do is go to every other important website,bank,computer you use with the same password as LinkedIn and change them too.  
  
Having trouble coming up with a new password, here’s some good advice from [XKCD](http://xkcd.com/936/):

![](/assets/0__VHJN0vDDRarW8j4C.png)

If you want to know if your password was taken you can also try [leakedin.org](http://www.leakedin.org/) to check your password, you may want to compute your password hash offline though rather trusting their site. If you have python installed (if you have a mac or linux machine this should be true by default) you can run the following on the command line to get your password encrypted and enter the resulting string into the LeakedIn website. Replace “password” with your password:

python -c 'import hashlib; print hashlib.sha1("password").hexdigest()'

(Thanks to [Nathan Taylor](https://plus.google.com/u/0/101229344744235690473/posts) for that snippet of code)
