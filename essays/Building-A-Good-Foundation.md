---
layout: essay
type: essay
title: Building a Good Foundation
# All dates must be YYYY-MM-DD format!
date: 2021-04-28
labels:
  - Design Patterns
  - Software Engineering
---

## Design Patterns as Foundations

People always ask me (they don't) what in the world is a design pattern? In my own words, I would define it as the foundation of the solution to an issue. The foundation of a building is necessary for every structure, the foundation of every structure will virtually never be the same. A design pattern will function similarly. It will exist for nearly any problem that occurs enough times in an environment but will never be able to be applied the same for all problems.

## The Foundations of (Some of) My Code
```ruby
/**
 * The singleton instance of the ClubsCollection.
 * @type {ClubsCollection}
 */
export const Clubs = new ClubsCollection();
```

An example of a Software Engineering design pattern is the singleton. The singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The snippet of code above this paragraph is an example of the singleton pattern in a [project](https://uhm-gitclubs.github.io) that I and four of my classmates have worked on as our final project for our ICS 314 'Software Engineering I' course at the University of Hawaii at Manoa. The singleton in this case is the 'Clubs' variable that we export to other directories. In the more general case, the singleton will not be a variable named 'clubs' that gets exported and is accessed globally. However, the main idea of the singleton pattern is still there. A global variable implemented where global variables aren't supported. 

## Trying to Understand Design Patterns

Once again bringing up the comparison to structural foundations, I think I've been taking the existence of design patterns for granted. I've only recently been implementing them but it feels like a disservice to myself and the software engineering community for not having acknowledged design patterns earlier. It also pains me to say that I don't feel like I fully understand design patterns. Their difficulty lies in their abstractness and simplicity, which also happens to be their strengths. Although the different design patterns may never be used in all cases, someday I hope to fully understand at least the most basic of design patterns.