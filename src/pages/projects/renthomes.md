---
layout: ../../layouts/project.astro
title: AirBnB Clone
client: Self
publishDate: 2023-07-22 00:00:00
img: /assets/renthomes.png
description: |
  An AirBnB clone that allows users to rent homes.
tags:
  - React
  - Next.js
  - Typescript
  - Tailwind CSS
  - NextAuth
  - Prisma
  - MongoDB
  - Zustand
  - Vercel
---


## Overview
For this project, I followed [Code with Antonio's](https://www.codewithantonio.com/) tutorial on how to build a AirBnB application. This tutorial was very useful to me because it helped me reinforce my learnings for the new Next13 app router structure. This project helped me become better with typescript and making sure that I resolve type errors.

## Features

Features:

- Tailwind design
- Tailwind animations and effects
- Full responsiveness
- Credential authentication
- Google authentication
- Github authentication
- Image upload using Cloudinary CDN
- Client form validation and handling using react-hook-form
- Server error handling using react-toast
- Calendars with react-date-range
- Page loading state
- Page empty state
- Booking / Reservation system
- Guest reservation cancellation
- Owner reservation cancellation
- Creation and deletion of properties
- Pricing calculation
- Advanced search algorithm by category, date range, map location, number of guests, rooms and bathrooms
    - For example we will filter out properties that have a reservation in your desired date range to travel
- Favorites system
- Shareable URL filters
    - Lets say you select a category, location and date range, you will be able to share URL with a logged out friend in another browser and they will see the same results
- How to write POST and DELETE routes in route handlers (app/api)
- How to fetch data in server react components by directly accessing database (WITHOUT API! like Magic!)
- How to handle files like error.tsx and loading.tsx which are new Next 13 templating files to unify loading and error handling
- How to handle relations between Server and Child components!

## Takeaways
I feel like I learned alot more about React server componenets and how it works with the new Next13 app router. I had experience using MongoDB, Prisma, and NextAuth from previous projects, but I was able to learn how to use Zustand, which is a state management library that is similar to Redux. I learned how to use zustand to create simple global states for modals in our application. This abstraction made it very easy to create custom hooks for opening and closing a modal. I also learned how to use react-hook-form to handle form validation and form submission. I also learned how to use react-toast to display error messages to the user. I also learned how to use react-date-range to create a calendar for the user to select a date range. I also learned how to use Cloudinary CDN to upload images to the cloud. I had experience using react-map-gl from a previous project, so using the Leaftlet API was similar where I had no issue using. I also learned how to use react-select to create a dropdown menu for the user to select a category. This project helped solidfy my confidence to make fullstack applications using Next.js as well as working with Typescript to provide a better developer experience.

Check out the website [Rent Homes](https://renthomes.vercel.app) and the [github](https://github.com/Davi-web/airbnb-clone)
