# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png" height="60"> Project 1 - Full-Stack JavaScript

**Read this entire document before writing a line of code.**

## Contents

* **[Overview](#overview):** What is this project?
* **[Planning & Deliverables](##planning--deliverables):** What will I be turning in?
* **[Technical Requirements](#technical-requirements):** What technologies will I be using?
* **[Further Exploration](#further-exploration):** What if I want to do more?
* **[Deadlines](#deadlines):** When is it due?

<!-- * **[Submission](#submission):** How do I turn in the project?
* **[Resources & Support](#resources--support):** Where can I get help?
* **[Instructor Groups](#instructor-groups):** Who is my assigned instructor for this project? -->


## Overview

###### What is this project?

It's time to put everything you've learned in the past month together! You'll use your knowledge of front-end and back-end web development to create a web application that can be used by friends, family, or any of the other billions of people who use the internet. The type of web application you create is your choice.

**The objective of this project is to:**

  * Apply the skills you've learned by building a web application from the ground up.
  * Demonstrate mastery of topics covered during this course so far.

**You will be working individually for this project**, but we encourage you to get help from your peers and even pair-program on each other's projects when bugs arise.

## Planning & Deliverables

###### What will I be turning in?

### Project Planning Deliverables

**You must review the following with your instructional team BEFORE you start to code.** Create a <a href="https://trello.com" target="_blank">Trello</a> board that includes user stories, wireframes, ERD, and project milestones.

* **Scope:** What are you planning to build? What do you reasonably think you can implement in the time period?
* **User Stories:** Who is your user? What features will your app have?
* **Wireframes:** Sketch out what each of your pages will look like and how they will work. Consider making a *paper prototype* to demonstrate and/or test key user interactions.
* **Data Models:** Draw out the models and any associations for your project in an entity relationship diagram (ERD).
* **Milestones:** What are major steps to completing the project?
* **Feasibility Check:** If you're using an external API, make sure you can get that data. If you are using a new tool, go through its getting started tutorial. We will ask to see your results.

### Completed Project Deliverables

* Link to Heroku hosted project, with all core technical requirements and two flexible technical requirements complete.
* Link to source code on GitHub.
* A `readme.md` file with the following:
  * Description: Short paragraph (2-3 sentences) "elevator pitch" describing what your project does
  * Link to Heroku hosted project
  * Technologies
  * Wishlist / Future Development

## Technical Requirements

###### What technologies will I be using?

### Core Technical Requirements

**Your app should have all of the following:**

* **Express API:** Implement a server-side JSON API with Express.
* **RESTful Routes:** Design your API routes in a <a href="http://restfulrouting.com/mappings/resources" target="_blank">RESTful</a> manner.
* **MongoDB:** Persist data with at least two models in a Mongo database.
* **AJAX:** Fetch JSON data from your server-side JSON API asynchronously to the client-side.
* **jQuery:** Use jQuery to manipulate the DOM and listen for events on the client-side.
* **Server-Side View Rendering:** Render your HTML views with `hbs`.
* **Client-Side Templating:** Use Handlebars.js on the client-side to template API data into your view.
* **Data Validation:** On the client-side, don't let a user submit a blank form, and give them a visible error message explaining why they weren't allowed to submit (see the <a href="http://jqueryvalidation.org/" target="_blank">jQuery Validate</a> library). In your database, use Mongoose validations for at least one attribute in each of your schemas (see the <a href="http://mongoosejs.com/docs/validation.html" target="_blank">Mongoose validation docs</a>).
* **Testing:** Write request tests for 50% of your API routes.
* **User Experience:** Leverage Bootstrap to kick-start your UX and UI.
* **Heroku:** Deploy your app to Heroku. Ensure no app secrets are exposed. *Do not commit secret keys to GitHub!*

### Flexible Technical Requirements

**Your app should have 2 out of the 4 following options:**

* **External API:** Use an external API to integrate third-party data into your app.
* **Model Relationship:** Create a one-to-many or many-to-many relationship between two models using embedded or referenced data.
* **Authentication:** Allow users to sign up, log in, and log out.
* **Custom Styling:** Go beyond Bootstrap with styles and/or animations customized for your app.

## Further Exploration

###### What if I want to do more?

If you want to push yourself and learn something new, optionally consider doing any of the following ideas. *Please talk to an instructor beforehand.*

* **Search:** Build a form that allows users to search your data, based on attributes.
* **Authorization:** Create and implement rules that prevent users from reading/editing/deleting content that belongs to other users. Start with one rule; the specifics are up to you. For example, a good challenge could be saying users cannot delete a post (or other resource) if it is not theirs. (This requires authentication.)
* **Email:** Send emails with <a href="https://github.com/RGBboy/express-mailer" target="_blank">express-mailer</a>.
* **Payments:** Add payments with <a href="https://stripe.com" target="_blank">Stripe</a>.
* **Web-Scraping** Use a web-scraper to collect data from a website that doesn't have an API. Example technologies include <a href="http://casperjs.org" target="_blank">Casper</a> or <a href="https://www.kimonolabs.com" target="_blank">Kimono</a>.
* **Web Sockets** Create an open, real-time connection between your server and client (e.g. live chatting) with a tool like <a href="http://socket.io" target="_blank">Socket.io</a>.
* **Whatever else you can think of!**

## Deadlines

###### When is it due?

* **Tuesday, November 24th, 9:17am** - [Project planning deliverables](#project-planning-deliverables) due! Before beginning work on your project, your idea, project scope, and other planning deliverables must be approved by an instructor.

* **Friday, December 4th, 10:00am** - [Completed project deliverables](#completed-project-deliverables) due and presentations!

<!-- ## Submission

###### How do I turn in the project?

* Google doc (GitHub + Heroku links) -->

<!-- ## Resources & Support

###### Where can I get help?

* Documentation, tutorials, Stack Overflow, module notes
* Your classmates - even though this is an individual project, we encourage you to get help from your peers and even pair-program on each other's projects. -->

<!-- * Instructor/student stand-ups every morning at 10:00am
* Scheduled 1:1 meetings for each student throughout the week
* Break-out lessons on selected topics as needed
* Instructors and DIR available in the classroom each weekday (will be taking turns)
* Evening and weekend TAs -->

<!-- ## Instructor Groups

###### Who is my assigned instructor for this project?

Each student has an assigned instructor, splitting the class into three informal groups. Your instructor will approve your project, lead your morning stand-ups (with the rest of your group), meet with you for 1:1s, and give you feedback after the project. Outside of those structured activities, you're welcome and encouraged to work with other instructors and students from any group you'd like!

### Ben

### Cameron

### Erik -->
