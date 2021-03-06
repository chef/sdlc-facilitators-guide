autoscale: true
footer: CHEF/SolutionsIQ CHEF SDLC, 2015
slidenumbers: true


![](pics/wall-art-modern.jpg)
# [fit] SDLC Facilitators Workshop

---

![](pics/Dave_Wylie.jpg)
![](pics/??.jpg)
![](pics/jeff_hackert.JPG)

Oliver Ferrigni
Engineering Manager - CHEF
@awesomesauce / oliver@chef.io

David Wylie
Managing Director - Solutions IQ
@davidwylie4 / dwylie@solutionsiq.com

Jeff Hackert
Director, Learning and development - CHEF
@jchackert / jhackert@chef.io / spacemonkeypants (LoL)

---

![](pics/jackson-pollock.jpg)

## [Values, Principles, Practices](#agile_principles)
<a name="principles_excercise"/>

^ Short speech about relationship between principles and practices. It's hard to start with the why, and it is exactly what is expected of us. Doing _the hard right thing_ presupposes a value system that leads to improved discernment. So be brave little buckaroos, you can do this and so can your teams!

^ Run an exercise: What principles do you see at work in your teams? How do they support what your teams do? How do values and principles support practices? - Handout a list of agile, XP, and Chef values and have folks pick or circle what they see in action vs.

---

![](pics/paint1.jpg)

## What will we learn?

+ Chef Engineering Values, Principles, Practices
+ Agile, XP, DevOps (just enough to be dangerous)
+ Our SDLC (how it works, how to run it, how to test, how to intervene)
+ Team Ceremony facilitation
+ Something about Modernism, Pragmatism, and Organizational Change

^ what are we getting up to today?

---

![](pics/wall-art-modern.jpg)

## (0) Why an SDLC?

---

![](pics/paint2.jpg)

> Technology means ​​the knowledge of making; that is, how we create structures in the world that help us do the things that we want and need to do to thrive as human beings.
-- Yoda

---

![](pics/wall-art-modern.jpg)

## (1) Agile, A brief history

^ How did we get here? Why is process necessary? Modernist vs Post Modernist
Open source moving to product focus.  Use of XP, Kanban as proven good practices instead of trying to invent a new way starting from zero.

---

## XP in brief

What practices have helped us be successful with more satisfaction? Let's do those more!

+ Is it good to test our code?  Let's test all the time.
+ Is it good to work with customers (aka the business)?  Let's work together daily.
+ Is it good to review code? Let's do it all the time via pairing.
+ Simple design is easier to develop, validate, and maintain, so keep it as a core principle.
+ Is feedback good?  Look for opportunities to get feedback more frequently (pairing, unit tests, CI, feature demo, early release).
+ When people work too long in a day or week, their productivity and quality goes down. So set and keep a sustainable pace.

---

## Lean
+ Visualize your work and workflow
+ Minimize work in process (WIP)
+ Pull the work
+ Strive for flow

---

![](pics/paint2.jpg)

> Prediction != Progress
-- Boba Fett

^ or Action != Progress

---

![](pics/wall-art-modern.jpg)

## (2) Team is a Verb

---

![](pics/paint2.jpg)

**Product Engineering Teams** are comprised of an Engineering Manager,
  Product Manager, UX Designer, and Software Engineers. Whole team
  collaborates on Road Map Items comprised of Features.

+ **Product Manager** determine what to build. Is it valuable?
+ **Engineering Manager** manage the engineers. Is it feasible?
+ **UX Designer** design how customers interact with the product. Is
  it usable?
+ **Software Engineer** design, create, test. Is it feasible?

Who provides advice, support, mentoring for your team?

---

![](pics/wall-art-modern.jpg)

## Conway's Law

^ organizational structure is a product of communication patterns, this means that your org structure
is a product of history, not of control - This is a good thing for change agents, but keep in mind that
change agents are never the agent of change :) It's a cruel truth and the sooner you get used to it the more helpful you will become to your colleagues and to your teams.

Conways Law: "organizations which design systems ... are constrained to produce designs which are copies of the communication structures of these organizations"

^ And Conway's Law is a feedback loop.  If there are issues with your org, there will be issues with the design.  If you detect issues with design, there are probably issues with org.
 
---

![](pics/paint2.jpg)

> Culture Debt > Technical Debt
-- Chewbaca

---

![](pics/paint1.jpg)

## B = F(p,e) Lewin's law

---

![](pics/wall-art-modern.jpg)

## (3) How we Work

---

![](pics/paint1.jpg)

## IOTA (How to think about thinking about process and product)

^ IOTA is a model that helps in approaching a very short form A3 doc (Justin and I call the J2)

---

![fit](pics/Devops  - 20.jpg)

---

![](pics/wall-art-modern.jpg)

## (4) Ceremonies & Cadence

---

## Standup

+ Daily
+ <=15 minutes
+ Address Expedited Issues
+ Address anything that is blocking you in completing tasks
+ For Fixed Delivery work, are we on track or need to communicate slip
+ Review stuck (aka Blocked) issues
+ Discuss work that is being done but not on board
	(DW: Do a Standup from Hell exercise?)

---

## Queue Replenishment (aka Refinement)

+ Weekly
+ 30 minutes
+ Ensure just enough work is ready for team
+ Review items In Analysis, Product Manager answers outstanding questions from team. Sort items in this state
+ Review Ready for Analysis. Sort items in this state
+ Refine work [at the top of ] the Backlog, ensuring there is enough work in
Ready for Analysis before the next Replenishment meeting

---

## Demo

+ Weekly
+ 30 minutes
+ Demonstrate features shipped that week.
+ Only show work deployed to an acceptance environment

^ (DW: Ask for acceptance by Product Manager?)
^ (SF: Product Manager should run demo)

---

## Retrospective

+ Monthly
+ 45 minutes
+ Connect as a team to discuss process and outcomes
+ Gather information to identify
	+ What went well?
	+ What were challenges?
	+ What [few] experiments could we try to improve our process, flow, and results?
+ Rank team health

---

## Health Check (across teams)

+ Monthly
+ 45 minutes
+ For Engineering Leadership, Engineering Leads, Product Engineers, and Employee Experience folks
+ Each Feature team ranked their health (Red/Yellow/Green)
+ Ask the Red teams to describe their issues, providing suggestions and scheduling follow-up with Leadership
+ Ask the Yellow teams to describe their issues, providing suggestions and feedback.

---

![](pics/wall-art-modern.jpg)

## (5) Product

^ Work with Product
+ Epics, Prioritization, Roadmap
+ Storymapping
+ Chores and Bugs too

^ *DW ideas: Day in the life of a Product Engineer?
Work is planned, discovered, and sometimes abandoned
Backlog of work should be visible and prioritized
Show Henrik Kniberg "Product Ownership in a Nutshell"?*

---

![](pics/paint1.jpg)

## 2 product Principle

^ we are continuously delivering 2 pieces of value, customer value and kaizen improvements
(DW: Ask "Do the teams know where their work comes from, and path to production?)

---

![](pics/wall-art-modern.jpg)

## (6) Practices and Craft

---

![](pics/paint1.jpg)

## Outside-In (Double Loop) TDD

^ Show flow diagram here

---

![](pics/paint1.jpg)

## Quick mention of Double Loop learning

---

![](pics/paint1.jpg)

## Oliver's TDD Tutorial

---

![](pics/paint1.jpg)

## Refactoring

---

![right autoplay mute](https://youtu.be/wmOofF7FnQA)

> When refactoring, work with either the test or the code, but never both at once.
-- Refactoring cat

---


---

![](pics/wall-art-modern.jpg)

## (7) Ship It!

^ Getting to done, getting to production - need lot's of input here from Seth and Joseph's team

---

![](pics/paint1.jpg)

+ What does “done” look like?
+ Who does code reviews? Who tests?
+ Who accepts the feature from product team?

^ DW: Put this into your Definition of Done and/or Working Agreement


---

![](pics/wall-art-modern.jpg)

## (8) Measurement

^ Little's Law, etc.

---

![](pics/paint1.jpg)

## Kanban in a nutshell

---

![](pics/paint1.jpg)

## Little's Law

---

![](pics/wall-art-modern.jpg)

## (9) Praxis
### How Pollock chose sticks

^ How do we help teams evolve their process and practices? What is the role of the coach?

---

![](pics/paint2.jpg)

> “I have a general notion of what I’m about and what the results will be … With experience, it seems possible to control the flow of paint to a great extent … I deny the accident.”
-- Jackson Pollock

---

![](pics/wall-art-modern.jpg)

## (10) Rules for Software Radicals

^ Change is hard, don't be a dick about it. Creating and sustaining org change (ELSA)

---

![](pics/paint1.jpg)

## ELSA (how to create org change, for reals)

---

![](pics/paint1.jpg)

## Our relationship to change

---

![](pics/paint1.jpg)

## SDLC Epics

---

![](pics/paint1.jpg)

## Stories

---

![](pics/paint1.jpg)

## Chores, Bugs, ...?

---

![](pics/paint2.jpg)

> "It is conceivable to imagine a future in which this problem of generating the living structure in the world is something that you would explicitly recognize as part of your responsibility…I do think you are capable of that and I don’t think anyone else is going to do this job.”
-- Christopher Alexander​​

---

![](pics/paint1.jpg)

## Barriers

+ What exists in our current organization and culture that would prevent you from making changes we have talked about?
+ What actions can you take tomorrow?

---

![](pics/IMG_2075.jpg)

---

<a name="agile_principles"/>
## Agile Principles

+ [Principles behind the Agile Manifesto](http://www.agilemanifesto.org/principles.html)

[back](#principles_excercise)

---
