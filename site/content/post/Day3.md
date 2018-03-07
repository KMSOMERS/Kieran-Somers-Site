+++ 
title = "Day 3 - Dagger Dagger Dagger"
draft = false 
comments = false 
slug = "" 
tags = []
categories = []

showpagemeta = true
showcomments = true
+++
Follow the project <a href="https://github.com/KMSOMERS/NeverHaveIEver100DaysChallenge">here!</a>

Its day 3 of the 100DaysOfCode and I had more than enough time to go to the gym and get the hour in. Today at work I spent most of the day reimplementing Dagger 2 to change it from provides to binds - for more information this is a <a href="https://proandroiddev.com/dagger-2-annotations-binds-contributesandroidinjector-a09e6a57758f?gi=a6b3e8259ab3">good post</a> that explains it. Thought I'd focus on implementing it in this style in the current project while its fresh in my mind.

<b>Today's Progress:</b> Finished the category select screen, this screen isn't very complex but hooking up all the components with Dagger takes some time. Reusing res files from previous project means that I got to focus on code quality instead of UI. 

<b>Thoughts:</b> The concept of dependency injection isn't complicated, its really just constructor arguments. Android likes to make things hard though. When I first tried using Dagger it made no sense to me, but as I have gotten a better understanding of how to implement mvp architecture, Dagger has really clicked. It no longer feels like magic (okay maybe it does a little) but a tool that makes connecting the pieces easier. 