---
layout: ../../layouts/project.astro
title: Expenses API
client: Self
publishDate: 2022-09-21 00:00:00
# img: https://elpythonista.com/wp-content/uploads/2020/10/Django-1024x576.jpg
img: /assets/django.jpg
description: |
  I've build an API to keep track of my expenses!
tags:
  - design
  - dev
  - backend
---

This is the backend that provides RESTful endpoints that a hybrid app consumes. You can read more about the app [here](/project/nested/pocket-front).


In my country there is this expression "tarjetazo", which refers to using your card in an emotional expense without really thinking about what you're buying. And I honestly have been doing too much tarjetazos recently LOL.

So I decided to make an app where I could record all my expenses and have an expending plan for every month.

It's made with Django and Django Rest Framework. Django provides a nice admin panel to manage all my models, and Django Rest Framework provides the REST API support that the mobile app consumes.

Although I'd have loved to implement this backend with an webhook or API from my bank, they don't implement those, so I have to record each transaction manually. Fortunately, the app is really easy to use, so it's not that much of an issue.

Check out the code in [GitHub](https://github.com/robCastro/pocket), it's not yet Dockerizable, and lacks a README with info about the project and instructions, but I plan on implement it.