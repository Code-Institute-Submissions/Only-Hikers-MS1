<img src="assets/uxd/logo/onlyhikerslogo.png" alt="site logo" title="Only Hikers Logo" width="200" height="112">

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
    1. [Responsive across devices](#responsive-across-devices)
    2. [HTML and CSS Validator Tests](#html-and-css-validator-tests)]
    3. [Navigation links](#navigation-links)
    4. [Modal Component](#modal-component)
    5. [Contact Form](#contact-form)
    6. [Hover Transitions](#hover-transitions)
    7. [Lighthouse Tool](#lighthouse-tool)
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

 * #D9E4DD
 * #FBF7F0  
 * #CDC9C3
 * #555555

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
    <img src="assets/uxd/logo/onlyhikerslogo.png" alt="site logo" title="Only Hikers Logo" width="200" height="112">
</h1>


### 4. Wireframing

I used <a href="https://balsamiq.com/">Balsamiq</a> to create rough wireframes for my project in order to plan out the layout of the webpage on both desktop and mobile devices.
* Large device Wireframe for Home Page. Alternatively you can view the wireframe here : [Landing Page Desktop](assets/uxd/balsamiqWireframe/LandingPageDesktop.png)
 and [Landing Page Mobile](assets/uxd/balsamiqWireframe/LandingPageMobile.png)
<h1 align="left">
    <img src="assets/uxd/balsamiqWireframe/LandingPageDesktop.png" alt="wireframe1" title="Landing Page Wireframe" width="600" height="1050">
    <img src="assets/uxd/balsamiqWireframe/LandingPageMobile.png" alt="mobilew wireframe1" title="Mobile Landing Page Wireframe" width="350" height="900">
</h1>

* Large device Wireframe for Gallery Page. Alternatively you can view the wireframe here : [Gallery Page Desktop](assets/uxd/balsamiqWireframe/GalleryPageDesktop.png) 
and [Gallery Page Mobile](assets/uxd/balsamiqWireframe/GalleryPageMobile.png)
<h1 align="left">
    <img src="assets/uxd/balsamiqWireframe/GalleryPageDesktop.png" alt="wireframe2" title="Gallery Page Wireframe" width="600" height="1250">
    <img src="assets/uxd/balsamiqWireframe/GalleryPageMobile.png" alt="mobile wireframe2" title="Mobile Gallery Page Wireframe" width="1000" height="1300">
</h1>

* Large device Wireframe for Contact Page. Alternatively you can view the wireframe here : [Contact Page Desktop](assets/uxd/balsamiqWireframe/GalleryPageDesktop.png) 
and [Contact Page Mobile](assets/uxd/balsamiqWireframe/ContactPageMobile.png)
<h1 align="left">
    <img src="assets/uxd/balsamiqWireframe/ContactPageDesktop.png" alt="wireframe3" title="Contact Page Wireframe" width="500" height="1000">
    <img src="assets/uxd/balsamiqWireframe/ContactPageMobile.png" alt="mobile wireframe3" title="Mobile Contact Page Wireframe" width="367" height="855">
</h1>

## Features
### Existing Features
This project consists of three pages.

### Features found on all three:
* Headers are fixed across all devices and contain the logo with an anchor tag to the home page and the navbar has anchor tags to their corresponding pages. 
* Headers on mobile devices contain the navbar in the form of a hamburger menu to use the screen space more efficiently.

See below the difference between desktop and mobile view:
<br>
<img src="assets/images/testing/header-desktop.PNG" alt="header desktop" title="header desktop" width="667" height="78">
<br>
<img src="assets/images/testing/header-mobile.PNG" alt="header mobile" title="header mobile" width="363" height="88">
<br>
<img src="assets/images/testing/header-mobile-alt.PNG" alt="head mobile dropdown" title="header mobile dropdown" width="363" height="206">
* Footers across all devices contain the sites logo with an anchor tag to the home page and a link to the contact page .
On desktop view, social media icons are located on the right side of the footer and are linked to the relevant social media sites opening a new tab when clicked. 
The footer also contains the address and phone number of the website located on the left of the footer.

See below the difference between desktop and mobile view:
<br>
<img src="assets/images/testing/footer-desktop.PNG" alt="footer desktop view" title="footer desktop" width="945" height="123">
<br>
<img src="assets/images/testing/footer-mobile.PNG" alt="footer mobile view" title="footer mobile" width="363" height="320">

### Features unique to Home Page:
- Large hero-image spanning across entire width of the page with a "Subscribe" modal button inside
- Modal contains a name input box, an email input box and a submit button
- A text area with a quote on hiking inside
- An image of the OnlyHikers page owners
- Text area with brief introduction on the owners and what the page is about

### Features unique to Gallery Page:
- 6 thumbnail images for 3 different hikes, making a total of 18 images
- On mobile devices, all 18 images appear vertically with one per row to make the image a better size for the viewer
- On mobile devices, there is a link "click to top of page" to bring the user to the top of the page rather than scrolling the whole way up

### Features unique to Contact Page:
- Large image under the navbar with text inside
- Contact form with three different inputs, 'Name', 'Email Address' and 'Message' and a submit button underneath

 
### Features Left to Implement
- Events page where users can book into hikes as spaces will be limited due to health and safety
- Expand on gallery and implement bootstraps carousel component for a nice slideshow efficiently
- Introduce a blog page and enable commenting on blogs and gallery to better connect users and open up the site to discussions
- Set up the Back End script so that the subscription modal and contact form are sent for processing

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

The aim of this testing section is to:
1. Ensure that my site is fully responsive across all devices ranging from mobile (<576px) to large desktop screens (>1200px) and across different browsers including Chrome, Safari, Mozilla and Opera.  
2. Perform tests on the HTML and CSS code through their respective validators. 
3. Test each navigation link on the webpage to make sure it brings you to the correct page including social links
4. Test the modal subscription component to ensure it opens up the subscription form across all devices on index.html page
5. Ensure the form component on the Contact page is functioning properly requiring both inputs to be in the correct format before submit button will work
6. Check hovering over the site logo, nav-items in the header, "contact" and "gallery" in About Us section on index.html and site logo, "contact us", 
telephone number and social icons have the appropriate response
7. Run DevTools Lighthouse across all pages of the site in both mobile and desktop versions

*** 

1. 
### Responsive across devices
- I checked the site across [Google Chrome](https://www.google.com/intl/en_ie/chrome/), [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/), [Safari](https://www.apple.com/safari/) 
and [Opera](https://www.opera.com/) and all were completely responsive with all pages viewing with layout remaining intact.
- Using [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools), (to open I right-clicked anywhere on my website and clicked "Inspect"), I ran my site in mobile/tablet display 
across the following devices: Galaxy Note 3, Galaxy S III, Moto G4, iPhone 4, Galaxy S5, Pixel 2, Pixel 2 XL, iPhone 5/SE, iPhone 6/7/8, iPhone 6/7/8 Plus, iPhone X, iPad, iPad Pro. Everything 
ran normally on these devices.

***

2.  
### HTML and CSS Validator Tests
* W3C HTML Validator
    - I opened [W3C HTML Validator](https://validator.w3.org/) and selected the "Validate by Direct Input" option and pasted index.html, gallery.html and contact.html all in separately.
    - I removed the h5 elements as a child element of the label. I removed p-0 from the inline style for h4. I removed the space between the "tel:" and the "555" and finally I matched the aria-describedly 
with its appropriate ID element. 
    - I ran the code through [W3C HTML Validator](https://validator.w3.org/) again and got the following message "Document checking completed. No errors or warnings to show."
    
    All pages initally came up with the following errors:


<img src="assets/images/testing/html-validator-error.PNG" alt="html errors" title="HTML Errors" width="1549" height="445">



* Similarly, I ran the code through the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) 
    - I selected the "by Direct Input" option 
    - I received the message "Congratulations! No Error Found." 

***

3. 
### Navigation links

#### Navigation links on all three pages
* Site logo 
    - Can be found at top left of navbar and in the center of the footer on each of the three pages
    - When clicked on any of the pages at either position (header and footer), it redirects to index.html page or stays on index.html if that is the page you clicked it on but it refreshes the page
* Home Nav Item
    - Visible on navbar across all three pages
    - Visible on mobile devices once you click the hambruger icon dropdown menu
    - Click it and it redirects you to index.html (except from index.html which will refresh page)
* Gallery Nav Item
    - Visible on navbar across all three pages
    - Visible on mobile devices once you click the hambruger icon dropdown menu
    - Click it and it redirects you to gallery.html (except from gallery.html which will refresh page)
* Contact Nav Item
    - Visible on navbar across all three pages
    - Visible on mobile devices once you click the hambruger icon dropdown menu
    - Click it and it redirects you to contact.html (except from contact.html which will refresh page)
* Phone Number anchor tag
    - Visible in the footer across mobile and desktop 
    - Click the phone number and it will promt you to pick and application to make the call on 
* Contact Us
    - Visible in the footer across mobile and desktop
    - Click it and it redirects you to contact.html (except from contact.html which will refresh page)
* Social Media links
    - Visible in the footer across mobile and desktop
    - Click each icon on each of the three pages
    - Social sites open in a new tab
    - Each social icon brings you to the correct social media site

#### Navigation links on index.html
* "contact us" in "ABOUT US" section
    - Go to index.html page
    - Scroll to "ABOUT US" section
    - Click the "contact us" text with a heavier font-weight than the surrounding text
    - It will redirect you to the contact.html page
* "gallery" in "ABOUT US" section
    - Go to index.html page
    - Scroll to "ABOUT US" section
    - Click the "gallery" text with a heavier font-weight than the surrounding text
    - It will redirect you to the gallery.html page

#### Navigation links on gallery.html
* "Click to top of page" link at the bottom of gallery.html page on mobile device
    - Go to gallery.html page
    - Scroll down the page to the bottom of the images
    - Click the link "Click to top of page"
    - You are brought to the top of the gallery.html page

***

4. 
### Modal Component
* Check modal component on desktop
    - Go to to index.html page
    - Click the "SUBSCRIBE!" button
    - Attempt to submit the empty form to confirm that an error message appears for the empty input box
    - Attempt to submit the form with an email missing the "@" symbol
    - Attempt to sumbit the form with all inputs correctly filled in to confirm page reloads once submitted
* Check modal component on mobile
    - Repeat the above steps on a mobile device

***
5. 
### Contact Form 
* Contact form on contact.html
    - Go to the contact.html page
    - Attempt to submit the empty form to confirm that an error message appears for the empty input box
    - Attempt to submit the form with an email missing the "@" symbol to confirm appropriate error message appears
    - Attempt to sumbit the form with all inputs correctly filled in
    - Attempt to sumbit the form with all inputs correctly filled in to confirm page reloads once submitted

***

6. 
### Hover Transitions
* Test hover elements found across all three pages
    - Open the index.html, gallery.html and contact.html pages and test the following on each page:
        - In the header and footer, hover over the site logo to observe the logo enlarge
        - In the header, hover over the navbar items "Home", "Gallery" and "Contact" to observe each individually get bigger
        - In the footer, hover over the "Contact us" anchor tag and observe the colour change from #FBF7F0 to #799e82
        - In the footer, hover over the social media icons and observe both the icons grow and the colour change from #FBF7F0 to #799e82
        - In the footer, hover over the telepohone number and observe the colour change from #FBF7F0 to #799e82
* Test hover elements found on index.html and contact.html
    - Open the index.html and contact.html pages and test the following on each page:
        - Hover over the respective "SUBSCRIBE" and "SUBMIT button on each page and observe the button reverse font colour to background colour
* Test hover elements found on index.html
    - Open index.html
        - Hover over the "contact us" and "gallery" text in the "ABOUT US" section and observe the font colour change from #383737 to #799e82

***

7. 
### Lighthouse Tool
<br>
In Lighthouse, scores from 90-100(green) are considered good, scores from 50-89(orange) needs improvement and below 50(red) are considered poor. 

* On desktops:
    - Open each page, right-click and click "Inspect"
    - Click "Lighthouse" on the top right of the DevTools navbar
    - Ensure "Desktop" is ticked and click "Generate Report"
        - index.html: Scored 97 in "Performance", 94 in "Accessibility" and 100 in "Best Practises"
        - gallery.html: Scored 98 in "Performance", 97 in "Accessibility" and 100 in "Best Practises"
        - contact.html: Scored 99 in "Performance", 96 in "Accessibility" and 100 in "Best Practises"
* On mobile devices:
    - Open each page, right-click and click "Inspect"
    - Click "Lighthouse" on the top right of the DevTools navbar
    - Ensure "Mobile" is ticked and click "Generate Report"
        - index.html: Scored 83 in "Performance", 95 in "Accessibility" and 93 in "Best Practises"
        - gallery.html: Scored 95 in "Performance", 95 in "Accessibility" and 93 in "Best Practises"
        - contact.html: Scored 91 in "Performance", 96 in "Accessibility" and 93 in "Best Practises"

### Issues and Solutions
* My index.html Lighthouse score for performace was 83 which falls in the "needs improvement" category. I tried compressing the hero image further to 
help reduce the "Lowest Contentful Paint" time but it didn't make much of a difference. I tried resizing the image to have a mobile version and then 
used a media query to have a larger version of the image for desktop view. Again, this didn't make much of a difference however it did move the score up 
from 72 to 83. I made the decision to not waste any more time on this issue and to leave as is and to make note for future reference.
* Throughout the development, I came across a bug where lots of Pinterest icons were hidden in the background of the footer making the height of the 
footer much larger than it needed to be. I discover there was an unclosed "a tag" which was causing this issue.


In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:




You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here

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

- A big thank you to my mentor Rohit Sharma for his help and guidance throughout my first project
- Thanks to everyone in the Slack community especially my September onboarding channel where my peers were always quick to respond to any questions I had
- Thanks to my sister for going on all these hikes with me throughout this crazy pandemic year, keeping us sane 


