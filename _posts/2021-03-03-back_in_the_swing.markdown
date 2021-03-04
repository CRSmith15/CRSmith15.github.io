---
layout: post
title:      "Back In The Swing"
date:       2021-03-04 02:50:51 +0000
permalink:  back_in_the_swing
---


I recently found out that my first project which was a ruby cli gem had been either deleted or overwritten and had no way of finding it. I knew something had to be done and the only thing I could do was remake the whole thing! Not a fun thing to realize, but I needed to do it. The biggest hurdle was that I had not touched my previous ruby CLI in a long time and was kinda fuzzy on the process. Getting back in the swing of things was gonna be tough, but I was ready for it. 

The first thing that was on my mind was how I would get a skeleton of my ideas stubbed out. Referring back to early lessons and watching a couple of study group recordings was all I needed to get the ball rolling. I first set up my CLI file with a call method, which I would then call in my executable file. Just putting some "fake" data in to see what I would get back. I then proceeded create some methods that I would put into my first call method to set off a chain of the methods I wrote that would bring my project to life.

Once I got the CLI basics written and working I then created my API class to draw info from Magic the Gathing cards api. I wanted to print out some cards for the use to choose from and give them more info on their card. Using HTTParty I made a fetch request to the api and got some JSON data back. Once I had that I felt a lot better and then proceeded to itterate through the collection of cards that I got back and assign variables to the data that I wanted. Once they were assigned I then passed them into a new Card class in order to have the cards persist in my "@@all" array in Cards.

Finally I moved on to printing out all the cards for the user and then once the selection functionality was in place, I decided to make the CLI a little more interactive with the user. I would ask them if they wanted to view another card or to exit the program. Getting the loop just right was a little tricky after not doing much with base ruby in a while. I ended up using an "if" and "else" statement so that when the user chose to view another card, it would run almost the entire app again for them. When the chose to exit the app I would then print out a leaving message to assure them that they had exited the app.

Getting back into all this after not touching it for a while was a bit challenging, but I feel as if it helped better my problem solving skills and dilled in a little more some fundamentals of ruby!
