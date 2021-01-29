---
layout: essay
type: essay
title: There is Such Thing as a Stupid Question
date: 2021-01-20
labels:
  - Android
  - Software Engineering
  - Learning
---
## My Dad Used to Say...

  One of my Dad's favorite jokes used to be "There's no such thing as a stupid question, only stupid people," and of course, he was joking, but as it turns out, he might have been onto something.  After reading the article "How To Ask Questions the Smart Way" by Eric Steven Raymond and Rick Moen, I learned that there are clear ways of asking a "smart" question versus appearing stupid and/or lazy by asking a "not smart" question.  There are several different aspects of asking a smart question to attract a good answer, from meaningful subject headers to being informative about the problem you're having.  In this essay, I plan to go over a couple of StackOverflow examples to showcase a "smart" question and a "not smart" question.
  
  I have already been looking for a solution to a problem that I currently am facing and came across several people who have had similar problems.  While I haven't had any luck finding a solution for myself, it was easy for me to pick out a good and bad example to write this essay.  The issue will be about Android app development, so I will reference the term "logcat" a lot because it's what Android Studio uses for debugging.  If you come from a JavaScript background, think of logcat like the console.  It'll help display error messages or things that you want to print to it (amongst other things).

## Let's Start at the Beginning

  The real first thing to do according to the above mentioned article is to choose your forum correctly, but since we're going to stick to StackOverflow for this essay, we won't worry about that part.  So the first thing people will read on StackOverflow about your issue will be your subject header.  Since these headers are limited in characters, to attract a good answer a header should be clear and consice about the issue being experienced. 
  
   This is about the point where we'll want to introduce our good and bad examples of smart questions for reference:
   Here is the link to [A Smart Question](https://stackoverflow.com/questions/60472222/e-loadedapk-unable-to-instantiate-appcomponentfactory-only-on-android-q-api-29).
   Here is the link to [A Not Smart Question](https://stackoverflow.com/questions/58079720/why-does-my-app-crashes-after-without-any-error-in-my-code).
   
   The header for our smart question example reads, "E/LoadedApk: Unable to instantiate appComponentFactory only on Android Q (API 29)," which already gives us information about the issue at hand.  The first part of the header looks like it's part of an error message recieved, and he or she states what looks like the version/type of software they're trying to run it on.  Already this gives a potential answer-giver some insight on the issue, and they're more likely to click on that thread.
   
   The header for our not smart question example reads, "Why does my app crashes after without any error in my code?"  This gives no information about the current issue.  Although it does state that there is no error code to give (which we'll see is incorrect, but he or she may not have known how to read the logcat), he or she still does not provide any information about the language or system they are trying to run his or her app in.
   
## The Journey is Just as Important as the Destination

  People want to help those who help themselves more.  If a person just seems like they want an answer without doing their own research, people are less likely to respond.  A couple of good examples of trying to help yourself are doing your own research and trying to debug your own system.  If those don't work, indicate in your question asked that you already tried some things.  
  
  While both the good and bad example indicate that they have tried to debug their own code, the good example indicates that he or she has tried to do research on the error as well as tried a few fixes before turning to the internet for help.  The bad example basically says they tried clearing the cache and restarting the app.  In my opinion, the good example shows a bit more effort on their half because they've already tried to research and fix the issue, but couldn't find anything that works.
  
## Giving Just the Right Amount of Information

  While it's true that coders and hackers need enough information to be able to help you, no one wants to look through a whole logcat of error messages or a bunch of lines of code.  If you know where your error might be occurring, or at least have an idea of some places, it's better to be clear about it and only post what's necessary.  In the good example, he or she only posts what he or she thinks is relevant.  The first part is the error in the logcat, then he or she shares what they've tried, as well as a few relevant lines of code from different files.  In the bad example, it looks like he or she has copied their entire logcat without looking through it, and the error message can be read right at the top of it.
  
  I learned a lot about asking smart questions from reading the article "How To Ask Questions the Smart Way" by Eric Steven Raymond and Rick Moen, and I think reading this article could still help a lot of people, so I'll leave whoever reads this a link to [How To Ask Questions the Smart Way](http://www.catb.org/esr/faqs/smart-questions.html). But please remember that the authors of this article are *not a help desk and should not be asked questions.* The article insists on this disclaimer message!

