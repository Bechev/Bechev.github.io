---
layout: post
title:      "Rails Javascript project"
date:       2018-08-31 20:27:31 +0000
permalink:  rails_javascript_project
---


The big challenge for this project is to piggy back on a previous one which was not built with having in mind what would come next.
Given the specificities of my previous project, I had to tailor a bit my app to fit all the requirements of this new project.
I developed 3 AJAX queries:
* One is to list an index of all my items that are sold (i.e. there is a filter on one attribute of my items
* One is the list of all items for one brand (i.e.: has_many relationship)
* One is the creation of an item and display of it (i.e.: post ajax request) - for this last one I added an additional difficutly of rendering the item through handlebar (the complexity of the HTML to be rendered was sufficient to justify it.

Overall, the logic is pretty straightforward for this project. What makes it complicated is starting to mix a lot of different languages (Ruby, HTML, ERB, Javascript, HandleBar and I'm sure I'm missing some).

At this point, it is key to have a very good understand of the flow of the application in order not to be confused in what language to be used.

What I developed the most during this project are my debugging skills. Indeed, when integrating some Javascript in your Rails app, it's about leveraging the browser capabilities (identifying if a request fired, if we reach our debugger, put an occasional pry here or there to ensure that the controller logic is good). That is actually a fun part even though a bit endless as there's always the next bug ;).

On to the last project now !
