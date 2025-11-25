---
title: "DevOps Roadmap - A big list of resources"
date: 2025-11-23T18:00:00-03:00
draft: false
summary: "Roadmap ideas made by me"
categories: ["mentorships", "learning"]
tags: ["mentorships", "learning", "roadmap"]
lightbox:
  enabled: true
justified_gallery:
  enabled: true
cover: '/images/mentorshipsfirstyear.png'
---

Here are outlined some ideas on how to improve DevOps skills.

The main idea is that you do 5 actions for every skill you need to practice:

1. **Read or watch** about a given subject
2. **Exercise** by doing a project by yourself without following a course
3. **Explain** what you did for someone with more experience than you
4. **Receive Feedback** about your skill/project
5. **Improve** your skill

In this post I will provide material so you can do item 1 and 2.

For items 3-5 you need a peer. In case you need someone to help you through this process or just a peer: I do mentorships and you can schedule a mentorship session with me using this [link](/about)

What you will see is a big list of resources! I hope I can one day divide this post in smaller sections and make this better!

## Table of contents
- [Table of contents](#table-of-contents)
- [About IT career](#about-it-career)
- [What is DevOps](#what-is-devops)
- [Starting in DevOps](#starting-in-devops)
  - [Coding](#coding)
  - [Git](#git)
  - [Linux](#linux)
  - [Docker](#docker)
  - [Exercise](#exercise)
- [CI/CD](#cicd)
  - [Exercise](#exercise-1)
- [Cloud](#cloud)
  - [AWS Courses](#aws-courses)
  - [Exercise](#exercise-2)
- [Scripting/APIs](#scriptingapis)
  - [Python](#python)
  - [Exercise - Make a tiny webserver](#exercise---make-a-tiny-webserver)
- [Kubernetes](#kubernetes)
  - [Exercise](#exercise-3)
- [Other topics](#other-topics)


## About IT career

If you are new to IT, it might a good idea to familiarize yourself with the carrer possibilities.

[How to get started in IT](https://www.youtube.com/watch?v=XmWkcePhf84)

If you want to know more about **programing** scroll down

## What is DevOps

This roadmap focus on an area of IT. Here is more information about it.

**Watch**
* [What is DevOps Video](https://www.youtube.com/watch?v=0yWAtQ6wYNM) 
* [Responsabilities of a DevOps Engineer](https://www.youtube.com/watch?v=9pZ2xmsSDdo)

**Read**

* The Phoenix Project by Gene Kim


## Starting in DevOps

### Coding

These are generic Computer Science and programing classes for someone who never did programing. It will teach you basic coding. Below are courses:
 
[Speed/Overview Harvard IT course](https://youtu.be/8mAITcNt710)

[Python and programing course](https://www.edx.org/learn/computer-science/massachusetts-institute-of-technology-introduction-to-computer-science-and-programming-using-python)

### Git

Every IT professional must know it.

Check [Gettings started with Git](https://docs.gitlab.com/ee/tutorials/learn_git.html) 

### Linux

[Free Course on Linux](https://www.edx.org/learn/linux/the-linux-foundation-introduction-to-linux)

### Docker

[Free Deep Course](https://kodekloud.com/courses/docker-for-the-absolute-beginner/).

[Differences between VMs, Containers and Docker](https://www.freecodecamp.org/news/a-beginner-friendly-introduction-to-containers-vms-and-docker-79a9e3e119b)


### Exercise

If you are tired of courses and/or feel you are confident with the Basics try doing:

1. Print "Hello World" in python on the screen. Run it in your laptop.

2. Run it in a container using Docker Desktop

3. Explain to someone, receive feedback and improve


## CI/CD

If you already know a little bit of the Basics above and know a little about Docker. CI/CD is another important skill to learn.

**Watch**

* [What is CICD](https://www.youtube.com/watch?v=G1u4WBdlWgU)
* [Github Actions Course]( https://www.youtube.com/watch?v=R8_veQiYBjI)
* [Gitlab Course](https://www.youtube.com/watch?v=z7nLsJvEyMY)

**Read**

[Gitlab Tutorials](https://docs.gitlab.com/ee/tutorials/build_application.html)

### Exercise

1. Do the Docker Exercise on Basics.md file above

2. Create a pipeline in Gitlab/Github that will build your docker image using the same tag
  
3. Version the docker image to use different tags

4. Explain your pipeline to someone, get feedback and improve

## Cloud

**Watch** 

[Basic Cloud Course](https://www.edx.org/learn/cloud-computing/the-linux-foundation-introduction-to-cloud-infrastructure-technologies)

### AWS Courses
- [AWS Cloud Practitioner Essentials](https://learning.edx.org/course/course-v1:AWS+AWS-OTP-AWSD15+1T2021/home)
- [AWS: AWS Cloud Technical Essentials](https://www.edx.org/learn/amazon-web-services-aws/amazon-web-services-aws-cloud-technical-essentials?index=product&queryID=b5129a8cf3489b4139ee6b7ad898c074&position=2&results_level=first-level-results&term=aws&objectID=course-1598bd52-f62f-4596-808d-4bc993da4929&campaign=AWS+Cloud+Technical+Essentials&source=edX&product_category=course&placement_url=https%3A%2F%2Fwww.edx.org%2Fsearch)

### Exercise

1. Pick an exercise from [AWS](https://workshops.aws/) or [Azure](https://learn.microsoft.com/en-us/training/browse/)
2. Explain what you build to someone, get feedback and improve

3. Automate what you did in step 1 and 2. You can use Terraform. Use this [tutorial page](https://developer.hashicorp.com/terraform/tutorials) if you need help.

4. Build a pipeline that runs the automation for you. If you need help refer to CI/CD section of this page.

## Scripting/APIs

### Python
[Python from zero to hero](https://www.youtube.com/watch?v=t8pPdKYpowI)

### Exercise - Make a tiny webserver

Improve your scripting skills.

Build a python web server that listens to 2 endpoints:
1. /health endpoint should return the version of your application
2. /projects endpoint should return the list of all your projects in GitHub or Gitlab
3. Use CICD.md to built a container + pipeline


## Kubernetes

**Watch**

[Introduction to Kubernetes](https://www.edx.org/learn/kubernetes/the-linux-foundation-introduction-to-kubernetes)
[Kubernetes Tutorials](https://kubernetes.io/docs/tutorials/)

**Read**
https://kubernetes.io/training/

https://kubernetes.io/docs/tutorials/

### Exercise

1. Deploy a webserver from previous section using kind
2. Expose your app to a URL so you can access from your browser

If you don't have a webserver you can deploy [Google Online Boutique](https://github.com/GoogleCloudPlatform/microservices-demo) in a local kubernetes



## Other topics


[How DNS Works](https://www.youtube.com/watch?v=Ah7fYex6Ups)

**System Design:** https://github.com/donnemartin/system-design-primer?tab=readme-ov-file#system-design-topics-start-here


**Troubleshooting:** https://sadservers.com/
