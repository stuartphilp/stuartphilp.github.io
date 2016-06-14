---
layout: post
title:  "Change is not evil"
date:   2016-06-01 12:00
author: Stuart Philp
categories: devops engineering change
summary: "Changing the way we work, the way we build software, the way people view and do their jobs is scary and hard. Persistence, dedication and a clear plan are crucial. You also just need to rip the band-aid off, as hemming and hawing over a decision and trying to get it just right by tweaking and reverting one thing at a time will lead to you ending up in a different place than you originally wanted. It's difficult to balance the need to get something out quick and get something right, but bare in mind getting something wrong can also be right."
---

We have a bit of what's called "learned helplessness" at Mozilla, in that we’ve done things one way for so long that it is easy and natural to think that any other ways of doing this whole software thing would ultimately fail. This is a normal reaction, but it’s important to keep in mind where to do we want to be, and why our current modus operandi can’t get us there.

What is it that we really want? We want to deliver great software that users love, faster. Why faster? So we can gather feedback (directly or indirectly) from users, learn what features they like (and don’t) and use most often, and roll that back into the product to make our software better and put out more things our users love (love^2).

At Mozilla our current train release is every 6 weeks, which means we only have ~9 points in time for learning opportunities per year. If instead we were capable of releasing every working day, we would have roughly 250 points, and even (lets get crazy here) releasing every hour gives us up to 6000 opportunities. By the same token, if individual parts of our product (think microservices, modules, addons, etc.) could be updated independently, then the learning opportunities become exponential. More learning + better decisions = growth.

Put simple, this is about change. We fear change - we shouldn't, but we do. This fear comes from states that people go through when they see or experience or are asked to do something differently. Maybe it looks something like:

Proposed Change -> Reactionary Backlash -> Ongoing Doubt -> Gradual Acceptance -> Natural Evangelism

It's a process that people have to go through internally, not unlike grieving or learning - you could even argue that change IS learning.

In QA we live and breath change every day. There's a constant flux of priorities and new projects (we have over 30 at the moment, and growing), old projects phasing into and out of existence, small asks and large paradigm shifts. We are comfortable with going with the flow because we are accustomed to doing so, we are able to jump from hearing about something to being on board with it very, very quickly. But while we are comfortable with change, it's important to realize that this obviously isn't the case for say a dev team that has been developing the same product for 5 years with very little change going on. When you ask a dev team like this to change, they immediately go to the 'backlash' phase. This is normal, and perhaps even should be encouraged, as part of the process every individual has to go through to accept the change.

One way to look at change is imagine it as continuous improvement and continuous learning. If you're like me, you like to learn, it doesn't matter the topic or the difficulty, as long as it's interesting I can dive in and dig up Wikipedia pages, news articles, or research papers and begin the process of understanding. In a software organization this is applied through metrics and monitoring, with process controls in place to tweak things when something looks a little off allowing the organization to continuous learn and improve itself. The principle of continuous improvement is small % improvements made frequently towards a larger goal.

Constant change, or continuous improvement, means you need an understanding of how a given change effects users for any aspect of your product. Not just A/B testing a feature, but constantly looking at all areas your users are interacting with, how long something takes to load, crashes and bugs that force a user out of your product, everything matters. This measurability isn’t easy to implement, and some users don’t like being tracked in that way, but it is required to give us the confidence we need to make decisions that we know, empirically, are correct. When people talk data driven, they usually mean something along these lines.

Measurable -> Consistent -> Predictable

Once you nail down the measureable piece, you can make these continuous improvements until you become consistent. Consistency in your product quality, releases, and process eliminates variability with each new change that takes place in the future, meaning you can be more relaxed and confident that you aren't messing things up. You can also use this consistency to predict required effort/work to determine estimates and velocity, making you more effective as a team because you know when, where, and how things will happen. Once you're comfortable in this new state of constant change, you can self-asses to determine if you are indeed fast enough. If yes, how can you improve? If no, how can you improve?
