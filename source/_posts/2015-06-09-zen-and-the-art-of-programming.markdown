---
layout: post
title: "Zen and the Art of Programming"
date: 2015-06-09 17:21:57 -0400
comments: true
categories: 
---

*Practice makes the master.* -Spanish saying

Some time ago, I was applying for a developer job at a startup. Part of the application process involved solving a code challenge that required you to programmatically retrieve and manipulate a set of data through an API. I chose to do the challenge in Node.js, because I like Node (and Javascript-y things in general) and because Node was a key part of the company's product and of the job I was applying for.

I remember firing up Sublime, writing some preliminary code, and retreiving the first set of data. I felt great. I felt like, "I got this". In fact, I had a lot of big feelings about this one code challenge. Up until that point, I was largely self-taught. I thought, how amazing would it be if I got this job, having learned to code mostly on my own. Like, it would be mean I Am Really Smart after all and Totally A Real Developer and all these other big things that would validate me and free me from my insecurities. Then I got deeper into the problem. 

Long story short, I hit a [nested tree-like structure](http://en.wikipedia.org/wiki/Tree_(data_structure)) part of the problem. I tried recursion, but that seemed to be a friggin nightmare. Then a colleague suggested I try a queue instead of recursion. That seemed to be better, but I was still in [callback hell](http://callbackhell.com) thanks to Javascript's lovely [asynchronous nature](https://msdn.microsoft.com/en-us/library/windows/apps/hh700330.aspx).

The details of the problem are largely unimportant. What *is* important is that I spent a weekend on the problem. Actually, more than a weekend on it. From the time I received the challenge, I spent literally every waking second on it, well into the week, well into when I should not have been thinking about it anymore, like when I should have been eating or taking bathroom breaks or sleeping. I was totally out of my element, and that was incredibly hard to accept. For most of that week, I couldn't even understand what my problem was, let alone how to fix it. It took me half the week alone to learn about tree structures -- a way for me to conceptualize my problem -- and even more days for me to learn about callback hell, and about Javascript's asynchronous nature.

The important thing about the problem was not that I solved it, but that I couldn't solve it, no matter how hard I tried, no matter jow much I wanted it. It was torture. Just like I had felt solving the problem would say something great about me, not solving the problem seemed to say something awful about me. 

So much in life is actually pretty easy. You show up, you do the work, you get the brownie points. Actually, most things in life are pretty effortless. And so even when we know we have to put in the time to learn something, or to solve something, we still expect that process to be effortless. Like a savings account, we expect to put some time in and get a reliable return. 

But sometimes things are beyond our control. Sometimes you can't solve that problem, at least, not right now, perhaps in this place, not in this way, or with this tool. I couldn't solve the problem on my own through the sheer force of my intellect. I researched it, wrestled with it, and yet I still didn't "win" -- though what exactly I was trying to win remains a mystery.

Here is the paradox: we can't fully believe in our own mastery if it has been effortless. Problems in programming, as in life, require patience and faith -- the faith that they will be resolved in time, though perhaps not in the way you would like, and the patience to recognize the struggle is, in the end, its own reward. It is here where I like the Zen concept of beginner mind. No matter how experienced we are, if we always think of ourselves as a beginner, we can approach a problem with humility, openness, and a certain amount of self-forgiveness. We can accept our frustration simply as evidence that we care deeply about our craft, and that we want it to be worth the struggle. In the words of one of my former coworkers, "All is practice." If we are always practicing, then we are always learning. If we are always learning, then we have never fully arrived, and that's okay, because that was never really the point anyway. Mastery is not a binary state but a gradual unfolding, revealing itself to you when you least expect it.

In the end, I did end up submitting a beautiful little program with the help of my colleague and [Promises.js](https://www.promisejs.org). It worked, and while I didn't end up working for the company, I gained so much more by pushing myself farther beyond where I possibly thought I could go.
 



