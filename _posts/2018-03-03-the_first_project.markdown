---
layout: post
title:      "The first project"
date:       2018-03-03 11:54:00 -0500
permalink:  the_first_project
---

Time to work on my first project. We have a goal: scraping, but besides that. We can do what we want..
That's exiting.

Ok. I want to make something interesting. Useful.
I saw a post from another student scraping Rubydoc. That's a great idea, inspiring, but already taken.
What is useful for a CLI app and not rubydoc? Looking up for things of course. But what? Anything!
Ok. I want to scrape a search engine. The goto is google.
A quick check on rubygems.org tells me that 10 versions of that exists already.

It's fine. I'll pick another search engine. I'm French. Let's promote the French tech. I'll scrap qwant.com. Who doesn't want their privacy preserved in while using CLI after all ;).

I'll skip on the frustrating learning curve on the require, require all, absolute path, cd. cd.., losing my code because of error of manipulation (do not forget to commit every 2 lines of code - lesson learned.
I start by building an MVP of my app with dummy results. Easy, done in less than one hour. I start with everything in a CLI object. I create the user interaction flow.
Ok, now is time to extract all the results in a scrapper object. Still with dummy results. The scrapper object is ready. Now, the *plat de resistance*. Let's scrap.
The website seems easy to scrap. all the results of the search engine have the same class. Well ordered. A  .collect should work perfectly.
Let's try to scrap the title of an article first. 
Hmmmm.. interesting, not working. Let's see what I missed... All seems correct to me. Really weird.
It's ok. An office hour for this project is starting, maybe I missed something. I'll just attend and ask. 
Well, the answer is not very encouraging. The website I need to scrap is built in ajax. I need to virtually load the website before collecting the HTML with Nokogiri. I'll try to see how to do that with Selenium-webdriver, watir-webdriver etc. I can't figure out how to do that.
It's ok. I'll schedule a 30 min 1:1 session. No spots available before a couple of days. I won't lose my time. I'll build another scraper in case I can't figure out this one

I'll scrap the Nakamoto Institute literature section. How doesn't want to read about bitcoin after all?
I have to rebuild everything from scratch. Or do I?
No - I heavily leverage what I built so far, adapt it, refine so it matches my new program structure. Everything works fine.
I add the scrapping component. Bummer it's a table. Actually, it makes it super easy to scrape. 
It works. Perfect. Now let's refactor a bit the program. I use arrays to store the elements scrapped from the website. It works but we're here for some object work - I'll create a document object. A little bit of debugging an DONE.
My program works. Good thing.

Now it's time for my 1:1 session. We retry some new gems. The instructor is super nice but the end recommendation is: with the IDE, it will be hard. You will need to set up your on environment and get back to this program with it.

I am NOT abandoning it. But I'm glad I developed my plan B.

It took me way longer that expect to build this, but a lot of lessons learned among which:
* When you're stuck, take a break, come back with fresh eyes
* When you have to put something on the side, you can still salvage big components of it
* Coding is about problem solving and learning - that matches my day job skills. Cool!


And most importantly, coding is SO MUCH FUN!

