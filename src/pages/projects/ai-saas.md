---
layout: ../../layouts/project.astro
title: Ai-SaaS application
client: Self
publishDate: 2023-07-22 00:00:00
img: /assets/ai-saas-dashboard.png
description: |
  An application that uses AI to generate a SaaS application.
tags:
  - React
  - Next.js
  - Typescript
  - Tailwind CSS
  - ShadCN/ui
  - Clerk
  - Prisma
  - Planetscale
  - OpenAI
  - Replicate AI
  - Stripe
  - Vercel
---

## Overview
For this project, I followed [Code with Antonio's](https://www.codewithantonio.com/) tutorial on how to build a SaaS application. 




## Features:

- Tailwind design
- Tailwind animations and effects
- Full responsiveness
- Clerk Authentication (Email, Google, 9+ Social Logins)
- Client form validation and handling using react-hook-form
- Server error handling using react-toast
- Image Generation Tool (Open AI)
- Video Generation Tool (Replicate AI)
- Conversation Generation Tool (Open AI)
- Music Generation Tool (Replicate AI)
- Page loading state
- Stripe monthly subscription
- Free tier with API limiting
- POST, DELETE, and GET routes in route handlers (app/api)
- Fetch data in server react components by directly accessing database (WITHOUT API! like Magic!)
- Folder structure in Next 13 App Router

## Takeaways
I feel like I learned alot more about React server componenets and how it works with the new Next13 app router. I also learned how to use shadcn/ui, which is a frontend component library built on top of Radix/UI and Tailwind CSS. I felt that there was alot more room for customizing the components that you download from shadcn/ui as you can edit it to fit the design for your website.  It was my first time working with webhooks and I felt that it was a very useful tool to use. I was able to set up a webhook that would listen for events from Stripe and update my database accordingly. I also learned how to use Stripe's checkout session to create a checkout page for my application. I was able to set up a free trial system where users can generate a limited free prompts before they have to upgrade to the pro tier using Stripe's checkout session. I took an AI course my senior year at Vanderbilt, but never really applied it any of my projects. It was super cool to see how I could leverage AI so easily in my projects with REST endpoints with a prebuilt model vs actually building and training your model. After completing both the Airbnb Clone and this tutorial, it solidified my web dev skills. It also gave me confidence in trying out different frameworks as I understand the fundamentals of web development.

Check out the website [Genius](https://ai-sass.vercel.app) and the [github](https://github.com/Davi-web/ai-sass)
