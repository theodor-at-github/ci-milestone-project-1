A static frontend page as part of Code Institute's milestone projects and a portfolio build with maximum effort and heart. You can check out the website [here!](https://theodorcodes.github.io/milestone-project-1/) 

![portfolio](/assets/images/portfolio.png)

### Table of Contents

- Project
    - Project Introduction
    - User Story and Goals
    - Developer Story and Goals
- Features
    -   Planned Features
    -   Features Implemented
    -   Features Left to Implement
- UX
    -   Design Choices and UX
    -   Wireframes
- Technologies Used
- Testing
- Deployment
- Credits
    -   Acknowledgements

## Project Introduction

As part of a student project of Code Institute, this page aims to deliver a static website written in pure HTML and CSS. 

### User Story and Goals

This portfolio is build to showcase current developer skills, experience level and quality of work to prospective employers and potential recruiters who look for web developer profiles that stand out. To present what employers seek for when looking at a programmer portfolio, this site focuses on the representation of **skills**, **educational background**, **current work** or **projects** and an introduction to a problem solving **personality**.

### Developer Story and Goals

**Hands-on experience** to built a web development portfolio that looks and works flawlessly. **Implementation of features**, **run test** and gain **valuable experience** and problem-solving **practice**.

## Features

### Planned Features

To give the user a good overview of the developer this portfolio should have a section showing the **educational history**, as well as a list of **technologies learned**. To get to know the developer as a person, an **about section** should be included as well as **social media links** and **contact information** for reachability and social proof. To further showcase the developers experience and body of work, a **portfolio section** of projects stating technologies used would deepen the understanding of the user.

### Features Implemented

- About section
- Technology skills
- Work experience
- Educational History
- Portfolio
- Contact section with Social Media links

### Features Left to Implement

 A personal **blog page** gives the developer a more personal and approachable note. Adding samples of coding work or short tutorials could be a way to contribute to the commnunity and shows the developers problem solving interest and invites other problem solving developers to discuss technology related topics.

## UX

### Design Choices and UX

The design goal of this page is to deliver a static website written in HTML and CSS only, with a simple HTML structure and CSS effects to catch the eye for both mobile and desktop users. The navigation should be simple and intuitive yet fun to use to browse each section of the site. 

The UX idea for this project is to make the different sections of the content instantly available without too much interaction with the navigation menu and to see the portfolio at a glance. Therefor this site is build as an one page experience where visitors can use gestures such as swiping on mobile, or scrolling on desktop to navigate through the site and consume the content quickly. 

The background should appear calm so that the user can focus on the content itself but should have some stylistic elements as well, to make the page memorizable such as a color theme or a specific font type. To further enhance the idea of immediate content access, a typical landing page is left out by choice. 



### Wireframes

A simple one page site to present content for instant consumption in desktop and mobile view. 

Below the wireframes you see little blocks that represents the 12 column **Bootstrap grid**. This helped to plan the layout of the page. The first three columns of the 12 column grid are left empty to create whitespace for a simplistic and calm appearance but as well reserves a place for future development such as a navigation menu for a blog page that may have a lot of topics to cover.

![wireframe-1](/assets/images/wireframe-1.png)

![wireframe-2](/assets/images/wireframe-2.png)



### UI Features

To give visitors more control and confidence using the site, a **top bar navigation** for desktop users and a subtle **animated modal view** for mobile users has been planned. As a personal goal I chose to code the **mobile navigation** with a [modal view](https://www.w3schools.com/cssref/tryit.asp?filename=trycss3_target_modal ) instead of using the predefined Bootstrap navigation to understand the possibilties and limitations of animation in CSS without JavaScript.

Testing if content fits within the planned areas with Lorem Ipsum text:

![proto-context-nocolor-1](/assets/images/proto-context-nocolor-1.png)

Further planning of the portfolio section:

![proto-context-nocolor-2](/assets/images/proto-context-nocolor-2.png)

Screenshots of the about and skills section with implemented color scheme:

![color-scheme-screenshot](/assets/images/color-scheme-screenshot.png)





## Technologies Used

This project is written in **HTML** and uses custom **CSS** for styling combined with **Bootstrap** grid elements. 
All of the custom code is partially written with the **Gitpod online editor** and **Visual Studio Code** on a personal **Mac** computer. This project uses **Git** for version control and is stored as a public repository at **GitHub**. Images are produced in **Photoshop** and composed using **Sketch**.

## Testing

### Testing of HTML and CSS
The HTML code has been tested with the [W3C validator](https://validator.w3.org/) without errors or any warnings. 

The CSS code has been tested with the [W3C Jigsaw validator](https://jigsaw.w3.org/) and it turned out that variables used in the CSS document as well as -webkit extensions are recognised as imported style sheets that are not checked in direct input or file upload mode of the validator. 

#### Validation by direct input

When passing the style.css document through direct input in the Jigsaw validator, the code seem to be alright except that all **color variables** are getting a warning by the validator although most browsers, except IE, are compatible with variables according to the [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties). The validator also throws an error for the `background-image: radial-gradient(var(--dot-color) 1px, transparent 0);` property where I used a color variable instead of a hex-color description. 

Further properties such as `scrollbar-width: none` throws an error although this property is supported by the [Firefox browser](https://developer.mozilla.org/en-US/docs/Web/CSS/scrollbar-width).

### Testing of the UI

**Google Chrome's Developer Tools** are used extensively for debugging as well as the built-in **Lighthouse** project to test the performance of this page. The responsive design has been tested using **Google Chrome's responsive feature** that emulates screen sizes of various mobile devices. Further testing has been conducted through available devices such as MacBook Pro 13", iPad 12" and iPhone 8. 

## Deployment

The repository of this project is stored at **GitHub** and the site is deployed as **GitHub page**. Please <a href="https://theodorcodes.github.io/milestone-project-1/" target="_blank">Click here!</a> to visit the project site.

## Credits

### Acknowledgements

This project is initiated by [Code Institute](https://codeinstitute.net/) to teach and mentor students on their journey to become a software developer.

This site uses the [Bootstrap](https://getbootstrap.com/) v5.0.0-beta2 release built by the [Bootstrap team](https://getbootstrap.com/docs/5.0/about/team/).
Icons that you see on this site are provided by [Feather](https://feathericons.com/), who provide simply beautiful open source icons.
Fonts are provided by the [Google Fonts](https://fonts.google.com/) library.


