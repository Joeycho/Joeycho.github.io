---
layout: post
title:      "Javascript Pet management System"
date:       2021-06-27 15:43:13 +0000
permalink:  javascript_pet_management_system
---



I have keep made Pet-management System in the project. So, I am familiar with the topics and I could more focus on technologies which I used for the project.

![javascript_backend](https://user-images.githubusercontent.com/29337166/123549950-763b4380-d76b-11eb-8161-0f51534d7f51.JPG)

I generate this image with `rails erd`. It works after installing `Graphviz`. So be aware of prerequisite `Graphviz` for using rails erd.

So, the models are simple. There are Owner, Pet and Clinic and Pet belongs to owner and Clinic.

Owner and Clinic, they could have many other ones via Pet.

Other parts which I want to highlight is..


Every click in the App is calling fetch request for Creating, Deleteing and Viewing for all. So this application relies on the interaction between Backend and Frontend. Interaction was possible via JSON format.

Data Persistency is achieved.

I contolled each dom by using `addEventListener`. `click` and `submit` Events were handled. `preventDefault` was used for preventing unexpected click event. For example, when loading the data, it automatically click `delete` button too. Therefore, in Data model, after fetching the data, Data were already deleted. I fixed this by using `preventDefault` function.

`render json:` was used in Backend Controller code.
