---
layout: post
title:      "Sinatra Project"
date:       2021-01-11 22:28:05 +0000
permalink:  sinatra_project
---


For my Sinatra project, I created a digital bullet journal in which you can create an account and log a journal entry a day complete with a goal of the day as well as a gratitude of the day. Users can create accounts, log in and out, and create, delete, and edit their own journal entries. 

At first glance, the Sinatra Project seems so simple, as though it will take you an hour to finish when you're doing it for the first time. This definitely was not the case. This project required me to be very meticulous. I found myself triple checking that all my routes matched among other things.

While I did not struggle with this project, I made a few mistakes that took a while to troubleshoot. My first roadblock was troubleshooting shotgun. I typed shotgun twice in the terminal. The second time I typed it, it stopped working and I couldn't kill the port with CTRL + C. I definitely panicked because it was during the start of the vacation and coudln't ask anyone for help. So, I was afraid that I wouldn't be able to kill the port. After googling for about an hour, I found the solution thankfully. 

I made several other mistakes over the course of the project:
* In one of the migrations, I had a date datatype set as text instead of date. 
* Created data entries with no data using binding.pry, which persisted and messed with some of the fomatting in the view files, which I did not expect to happen. 
* After creating another account, I could still see other journal entries from another account, which I had to remedy. 

Overall, it was a fun project that required a detailed eye. I would love to return to the project eventually to add css styling to make it look nice :). 
