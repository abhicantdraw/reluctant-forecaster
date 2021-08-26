---
toc: true
layout: post
description: There and Back again
categories: [markdown]
comments: true
title: Setting reluctant-forecaster up
---

So I mentioned on the home page that it was difficult to set this up. It really wasn't all THAT difficult. For starters, all I had to do was :
- Create a New Repo on my Github account with a name that was anything other than my username.github.io by Forking the fastpages repo. 
- This would basically create a copy of the demo Fastpages site on my created Repo, but you won't see any changes or a Github Page just yet. 
- To get that to happen, you'll have to merge the PR that gets raised on this newly created repo. 
- For example, my new repo was called : reluctant-forecaster. And my Github user name is abhicantdraw. So my new page would be abhicantdraw.github.io/reluctant-forecaster. 
- And that's it. The content that was available on the demo FastPages page is now also available on your new repo-ed page. 

That was the easy part. 

Now I wanted to get this to be serve-able on my local system as well. 
Why? So I can make changes to the repo of course! - Add new posts, make modifications to the home page etc. And also view those changes locally before I push them out onto the internet. 

This requires Docker to be installed on your system <groan> . This is a 544-ish MB behemoth software that is to be downloaded and then you can install it. Here's the catch though. If you just install it after downloading it, you run into a host of problems, not the least of which is Docker Desktop will refuse to start up. 
So you need to Install it as an administrator. 
It took me some time to realise that this was the mistake I'd made. 
Once that was done and Docker Desktop was restarted, all I had to do was run 
```shell 
docker-compose up
``` 
on the new shell prompt that I could open up right from inside Docker Desktop. The app does look pretty neat, I'll give them that. 

And voila, you should be able to access your page at 127.0.0.1:8080!

That's the end of this post. 

See you on the next one where I'll begin talking about what I've read and understood from each chapter or section from 
[Forecasting: Principles and Practice (3rd ed) by Rob J Hyndman and George Athanasopoulos](https://otexts.com/fpp3/).

![]({{site.baseurl}}/images/cant-wait-yay.gif ) 

