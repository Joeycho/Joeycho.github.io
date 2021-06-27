---
layout: post
title:      "React Redux Pet management System"
date:       2021-06-27 16:36:23 +0000
permalink:  react_redux_pet_management_system
---


So, I started the application using `create-react-app` generator.

It is only one page app, but have different view based on which one you click. URL is also changed, Routing works via `react-router`.

There are 3 components per each model(owner, pet and clinic), so total 9 and most of them are stateless, because it gets data from Redux store or props from parent component.

Yes, I have exactly 3 routes. One route per model.

`Redux-thunk` was used for communicating with Backend, which is run by `Rails`. Fetch function call the `API` `POST, DELETE, GET` for creating, deleting and fetching information.

It's still pretty simple, but all works as I expected.
