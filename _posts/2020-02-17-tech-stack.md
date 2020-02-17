---
layout: post
title:  "A dive into SmartCampus's stack"
author: abhijeet_viswa
categories: [stack, frontend, backend, django, reactnative]
image: assets/images/tech-stack.png
featured: true
hidden: true
---

A tech stack is a set of tools, applications, technologies and frameworks which is used to construct and power an application. The tech stack of a project determines how rapidly we can iterate and get a finished product. The frontend (user-side) and the backend (server-side) will use different technologies, depending upon the specific usecase and expertise of the people involved. In this post, we introduce SmartCampus's tech stack.

## Frontend
One of the most critical aspects of choosing a frontend stack is the ease of doing UI/UX. We felt it to be a non-brainer to go with Javascript and React Native, developed and maintained by Facebook. 

The reason for this choice was primarily the cross-platform support that React Native provides. This allows us to build apps for both Android as well as iOS without having to maintain two seperate code bases. React Native also allowed us to build a beautifully polished and interactive user interface. Also, the large community around React Native meant that a lot of third party libraries already available for easy development and debugging.

Redux is employed for state management, providing single source of truth for data. The centralised store of data provided by Redux means that components can ready and modify data from just one location, making it easier to test code and understand data flow.

## Backend
The backend of an application is the part that users never see. Nor do users directly interact with it. However, the backend is responsible for storing and manipulating data.

We decided to go with Python and the Django web development framework for out application server. Being a mobile first app, we used Django Rest Framework to help ease with writing REST endpoints.  Django is one of the most popular web development frameworks available. Infact, Instagram's backend is also developed using Django. Being an old language and framework, Python and Django have an extensive array of libraries and packages. The ease of programming in Python and using Django (along side familiarity) and, their amazing community is what made us settle on Python+Django.

However, Django is just our web app. Our webserver (the application that faces the Internet and users connect to) is infact Nginx. Nginx is configured as reverse proxy, forwarding requests to Gunicorn, which actually runs our Django web app. For the database, we settled with PostgreSQL, since it has the greatest compatability with Django.

Hopefully, this blog post gives you a little bit of idea of the building blocks of SmartCampus. All the technologies mentioned here are fun and interesting to learn and we urge you to give at least one the stacks (frontend or backend) a shot.