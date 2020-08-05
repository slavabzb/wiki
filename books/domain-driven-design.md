---
description: Eric Evans
---

# Domain-Driven Design

## I: Putting the Domain Model to Work

Every software program relates to some activity or interest of its user. That subject area to which the user applies the program is the _**domain**_ of the software.

To create software that is valuably involved in users' activities, a development team must bring to bear a body of knowledge related to those activities. Models are tools for grappling with the volume and complexity of information. _**Model**_ is a rigorously organised and selective abstraction of that knowledge.

The utility of a model in DDD.

* The model and the heart of the design shape each other.
* The model is the backbone of a language used by all team members.
* The model is distilled knowledge.

### One. Crunching Knowledge

Ingredients of effective modelling.

* Binding the model and the implementation.
* Cultivating a language based on the model.
* Developing a knowledge-rich model.
* Distilling the model.
* Brainstorming and experimenting.

### Two. Communication and the Use of Language

A project faces serious problems when its language is fractured. Domain experts use their jargon while technical team have their own language tuned for discussing the domain in terms of design.

The terminology of day-to-day discussions is disconnected from the terminology embedded in the code \(ultimately the most important product of a software project\). And even the same person uses different language in speech and in writing, so that the most incisive expressions of the domain often emerge in a transient form that is never captured in the code or even in writing.

Translation blunts communication and makes knowledge crunching anemic.

Yet none of these dialects can be a common language because none serves all needs.

Use the model as the backbone of a language. Commit the team to exercising that language relentlessly in all communication within the team and in the code. Use the same language in diagrams, writing, and especially speech.

Iron out difficulties by experimenting with alternative expressions, which reflect alternative models. Then refactor the code, renaming classes, methods, and modules to conform to the new model. Resolve confusion over terms in conversation, in just the way we come to agree on the meaning of ordinary words.

Recognize that a change in the UBIQUITOUS LANGUAGE is a change to the model.

Domain experts should object to terms or structures that are awkward or inadequate to convey domain understanding; developers should watch for ambiguity or inconsistency that will trip up design.

Play with the model as you talk about the system. Describe scenarios out loud using the elements and interactions of the model, combining concepts in ways allowed by the model. Find easier ways to say what you need to say, and then take those new ideas back down to the diagrams and code.

