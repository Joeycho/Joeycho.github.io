---
layout: post
title:      "CLI Data gem project review"
date:       2018-06-23 11:47:40 +0000
permalink:  cli_data_gem_project_review
---


Overall, I tried to focus on understanding how to build a simple project on my own way, even though I got a lot of help from other codes and lecture video. I choose the best 10 countries to visit in 2018 from lonely planet website, and it was originally inspired by 100 best restaurants in the world project by other student. If it's required and reccommended, I'm ready to develope more for this project, but my main focus is learning, and experience the full procedure to create the project, and get used to interaction between github and the IDE environment. And have a experience that is called 'technical interview'.

Along reviewing the project, I want to leave several lessons I learned from the project. When building up the gem project, it was important to update `.gemspec' file` for using external APIs. In working process, link all APIs, which are used in the project, and test a simple code, such as print out 'Hello World'. For checking, `require` and `require_relative` should be used well. And if it is neccessory, editing file access is also important. If the executive file is not allowed to being executed by the user, it will show the error message. `chmod +x [filename]`, this is the command line in the terminal. Those keyword help linking each files to work together. I agreed with this is the first step to check before actual coding. 

After checking environment, start to develop the code, and debug the code together. `require 'pry'` and `binding.pry` are used in this process. And later I could write the test file, such as `rspec` and can keep coding by `test-driven style`. When scrapping the data from the website, `Ctrl + Alt + I, :  Inspect function in Browser ` will lead the user to catch how to access the data, such as `div#1.classname`. If focusing on the tag name, ID, and class, it's not that much difficult to scrap the data. For scrapping, `open-url` and `nokogirl` should be installed and tested before.

After finishing coding, last thing is uploading the project to the github. This process is reccommended to intervene before in the middle of coding. Because, it helps the other programmer be able to understand the history of the code, how the code is developed. In the working folder, `git init`, and `git status` to check, and `git add .` to add the changes,  `git ci -m  "Send message"` to commit with the message. After these three step, `git push origin master`, to upload the folder in github. I'm still unsure that how origin, master, all the branches is working, but until now, at least I could do push origin to master(both branch looks default) to upload my work into github web. 

There are still something I want to clearly know about how to control `the git`, and In my code, how `gem` is installed in each computer, and is started to be worked.  But at least, I start to be in the workflow to make first project with github and ruby.
