---
title: 100 Days Of Code - Round 1 Days 15 to 21
date: "2019-11-11"
featuredImage: './100DaysOfCode03.jpg'
---

Another week down, another blog post. I didn't skip out on any coding this week, but, I did do some coding at work one day instead of at home.

This upcoming week I'll be doing some maintenance on the [JRS Document Storage desktop application](https://www.jaderickerts.com/projects/jrs-document-storage.html). I won't learn a lot of new stuff. I will continue with the 5 AM tutorials though.

<!-- end -->

### It gets easier over time

When  I first started this 100 Days Of Code Challenge, I struggled to find time during the day to code. Before starting I also struggled to figure what to learn. There are so many technologies out there, it's hard to pick one and run with it.

Now that I've finally started and set a time each day to do my coding, its a  breeze. I'm close to halfway through the ASP.NET Core course I found on  YouTube. I already know what I'll be doing next. The only struggle now is figuring out what time is best to code on the weekends. I like to sleep in a little on the weekends. I used to get up at 7 AM, but lately I  can't get out of bed before 9 AM. By that time, it's a rush to get a  lot of things done. But, this past weekend, I managed to schedule in my coding sessions with ease.

### Bootstrap and User Interface

I  finally added some styling to the web project and its looking good.  It's not great, but its something at least. I didn't learn a lot about  Bootstrap but I've done a course on Udemy before where I got some practice with Bootstrap.

Bootstrap makes it easy to style your webpage. I prefer this because I am not that great with design. I'd rather spend more time on the backend than the frontend. The Bootstrap classes are also built into Visual Studio's IntelliSense which makes things a lot easier.

### Form Submission

I  learned how to submit a form. The ASP tag helpers take some getting used to but once I get the hang of it, future maintenance will be a  breeze. I also learned how to validate the user's input. In the past, I would use a NuGet package like FluentValidation but all you need to do is include the DataAnnotations namespace. Then you can validate your model and add some style to the error messages in the UI.

I  also learned how to upload a file with form submission. This one I  still need to get the hang of. I implemented the file upload but I'm still not 100% sure how it works. This is one of those things I'll need to practice a couple of times before I get the hang of it.

### Database creation with migrations

Finally, I got to the part of the tutorial where I can implement the database. Setting up the service is simple enough. Using the repository pattern makes things even simpler. You can swap out the different database implementations with ease.

I  did come across an error when it was time to commit my first database migration file. Lucky for me, I knew exactly what to because I saw this error in the past. All I did was manually create the database and amend the connection string to include the attach database property. After that things went a lot smoother.

Fixing migration issues is also a breeze because EF Core keeps a migration history table in your database. So if you make a mistake, check that table and revert to that point. It's kind of like Git. EF Core has your back, Jack.

### XML to Combo Box

This one I learned while working on a tool for work. The user had to specify the server's IP address. The database connection string was in the configuration file. The users requested for a dropdown list where they can select their store. Most users don't know the IP address of the server. I  used an XML file to store the necessary information and then the file is, loaded and added to the dropdown list. This was a bit of a challenge to put in place but I got there. Stack Overflow is a great resource,  but you need to know how to use that information in your project. It's not as easy as copying and pasting, which I would never recommend you do anyway.

### In conclusion

It was a pretty good week. I made a lot of progress. I can't wait to complete the tutorial. I have a project waiting for me. I'm doing the planning for the project so long so that I can jump into the coding the when I'm done with the tutorial. Developers, myself included, dislike the planning process, but it must be done.  

For more detail on how I did each day, check out my [100 Days of Code Log](https://github.com/Lakendary/100-days-of-code/blob/master/log.md) on Github. [Follow me](https://twitter.com/lkn_ant) on Twitter for all my 100 Days Of Code tweets.

Until next time. Thanks for reading.

Photo by [samer daboul](https://www.pexels.com/@samerdaboul?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels) from [Pexels](https://www.pexels.com/photo/person-holding-laptop-computer-1240532/?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels)
