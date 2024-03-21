
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
1. As a user interested in satire news, I expect to see lots of different articles on up to date topics.
0. I expect the Gallery to be updated with photos from all around the world
0. As a user interested in laughing at other peoples missery, I expect to see real world stories
0. I expect to be able to follow the company through social media.
0. I would like to view the gallery images on any device
0. If I were interested in submiting a story, I expect to know where.

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
- For this project I have utilised Bootstrap 4.5 source files to override their class defaults to my liking, making customisation much easier. The entire site can be restyled with a single switch in the code.
- The primary and secondary colors have been applied to bootstrap classes for easy use across the site.
- Using the SASS, sharp-edged boxes have been applied by default, taking advantage of the features.
- Responsive text sizing has also been enabled using SASS.
- As the site has a beeline focus on use, links on each page are re-used to direct the user to either the Gallery or the Contact page no matter where they look.
- Animations are utilised for smoothness in certain transitions, such as when a new country is selected in the gallery or on the Travel Gallery link.

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
- CSS has been validated with [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) and auto-prefixed with [CSS Autoprefixer](https://autoprefixer.github.io/).
- Links checked with [W3C Link Checker](https://validator.w3.org/checklink).
- Each javascript file was tested on the site for errors and functionality using the console and with [JSHint](https://jshint.com/).

### General Testing
- Each feature was developed and tested in its own branch before being merged with master. Branches were subsequently deleted.
- Each time a feature was added, all the functions were tested to see if there was an impact.
- The site was sent to friends for feedback and testing.
- All forms have validation and will not submit without the proper information.
- .gitignore file has been included to prevent system file commits.
- The image loading blur has been thoroughly tested and gone through numerous iterations to optimise the smoothness of the transition on different devices and internet speeds.
- Backup Map functions have been tested in a local deployment.
- Email error functions have been tested offline as well.
- External links open in a new tab.

### Mobile Testing
- I tested the site personally on my Android device, going through the entire process, checking buttons, functions, checking out, etc. I was personally unable to test on iOS.
- The site was sent to friends and relatives for them to follow the same process. They have tested on their devices, including iOS.
- Chrome was utilised to inspect the site in mobile format, going through the pages and functions.

### Desktop Testing
- The site was developed on a Chromebook and, as such, the majority of testing occurred on Chrome.
- The site was tested by friends and relatives on numerous desktop devices.
- The site was marginally tested on other browsers, such as Firefox and Edge.
- Internet Explorer was not tested and the site was not developed with it in mind as support for the browser is gradually being dropped.

## Bugs
### Known Bugs
- Occasionally on a device with low RAM, the Google Maps API won't load.
- Devices with low RAM may have stuttered animations.
- Offline, using the backup map, the images don't switch the first time the page loads. No errors are shown on the console. A refresh usually solves the issue.
- Very slow connections may have users see the thumbnails pop in during iframe loading, rather than having the switch occur during the animation.

### Fixed Bugs
- Jumbotron image wouldn't de-blur. Fixed by adding a custom class for selection and differentiation.
- Markers wouldn't load if the connection to the API was slow. Fixed by adding a backup array to be used as a fall-back.
- EmailJS wasn't allowing newsletters to be sent on the contact page. Fixed by giving each form a separate ID.
- The map info window wouldn't dispose of itself but would open multiple instances, one over the other. Fixed by moving the initialisation instance outside of the click function.
- The info window would concatenate one country's information with another after clicked. Fixed by clearing the info window content on each click before populating it with info.
- If a country had multiple first languages, the info window would have a display that clipped them as they were stored in an array themselves. Fixed by writing a custom function to deal with languages.
- All map markers would bounce if they had animations set to active. Fixed by looping through the markers and setting them to no animation before activating the clicked marker's animation.
- The modal for images in the gallery wouldn't open because of the blur function. Fixed by changing the HTML structure on the page and the iframe.
- One I added SASS, many of the site's display features were broken. Fixed by cleaning up the CSS files and removing clashing styles.

----

# Deployment
## Local Deployment
### Local Preparation
**Requirements:**
- An IDE of your choice, such as [Visual Studio Code](https://code.visualstudio.com/)
- [Git](https://git-scm.com/)
- You will have to set up a connection with an email server through EmailJS:
- You will have to install SASS to compile the CSS. This depends on your system and your method choice. Please see the instructions [here](https://sass-lang.com/install).

### Local Instructions
1. Download a copy of the project repository [here](https://github.com/Ri-Dearg/neverlost-thrift/archive/master.zip) and extract the zip file to your base folder. Or you can clone the repository with:
    ```
    git clone https://github.com/Ri-Dearg/neverlost-thrift
    ```
    To disconnect it from the master repository, use:
    ```
    git remote rm origin
    ```
2. Open your IDE and choose the base directory.
3. Here you can install SASS with npm, if you choose, with:
    ```
    npm install -g sass
    ```
4. Run the compiler with:
    ```
    sass --watch assets/css/bootstrap_sass:assets/css
    ```
    This will also watch the bootstrap_sass folder for changes and re-compile the CSS when they are made. This way you can make changes quickly and not worry about re-compiling.
6. Switch the user token for EmailJS with your own. It can be found in the head tag:
    ```
    (function () {
        emailjs.init("<your user token>");
    })();
    ```
5. Run the project with your chosen method. You can drop index.html into a web browser and it should run fine, open a local port and access it or, if you have python installed, run it on an HTTP server with python with a command such as:
    ```
    python3 -m http.server
    ```
6. Enjoy the site!

## Github Deployment
### Github Preparation
- It is possible to copy or clone the repository to directly for deployment, but you will have to compile the make sure the SCSS compiles correctly first. Github Pages' Jekyll themes support this but you will have to make some customisations. Details can be found [here](https://jekyllrb.com/docs/assets/).
**Requirements:**
- A free GitHub account.
- A free EmailJS account.

### Github Instructions
1. Log in to your GitHub account.
navigate to [https://github.com/Ri-Dearg/neverlost-thrift](https://github.com/Ri-Dearg/neverlost-thrift).
1. You can set up your own repository and copy or clone it, or you fork the repository.
2. `git add`, `git commit` and `git push` to a GitHub repository, if necessary.
3. GitHub pages will update from the master branch by default.
4. Go to the **Settings** page of the repository.
5. Scroll down to the **Github Pages** section.
7. Select the Master Branch as the source and **Confirm** the selection.
8. Wait a minute or two and it should be live for viewing. See my own [here](https://ri-dearg.github.io/horizon-photo/).

## Credits and Contact
### Content
Nearly all text content was generated by the AI, GPT-2, at [Talk to Transformer](https://talktotransformer.com/).
**(So there will be plenty of grammar or spelling errors or even a bit of nonsense, but I thought it would be a fun addition to the project)88 
Any code utilised from a site is documented and credited within the code.
All photographs, authors, license rights, copyright, etc. used in this project can be found [here](https://unsplash.com/collections/8825126/used-in-horizon-photo). No credit is required from Unsplash,  
All other media used is my own.

### Contact
Please feel free to contact me at `sheridan.rp@gmail.com`