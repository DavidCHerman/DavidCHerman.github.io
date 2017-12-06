---
layout: essay
type: essay
title: The Industrial Coding Revolution
date: 2017-12-5
labels:
  - Software Engineering
  - Design Patterns
---

Long ago, when man first put hammer to nail, people built things with their hands. A craftsman in their lifetime would go on to create many, many instances of whatever item they spent their lives perfecting. Some, look fondly back to the days where craftsmen built things by hand, and each piece of fabric was lovingly stiched. I'd be willing to bet though that if the craftsmen had it their way, they'd prefer it if they could just press a button and have a day's work done. This is what we have today, a world where craftsmen design machines that do everything automatically. We have become more efficient, eliminating repetitive tasks with machines. 

This is the route we've taken in programming, very closely mirroring the progress of the civilization's industry. First we learned programming languages, typing out codes by hand, stictching together for loops if-else statements. Then we gained tools, objects, databases, and frameworks to name a few. These tools made programming much faster and more efficient. Now we've reached the industrial revolution. Machines and methods have been designed that solve common problems in almost every industry. This is what design patterns are. Design patterns are a series of solutions to very common problems that can be repeated and reused.

Design patterns are tried and tested methods for solving common problems. They're a framework used by professionals to protect data, access data, create new data in ways that are generally much more efficient and safe. In the Manoa Recipes project that I'm currently working on, several different design patterns are used. It's not something you notice right away. Before you know what design patterns are, you've typically come across and worked with several.

Manoa Recipes runs as a Model-View-Controller design pattern. This essentially is a distribution of displaying information, managing information, and controlling the flow between the two of these things. It is of course more complex than this, but the general idea is something of a common problem that most applications run into. The user needs to access the data, but the data needs to be protected. Also, the data needs to be displayed in a way that makes sense to the user, but the efficient way to store data is rarely the ideal way to display it. Manoa Recipes uses Mongo Databases to handle the data in the form of collections, in this case, recipes, profiles, ingredients, and tags. The user views that data through Blaze's templates. FlowRouter moves the user between these different templates to access different parts of the data.

While MVC is the frame of the application, the heart lies in another design pattern. Manoa Recipes is a recipe database. Clearly the most important thing in a recipe database is the database. The databases are accessed using the Publish-Subscribe design pattern. Manoa Recipes is a database constantly being updated by its users. Users can add recipes, edit their recipes, and favorite the ones they like. The data is constantly changing, and as such, the data needs to be constantly updated. Publish-Subscribe allows that changing data to be constantly updated. It's a design pattern very useful for reactive databases.

We have gotten as far as we have in this world standing on the shoulders of the clever ones that came before us. The most of the problems we face in programming are problems that people have faced many times before. We could spend hours figuring out a method for ourselves, or we could take a well-worn path straight to our goal. We should save our energy and not fight battles already won.
