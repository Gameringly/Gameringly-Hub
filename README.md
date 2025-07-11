# Gameringly Hub

[Gameringly Hub](https://gameringly.github.io/Gameringly-Hub/)

A portfolio of my various game development related projects with information about their status, links to downloads and social accounts related to them. Users can also request to join the development team of a projet through a form.  

<details>
<summary>Home page full screenshot</summary>
<br>
<img src="docs/home-page-full-screenshot.png">
</details>
<details>
<summary>Sonic projects page full screenshot</summary>
<br>
<img src="docs/sonic-page-full-screenshot.png">
</details>
<details>
<summary>Metroid projects page full screenshot</summary>
<br>
<img src="docs/metroid-page-full-screenshot.png">
</details>
<br>

Contents

- [Gameringly Hub](#gameringly-hub)
  * [Rationale](#rationale)
  * [User Goals](#user-goals)
  * [User Stories](#user-stories)
  * [Website Goals and Objectives](#website-goals-and-objectives)
  * [Target Audience](#target-audience)
  * [Wireframes](#wireframes)
  * [Design Choices](#design-choices)
    + [Typography](#typography)
    + [Colour Scheme](#colour-scheme)
    + [Images](#images)
    + [Responsiveness](#responsiveness)
  * [Features](#features)
    + [Existing Features](#existing-features)
      - [Nav bar](#nav-bar)
      - [Home page](#home-page)
      - [Footer](#footer)
    + [Project category pages](#project-category-pages)
    + [Future Enhancements](#future-enhancements)
  * [Technologies Used](#technologies-used)
    + [Languages](#languages)
    + [Libraries and Framework](#libraries-and-framework)
    + [Tools](#tools)
  * [Testing](#testing)
    + [Bugs](#bugs)
    + [Responsiveness Test](#responsiveness-test)
    + [Code Validation](#code-validation)
      - [HTML](#html)
      - [CSS](#css)
    + [User Story Testing](#user-story-testing)
    + [Feature Testing](#feature-testing)
    + [Accessibility Testing](#accessibility-testing)
    + [Lighthouse Testing](#lighthouse-testing)
    + [Browser Testing](#browser-testing)
  * [Deployment](#deployment)
    + [To deploy the project](#to-deploy-the-project)
    + [To fork the project](#to-fork-the-project)
    + [To clone the project](#to-clone-the-project)
  * [Credits](#credits)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

## Rationale

This website a catalogue of my various game development related projects that I've made in my free time. It offers general information about each project including what state of development they're in, links to any relevant social media accounts, Discord servers and downloads.

I often post about my projects on my Youtube account and dedicated social media accounts, however over time these posts and uploads become buried under new ones making them hard to find. There also isn't much overlap between the audiences of my different projects. I want to create this website to have a place where anyone can go at any time and easily be able to see all my different creations without the hassel of searching through social media accounts. I also want to try and find more talented artists to potentially join some of my projects development team.

To do this I have a home page that cleanly displays cards of various categories of my projects, for what they're based on and different audience groups. This immediately informs the users about all the differnt types of projects I've done and potentially peak their interest. These cards will have a direct link to the dedicated projects page for that category. These category pages will display all the vital information someone would want to know about a given project, a description of what its about, visuals of what it looks like, what its current development status is, any available download links, and links to the related social media accounts all in a compact easy to read layout. The navigation menu on all pages also allows for a quick way to flip through category pages, while the footer on all pages contains the link to every one of my social media accounts related to my projects making it a consistent place users can just scroll down to if they need to find one of them. The home page also has a form to encourage any interested users to consider joining the development of one of the projects, all they need to do is provide a username for contact, select a project and give a description of how they would like to help, making it a quick and easy process.

To start the website will just contain pages for my most popular and ambitious projects that the most amount of my viewers are interested in, but thanks to the design of the layout it will be easy to expand the number of category pages and number of projects on each page for my more niche projects. I could also potentially add new features such as displaying the ratings for projects uploaded to sites with user ratings.

By creating this website I can link it to the about sections of all my various accounts, so that anyone who finds and enjoys one of my projects can instantly get the information they're looking for about it, and also expose them to all my other projects that may also catch their attention. This means that I can potentially increase the audience for all of my projects to grow as a creator, and attracting more people means more potential talent to help with developemnt.

## User Goals

* Clearly laid out information
* Relevant social links are easy to find
* Able to provide information to join a project
* User friendly navigation

## User Stories

* As a user, I want to be able to find information on a project
* As a user, I want to find out where I can get updates on a project
* As a user, I want to ask to join a project
* As a user, I want navigation to be intuitive
* As a user, I want to be able to use the website on a variety of devices

## Website Goals and Objectives

* Attract the audience of one project to other projects
* Proivde easy access for users to obtain projects
* Increase the following of various social media accounts
* Find potential new team members for the projects
* Include projects of various interests

## Target Audience

* Online fan communities
* Existing fans of projects
* Casual viewers

## Wireframes

Wireframes designed using Balsamiq tool.

[Home Page](docs/home-page.png)

[Project Category Page](docs/project-category-page.png)

## Design Choices

### Typography

The font family that was chosen was [Lato](https://fonts.google.com/specimen/Lato?query=lato), a rounded sans-serif font. Lato is clean and easy to read making it suitable for general use in the website.

### Colour Scheme

Since the majority of my viewers are from my Sonic The Hedgehog fan projects I chose a cool blue colour palette for the website.
![Colour Palette](docs\blue-palette.png)
I used [Contrast Grid](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%2399D2EB%0D%0A%236564DB%0D%0A%23232ED1%0D%0A%23101D42%0D%0A%230D1317&es-color-form__tile-size=compact&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18&es-color-form__show-contrast=dnp) to see what colour combinations have good contrast for text.
![Contrast Grid](docs/contrast-grid.png)

### Images

All images used are either created by me or screenshots from my projects, with exception of the navbar image which is from the sonic adventure mod manager. The images used for the icons of the social media accounts and servers are the same as the actual profile pictures for those accounts.

### Responsiveness

The website is responsive with 3 different layouts for small, medium and large screens based on the breakpoints from bootstrap and by using media queries.

## Features

Website is easy to use and easy to navigate between pages, users can easily find information on any point of interest with relevant links placed to be immediately accessible and all social links are always available at the bottom of the pages. Images and videos can catch users attention and give them a quick way to see what a project is about without having to read the supporting text. This can draw users to check out the social links for more or to download the project for themselves. Users can also fill out a forum to request to join a project that they may be intersted in which can help find more people to join our development teams.

### Existing Features

#### Nav bar

The website has a row of nav tabs that line the top of the header, it has a dark image for its background that makes it stand out from the rest of the page, the tab for the current page is highlighted in a bold blue. On small screens this is replaced with a navbar toggle button that opens a panel with vertical navigation tabs, since scrolling can be much further on smaller devices, the button for opening the navigation panel stays at the top right of the screen so it can be accessed at any time.

<details>
<summary>Nav bar large screens</summary>
<br>
<img src="docs/navbar-large-screenshot.png">
</details>
<details>
<summary>Nav bar small screens</summary>
<br>
<img src="docs/navbar-small-screenshot.png">
</details>

#### Home page

The first section of the home page has cards for the project category pages, they have an image and the description from the page, they have buttons that take the user to the page so they don't have to scroll back to the navbar. On large and medium screens the cards are side by side, on small screens one card takes up the entire width.

<details>
<summary>Home cards large screens</summary>
<br>
<img src="docs/card-large-screenshot.png">
</details>
<details>
<summary>Home cards small screens</summary>
<br>
<img src="docs/card-small-screenshot.png">
</details>
<br>
  
The second section of the home page has a forum where users can submit a request to join one of the available projects, it asks for their twitter username, a choice of which project, and a message box for them to write what their skills are and what they would like to do.

<details>
<summary>Request form</summary>
<br>
<img src="docs/forum-screenshot.png">
</details>

#### Footer

The footer is consistent across pages with a dark background unique from the rest of the sections, it has the the links for all the different social media accounts and servers related to all the projects, which open in seperate tabs, so that users can browse through them from any page. It also has a contact email at the very bottom. There are 3 different screen size layouts for the social media accounts.

<details>
<summary>Footer large screens</summary>
<br>
<img src="docs/footer-large-screenshot.png">
</details>
<details>
<summary>Footer medium screens</summary>
<br>
<img src="docs/footer-medium-screenshot.png">
</details>
<details>
<summary>Footer small screens</summary>
<br>
<img src="docs/footer-small-top-screenshot.png">
<img src="docs/footer-small-bottom-screenshot.png">
</details>

### Project category pages

Both project category pages follow the same format. Each project gets its own section, on large screens the page is split into 2 halfs, the left half has a description of the project and links to related social media accounts for immediate access for users. The right side has a carousel of images of the project, an embedded youtube video if one exists for it, the development status of the project and a download link if one is available. For the second project on each page the arrangement is flipped with the description and links on the right side and the images and video on the left, this creates visual variety in the page. On medium and smaller screens the elements take up the full width of the page, with the images, video, status and download first and the description and links underneath.

<details>
<summary>Project category pages large screens</summary>
<br>
<img src="docs/project-large-screenshot.png">
<img src="docs/project-large-reverse-screenshot.png">
</details>
<details>
<summary>Project category pages small screens</summary>
<br>
<img src="docs/project-small-top-screenshot.png">
<img src="docs/project-small-bottom-screenshot.png">
</details>

### Future Enhancements

* Include more projects in categories including cancelled and on hiatus projects
* Add more project categories for more niche projects
* show ratings for applicable projects
* Add recuitment advertisements for hiring projects
* Create artwork for the website to make it more visually striking

## Technologies Used

### Languages

* [HTML](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

### Libraries and Framework

* [Google Fonts](https://fonts.google.com/)
* [Bootstrap](https://getbootstrap.com/)

### Tools

* [GitHub](https://github.com/)
* [Balsamiq](https://balsamiq.com/product/)
* [Coolors colour palette generator](https://coolors.co/)
* [Eight Shapes Contrast Grid](https://eightshapes.com/)
* [Markdown table generator](https://www.tablesgenerator.com/markdown_tables#)
* [W3C HTML Validation Service](https://validator.w3.org/)
* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
* [Wave accessibility tool](https://wave.webaim.org/)
* [TOC generator](https://ecotrust-canada.github.io/markdown-toc/)

## Testing

### Bugs

The website was thoroughly tested throughout the development process and three major bugs were encountered during development which were all fixed.

| Bug                                              | Status | Description                                                                                                                                 | Steps to resolve                                                                                                                                         |
|--------------------------------------------------|--------|---------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Active navbar tab not updating                   | Fixed  | On the metroid projects category page the navbar tabs wouldn't update which tab was active with it being stuck on the home tab being active | Wrong part of the navbar code was being edited was modifying the off canvas panel navbar instead of the main navbar                                      |
| Youtube videos not appearing                     | Fixed  | Youtube video iframes were not displaying on the page                                                                                       | instead of manually creating the iframe, right click the video on youtube and click "copy embed code", pasting that in will have the video load properly |
| Image carousel arrow buttons not changing colour | Fixed  | The arrows to manually scroll through images would not change colours with styling                                                          | by using the filter style rule instead I could change the arrows to a grey colour that was more visible on all the images                                |

### Responsiveness Test

To test responsiveness I used FireFox responsive design mode on the deployed version of the site to test a variety of different screen sizes. I tested to check the functionality, content placement and alignment of elements at different break points

| Size     | Device                     | Functionality | Placement | alignment|
| -------- | -------------------------- | ------------- | --------- | -------- |
|    sm    | Galaxy Note 20 Android 11  |    good       |   good    |   good   |
|    sm    | Galaxy S20 Android 11      |    good       |   good    |   good   |
|    md    | iPad IpadOS 14.7.1         |    good       |   good    |   good   |
|    md    | Kindle Fire HDX Linux      |    good       |   good    |   good   |
|    lg    | Laptop with HiDPI screen   |    good       |   good    |   good   |
|    xl    | 1080p Full HD Television   |    good       |   good    |   Bad    |

I found that I needed to adjust the margins and padding for the footer on xl screens and made those changes

### Code Validation

#### HTML

I have used [W3C HTML Validation Service](https://validator.w3.org/nu/#textarea) to test all 3 pages, and they all came back with no errors

Home Page:
![Home page html validation](docs/home-html-validation.png)

Sonic Projects Page:
![Sonic fan projects html validation](docs/sonic-html-validation.png)

Metroid Projects Page:
![Metroid romhack projects html validation](docs/metroid-html-validation.png)

#### CSS

I have used [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/validator#css) to test the CSS code and it has returned no errors, only 1 warning that imported style sheets are not checked in direct input and file upload modes

![CSS validation](docs/css-validation.png)

### User Story Testing

| User Story                                                              | Result                                                                                                  | Pass |
|-------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|------|
| As a user, I want to be able to find information on a project           | Information is clearly laid out and easy to find                                                        | yes  |
| As a user, I want to find out where I can get updates on a project      | Related social media account links are immediately accessible                                           | yes  |
| As a user, I want to ask to join a project                              | Request to join form available and contact email provided                                               | yes  |
| As a user, I want navigation to be intuitive                            | Navigation tabs clearly labelled, extra buttons on home page cards to also take users to project pages  | yes  |
| As a user, I want to be able to use the website on a variety of devices | Website is functional on all devices                                                                    | yes  |

### Feature Testing

The website has been manually tested for functionality and the results put in this table
![Feature testing table](docs/feature-testing-table.png)

### Accessibility Testing

To test accessibilty I used [WAVE tool](https://wave.webaim.org/report#/https://gameringly.github.io/Gameringly-Hub/index.html) and returned no errors for all pages.

![wave accessobility test](docs/wave-home-screenshot.png)

### Lighthouse Testing

The website performance has been tested with Lighthouse testing tool, it showed that the website takes a while to load, this could be improved by optimsing the file size of all the images.

Desktop test
![Lighthouse desktop test](docs/lighthouse-desktop.png)
Mobile test
![Lighthouse mobile test](docs/lighthouse-mobile.png)

### Browser Testing

The website was tested for bugs and issues on multiple browsers including Firefox, Google Chrome and Microsoft Edge. No issues were found in any of the browsers and the website functioned as expected.

|         | desktop | mobile |
|---------|---------|--------|
| Chrome  | Pass    | Pass   |
| Firefox | Pass    | Pass   |
| Edge    | Pass    | Pass   |

## Deployment

### To deploy the project

The website was deployed as soon as the index.html file was created with these steps:

* Navigate to the repository on GitHub and click on the settings tab.
* In the side menu, under the Code and automation section click on pages.
* In the Branch section click the dropdown that says None and choose Main.
* Click on the Save button.
* The website is now live at [https://gameringly.github.io/Gameringly-Hub/](https://gameringly.github.io/Gameringly-Hub/).

### To fork the project

Forking the GitHub repository will allow you to create a duplicate of the repository and website. This means you can make changes to the copy without affecting the original repository.

* Open the repository on Github
* Click the fork button which is to the right of the repository name
* Give it a new name and then press the create fork button

### To clone the project

Cloning the repository will create a local copy on your computer that you can use to make and sync changes to the repository

* Open the repository on Github
* Click on the green Code button
* Copy the URL for the repository.
* Open your local IDE.
* Select the location where you want the directory to be cloned to.
* Type git clone, and then paste the URL you copied earlier.
* Press Enter to create your local clone.

## Credits

* Feedback, support and advice:
    * [Simen Daehlin](https://github.com/Eventyret)

* README formatting inspiration:
    * [Indre-V](https://github.com/Indre-V/animation-quiz?tab=readme-ov-file#credits)

* Navbar Image:
    * [Sonic Adventure Mod Manager](https://gamebanana.com/tools/15436)

* Sonic The Hedgehog is owned by [SEGA](https://www.sega.com/homepage)
* Metroid is owned by [Nintendo](https://www.nintendo.com/en-gb/)
