---
layout: post
title:      "TOP MOVIES!"
date:       2018-08-01 18:09:33 +0000
permalink:  top_movies
---



![](https://youtu.be/Sh-OHHosvsc)


 


So, I finally took the plunge.



I finished most of my Ruby section a few months ago, but I wasn't quite ready to start my portfolio project. Why? I knew this would be something that potential employers would see and so I was hesitant to begin. I wanted everything I coded to be absolutely perfect; with that train of thought, I made my first mistake.There's not one right way to code - sure, there are practices that make your code more DRY and much easier to debug/read through, but as I kept going through my Flatiron course I realized I had to just take the leap. With coding, there's not only one right way to do something - something I've grown to love and appreciate about the subject matter. So, I finally did it. And here's how it went.


 For my CLI data gem, I decided that I wanted to scrape the Rotten Tomatoes website for their Top Movies lists. What scraping means is I was essentially taking all the data from the Rotten Tomatoes webpage and then using that data for my gem. In this instance, that meant I was taking all of the data from a top movie page and then making methods in order to get usable information out of all that raw data. I created methods in order to pick out all the movie titles so I could then print them out to the user; all of this was contingent on  having a method that would visit that year's top movie page and scraping the relevant information. Once I printed out the list, I wanted the user to be able to pick a specific movie and learn more, such as its Rotten Tomatoes rating and a short summary. That meant more methods in order to visit a specific movie's page and scrape the data from there as well. 

The big difference between the scraping of the entire list of top movies and the added details of one specific movie is that anytime a user typed in the number of the movie he/she wanted to learn more about, I had a method that was creating a Movie object and then adding attributes to that object according to the data from the scraped page. I first had my code typed so that all of the movies in the list were being made into objects and once a user picked a specific one, it would head to the movie's page and scrape the rest of the attributes and add them to the object accordingly. However, I noticed doing that meant that the gem was running very slowly - it was gathering information for movies that it did not need at that time! So, I decided that I would only create an object when necessary, once the user wanted to learn more detailed information.

Pry ended up being my savior, as usual. Most of the time I spent on the lab was typing a few lines of code, throwing a binding.pry in there, and just seeing what kind of a mess I made. Sometimes the mess ended up taking hours to fix, sometimes it was something as simple as a missing end. That's the name of the game though and it's what I enjoy most about coding, because the feeling of finally seeing something working after what seems like hours of staring at the same code is incredibly satisfying. 
​



