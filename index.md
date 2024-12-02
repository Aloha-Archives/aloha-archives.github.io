---
title: "Aloha Archives"
---

![ci-badge](https://github.com/ics-software-engineering/meteor-application-template-react/workflows/ci-meteor-application-template-react/badge.svg)

# Table of Contents
- [Overview](#overview)
- [User Guide](#user-guide)
- [Community Feedback](#community-feedback)
- [Developer Guide](#developer-guide)
- [Development history](#development-history)
- [Contact Us](#contact-us)

## Team Contract
To see the team contract for this project, click [here](https://docs.google.com/document/d/1P-EUtJDOpm3DrSK2WEZ7VvwGKifwNqZ6sU6OpzdtIxc/edit?usp=sharing).

## Github Organization
To see the GitHub Organization associated with this project, go to [https://github.com/Aloha-Archives](https://github.com/Aloha-Archives)

## Deployment
Our project is currently being deployed at, [https://aloha-archives.vercel.app/](https://aloha-archives.vercel.app/)

# Overview
Aloha Archives is an innovative data portal designed to simplify access to open data in Hawai’i, making it user-friendly, personalized, and visually appealing for citizens of varying technical expertise. Unlike traditional open data platforms, Aloha Archives focuses on tailoring the experience to meet the unique needs of its users through persona-based customization, intuitive navigation, and accessibility for all. It bridges the gap between raw datasets and meaningful insights by providing relevant visualizations, advanced search capabilities, and a seamless user interface.
While other data portals focus primarily on displaying datasets, Aloha Archives transforms the experience into a personalized journey. By prioritizing user personas, providing relevant data visualizations, and ensuring a clean, interactive interface, it democratizes access to data for all Hawai’i citizens, empowering them to make informed decisions, advocate for their communities, and foster innovation.

# User Guide
This section provides a walkthrough of the Aloha Archives user interface and its capabilities.

## For Regular Users
### Landing Page
The landing page is presented to users when they visit the top-level URL to the site.
<img src="pics/login.png">

### Explore Page
After clicking on the **Datasets** tab in the nav bar, users are taken to the explore page where they can view all available datasets. This explore page is accompanied by a filter bar to the left of the screen.
<img src="pics/datasets.png">

### Inspect a Dataset
After finding a dataset of interest, you can click on it to expand information related to it. Along with general information related to the dataset, there is also a data visualization tool you can use prior to downloading the data.
<img src="pics/ds-1.png">
<img src="pics/ds-2.png">

### Sign In
To get access to more features, you can sign in or create an account if necessary.
<img src="pics/signin.png">

### Favorites
After signing in, you are able to add datasets to your favorites and access them via a **Favorites** tab on the navigation bar.
<img src="pics/fav-2.png">
<img src="pics/fav-1.png">

### Recommended
You can also access recommended datasets by taking a **Persona Quiz** and being recommended different datasets based off of your persona.

<img src="pics/persona-quiz.png">
<img src="pics/recs.png">

## For Admin Users
### Manage Datasets
When you log in as an admin user, while having access to all the features a regular user has, admin users also get access to as special **Manage Datasets** tab, which allows the user to upload, delete, and edit the datasets related to the users account.

<img src="pics/manage.png">
<img src="pics/edit.png">

# Community Feedback
We are interested in your experience using Aloha Archives! If you have any suggestions on how we can improve the application, feel free to fill out our feedback form [https://forms.gle/yJkAZ5UfKk6JsWMv6](https://forms.gle/yJkAZ5UfKk6JsWMv6).

# Developer Guide
Developers who are interested in running our project locally must have Next.js and PostgreSQL installed. Our tech stack also uses ESLint, Typescript, Bootstrap 5, and React, with deployment via Vercel.

1. Clone the repository to your local computer.
2. Change into the root directory for the project (aloha-archives) using `cd` command. Then install the necessary third party libraries using `npm install`.
3. Configure PostgreSQL Database by installing PostgreSQL on your local machine.
Then set up your .env.local file in the root of the project with the PostgreSQL connection string: `DATABASE_URL=postgresql://user:password@localhost:5432/dbname` and run database migrations with `npx prisma migrate reset`
4. Run the Project Locally with `npm run dev`
5. Open http://localhost:3000 to view the running local application.

# Development History
## Milestone 1
Milestone 1 aimed to establish a basic outline of our website’s design. Our primary focus was on creating the visual structure and layout to resemble a functional website, without yet implementing full functionality. By setting up the foundational framework, we can efficiently add and refine features in future milestones.

Milestone 1 was managed using [Aloha Archives GitHub Project Board M1](https://github.com/orgs/Aloha-Archives/projects/1/views/1):

<img src="pics/m1-page.png">

## Milestone 2
Milestone 2 aimed to implement more functionality in the website now that the basic outlines have been completed in M1.
This milestone included uploading mock datasets to the PostgreSQL database that can then be read and populated on the website,
making a 'Persona Quiz' option that allows users to take a quiz and get recommended datasets based on their assigned persona,
as well as adding functionality to the dataset search page. This milestone also covered styling improvments, such as adding color schemes,
images, and animation to the different pages. For more detail on what was completed in this milestone, refer to the section below.

Milestone 2 was managed using [Aloha Archives GitHub Project Board M2](https://github.com/orgs/Aloha-Archives/projects/3):
<img src="pics/m2.png">

## Milestone 3
Milestone 3 was managed using [Aloha Archives GitHub Project Board M3](https://github.com/orgs/Aloha-Archives/projects/4):

# Contact Us
Aloha Archives is designed, maintained, and implemented by [JR Lee](https://jswlee.github.io/), [Jared Seto](https://jseto808.github.io/), [Shaelyn Loo](https://shaelyn-l.github.io/), [Kevin Clarkin](https://kevin-clarkin29.github.io/), and [Harry Mills](https://thingy18.github.io/harrymills.github.io/)