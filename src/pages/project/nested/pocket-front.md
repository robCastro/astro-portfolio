---
layout: ../../../layouts/project.astro
title: Expenses Mobile App
client: Self
publishDate: 2020-03-04 00:00:00
img: /assets/ionic.png
description: |
  A mobile app to keep track of my expenses!
tags:
  - design
  - dev
  - mobile
  - hybrid
  - frontend
---

This is the hybrid app that works with the backend REST API, details about the backend [here](/project/pocket-api).

In my country there is this expression "tarjetazo", which refers to using your card in an emotional expense without really thinking about what you're buying. And I honestly have been doing too much tarjetazos recently LOL.

So I decided to make an app where I could record all my expenses and have an expending plan for every month.

It's made with Ionic Framework and Angular!
Angular is currently my favorite frontend framework (with svelte in second place).
It has a dashboard, which shows how much I've spend this month in different areas, each one with a different budget!

![dashboard](/assets/pocket-front/dashboard.jpg "App's Dashboard")


You can register budgets in the form of "categories".

INSERTAR IMAGEN DE CREAR CATEGORY AQUI
![new budget](/assets/pocket-front/new-budget.jpg "Creating a new Budget")

And declare expenses for different budgets.

![new expense](/assets/pocket-front/new-expense.jpg "Creating a new expense")


It's been a lot of fun, and I can now keep an eye out for my expenses!

For the future, I'm planning on building this app for any user which will requiere storing their expenses in their phone. I'll probably achieve this with the SQLite embebbed in most smart phones!

Will update when this is done :)

In the mean time, you can check out the source code in [Github](https://github.com/robCastro/pocket-front)

