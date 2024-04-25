---
layout: essay
type: essay
title: "Unwrapping the Power of Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2024-04-25
published: true
labels:
  - Software Engineering
  - Design Patterns
  - Decorater
  - Structural Design Patterns

---

<img width="100px" class="rounded float-start pe-4" src= "https://www.creativefabrica.com/wp-content/uploads/2020/11/17/Christmas-Present-Gift-Box-Asset-Vector-Graphics-6658356-2-580x387.jpg" >

Design patterns as a whole are patterns that essentially provide a template or a general guideline on how to structure code to solve a particular problem effectively while at the same time making it efficient and reusable, so that other programmers can read it easily and potentially reuse it. Design patterns can be applied to various situations and basically demonstrate the best practices in software development due to their ability to help developers communicate more efficiently about software design and make it easier to understand and maintain difficult systems. Design patterns are like trees, where they branch out from the root into specific branches and leaves. In design patterns, it is sectioned into 3 main categories, Creational, Structural, and Behavioral design patterns. Then in these 3 main categories, it expands further into more specific design patterns.

In particular, I will be focusing on Structural design patterns, and in Structural design patterns I will be focusing on the design pattern Decorator. Decorator is like a Russian nesting doll, in the sense that it is a structural design pattern that lets you attach new behaviors to objects by placing these objects inside wrapper objects that contain the behaviors. The Decorator functions as a Russian nesting doll because it involves nesting objects within wrapper objects, where each layer represents adding new behaviors or functionalities.

Another way of thinking of the Decorator is like wrapping gifts. Wrapping a gift, putting it in a box, and wrapping the box. Here the gift itself represents the core functionality/object that you want to enhance. Then wrapping the gift with the first layer of wrapping represents the basic functionality of the object. Then you put it in the box, which is what we would say you want to add some extra features or behavior to your gift. Instead of modifying the original gift directly, you put it in a box. This box acts as a wrapper around the original gift, allowing you to add new functionality without altering the original object. Finally, you wrap the box with another layer of wrapping paper. This outer layer represents additional features or behavior that you might want to add on top of the existing ones. In my code, I use decorators a lot, this includes reuse of some components from existing code. For example, with our web application, we reuse a lot of code from meteor like for example, putting in default cards or the login and sign-up pages. Another example of a decorator used in our web application and was used in a lot of the WODs and assignments we did was wrapping our components with containers to add style. One example is a basic button component. Instead of directly modifying the button component to apply specific styles, such as changing its background color or adding a border, we created a decorator that wraps the button component and applies these styles. Overall, design patterns are really useful and make a programmer's life easier and more efficient.
