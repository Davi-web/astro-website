---
layout: ../../layouts/project.astro
title: Enlyte
client: Self
publishDate: 2020-03-04 00:00:00
img: https://source.unsplash.com/8e2gal_GIE8
description: |
  Software Developer Engineer Intern (May 2022 - October 2022)
tags:
  - React/Redux 
  - Java Spring Boot
  - MVC Microservice
  - Reactive Programming
---

## Overview 
This summer, I was a Software Developer Engineer Intern at Enlyte, which is a P&C company that specializes in Auto Physical Damages. I was on the Mitchell Cloud Repair team, where I mainly worked on creating a microservice "MC-JAVA-EMS-SCANNED-JOB-INTERNAL-CLEAN-UP-API" that deletes EMS Scanned jobs from the Mitchell Connect website. In the beginning, I started with the **React/Redux** tutorial, where I learned how to use Redux with testing. Then I started out unit testing with JUnit, where I increased the code coverage for a microservice by 15%. Then, I created a microservice using Maven Spring Boot, which was used as an internal tool to clean up EMS Scanned jobs in the Mitchell Connect website. This microservice used Reactive Programming to allow asyncrhonous calls in the microservice(Reactor 3) using **subscribers**, **producers**, and the **observer pattern**.  After finishing developing the microservice, I was able to deploy it in **DEV** and **QA** and was able to demo the funtionality of the microservice to the system's team so that they can start using it for testing purposes. I was also able to create a dynamic postman collection which does the same functionality as the microservice but also for non EMS Scanned jobs as well. Then, I worked on Load Testing the microservice using a python script to easily generate EMS scanned jobs, Jmeter to hit the microservice endpoint for load testing, and then Kibana to visualize the microservice's data to see which API dependencies are bottlenecks to this API.

## Takeaways
I learned alot from my managers and other senior engineers who were there as mentors. We would have Scrum meetings everyday where we would share our progress with tasks and any blockers we had for the day. Because the internship was remote, I had a greater need to be proactive with my communication with my progress. I also learned to figure things out using the documentation Enlyte had in Confluence as well as Googling for alternative solutions. I also never had experience with unit testing, so spending a week or two unit testing as well as going over one of the API's with the most traffic helped me gain my skills in writing good unit tests as well as getting familiar with the company product's workflows. Although I had experience building monolythic backend applications using **Node.js** or **Django**, it was my first time using **Java Spring Boot** and my first time building a microservice. I personally enjoyed Java because of its typesafety as well as annotations to reduce boiler plate code. To do this, the logic of the microservice was done functionally using operations like map and flatMap to mainuplate data and chain events. This was something I have done in class in Programming Languages, but it was the first time I was able to experiment with in a real life setting. It was a different way to think and it allowed me to reinforce my learning in Functional Programming. Overall I learned alot from the internship and it gave me confidence/experince in Backend.

## Technologies Used
- React/Redux from tutorial
- JUNIT 4&5 from unit testing
- Maven Spring Boot for the microservice
- Jenkins for automating Pull Requests
- Jacoco for Code Coverage metrics
- Sonar for checkstyle violations
- Swagger-UI for easily generating UI to run the microservice
- Postman for testing endpoints
- Python for generating EMS Scanned jobs in Connect
- SQL for querying jobUids of EMS Scanned jobs created in Connect
- JMeter for Load Testing
- Kibana for visualizing data

