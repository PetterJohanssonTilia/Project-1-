
<div align="center">
  <img src="./assets/readme/images/different-screens.png" alt="Home Page">
</div>

<h1>Angry neighbors</h1>
This is a HTML/CSS only portfolio-project. <br>
The website is designed to be a satire-news site with the focus on bad neighbors. The website also allows for users to upload their own photos and share their real world neighbor stories. The goal is to make the website fun. You'll either laugh at the satire articles or laugh/symphatise with other people that don't have the best of neighbors.<br><br>

The design is stylized in a cartoonish way to emphasize the light-heartedness of the website and to prevent it from becoming a place meant to promote actual hate of your neighbors.

## Table of Contents
1. <details open>
    <summary><a href="#ux">UX</a></summary>

    <ul>
    <li><details>
    <summary><a href="#goals">Goals</a></summary>

    - [Visitor Goals](#visitor-goals)
    - [Business Goals](#business-goals)
    - [User Stories](#user-stories)
    </details></li>

    <li><details>
    <summary><a href="#visual-design">Visual Design</a></summary>

    - [Wireframes](#wireframes)
    - [Fonts](#fonts)
    - [Icons](#icons)
    - [Colors](#colors)
    - [Images](#images)
    - [Styling](#styling)
    </details></li>
    </ul>
</details>

2. <details open>
    <summary><a href="#features">Features</a></summary>

    <ul>
    <li><details>
    <summary><a href="#page-elements">Page Elements</a></summary>

    - [All Pages](#all-pages)
    - [Index Page](#index-page)
    - [Gallery Page](#gallery-page)
    - [Contact Page](#contact-page)
    </details></li>

    <li><details>
    <summary><a href="#additional-features">Additional Features</a></summary>

    - [Image Loading Blur](#image-loading-blur)
    - [Email](#email)
    </details></li>

    <li><details>
    <summary><a href="#feature-ideas">Feature Ideas</a></summary>
    - [Basic](#basic)
    - [Content](#content)
    </details></li>
    </ul>
</details>

3. <details open>
    <summary><a href="#technologies-used">Technologies Used</a></summary>

    - [Languages](#languages)
    - [Frameworks](#frameworks)
    - [Libraries](#libraries)
    - [APIs](#apis)
    - [Platforms](#platforms)
    - [Other Tools](#other-tools)
</details>

4. <details open>
    <summary><a href="#testing">Testing</a></summary>

    <ul>
    <li><details>
    <summary><a href="#methods">Methods</a></summary>
    - [Validation](#validation)
    - [General Testing](#general-testing)
    - [Mobile Testing](#mobile-testing)
    - [Desktop Testing](#desktop-testing)
    </details></li>

    <li><details>
    <summary><a href="#bugs">Bugs</a></summary>

    - [Known Bugs](#known-bugs)
    - [Fixed Bugs](#fixed-bugs)
    </details></li>
    </ul>
</details>

5. <details open>
    <summary><a href="#deployment">Deployment</a></summary>

    <ul>
    <li><details>
    <summary><a href="#local-deployment">Local Deployment</a></summary>
    - [Local Preparation](#local-preparation)
    - [Local Instructions](#local-instructions)
    </details></li>

    <li><details>
    <summary><a href="#github-deployment">Github Deployment</a></summary>
    - [Github Preparation](#github-preparation)
    - [Github Instructions](#github-instructions)
    </details></li>
    </ul>
</details>

6. <details open>
    <summary><a href="#credit-and-contact">Credit and Contact</a></summary>
    
    - [Content](#content)
    - [Contact](#contact)
</details>

----

# UX
## Goals
### Visitor Goals
The target audience for Angry Neighors are:
- People who want read satire articles.
- People who are interested in other peoples stories and photos.
- People that want to share their stories and  photos.

User goals are:
- View and submit photos.
- Read and submit stories.
- Read the articles.

Horizon Photography fills these needs by:
- Putting the articles and a big colorful heropicture on the front page, capturing the users interest
- letting the users navigate easily through the site
- making the site very simple with little distractions

### User Stories

1. As a user interested in laughing at other peoples missery, I expect to see real world stories.
0. As a user I'd like to be able to share my own stories
0. If I were interested in submiting a story, I expect to know where.
0. I would like to view the gallery images on any device
0. I expect to be able to follow the company through social media.

## Visual Design
### Wireframes
Wireframes: <a href="./assets/readme/wireframes/Wireframes.pdf">Wireframes</a>
<img src="./assets/readme/images/wireframes.png" alt="Wireframes">

### Fonts
<div align="center">
  <img src="./assets/readme/images/Fonts.JPG" alt="Fonts">
</div>
- The primary font, [Pridi](https://fonts.google.com/specimen/Pridi?query=pridi) was chosen because it is big, bold and a bit cartoonish. It looks friendly and playful. It is also sans-serif, making it very easily readable throughout different color schemes
- The secondary font, [Pontano](https://fonts.google.com/specimen/Pontano+Sans?query=pontano) was chosen because it is thin, and plain. As a font, it gave me the impression of writing in word or a type writer. That is why it was chosen as the font for the user stories, making them look more serious and real compared to the satire on the front page

### Icons
<div align="center">
  <img src="./assets/readme/images/Icons.JPG" alt="Icons">
</div>

- Icons are taken from the [Fontawesome](https://fontawesome.com/) Icon library and are utilised as classes in the `<i>` tag.
- As they are utilised as classes, they can easily be styled using other classes or IDs in the same tag.
- Icons are utilised in the footer for social account icons.

### Colors
<div align="center">
  <img src="./assets/readme/images/colorpalette.png" alt="Color Pallette">
</div>

- I wanted the site to look friendly, cartoonish and light hearted
- The primary color used is the deep blue. This is used to create a stark contrast with the colors of the other elements on the page, drawing the eyes and focus on them.
- One accent color was chosen, the dark yellow, to give a feeling of "warning", reminiscing of a stop signal to showcase that this is a site of satirical complaints.
- Text is primarily written in white to contrast on the bold color backgrounds of the primary and accent colors.

### Images
<div align="center">
  <img src="./assets/readme/images/gallery.JPG" alt="Gallery Images">
</div>

- The site has little focus on the images and therefore doesn't display them front and center
- As such, the images are displayed all jumbled together to showcase more of a collage for the user to explore

### Styling
- For this project I used flexbox to make it more responsive and for it's ease of use. Instead of tables, grids and floats
- I used a has function for the "anger scale" buttons to indicate they've been selected
----

# Features
## Page Elements
### All Pages
#### Navbar
<div align="center">
  <img src="./assets/readme/images/navbar.png" alt="Two navbars">
</div>

- The Navbar is simple, providing four options.
- The Logo is always highlighted, swapping position as necessary depending on device size.
- On smaller devices, the menu becomes collapsible.
- The mobile nav button has been placed to the right for ease of use with one hand.
- The navbar is fixed so it is visible no matter how far you scroll.

#### Footer
<div align="center">
  <img src="./assets/readme/images/Icons.JPG" alt="Footer">
</div>

- Located at the bottom of every page, only highlighting social sites.
- Changing shape for larger or smaller devices.

### Index Page
#### Jumbotron Image
- Used as a splash image that highlights a cartoonish neighborhood at night
- An image with a mountain in the middle that stays in the center of the screen on all devices
----

# Technologies Used
## Languages
- [HTML](w3.org/standards/webdesign/htmlcss)
    * Page markup.
- [CSS](w3.org/standards/webdesign/htmlcss)
    * Styling.

## Frameworks
- [Bootstrap4](https://getbootstrap.com/)
    * Used for basic styles and outline.

## Libraries

- [Google Fonts](https://fonts.google.com)
    * Font Styles.
- [Fontawesome](https://fontawesome.com/)
    * Used for icons

## Platforms
- [Github](https://github.com/)
    * Storing code remotely and deployment.
- [Gitpod](https://gitpod.io/)
    * IDE for project development.

## Other Tools
- [Figma](https://figma.com/)
    * To create wireframes.
- [Favicon Generator](https://www.favicon-generator.org/)
    * Favicons
- [Colorhunt](https://colorhunt.co/)
    * Creating color pallettes.

----

# Testing
## Methods
### Validation
- HTML has been validated with [W3C HTML5 Validator](https://validator.w3.org/).
- HTML has been validated with [Wave.webaim HTML5 Validator](https://wave.webaim.org/).
- CSS has been validated with [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) and auto-prefixed with [CSS Autoprefixer](https://autoprefixer.github.io/).
- Links checked with [W3C Link Checker](https://validator.w3.org/checklink).

| Problems     | Index       | Gallery  | Stories | Submit stories|
| ------------- |:-------------:| -----------:| --------:| -------:|
|      |<img src="assets/readme/validator/index.PNG" style=" height: 100px;">| <img src="assets/readme/validator/gallery.PNG" style=" height: 100px;">| <img src="assets/readme/validator/stories.PNG" style=" height: 100px;">|<img src="assets/readme/validator/submitstories.PNG" style=" height: 100px;">| pic|
| Warnings      | right-aligned | $1600| pic| Section lacks heading.|
| Bugs | hello| hello| hello| hello|

### General Testing
- Each time a feature was added, all the functions were tested to see if there was an impact.
- The site was sent to friends for feedback and testing.
- All forms have validation and will not submit without the proper information.
- .gitignore file has been included to prevent system file commits.
- External links open in a new tab.

### Mobile Testing
- I tested the site personally on my Android device, going through the entire process, checking buttons, functions, checking out, etc. I was personally unable to test on iOS.
- The site was sent to friends and relatives for them to follow the same process. They have tested on their devices, including iOS.
- Chrome was utilised to inspect the site in mobile format, going through the pages and functions.

### Desktop Testing
- the majority of testing occurred on Chrome and Edge
- The site was tested by friends and relatives on numerous desktop devices.
- Internet Explorer was not tested and the site was not developed with it in mind as support for the browser is gradually being dropped.

## Bugs
### Known Bugs
- wave.webaim.org validator reports empty labels while using the Fontawesome i elements
- wave.webaim.org validator thinks Home button has adjacent links with the same url

### Fixed Bugs
- Post method on the form not working Issue:https://github.com/PetterJohanssonTilia/Project-1-/issues/1
- CSS validator error - https://github.com/PetterJohanssonTilia/Project-1-/issues/2
- Wrong sizing of objects through different screens
-  Wrong sizing of text through different screens

----

# Deployment
## Local Deployment
### Local Preparation
**Requirements:**
-A webbrowser of your choice, Chrome being recommended

### Local Instructions
1. Download a copy of the project repository [here](https://github.com/PetterJohanssonTilia/Project-1-/archive/refs/heads/main.zip) and extract the zip file
2. Open the index.html file in your browser, This file can be dragged and droped into your browser to open it.
3. Enjoy the site!

## Github Deployment
### Github Preparation
- It is possible to copy or clone the repository to directly for deployment,
**Requirements:**
- A free GitHub account.
- A free EmailJS account.

### Github Instructions
1. Log in to your GitHub account.
navigate to [https://github.com/PetterJohanssonTilia/Project-1-](https://github.com/PetterJohanssonTilia/Project-1-).
1. You can set up your own repository and copy or clone it, or you fork the repository.
2. `git add`, `git commit` and `git push` to a GitHub repository, if necessary.
3. GitHub pages will update from the Main branch by default.
4. Go to the **Settings** page of the repository.
5. Scroll down to the **Github Pages** section.
7. Select the Main Branch as the source and **Confirm** the selection.
8. Wait a minute or two and it should be live for viewing.

## Credits and Contact
### Content
Nearly all text content was generated by the AI, GPT-2, at [Talk to Transformer](https://talktotransformer.com/).
**(So there will be plenty of grammar or spelling errors or even a bit of nonsense, but I thought it would be a fun addition to the project)88 
Any code utilised from a site is documented and credited within the code.
All photographs, authors, license rights, copyright, etc. used in this project can be found [here](https://unsplash.com/collections/8825126/used-in-horizon-photo). No credit is required from Unsplash,  
All other media used is my own.

### Contact
Please feel free to contact me at `Petter.johansson@outlook.com`