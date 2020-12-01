<img src="assets/uxd/logo/onlyhikerslogo.png" alt="site logo" title="Only Hikers Logo" width="75" height="75">

## Table of Contents:

* [Project Overview](#project-overview)
* [User Experience](#user-experience)
    * [Project Goals](#project-goals)
    * [User Stories](#user-stories)
    * [Design](#design)
        * [1. Font](#1-font)
        * [2. Color Scheme](#2-color-scheme)
        * [3. Logo](#3-logo)
        * [4. Wireframing](#5-wireframing)
* [Features](#features)
    * [Existing Features](#existing-features)
    * [Features Left to Implement](#features-left-to-implement)
* [Technology Used](#technology-used)
    * [Languages Used](#languages-used)
    * [Frameworks Libraries & Programs Used](#frameworks-libraries-and-programs-used)
* [Testing](#testing)
* [Deployment](#deployment)
    * [Initial Creation](#initial-creation)
    * [Deployment via GitHub](#deployment-via-github)
    * [Local Deployment](#local-deployment)
* [Credits](#credits)
    * [Special Thanks & Acknowledgements](#special-thanks--acknowledgements)

***



# Project Overview

##  Only Hikers     


***

A live verson of my site can be found <a href="https://shielh.github.io/Only-Hikers-MS1/">here</a>.

This milestone project is my first ever solo coding project where I aim to showcase the skills learnt thus far.
This project is a static front-end site built using HTML and CSS in conjunction with the Bootstrap Framework to create a responsive, mobile-first approach webpage.

Travel and hiking have always been two huge passions of mine so the idea for this project came about throughout lockdown this year when I was restricted 
from travelling anywhere overseas. I began to explore and discover hikes and trails in Ireland that are some of the most beauitful I have ever seen. 
After all these hikes, I had so many beautiful photos of Ireland and nowhere to showcase them. A picture is worth a thousand words, right?

My goal for this site is to inspire and spread the word about hiking in Ireland and how anyone can do it.

## Responsive site

Using the website <a href="http://ami.responsivedesign.is/">Am I Responsive</a>, I got the below image showing what the site looks like across all devices.

 ![Website Mockup](assets/uxd/mockup/am-i-responsive-mockup.PNG)
## User Experience

#### Project Goals

- To build a fully responsive website across all devices 
- To create an easy-to-use website that is simple to navigate
- To set up the basic layout and content for this webpage which can be added to in the future
- To inspire users through images of breathtaking scenery to get out and explore our beauitful country
- To have a contact form where like-minded hiking individuals or people that are keen to start can get in touch  
 
#### User Stories

* As a user, I want a website that is easy to navigate so I can access all of the information without any challenges
* As a user who is new to hiking, I want to be able to find a contact form quickly in order to get in touch with all my questions
* As a user who enjoys the great outdoors, I want lots of visually pleasing images that capture the beauty of Ireland
* As a user living in Ireland, I want ideas for my next hiking getaway 
* As a user who tends to use their mobile more than desktop, I want a webpage that is fully responsive across all devices 

## Design
### 1. Font
I used <a href="https://fontpair.co/">Font Pair</a> to choose the two main fonts for my website which are
 <a href="https://fonts.google.com/specimen/Roboto">'Roboto'</a> and <a href="https://fonts.google.com/specimen/Nunito"> 'Nunito'.</a>
 I'll use Roboto for the headings of the site and Nunito for the body, both of which are easy to read for the users.

### 2. Color Scheme
I used <a href="https://colorhunt.co/palette/">Color Hunt</a> to pick the colors for my website. I wanted to pick earthy tones to tie in with the concept of nature and hiking. 
The colors are as follows from top to bottom:

 - #D9E4DD
 - #FBF7F0  
 - #CDC9C3
 - #555555

<h1 align="left">
    <img src="assets/uxd/colorScheme/colorHuntPalette.png" alt="color palette" title="Color Palette" width="600" height="400">
</h1>


- I used #3f3f3c across the borders of the site as it gave more of a contrast than #555555 and it matched perfectly with the darkest colour of the logo.

### 3. Logo

I used <a href="https://www.freelogodesign.org/">Free Logo Design</a> , a free website to make my logo for my website. 
I entered the name of the site, "Only Hikers", and then selected the "Environmental & Green" category which gave me a 
multitude of logos to choose from. I chose the logo that I found most visually pleasing and also one with a transparent 
background so it could fit into any header color of my choosing.

<h1 align="left">
    <img src="assets/uxd/logo/onlyhikerslogo.png" alt="site logo" title="Only Hikers Logo" width="150" height="150">
</h1>


### 4. Wireframing

I used <a href="https://balsamiq.com/">Balsamiq</a> to create rough wireframes for my project in order to plan out the layout of the webpage on both desktop and mobile devices.
* Large device Wireframe for Home Page. Alternatively you can view the wireframe here : [Landing Page Desktop](assets/uxd/balsamiqWireframe/LandingPageDesktop.png)
 and [Landing Page Mobile](assets/uxd/balsamiqWireframe/LandingPageMobile.png)
<h1 align="left">
    <img src="assets/uxd/balsamiqWireframe/LandingPageDesktop.png" alt="wireframe1" title="Landing Page Wireframe" width="500" height="500">
    <img src="assets/uxd/balsamiqWireframe/LandingPageMobile.png" alt="mobilew wireframe1" title="Mobile Landing Page Wireframe" width="200" height="400">
</h1>

* Large device Wireframe for Gallery Page. Alternatively you can view the wireframe here : [Gallery Page Desktop](assets/uxd/balsamiqWireframe/GalleryPageDesktop.png) 
and [Gallery Page Mobile](assets/uxd/balsamiqWireframe/GalleryPageMobile.png)
<h1 align="left">
    <img src="assets/uxd/balsamiqWireframe/GalleryPageDesktop.png" alt="wireframe2" title="Gallery Page Wireframe" width="500" height="500">
    <img src="assets/uxd/balsamiqWireframe/GalleryPageMobile.png" alt="mobile wireframe2" title="Mobile Gallery Page Wireframe" width="500" height="700">
</h1>

* Large device Wireframe for Contact Page. Alternatively you can view the wireframe here : [Contact Page Desktop](assets/uxd/balsamiqWireframe/GalleryPageDesktop.png) 
and [Contact Page Mobile](assets/uxd/balsamiqWireframe/ContactPageMobile.png)
<h1 align="left">
    <img src="assets/uxd/balsamiqWireframe/ContactPageDesktop.png" alt="wireframe3" title="Contact Page Wireframe" width="500" height="500">
    <img src="assets/uxd/balsamiqWireframe/ContactPageMobile.png" alt="mobile wireframe3" title="Mobile Contact Page Wireframe" width="200" height="400">
</h1>

## Features
### Existing Features
This project consists of three pages.

### Features found on all three:
- Headers are fixed across all devices and contain the logo with an anchor tag to the home page and the navbar has anchor tags to their corresponding pages. 
- Headers on mobile devices contain the navbar in the form of a hamburger menu to use the screen space more efficiently.
- Footers across all devices contain the sites logo with an anchor tag to the home page with all relevant social media icons linked to the relevant sites. The footer also has a link to the contact
page and contains the address and phone number of the website.

### Features unique to Home Page:
- Large hero-image spanning across entire width of the page with a "Subscribe" modal button inside
- Modal contains a name input box, an email input box and a submit button
- A text area with a quote on hiking inside
- An image of the OnlyHikers page owners
- Text area with brief introduction on the owners and what the page is about

### Features unique to Gallery Page:
- 6 thumbnail images for 3 different hikes, making a total of 18 images

### Features unique to Contact Page:
- Large image under the navbar with text inside
- Contact form with three different inputs, 'Name', 'Email Address' and 'Message' and a submit button underneath

 
### Features Left to Implement
- Events page where users can book into hikes as spaces will be limited due to health and safety
- Expand on gallery and implement bootstraps carousel component for a nice slideshow efficiently
- Introduce a blog page and enable commenting on blogs and gallery to better connect users and open up the site to discussions

## Technologies Used

### Languages Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5) - I used HTML as the main language for structuring the content
- [CSS3](https://en.wikipedia.org/wiki/CSS) - I used CSS as the primary language for styling the sites content

### Frameworks Libraries and Programs Used

- [Bootstrap](https://getbootstrap.com/) <br>
Used to help in the design and layout of the website in conjunction with HTML and CSS
- [Font Awesome](https://fontawesome.com/) <br>
I used the icons from this site for the social media anchor tags in the footer
- [Balsamiq](https://balsamiq.com/) <br>
I used this to create my rough wireframes
- [Google Fonts](https://fonts.google.com/) <br>
I used Google Fonts to import my two fonts for this site, Roboto and Nunito
- [Color Hunt](https://colorhunt.co/)<br>
I found the palette of colours I would use for my site here
- [GitHub](https://github.com/) <br>
This is the hosting site where I first created the repository for this webpage and also where the live site is deployed from 
- [Git](https://git-scm.com/) <br>
This is the version control software used where can I commit and push the updated information to the hosting website GitHub
- [Free Logo Design](https://www.freelogodesign.org/) <br>
I created my free logo here for my site
- [Font Pair](https://fontpair.co/) <br>
I chose my two complementary fonts for my webpage here
- [Tiny JPG](https://tinyjpg.com/) <br>
I used this to compress my images
- [Paint 3D](https://www.microsoft.com/en-us/p/paint-3d/9nblggh5fv99?activetab=pivot:overviewtab) <br>
I used this progran to crop my site logo while still maintaing the clear background
- [Rapid Tables](https://www.rapidtables.com/convert/color/hex-to-rgb.html)
I used this to convert my dark green colour to rgb to use for the slightly transparent jumbotron and contact form background

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment
### Initial Creation
Only Hikers was first created by completing the following steps on GitHub:
1. Open [Github](https://github.com/) page up in browser
2. Log in using your username and password
3. Click the "New" green button to the left-hand side repository section
4. Click template dropdown menu and select the "Code Institute Full Template"
5. Enter name of project "Only-Hikers-MS1"
6. Click "Create repository"
7. Click the green "Gitpod" button ONCE to redirect to the Gitpod workspace
8. Open via [Gitpod Workspaces](https://gitpod.io/workspaces/) only from then on

Throughout development, three primary commands were used with the CLI [Git](https://git-scm.com/) and were as follows :

- "git add" followed by the file name you wish to stage or "git add ." stages all unstaged files
- "git commit -m" followed by a detailed comprehensive comment pertaining to the changes made since the previous commit
- "git push" makes all changes visible on the GitHub Repo

### Deployment via GitHub
1. Open [Github](https://github.com/) page up in browser
2. Log in using your username and password
3. Select "shielh/Only-Hikers-MS1" from repositories displayed on left-hand side of screen
4. Click "settings", the last option displayed in the navigation menu
5. Scroll down until you reach "GitHub Pages" section
6. Select "Master Branch" in the dropdown under the Source heading
7. Finally, click to confirm my selection
8. A live version of Only Hikers is now live on Github [here](https://shielh.github.io/Only-Hikers-MS1/)

### Local Deployment
1. Open up "shielh/Only-Hikers-MS1 on GitHub as previously described in steps 1-3 above
2. Click the "Code" button with the download icon beside it (beside the green GitPod button) 
3. Copy the url visible underneath "https://github.com/shielh/Only-Hikers-MS1.git"
4. Using your preferred IDE, type the command "git clone" followed by the above url
5. A clone of your project will be created on your device 

## Credits

### Content
- The text for the quote section was taken from  [The Globe Trotter](https://thesologlobetrotter.com/hiking-quotes/)
- The CSS styling for the hero image and the image on the contact page was taken from [Laura Lee Flores Blog](https://www.lauraleeflores.com/blog/header-image-sizing-guide)
- The modal component on the home page and the form section were both taken from [Bootstrap's Components](https://getbootstrap.com/docs/4.5/components/modal/)
- I used [Stack Overflow](https://stackoverflow.com/questions/37814508/order-columns-through-bootstrap4) to learn about how to order columns differently across various devices
- I got inspiration from [CSS Tricks](https://css-tricks.com/examples/hrs/) on how to style my horizontal rule 
- I watched this [Youtube Video](https://www.youtube.com/watch?v=V_lAhqLXT9A) to brush up on everything I had learnt about combining HTML, CSS and Bootstrap to create a fully responsive website

### Media
- I took all the images used across this webpage so I didn't need to obtain permissions from anyone

### Acknowledgements

- A big thank you to my mentor Rohit Sharma for his help and guidance through my first project
- Thanks to everyone in the Slack community especially my September onboarding channel where my peers were always quick to respond to any questions I had
- Thanks to my sister for going on all these hikes with me throughout this crazy pandemic year, keeping us sane 


