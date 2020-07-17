---
template: post
title: Learnings from a Pharma Client
slug: analytics-implementation-eddl-approach
draft: true
date: 2020-06-12T07:54:27.841Z
description: "A project retrospective is a good place to start reminiscing about
  the learning of a project and how the scope of work defined your months of
  effort. This post and the coming series will talk about my experience working
  on the project. "
category: development
tags:
  - development
  - project
  - event driven data layer
---
A eager to move ahead client. And a tighter deadline. This is the most common scenario that I as a client facing consultant face on daily basis. But to exacerbate the situation imagine six different vendors and three different platforms (web and two native platform apps). All planned to go live at the same time in moment. 

The complexity only surmounts when you know that you are the only primary tech lead to work on this project. And that there are no ready to use templates where you can start the implementation. You are building the engine as you start flying. Many things could go wrong and things could have turned for the worse. But it is during these times you dig into your resilient nature and take out all the tricks from your bag.

I got assigned to this mammoth project in the mid of June 2019. Right from out of the gate the complexity started making its presence felt when an OOTB implementation turned into a custom implementation for the app and the web components. 

Post the first phase release, then the reality came home that the next level of work is much more complicated and the timeline much more shorter. The complications were due to the fact that the project was still being designed and the timeline was shorter due to year end holidays. Yet, the wheel was supposed to be spinning and the work was supposed to progress.

I had to improvise and come up with a solution design that should be or more correctly needed to be scalable, modular, manageable and not stall code development. With this thought, I set out to start designing a data layer approach that is not the standard w3c as all tech consultants know. Thanks to Jim Gordon from Jimalytics, and his foresight in proposing a new way of data layer (he calls it the Event Driven Data Layer) . I knew from the get go that this data layer design will solve all the unforeseen problems and keep me free to work on other tasks while the development work is being undertaken.