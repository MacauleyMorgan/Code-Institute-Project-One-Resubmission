# Code Institute Project One Resubmission
 Resubmission attempt for CI Milestone 1

Crossfit website is a website designed for the public who would like to participate in exercise activities as part of a group and request guidance and tips from licensed professionals.
![Site Mockup](/assets/images/site-mockup.png "Site Mockup")
---
# User Stories
## First Time Visitor
As a first time user I want to understand what the website is about and develop awareness of the gym and the classes they offer.

As a first time user I want to be able to find my way through the website seamlessly to digest content.

As a first time user I want to display the website on any device and be eligible to read.

As a first time user I want to learn more about the trainers and how they may meet my needs.

## Returning User
As a returning user, I want to keep up to date with new staff members and specializations in the gym to ensure my needs are met.

As a returning user, I want to be able to contact the gym using a form to request to book sessions and see what sessions are offered

As a returning user, I want to see pricing information about memberships and what they may offer as part of the plans.

## Frequent User
As a frequent user, I want to check if any new classes have been added to sign up to the website

As a frequent user, I want to see if any trainers have joined or left the company and information about them.

As a frequent user I want to be able to repeatedly use a form to request contact and sign  up to events and classes.

---
# Features
## Site wide
### Nav
This menu contains links to the various pages in the site. Such as the home page, meet the PT page and also find a class page to allow the user to navigate between content.
    
    - As a first time user I want to be able to find my way through the website seamlessly to digest content.

![Navigation Bar](/assets/images/nav-bar.png "Navigation Bar")
### Footer
The footer contains a simple message to inform the user that the site was created for educational purposes only.

![Footer](/assets/images/footer.png "Footer")
### Favicon
The favicon will be displayed site wide and will contain the primary and secondary color of the website with the logo "CF" for the word CrossFit.

The favicon will allow the user to find the website with ease if they have multiple tabs open or are viewing with a limited/smaller screen size.
    
    - As a first time user I want to display the website on any device and be eligible to read.

![Favicon](/assets/images/favicon.png "Favicon")
### 404
The 404 page will be used to display a message that the page the user is looking for does not exist and allow them to navigate home in the event of a typing error.

![404 Page](/assets/images/404.png "404 Page")
### Lighthouse & Wave

![404 Lighthouse](/assets/images/lighthouse-404.png "404 Page lighthouse")

![404 Wave](/assets/images/wave-404.png "404 Page wave")

    - As a first time user I want to display the website on any device and be eligible to read.

## Landing Page
        
### Hero Image
The landing page of the website will incorporate a large hero image to grab the users attention and act as motivation.

    - As a first time user I want to understand what the website is about and develop awareness of the gym and the classes they offer.

### Pricing Cards
The landing page will have pricing cards immediately visible and display information about what the level of membership entails.
    
    - As a returning user, I want to see pricing information about memberships and what they may offer as part of the plans.

### Find a gym
The landing page will also contain a white portion below the pricing cards to indicate that it can be scrolled down to reveal some more content which will display the locations of the company premises.
### Image Attribution
The landing page will show the hero image attribution in the footer for information and accreditation purposes.

### Lighthouse & Wave

![Landing page Lighthouse](/assets/images/lighthouse-index.png "Landing page Page lighthouse")

![Landing page Wave](/assets/images/wave-index.png "Landing page Page wave")

## Meet The PT Page
### Personal trainer information
The PT page will display a list of staff that work within the company as well as images and skills they may have in the business to allow the user to identify which service best suits there needs.

    - As a returning user, I want to keep up to date with new staff members and specializations in the gym to ensure my needs are met.
    - As a frequent user, I want to see if any trainers have joined or left the company and information about them.

### Image Attribution
Image attribution on the page are listed as the following.
- https://www.freepik.com/free-photo/waist-up-portrait-handsome-serious-unshaven-male-keeps-hands-together-dressed-dark-blue-shirt-has-talk-with-interlocutor-stands-against-white-wall-self-confident-man-freelancer_10421502.htm#&position=2&from_view=search
- https://www.freepik.com/free-photo/side-view-woman-drinking-water_29301556.htm#query=personal%20trainer&position=5&from_view=search&track=robertav1_2_sidr
- https://www.freepik.com/free-photo/sports-man-spend-time-morning-gym_6424731.htm#query=personal%20trainer&position=1&from_view=search&track=robertav1_2_sidr

These images were saved locally and resized to 300x300px for scaling and responsiveness purposes.

### Lighthouse & Wave

![PT's Lighthouse](/assets/images/lighthouse-pts.png "PT's Page lighthouse")

![PT's Wave](/assets/images/wave-pts.png "PT's Page wave")

## Find a class page
### Class information table
The class information table will display a series of daily classes that the gym offers as service to its members along with times that the class is on. To request a place in the class the user is required to provide there information via the form below.

    - As a frequent user, I want to check if any new classes have been added to sign up to the website

### Contact Form
The contact form will allow users to request bookings for classes. It requires a first name and an email address as inputs and will not allow the user to submit information that does not match this criteria. After completion if the form the page will redirect you to a new page created inside the website to confirm the data has been sent and a prompt to return to the home page.

    - As a returning user, I want to be able to contact the gym using a form to request to book sessions and see what sessions are offered
    - As a frequent user I want to be able to repeatedly use a form to request contact and sign  up to events and classes.

### Form completion confirmation
The form completion page will thank the user for registering interest in one of the classes as a confirmation their input has been received. After this it will display a link to go back to the home page.

    - As a returning user, I want to be able to contact the gym using a form to request to book sessions and see what sessions are offered
    - As a frequent user I want to be able to repeatedly use a form to request contact and sign  up to events and classes.

### Lighthouse & Wave

![Find a class Lighthouse](/assets/images/lighthouse-classes.png "Find a class Page lighthouse")

![Find a class Wave](/assets/images/wave-classes.png "Find a class Page wave")

## Register Page
The register page allows a user to redirect to the index page without the use of window buttons via an anchor tag to return home.

The register page also allows the user to view a brief video tutorial via a youtube video to freshen up on exercise for beginners. Disclaimer: I do not own the content in the video and credit is given to the youtube channel 'Magnus Method' for the video which can be found by following this url.
https://www.youtube.com/watch?v=EKUNGQ4LmH8&t=2s

### Lighthouse & Wave

![register Lighthouse](/assets/images/lighthouse-register.png "register Page lighthouse")

![register Wave](/assets/images/wave-register.png "register Page wave")

---
# Existing Features
- Responsive design catered to 280px+

    - As a first time user I want to display the website on any device and be eligible to read. 

- Contact form and success page
- Existing personal trainer information
- Classes table
# Features left to implement
## Ecommerce section
- As a future enhancement to the website an e-commerce section can be added and linked to the pricing cards section allowing the user to purchase memberships online and a login page to have a personal account. 

- Another future enhancement to the website could be added by creating a form that the user inputs a postcode into and then it is used to find the closest gym.
---
# Design
## Wireframes
### Landing Page
![Landing Page Wireframe](/assets/images/index-wireframe.png "Home page wireframe")

![Landing Page Wireframe Breakpoint 1](/assets/images/index-bp1-wireframe.png "Home page wireframe breakpoint 1")

![Landing Page Wireframe Breakpoint 2](/assets/images/index-bp2-wireframe.png "Home page wireframe breakpoint 2")
### Meet the PT Page
![Meet the PT's Wireframe](/assets/images/meet-the-pts-wireframe.png "Meet the PT's Wireframe")

![Meet the PT's Wireframe Breakpoint 1](/assets/images/meet-the-pts-bp1-wireframe.png "Meet the PT's Wireframe breakpoint 1")

![Meet the PT's Wireframe Breakpoint 2](/assets/images/meet-the-pts-bp2-wireframe.png "Meet the PT's Wireframe breakpoint 2")

### Find a class page
![Find a Class Wireframe](/assets/images/find-a-class-wireframe.png "Find a Class Wireframe")

![Find a Class Wireframe Breakpoint 1](/assets/images/find-a-class-bp1-wireframe.png "Find a Class Wireframe breakpoint 1")

![Find a Class Wireframe Breakpoint 2](/assets/images/find-a-class-bp2-wireframe.png "Find a Class Wireframe breakpoint 2")

### 404 Page
Upon typing in an invalid link, a 404 page is returned by the website.
![404 Page](/assets/images/404.png "404 Page")
### Form confirmation
Upon completion of the form a confirmation screen will be displayed allowing the user to receive a confirmation that the input was recorded and the website has received a request to be contacted.

---
# Technology utilisation
## HTML
HTML was the main language used to create the structural design of the website.
## CSS
The website was styled using a collapsible style sheet (CSS) externally in the folder.
## Visual Studio Code
The website was developed using the Visual Studio Code IDE.
## Github
The source code for this website is hosted on Github.
## Git
Git was utilized in unison with github to push and commit to the repository of the source code.
## Favicon.io
This website was used to generate the favicon image then to download the image and use the file in the documents.
## balsamiq
Balsamiq was used to create wireframes for the website and create ideas of structure to work from.
## ChatGPT
Chat GPT was used to create generic text content for the site in the form of pt descriptions for the paragraph tags
## Youtube
A youtube link was included inside the register page in the form of an embedded link to the page which does not autoplay in line with marking criteria.

---
# Accessibility
## Wave extension
The wave extension was used to provide statistics based on the accessibility of the site. The wave extension purports 0 errors in contrast or structural accessibility.

## Lighthouse
The lighthouse extension was used to provide accessibility information when the site is loaded on chrome browsers.

# Functional Testing

![Functional testing](/assets/images/functional-testing.png "Functional Testing")

# Validation Testing
## HTML validator
The HTML files were placed into a HTML validator courtesy of W3 Schools and produced 0 errors in all files.
![index validation](/assets/images/index-validation.png "index validation")

![pts validation](/assets/images/pts-validation.png "pts validation")

![Class validation](/assets/images/classes-validation.png "Class validation")

![Register validation](/assets/images/register-validation.png "Register validation")

![404 validation](/assets/images/404-validation.png "404 validation")

## CSS Validator
The CSS files were placed into a CSS validator courtesy of W3 Schools and produced 0 errors in all files.

![CSS validation](/assets/images/css-validation.png "CSS validation")

# Version Control
The website was coded inside visual studio code and pushed to the github repository "ProjectOne".

The github desktop app was used in order to commit the files into the repository by adding the name of the commit followed by a short description of the change before pressing the "commit" button and pushing it to the repository.

## Github Pages

1. Adding it to Github Pages
2. To create the live link for the site, github pages was used in the following way.
3. Navigate to settings
4. Click on the Pages tab
5. Select the branch "main"
6. This will generate the link to the live site when created.
7. Click Save

The live site link can be found here [Live Site](https://macauleymorgan.github.io/Code-Institute-Project-One-Resubmission/ "Live Site")

## Cloning

1. Select the github repository to clone.
2. CLick on the code button to access the dropdown menu.
3. Download the file then open with IDE or copy Git URL from the HTTPS dialogue box.
4. Open the console window in the IDE of your choice. 
5. Use the 'git clone' command inside the terminal and follow the command with the url you wish to clone.
6. A clone of the project will be created locally on your machine.

# Credits
## Image Attribution
## Code Written
The code written in the HTML and CSS files are custom codes written by myself as the developer for submission of the project and are for personal development and educational purposes (with the exception of the GPT generated PT paragraphs specified earlier in technologies utilized part of Readme)

Project for a crossfit gym made for educational purposes to complete milestone project one for Code Institute.