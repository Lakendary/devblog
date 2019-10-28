---
title: 100 Days Of Code - Round 1 Days 1 to 7
date: "2019-10-27"
featuredImage: './100DaysOfCode01.jpg'
---

I've committed to the 100 Days of Code Challenge. This is my second attempt. The last time around I only managed to get to about 14 days but then life happened. I decided that I would rather start again then continue after having missed so many days. It just didn't feel right.

This is the first post of 15 blog posts about my 100 Days of Code Challenge. I'll post every week what I've learned.

<!-- end -->

I started off with my 100 day challenge by doing a YouTube [ASP.NET Core tutorial](https://www.youtube.com/playlist?list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU) by [Kudvenkat](https://twitter.com/kudvenkat). YouTube is free and I wanted to see what I can learn for free first before investing money on a paid course.

I like that the tutorials are 5 - 15 minutes each, that means you can quickly go through a video. Going through a 1 - 5 hour tutorial isn't really that easy unless you have a media player where you can save bookmarks.

### Setting Up My Environment

I started off by setting up my development environment. This was easy because I come from a Windows background and I run a Windows machine. I'm doing an ASP.NET Core tutorial. The Core part means its opensource and I can actually use Mac or Linux to setup my environment. 

I'm hoping to later on use Ubuntu to develop my next project. However, I saw in the tutorial the instructor uses Visual Studio as an IDE and I'm not 100% if VS is on Linux yet. Its best to stick to the tools the instructor uses otherwise you'll be lost if you run into error.

That is exactly what happened to me. I had the ASP.NET Core 2.1 SDK installed instead of the 2.2. I did eventually download and install version 2.2 and when I build my project, I got a build error. I did the exact same things as in the tutorial, but mine didn't work. 

I decided to ditch 2.2 and went back to 2.1 instead. But now, whenever something didn't work as planned, like In Process hosting, I chalked it off to the versions not being the same which I wasn't sure if that's the case.

Always to try follow up-to-date courses and always try to use the same tools as the instructor to avoid any confusion.

### Learning about the theory

At the start of the tutorial course, the instructor went through a lot of the theoratical stuff. I've done another tutorial before and it didn't go into that much detail but I managed to get a web app up and running in less than 2 hours of following this other tutorial. 

However, thinking about it now, even though the theory is boring, I do understand much more about ASP.NET Core than I did before where the CLI would build my views and controllers and set my layouts etc. I just know that somewhere down the line when I need to debug my project, it would help to know what's going on under the hood to find and clear those pesky bugs.

### Interfaces

I'm embarrased to write that I didn't use interfaces before in my projects. I know what it is and the benefits of having using them, but my projects were fine without them. 

Granted, after I completed a project, I didn't do a lot of maintenance afterwards and there where I did do some maintenance, I probably would've done it faster had I used interfaces. Who knows, maybe I would.

I used an interface to create an employee repository for an employee model. I'm still unsure how this helps, I'm hoping that a light bulb turns on later in the course when I need to make changes or when I finally connect to a database.

### Decoupling

Decoupling is a concept I've learned about in Software Engineering class two to three years back but I've never used it in practice. Now, the instructor mentioned it a couple of times and explained why it is important. 

There are three types of ways to pass data from a model to a view. Using ViewBag and ViewData doesn't follow the principle of decoupling. Its best to use a strongly typed view by specifying the model type in the view using @model directive.

Later down the line it should be easier to make changes to your code if objects or methods are decoupled. Less changes would be required. Swapping out parts would be a breeze. 

### In conclusion

I learned a lot this week and I expect the same in upcoming weeks. I'm not too sure how I will blog about what I've learned. I like giving a short summary instead of giving technical details and code examples of what I've learned. 

Once I become an expert in ASP.NET Core, I'll write technical blog posts. For now, I'm just documenting my journey from 1 to 100 days. 

Until next time. Thanks for reading.

Photo by [Lukas](https://www.pexels.com/@goumbik?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels) from [Pexels](https://www.pexels.com/photo/apple-code-coding-computer-574069/?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels)