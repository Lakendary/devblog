---
title: 100 Days Of Code - Round 1 Days 8 to 14
date: "2019-11-04"
featuredImage: './100DaysOfCode02.jpg'
---

Second week into my 100 Days of Code Challenge and already I've missed out on a day of coding. I'm pretty disappointed because it wasn't for anything major that I did miss a day. All I did was stay up late to watch Chelsea vs Manchester United and I was too tired the following day to wake up at 5 AM. That one football match was enough to put me off my schedule.

But, I won't dwell too much on the negative and focus rather on the other 6 days I managed to code for at least an hour. Here is what I've learned this past week.

<!-- end -->

### Mornings are better than Evenings

The best time for me to get my hour of coding in is at 5 AM in the morning. It sounds gruelling at first but I've already managed to form this habit. I did a 100 days challenge for waking up at 5 AM earlier this year. This is also the time where everyone else is asleep and I can do what I want without interruptions. On most days, the baby is asleep at that time and if he is awake, my wife is feeding him. But, I'll drop everything if the baby is too fussy and my wife needs my help.

On the weekends when I sleep in a little, I stress a little trying to find a time during the day to schedule my coding sessions. Most of my weekends are usually planned for me. There is always a ton to get done that wasn't done during the week. Or there are some festivities to attend to and planning for that is also a mission most days.

When I do find a quiet time later the day to squeeze in some code, I'm tired because the day took a toll on me. I force myself to get through the coding session, staring at the time hoping the hour elapses soon. This is the opposite effect I want from coding. I want to enjoy it rather than dread it.

### Model View is a thing

I've read about the MVVM design pattern. It's mostly used with mobile application development. It stands for Model View View-Model. I've never used this pattern before. I'm much more familiar with MVC, which stands for Model View Controller. I'm guessing that the View-Model replaces the Controller. Anyway, my point is, I can use the Model-View with web applications as well.

I wish I knew about the Model-View class before. It would have saved me a lot of headache in the past when I developed the Document Storage desktop application. Your model doesn't always have all the information required for your view. In the past I would add the information I needed to that model and ended up with a very bloated model that didn't make sense. Re-using that model for another view presented its own challenges as well. The model-view class is a life-saver.

### Library Manager is simple

In the past I used Nuget Package Manager to add client-side class libraries to my projects. This week I learned about Library Manager which is already in Visual Studio. I didn't explore Library Manager at length but the little I got to use I liked. It is a very simple way of adding class libraries. Selecting the version you want to install is a breeze as well. Updating and downgrading the version is as simple as editing a number in the libman JSON file.

### Tag Helpers

This is one of those things I know it will save me a lot of time in the future, but I don't know why yet. I actually do know how it will save me time. If the requirements of your project changes, tag helpers will help in that sense. Its quicker and easier to type out a link rather than use a link tag helper. But when the routing needs to change, you'll need to manually change a lot of links. The link tag helper will do all the changes for you. Put in the work now to save yourself a lot of work in the future.

The image tag helper is also pretty nifty. It helps with the caching of images. I knew that the web browser saved some files on your local disk. Now I know how to do that more efficiently with image tag helpers. The image tag helper will only download newly updated images from the web server. It will load the local image from the cache if it hasn't updated.

### In conclusion

Life happens and we shouldn't forget that. Instead of getting discouraged for skipping a day of coding, I shouldn't be so hard on myself. But I also need to plan for these unexpected events and come up with another way to learn code. I have Clean Code: A Handbook of Agile Software Craftsmanship by Robert C. Martins on my kindle. I will give that a read if I miss out on my 5 AM coding session.

For more detail on how I did each day, check out my [100 Days of Code Log](https://github.com/Lakendary/100-days-of-code/blob/master/log.md) on Github. [Follow me](https://twitter.com/lkn_ant) on Twitter for all my 100 Days Of Code tweets.

Until next time. Thanks for reading.

Photo by [Luca Bravo](https://unsplash.com/@lucabravo?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/computer?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
