---
title: "Starting my adventure with fastpages."
summary: "This blog started because I'm lazy but I want to do better."
toc: true
comments: false
layout: post
hide: false
search_exclude: true
categories: [introduction, fastpages, jupyter]
use_math: true
---

# About me, this blog and I

My name is Gregory Sech, currently I'm a Computer Science student at Ca'Foscari 
University of Venice pursuing a Data Science curriculum.  
During the COVID-19 pandemic I've had time to ponder quite a lot about what my 
life was leading to and what mistakes I did and what I needed to change about 
my mindset to have a positive impact on this world.  
I do not have the presumption to being able to change the world however I do 
belive that I am not doing enough, especially I never really wanted to share 
my thoughts and my experiences to others.   
I decided to start this blog to share some experiences, it will not always be 
about Data Science, heck, it might take a while before the first "real" Data
Science post to be published. I'd like this blog to be a kind of a journal where
I will share with whoever finds this fragments of my experiences and thoughts.

# `fastpages`: a choice of laziness, procrastination and Actions.

I'm lazy and I will probably always be.  
My laziness is at the core of my passion for Computer Science.  
I really didn't want to write code or become an expert in CI/CD to integrate 
Jupyter Notebooks in my blog, also I didn't want to create a conversion and 
embedding process from scratch.  
While I was researching how to use GitHub Actions to automatically export them 
and commit the result in a different repository I came across `fastpages` and 
looked like a perfect fit.  
Obviously I had to procrastinate a little before getting on board with the idea 
so I watched the third movie of the Millenium saga while chatting with friends 
over Discord, played some videogames and then went to sleep. All of this 
yesterday.  
Today I woke up quite early and unable to sleep I decided of rolling up my 
sleeves and starting to integrate this bad boy.  

# My first hour or so with `fastpages`.
My first half an hour were pretty simple, I've ended reading most of the 
readme about `fastpages` and discovered that to use it locally I had to install
`Docker` and `docker-compose`, instruments I'm familiar with thankfully.  
So on my terminal I installed and added myself to the `docker` group to use 
that without `sudo` privileges.

```bash
sudo apt install docker.io
sudo gpasswd -a $USER docker
sudo apt install docker-compose
```

This and rebooting the machine did the trick.  
As described by the documentation I created a new GitHub repository using the 
`fastpages` template followed the initialization PR instructions to setup the 
deployment keys and discovered that I had to make the repository public to have 
free access to GitHub Pages, fair enough.  
Now I've cloned the repository locally and started the website with `make server`
to start editing the website.  
I've got some problem with my first markdown post but I discovered that I 
forgot to add the `layout: post` directive to the post `Front matter`.   
I'm quite happy with the start of this process, it was mostly painless, I'll 
just customize a little more the blog and then publish everything.  
If I do not procrastinate too much I hope to write about the publishing process
in the next post.