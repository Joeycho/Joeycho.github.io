---
layout: post
title:      "Sinatra project  walk-through review"
date:       2019-02-07 07:58:13 +0000
permalink:  sinatra_project_walk-through_review
---


It has been so while since I blogged last time. Later, I will briefly catch up with all I've gone through during the time.

As you noticed, this is walk-through review. I am still in the project, and I am quite concerned about how much I get through all of the lessons and labs by myself. It is quite difficult to pair-programming and team-coding. I started to feel pressure to do that. At least, be aware of how necessary it is, and be prepared for that. So, I restart the blogging for my project and for being prepared to cowork with others :)

Regarding the Sinatra project, I tried to implement commiting and branching each time I coded in the project. Briefly, I divided the functions. For example, first part is to make sure run the sinatra web application from the scatch. This is quite important starting breaking point. If I keep coding without checking running, it will be disaster to debug after-function in the end. I did it well with the video which Avi recorded before. Rakefile and Gitignore are still confusing me a bit, but currently, it is good to go for the next. What I learned was focusing on 'config.ru' and take care of 'environment' area, and fundamental structure of folders, such as app and db.

Second part is modeling and buiding the database.  I don't know why, but Database seems unstable in my level. I've been not comfortable when I tried to delete with the command 'rm' in db folder. This seems unsafe way and I think I was enforcing to delete something. As long as I know, database has 'rollback' function, and very stable and liable data structure with security. I want to figure it out later. Currently, it works perfectly fine with 'rm' command. Defining the relationship between the model is very fundamental, and could be debugged with 'tux' gem. Tux was used during the time. But in real, it was just passed without verifcation. However, Authentication requires me to be aware of 'password' field and 'password_digest' field in the database. This is quite important to remember. 'has_secure_password', metaprogramming code in the model file, and bcrypt gem should be included in the GemFile.

Third part is automatically for basic view files and controller files in app. This is starting point to implement some functions, such as reading some datas, and explicitly showing data in the web. Constant debugging is required. For this, shotgun, pry gems should be used. This part is actually interesting parts to see the real working parts of the application. 

Regarding Git usage, I started to be aware of how the branches works, and each time I tried to implement some functions, I branched it out from the master branch. However, I have not tried to use 'rollback function' in each branch. And still  a bit confused with remote environment and push/pull command in git. Now, I only use push for saving the local work into the remote server. That's all.

Forth part will come with CRUD functions in the next blog, or in the video! :)
