---
layout: post
title: "CCT Pi Cloud Project Using a Docker- Part 1"
date: 2018-01-11 01:53:24 +0000
---

### Why Docker?

Docker solves the many problems you would encounter when you are developing software. When you making an application, you have to think about the not only application itself but, also how it runs, and where it will be deployed, and how you delivery the apps. Docker provides solution that you only need to focus on developing an app. using a Container concept.

### What is container?

The container is a platform that your application will be running on. Every container has a different environment for each application’s needs. - As in, Mysql for a database, Web Apache server for website or web application. So container can have any requirement you want. (one or many of it) You can make several containers on a one host machine. Each container will be isolated but share the resource of the host machine.
