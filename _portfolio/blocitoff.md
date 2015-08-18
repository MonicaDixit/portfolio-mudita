---
layout: post
title: Blocitoff
thumbnail-path: "img/blocitoff1.png"
short-description: Build a self-destructing to-do list application using angularJS and firebase api.

---

{:.center}
![]({{ site.baseurl }}/img/blocitoff1.png)

## Synopsys

To-do lists are notorious for collecting junk - tasks that you want to remember but constantly reprioritize. To solve the problem of to-do list clutter, you will build Blocitoff. Blocitoff is a web application that will manage your to-do lists by automatically deleting tasks that have not been completed after seven days.

Rule of the thumb: if the task is not important enough to be completed within seven days, it does not belong on your to-do list.


## Know more
Users can easily create tasks on the user friendly UI. The tasks are synced in a persistent firebase array.Users need to authenticate before they can start using the app.
A gmail style authentication box(built using the bootstrap framework) provides each user an affordance to store their tasks to the backend. An authenticated user can see only their own tasks. This is achieved by using angular filters on the frontend.

Also worth noting are the separate view for expired, completed and active tasks in this single page app.

{:.center}
![]({{ site.baseurl }}/img/BlocifOffActive.png)


A task that is past 7 days from the date of its creating is marked as expired and a CSS strikethrough gives it a distinct look on the expired tasks view.

A task can be marked complete by a simple checkbox and the task is moved from the list of active tasks to the list of completed tasks.

{:.center}
![]({{ site.baseurl }}/img/BlocitOffComplete.png)


The landing page has the brand logo and a simple navigation bar that has links to login , register and logout.The high risers in the background image are indictive of the very full lives that we all live and the need of a very own personal assitant like blocitoff !


