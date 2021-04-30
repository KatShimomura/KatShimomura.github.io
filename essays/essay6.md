---
layout: essay
type: essay
title: A Profession Spanning Concept: Design Patterns
date: 2021-04-29
labels:
  - Javascript
  - Semantic UI
  - Learning
  - Meteor
---

## Great Ideas

Every so often, there's a great idea that's such a good concept that it can be applied to multiple different issues.  Design patterns is one of those great ideas.  It all started with a man who was in architecture/construction writing a book called "A Pattern Language," and in that book he defined what design patterns were.  The definition of design patters is as follows:

"A Design Pattern describes a problem that occurs over and over again in our environment, and then describes the core of the solution to that problem, in such a way that you could use this solution a million times over, without ever doing it the same way twice" -- Christopher Alexander, 1977

Hardly ever do I see concepts that can be carried from one profession to another, but in 1994 four software developers somehow connected the dots between object oriented coding and this concept, and it became a huge phenomenon known as "Design Patterns" (which is also the name of the book they wrote on it).  The concept of design patterns is basically that they are solutions to problems that people often encounter, but these solutions can be tweaked in ways to suit each individual case.  If you were to think of it in the most basic scenarios, it seems like common knowledge, but once it's applied to a profession like architecture or software development, it becomes such a broad and interesting idea.  For example, in the most basic scenario, say I needed something to put my comptuer on.  Well, maybe a desk, or a table would work?  The solution is obvious, but the little details of the solution aren't always the same.  For example, what kind of desk or table works best for me, in my current living situation?  In these terms, this concept seems so basic, but it's when the concept is applied to more difficult issues that it really starts to shine.

## Design Concept Examples in Software Development

There are so many existing design concepts in software development, and what they do is not always easy to identify from their titles alone, so in this section I'll be writing about a few of them while also providing examples of how I've used them in my own code.

### Model View Controller (MVC)

The problem presented with the Model View Controller (MVC) design pattern is that when there's any kind of user interface (UI), usually you want to be able to control how the user is viewing and interacting with the software.  This is normally because not all users have a software development background, and even if they did it's much more enjoyable when a UI is easy to understand and manage.  For example, I would like my phone a lot less if I could see the functionings of what's really happening behind all the UI pleasantries.

There are many ways to implement the MVC Design pattern, but the way that I've used in my coding was through Meteor.  In web application, I used Meteor to implement MongoDB as my model, React as my view (UI), and Meteor as my controller.  To explain the MVC roles more clearly, model manages the application's data and data structure, view is how it's represented on the UI, and controller takes any input (whether it's from the UI or if the data has a dynamic data structure) and translates it to the other side (either model or view).

### Observer

The problem presented with the Observer design pattern is that there are times when you need your system to react to a change in state.  For example, if someone enters something into a search bar, you might want suggestions to populate under the search bar as their typing.  Each character typed is a change in state, and your system can react to that if there is an observer implemented. In these types of "event driven scenarios," observers are often called "event handlers".

The way I'm (currently working on) implementing the observer design pattern is actually through the example I just gave!  For a course I'm taking this semester, I'm building a web application in a group as my final project, and I have been researching how to implement a search function into it.

### Singleton

The problem presented with the Singleton design pattern is that there may be a need for a "global variable," but no means to provide that global variable in the object oriented language that is being used.  This can be acheived through Javascript and Mongo DB with the Javascript classes and Mongo DB collections.

The way that I have implemented the Singleton design pattern is by making a collection in Mongo DB called "Contacts".  So, there's a "contactsCollection" class in Javascript which manages the access to the underlying "contactsCollection" in Mongo DB.  Our class "contactsCollection" will export a variable "Contacts", which will be used each time a contact is created.  This creates a global variable, "Contacts," from a single instance, "contactsCollection."

### Factory

The problem presented for the Factory design pattern was the need to create objects without them being exactly the same.  For example, you might want to create objects that are associated with different classes or are dependant objects.  
