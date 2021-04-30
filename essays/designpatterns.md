---
layout: essay
type: essay
title: Design Pattern Toolkit
date: 2021-04-29
labels:
 - Design Patterns
 - Web Development
---

<img class="ui image" src="/images/designpatterns.png">

## Adding to the tool belt 
You can't go wrong with having extra tools in your tool belt. It allows you to have the resources you need to solve a variety of problems. Design patterns can be an important and useful tool to have in your tool belt in the programming world. So, what is design patterns anyway? Well, to put it into simpler terms, design patterns are solutions to recurring problems. They are "templates" or guidelines on how to solve specific problems. They are NOT, however, solutions to *all* your problems. Design patterns can be great if used correctly and under the right circumstance. However, design patterns should not be forced as it may cause more problems and unnecessary stress.

## Design patterns for dummies
Listed below are simplified definitions of some of the most common design patterns:
-  **Singleton**: Makes sure that only a *single* object of a class is created.
-  **MVC**: A way to manage your program in 3 different parts. *M*odel (the data or input), *V*iew (presentation of the data or output), *C*ontroller (the logic).
-  **Observer**: Dependents (or *observers*) of objects knows when the object state changes.
-  **Factory**: Create an object without exposing any of the logic used to create the object. 
-  **Publish-Subscribe**: Similar to *observer* except in observer the object and its dependents (or *observers*) are aware of each other, whereas with Pub-Sub they are not. Basically, with Pub-Sub, publishers don't send information to specific subscribers. 
-  **Prototype**: Create an object based on an existing object by copying.
-  **Front Controller**: All requests are handled by a single handler then sent to separate appropriate handlers. 

## Using the "tools" (design patterns)
I've recently been working on a [web development project](https://easy-chef.github.io). My team members and I have incorporated a few different design patterns into our project thus far. 
- Prototype: Javascript "classes" are examples of prototypes. 
- Publish-Subscribe: Used [meteor](https://docs.meteor.com/api/pubsub.html) to publish and subscribe to data/collections. 
- MVC: Model: MongoDB (collection classes), View: React, Controller: ReactRouter.
- Front Controller: Meteor/React for startup method.
- Singleton: MongoDB collections, one instance of each collection class that aere used throughout the program.
- Factory: MongoDB collection schemas.
