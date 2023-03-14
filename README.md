# scaping_project

## Introduction Rant/Summary
For a second I was worried I wouldn't finish this project in time. The hardest part for me was definitely figuring out the actions to get the results I wanted. My goal with this project was to get a database that could easily show you a variety of crystals and what they are for in regards to their intended chakras, zodiac signs, and outcomes. Not going to lie, I'm a fan of crystals and the hardest thing is trying to understand what stones I need for what and what actually are my options out there. With this database, I could possibly in the future create a searchable site where people could filter the results and find the best crystal for them. 

## Challenges
As for specific challenges, there were definitely a few. First one was pulling the things more the listed information, I kept trying different ways to go through nested lists, I tried to make a variable for each different level, connecting them all to each other with find functions. Turns out I didn't need to do any of that. I tried just pulling the span elements out of the li's by themselves and it worked. I felt pretty silly. 

The most challenging thing was definitely looping the button variables. I had never used an XPATH function-thing before and I quickly found out it is VERY particular on how you write in it and there are many ways they DON'T want you to write your values. It took forever to find out where I was allowed to put my alphabet variables but it wasn't impossible. Thanks, stack overflow.

Jupyter notebook also seems to be a little inconsistent, sometimes it would give me errors that hadn't pop up the last time I attempted to run it.

## Process
I started this project by first scraping the first page, I pulled the name, chakra, zodiacs, and uses out individually and put them all in seperate lists. Next, I scraped the next page and a few random other pages, just to make sure they were consistent. Then I spent THREE HOURS trying to create a for loop that would go through all the pages. Then I created another loop that made new lists out of the lists I had already made so that each name would be next to the correct qualities. Then I wrote each of those lists into a csv. In the grand scheme of things, the actions themselves didn't take too long but finding out how to was tricky.
