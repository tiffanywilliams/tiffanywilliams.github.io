---
layout: essay
type: essay
title: "Coding by the Book"
date: 2020-04-30
labels:
  - Software Engineering
  - Design Patterns
  - Cooking
---

<img class="ui medium right floated rounded image" src="/images/design.jpg">

### Design Patterns: An Instructional

You might have heard a phrase, “cooking by the book.” Well, design patterns are “coding by the book.” Design patterns provide software engineers a general template, or blueprint, that can help them find a solution to common problems in software engineering. To quote Christopher Alexander, an architect and design theorist:

> “Each pattern describes a problem which occurs over and over again in our environment, and then describes the core of the solution to that problem, in such a way that you can use this solution a million times over, without ever doing it the same way twice.”

Though the origins of design patterns lie in architecture, its ideas of defining common problems and providing a groundwork on how to solve them can be extended to any practice under the sun, including but not limited to software engineering. 

We can think of design patterns as a cookbook that’s more of a tips-and-tricks guide for a budding home-cook. This cookbook can provide a guide for solving cooking mishaps. Is the dish too sweet? Don’t worry! You can counteract that with something bitter like unsweetened cocoa. It doesn’t have to be unsweetened cocoa though; anything would work as long as it has some bitterness to downplay the sweetness. Dish too salty? There are several ways to fix that. One of them is by adding some acidity or sweetness to balance the salt, but this is only one method. It doesn’t really matter how you do it. Specifics like what you want to add and how much you want to add can be––and will most likely be––unique. This is essentially how design patterns work––there’s a general solution to a common problem and this general solution can be used over and over again, but it can be implemented differently to accommodate for novel nuances. 


### Experiences With Design Patterns

Until this point, I had no idea what design patterns were. However, because they are so ingrained in the practice of software engineering, they still popped up in my code regardless of my awareness. Now that I’m formally acquainted with a few design patterns, I am now able to recognize instances where I used them in my code. A few that I have used are observers and MVC. In my group project, [CL-UH-B](https://cl-uh-b.github.io/), I utilized observers through the publisher and subscribers, which accesses the database of clubs and publishes for the user to view on the server. Depending on the type of user and what page they are viewing, they could be subscribed to a different publisher, which will show them certain things within the database, such as the clubs that they own or the clubs that align with their interests. I have also used a model-view-controller (MVC) in CL-UH-B. The mongo collections Club, Interest, and Favorites interacts with the pages to present the users with the data where the user can then interact with the data by favoriting, editing, adding, or deleting clubs, 



