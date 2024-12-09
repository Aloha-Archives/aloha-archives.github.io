---
title: "Aloha Archives"
---

![ci-badge](https://github.com/Aloha-Archives/aloha-archives/workflows/aloha-archives/badge.svg)

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

Here are some suggestions we've gotten so far from community members who have used Aloha Archives!
### Person 1
- Overall, site is attractive and engaging and you immediately know it is about Hawaiʻi and data gathering. Nice work!
- On the homepage, might be good to include a very brief welcome/description about the site, its purpose and key features.
-  When signing up, put down instructions that the password needs to be at least 6 characters.
- In the Persona Quiz section, either put all periods or no periods in the “Select an Option” choices. Right now some sentences have and some donʻt.
- For the “How comfortable are you with data analysis tools?” question, consider rephrasing to “How familiar are you with data analysis tools?” and your options to be something more like…
    - Very familiar - I work with data regularly.
    - Familiar - I have basic data skills. 
    - Somewhat Familiar - I have limited data skills.
    - Not Familiar - I have no experience.

### Person 2
- It would be nice if there was a way to return to “all topics” from the Filters. Maybe a “Remove filters”. Or do you just have to click on “Datasets” again to pull up all topics? 
-  On “About Us’ page, “Only after countless hours (and some head banging one the table)”

### Person 3
-  I agree that a very brief description of what Aloha Archives is on the homepage might be helpful, something like “Aloha Archives provides access to State of Hawaii data to enhance open government, transparency, and accountability.” (I got this from your Terms of Use page. 🙂) 
-  I did sign up, and it was easy to follow. I like the Recommended and Favorite drop down menus. I was going to say I wasn’t sure how to populate the Favorite section but saw the “Add to favorites” when I went back to view the datasets.
- Nice job on the Filters. They were very helpful.
- For the Persona Quiz, would it be too much to have a “select all options that apply”?
- This is a small thing, and there could be a very good reason why it isn’t done yet: spelling place names in ʻolelo Hawaiʻi (so Hawaiʻi instead of Hawaii). It could be a state style thing not to do it and use the English spelling, but you might think about using ʻolelo Hawaiʻi spelling and starting a new trend.

### Person 4
- Persona Quiz probably shouldn't be called that. Maybe "data profile" or something.
quiz dropdowns are too constrained, need "Other" category. Prefer to interact question: each option is too similar at the end I got assigned Community Member but I was already a community member? Quiz "You are a Community Member" is odd result. Makes me feel like you're telling me what I am.
- Tropical background image on every page is more like a vacation rental website than government portal. Needs to be more professional plain background.
on /favorites, should probably not be "Delete" or trash can icon because we are not deleting the dataset, we are removing it from a favorites list. Suggest having it be consistent with the dataset detail page, with heart icon and "Remove from Favorites" title.
- Favorite button probably doesn't need the big title "add to favorites". Can just be a heart button you toggle. The alt text should be "remove from favorites" or "add to favorites"
- On the list view, the cards are pretty but can be hard to scan quickly. Perhaps a toggle to switch between cards/tiles and a list view?
- On the dataset detail view, the radio buttons for Histogram/Scatterplot are squished together.
- On other data portals I've used, there have been lots of options for formats to download. e.g. CSV, XLSX, JSON, etc.
- On my profile page, it would be great to have a list of past datasets I've downloaded or recent datasets I visited.
- On my profile page, the Choose Persona feels like a dead end. Perhaps provide a link or button to the Recommended datasets for this persona, and not just a "Retake Quiz" button.

### Person 5

- The scatter plot / Histogram. Commas in the years are atypical. For instance, it's not standard practice to write a year like 2,013. There doesn’t appear to be a space between the Histogram and the Scatterplot bubbles.
- Selecting a variable for the graph under a dataset. Selecting a variable is confusing. Eg, graphing SEX for the United States Census Bureau doesn’t appear to make sense. Another example with the y-axis being confusing would be the Hawaii Housing Market Trends MedianHomePrice Histogram variable. It states frequency and gives a scale from 0 to 1, but how does a person have 0.1 of a house for instance?
Selecting the variable itself is also confusing. Eg, not knowing what AGEP is as a variable to select for Census Bureau
- Selecting Datasets in Navbar. Shows a “results not found” before loading the dataset cards.
- Navbar Search Bar. Cut off slightly but functional

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
The main focus of Milestone 3 was to complete everything that was not done in Milestone 2 in order to reach our finished product.
This milestone included uploading more sets of data into the database to be used on the website, more styling within the different pages of the website
to be done, and adding the edit dataset page which allows admin users to manage the database from the website just to name a few tasks 
completed in this milestone. Overall, this milestone focused on wrapping up any loose ends in order for there to be a finished version of 
Aloha Archives for users to enjoy. This milestone is also when we shared our deployed application to people we through would use this website. After
sharing what the team had worked on, we were fortunate enough to be provided with feedback from the test users that can be seen in our *Community Feedback* section.

Milestone 3 was managed using [Aloha Archives GitHub Project Board M3](https://github.com/orgs/Aloha-Archives/projects/4):
<img src="pics/m3.png">

# Contact Us
Aloha Archives is designed, maintained, and implemented by [JR Lee](https://jswlee.github.io/), [Jared Seto](https://jseto808.github.io/), [Shaelyn Loo](https://shaelyn-l.github.io/), [Kevin Clarkin](https://kevin-clarkin29.github.io/), and [Harry Mills](https://thingy18.github.io/harrymills.github.io/)
