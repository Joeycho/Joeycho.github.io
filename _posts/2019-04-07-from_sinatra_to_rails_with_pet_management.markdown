---
layout: post
title:      "From sinatra to Rails with pet management"
date:       2019-04-07 07:11:59 -0400
permalink:  from_sinatra_to_rails_with_pet_management
---


My starting with this project was `rails init`. This means a lot for me. Sinatra framework was a test or education version of the real one for me. I am not sure that whether it is still publishable only with the Sinatra, but I could feel that I was in education when I've done my project in sinatra. However, I really appreciate that Sinatra helped me to understand MVC model in a practical way and I was proud of my first sinatra project which started from the scratch. Literally, I built the structure with files and folders.

Now, I've moved to Rails. Ruby on Rails, I heard this one even before I started this full-stack development program. I am so proud of myself to understand this framework, and it was desireable to finish each lab and lessons even though I sometimes confronted hard time during learning. Yes, I learned `Rails` and now I can say myself, not a beginner in the web development environment. I feel so good with this project even though I still understand that I am still not enough.

Okay, I will start walk-through on this project. `rails init` created basic structure of the project. I adopted the `pet-management system` in this rails project as I did in Sinatra, but I implemented a bit different scheme in this project. I abandoned `owner as one model with two types, such as normal and shelter` and chose `owner and clinic as each model` with `pet` model, of course :) The below is the diagram which made by `rails-erd`.

![model_relationship](https://drive.google.com/file/d/1lW21DBalrJ0zfAn6nezbjD9cEyab9VvC/view?usp=sharing)

With my effort to fullfill the requirement, I also implemented `the nav` in the top in my application. The feedback from sinatra project reminded me of that `nav` will help viewers to understand application better.

So, the application starts with login or signup from user. And then, create some pets in each owner, and each pet should be assigned to one clinic. Have you heard `GP` system in our real life? When I was in Norway, everyone should be assigned to one `GP` to check their health status. GP is responsible to guide them to get right practice in terms of health issue. As we are, pets also should be assigned to one clinic. That was my motivation to implement this function in this system.

Each clinic could have upto 5 pets. Over 5 pets are not allowed to the clinic. With this function, I used the class method, which implemented in clinic model file. 

Styling was interesting for me even though it was not included in the requirement. I hope that this project become more readable for testers and users and for myself it is important to practice to get used to with styling as a web programmer. But I still need more practice and understand how to manage each area in the webpage and to make it dynamically responsible.

The remaining issues are refactoring and taking care of `corner cases`, such as testing unexpected action and see whether it is handled or not. If it is not addressed well, it should be fixed. Additionally, `validation` error messages should be shown for users to see what is wrong in their inputs to help them put right input form.

So good to move from Sinatra to Rails and looking forward to work with `Javascript`! :)
