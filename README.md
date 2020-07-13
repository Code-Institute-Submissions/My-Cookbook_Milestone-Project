# [My Cookbook](https://github.com/Camila-Ribeiro/My-Cookbook_Milestone-Project)

## Table of Contents
1. [**My project overview**](#my Cookbook)
2. [**UX**](#ux)
   - [**User Stories**](#user-stories)
   - [**Design**](#design)
     - [**Libraries/Framework Used**](#Libraries/-framework-used)
     - [**Color Scheme**](#color-scheme)
     - [**Icons**](#icons)
     - [**Typography**](#typography)
   - [**Wireframes**](#wireframes)
3. [**Technologies Used**](#technologies-used)

   - [**Front-End Technologies**](#front-end-technologies)
   - [**Back-End Technologies**](#back-end-technologies)

4. [**Database Schema**](#database schema)

5. [**Testing**](#testing)

   - [**Validators**](#validators)
   - [**Automated Testing**](#automated-testing)

6. [**Deployment**](#deployment)

   - [**Local Deployment**](#local-deployment)
   - [**Remote Deployment**](#remote-deployment)

7. [**Credits**](#credits)
   - [**Content**](#content)
   - [**Media**](#media)
   - [**Acknowledgements**](#acknowledgements)

---

## My Cookbook application
It's an app built with Flask and MongoDB.

Throughout this project I will make use of Python a high-end programming language along with Flask a Python micro framework and MongoDB a document-based database.
Recipes for the cookbook have been gathered from the Spoonacular API


## UX

My Cookbook is an online web application designed for users with interest in gather information about recipes. The user can add their own recipes and also edit,update and delete them. 

The website is simple and structured in a way that is easy to navigate through and find recipes.

### User Stories

- As a user I want to search recipes filtered by allergen type, to perform this action I clicked on All recipes page, then I clicked on filter "Allergens", doing that I achieved my goal to see only recipes that were peanut free and I'm allergic to it.

- As a user I want to store my own recipes, to perform this action I registered into the website, then I clicked on "Add recipes", doing that I achieved my goal to store only recipes that were created by myself and have a list of my own recipes.

- As a user I want to edit my own recipes, to perform this action I logged into the website, then I clicked on "My recipes" and then on "Edit recipes", doing that I achieved my goal to edit and update recipes.

### Design

A standard layout is fully responsive on mobile devices and larger screens.

#### Libraries/ Framework Used

- [Bootstrap 4](https://getbootstrap.com/)
- [jQuery](https://jquery.com/download/)
- [Jasmine](https://jasmine.github.io/)
- [Jasmine - jQuery](https://github.com/velesin/jasmine-jquery)
- [MongoDB Atlas](https://www.mongodb.com/)
- [Flask](https://flask.palletsprojects.com/en/1.1.x/)

#### Color Scheme

- ![#343A40](https://placehold.it/15/343A40/343A40) navbar
- ![#EBECF0](https://placehold.it/15/EBECF0/EBECF0) body background
- ![#FFC107](https://placehold.it/15/FFC107/FFC107) yellow button
- ![#FEBB00](https://placehold.it/15/FEBB00/FEBB00) yellow star
- ![#FFFFFF](https://placehold.it/15/FFFFFF/FFFFFF) white cards
- ![#3A88FD](https://placehold.it/15/3A88FD/3A88FD) ![#343A40](https://placehold.it/15/343A40/343A40) ![#EBECF0](https://placehold.it/15/EBECF0/EBECF0) ![#FFC107](https://placehold.it/15/FFC107/FFC107) ![#FEBB00](https://placehold.it/15/FEBB00/FEBB00) loading gif

#### Icons

- [Icofont](https://icofont.com/)
  - 4 _Icofont_ icons were used on ....
    - [bars]()
    - [star]()
    - [phone]()
    - [globe]()

#### Typography

- 2 [Google Fonts](https://fonts.google.com/) were used across the site:
  - [Open Sans](https://fonts.google.com/specimen/OpenSans) : main body text.
  - [Lobster Two](https://fonts.google.com/specimen/LobsterTwo) : headings 1,2 and 3.
  - [Montserrat](https://fonts.google.com/specimen/Montserrat) : heading 6.

### Wireframes

My wireframes for this project can be found in the UX folder.

- [Desktop Wireframe](https://camila-ribeiro.github.io/)
- [Mobile Wireframe](https://camila-ribeiro.github.io/)

##### back to [top](#table-of-contents)

---

## Technologies Used

### Front-End Technologies

<b>Built with</b>

- ![HTML5](https://img.shields.io/static/v1?label=HTML&message=5&color=E34F26&logo=html5&logoColor=ffffff)
  - [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) - Used as the base for markup text.
- ![CSS3](https://img.shields.io/static/v1?label=CSS&message=3&color=1572B6&logo=css3&logoColor=ffffff)
  - [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3) - Used as the base for cascading styles.
- ![JavaScript](https://img.shields.io/static/v1?label=JavaScript&message=ES6&color=F7DF1E&logo=javascript&logoColor=ffffff)
  - [JavaScript ES6](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Used as the base for website interaction.
- ![Jasmine](https://img.shields.io/static/v1?label=Jasmine&message=3.5.0&color=8A4182)
  - [Jasmine](https://jasmine.github.io/) - Used for Test-Driven Development (TDD).
- ![jasmine-jquery](https://img.shields.io/static/v1?label=jasmine-jquery&message=2.1.1&color=535B9F)

  - [jasmine-jquery](https://www.npmjs.com/package/jasmine-jquery) - Used to simplify some of the automated Jasmine tests.

### Back-End Technologies

<b>Built with</b>

- ![Python]()
  - [jasmine-jquery](https://www.python.org/downloads/) - Used to automate specific series of tasks, making it more efficient.

##### back to [top](#table-of-contents)

---
## Database Schema

My MongoDB database consists of the following collections

- add_recipes
- cuisines
- allergens
- diets
- meals
- users

Diagram of website database schema

### Database data
All my recipe data was source from Edam a free recipe search API that can provide recipe data from calling a API endpoint and receiving the data back as JSON. The way I utilise this API was by using Python requests and creating a simple but yet effective CLI (Command Line Interface) script which was taken and adapted from the course material. In the course we made a program to work with MongoDB via the CLI. By creating a script to request data from the API I then adapt the Mongo CLI program to then inject my retrieved data and insert it into a Mongo collection. My import script can be found within this repo. 

##### back to [top](#table-of-contents)

---

## Testing

Automated and manual testing were conducted during this project. I also have validated all files using online validation sites cited bellow and checked across differents browsers and devices.
I have tried automated test as much as possible but based on the fact that it is purely running entirely from the XHR itself I couldn't get more done. It is a feature left to implement later after I graduate from the course. I have conducted a detailed [manual testing](testing/manual/testing.md) to show that I have testing done.

### Validators

#### HTML

- [W3C HTML Validator](https://validator.w3.org/) - `Document checking completed. No errors or warnings to show.`

#### CSS

- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - `Congratulations! No Error Found.`

#### JavaScript

- [JShint](https://jshint.com/)

### Manual Testing

**Testing Matrix**

**Chrome's DevTools Audit Report**

### Automated Testing

##### back to [top](#table-of-contents)

---

## Deployment

### Local Deployment

### Remote Deployment

This site was deployed using [GitHub Pages](https://pages.github.com/) using the **master branch**.

Deployed Site:

- [https://github.com/Camila-Ribeiro/My-Cookbook_Milestone-Project](https://github.com/Camila-Ribeiro/My-Cookbook_Milestone-Project)

Once you have the project setup locally, you can proceed to deploy it remotely with the following steps:

1. Navigate to your GitHub repository:
   - `https://github.com/USERNAME/REPO`
2. Click on the **Settings** tab at the top:
   - `https://github.com/USERNAME/REPO/settings`
3. Scroll down on that page to the **GitHub Pages** section.
4. The first drop-down field should be **Source** with _None_ preselected.
5. Select **master branch** from the list.
6. The page should refresh.
7. Scroll back down to the **GitHub Pages** section.
8. You should now have a deployed link:
   - `https://USERNAME.github.io/REPO`

**IMPORTANT NOTE**:

- Please allow a few minutes to pass before opening your newly deployed link! Clicking this link too quickly may result in a failure to build the site, causing an Error 404 page instead.

Congratulations! Your project should be deployed successfully on GitHub Pages! :tada:

##### back to [top](#table-of-contents)

---

## Credits

### Content

- [Spoonacular API](https://spoonacular.com/) - Database content

### Media

- [Spoonacular API](https://spoonacular.com/) - Database images
- [Unsplash](https://unsplash.com/) - Photo by

### Acknowledgements

I received inspiration for this project from Code Institute - Project Ideas

##### back to [top](#table-of-contents)
