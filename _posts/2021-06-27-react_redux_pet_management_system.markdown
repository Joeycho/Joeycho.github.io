---
layout: post
title:      "React Redux Pet management System"
date:       2021-06-27 12:36:23 -0400
permalink:  react_redux_pet_management_system
---


So, I started the application using `create-react-app` generator.

It is only one page app, but have different view based on which one you click. URL is also changed, Routing works via `react-router`.

There are 3 components per each model(owner, pet and clinic), so total 9 and most of them are stateless, because it gets data from Redux store or props from parent component.

Yes, I have exactly 3 routes. One route per model.

`Redux-thunk` was used for communicating with Backend, which is run by `Rails`. Fetch function call the `API` `POST, DELETE, GET` for creating, deleting and fetching information.

It's still pretty simple, but all works as I expected.

The used model is like the below:

![Petapi_model](https://user-images.githubusercontent.com/29337166/124007223-76da1100-d9db-11eb-9012-1918f621e4dc.JPG)
