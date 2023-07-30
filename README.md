# Hickman's Hideaway
Hickman's Hideaway is a fictional family-owned restaurant located in the heart of a picturesque seaside town. Our mission is to provide a warm and inviting atmosphere where guests can savor delicious dishes made from locally sourced, fresh ingredients.
The purpose of this website is to introduce visitors to our restaurant, showcase our menu, share our story, and provide a seamless online reservation experience.

The Hickman's Hideaway site is currently live, the link can be found [Here](https://sam92uk.github.io/Hickmans-Hideaway/index.html)

## Table of Contents
+ [UX](#ux "UX")
  + [Site Purpose](#site-purpose "Site Purpose")
  + [Site Goal](#site-goal "Site Goal")
  + [Audience](#audience "Audience")
  + [Communication](#communication "Communication")
  + [Current User Goals](#current-user-goals "Current User Goals")
  + [New User Goals](#new-user-goals "New User Goals")
+ [Design](#design "Design")
  + [Colour Scheme](#colour-scheme "Colour Scheme")
  + [Typography](#typography "Typography")
  + [Imagery](#imagery "Imagery")
+ [Features](#features "Features")
  + [Existing Features](#existing-features "Existing Features")
  + [Future Features](#future-features "Future Features")
+ [Testing](#testing "Testing")
  + [Validator Testing](#validator-testing "Validator Testing")
  + [Unfixed Bugs](#unfixed-bugs "Unfixed Bugs")
+ [Technologies Used](#technologies-used "Technologies Used")
  + [Main Languages Used](#main-languages-used "Main Languages Used")
  + [Frameworks, Libraries & Programs Used](#frameworks-libraries-programs-used "Frameworks, Libraries & Programs Used")
+ [Deployment](#deployment "Deployment")
+ [Credits](#credits "Credits")
  + [Content](#content "Content")
  + [Media](#media "Media")

## UX

### Site Purpose:
To introduce visitors to our restaurant, showcase our menu, share our story, and provide a seamless online reservation experience.

### Site Goal:
To update our current users with new menu changes, the location of the restaurant and allow reservations to be made online. 

### Audience:
Anyone looking for a relaxing meal by the sea who enjoy good food with locally sourced, fresh ingredients. Our target market are women & men ages 20 - 45.

### Communication:
Each page has a clear design with the information easily available to anyone who visits the site. Each page in the navbar is underlined so that the user knows which page they are currently on. The address & opening times are available in the footer of each page and when in mobile view they become available in the contacts page. 

### Current User Goals:
- To see the current menu available.
- To allow easy booking online.

### New User Goals:
- Allow easy navigation through the website & clearly understand the information provided.
- For all information to be up to date & relevant.

## Design

### Colour Scheme:
This colour palette was used with the thought of colours to match the seaside without feeling overwhelming. The main background & header colour is slate gray with federal blue text which mix well and do not overwhelm the user. The use of a subtle baby powder white was used when hovering over the nav links in the header and social links in the footer.

![Colour Palette](/assets/images/read-me/colour-palette.png)

### Typography:
Courgette Cursive was used for the main logo and the headings on each of the pages as it is a stylish and decorative font that has visually appealing qualities. Josefin Sans Normal is used for all over text as it is simple and delicate along with being easy to read.

### Imagery:
All of the imagery on the website was sourced from free stock photo platforms. The hero image on the home page was chosen so the user new this was a relaxing and warm location to go for a meal by the seaside. Each additional image added was to support the overall theme of the site, and to remind the user that the restaurant is all about a relaxed and warm atmosphere with good food.

## Features

### Existing Features
#### Navigation Bar:
The navigation bar is located on each of the 3 pages, and allows for easy navigation across the Home, Menu & Contact page. The page which the user is currently on will be underlined so they know which page they are on.

![Navigation Bar](/assets/images/read-me/nav-bar.png)

#### Home Page:
The home page defines the overall feel of the website, and provides the user with an image that they can associate with the restaurant and it's location.

![Home Hero Image](/assets/images/hero/home.jpg)

Below the hero image is a welcome message to greet the user and provide a more detailed description of the restaurant. This will allow the user to know what they have to look forward to when they book a table.

![Welcome Message](/assets/images/read-me/welcome-message.png)

#### Menu Page:
The hero image is the first thing the user will see and it gives an idea of the standard and quality of the food. 

![Menu Hero Image](/assets/images/hero/menu.jpg)

Below the menu hero image is the menu list with the main meals, each meal has an image for a visual representation along with a detailed description of what to expect.

![Menu Items](/assets/images/read-me/menu-items.png)

#### Contact Page:
The contact page contains a hero image to follow consistency of the other pages and it has the warm welcoming feel to it so people know that they will booking somewhere nice. 

![Contact Hero Image](/assets/images/hero/booking.jpg)

The page then goes straight to a message showing that bookings are available with the contact number and email just below to encourage users to want to book. Just below this message will be a form for an online reservation and a google map showing the location and for a quick view of how far the user may need to travel. This encourages the user to stay on the website and not have to google themselves to find out the distance.

![Booking Form](/assets/images/read-me/form-map.png)

#### Footer:
The footer is consistant over all of the pages and has the address, opening times and social links included on them so the user is always reminded of what times the restaurant is open, where it is located and can also check social links for some more iamges of the restaurant. 

![Footer](/assets/images/read-me/footer.png)

### Future Features
- Live chatbot.
- Venue page for large parties/groups.
- Interactive menu.
- Event calender for special events.
- Customer reviews section.

## Testing
A horizontal scroll bar was appearing on the Menu and Contact page after changing hero images to fill the width of the screen and object-fit. After changing multiple attributes in the styles.css file i found that the div was spilling over slightly causing it to push out of the screen to the right. I found a fix for this on a forum called Squarespace which fixed the issue by adding overflow-x:hidden; to the HTML and Body.

The form and map on the contact page appeared to be overlapping when in mobile view after making some changes to try and fix the issue with the horizontal scroll bar. This was resolved by adding the contact-column class back into the divs which was removed to see if that was causing the scroll bar issue.

### Validator Testing
- HTML files passed the [W3C Validator](https://validator.w3.org/) with no errors found.
![W3C Message](/assets/images/read-me/html-validator.png)

- HTML files passed the [Jigsaw Validator](https://jigsaw.w3.org/css-validator/) with 16 errors found but these were from Bootstrap that i have used throughout the website.
![Jigsaw Message](/assets/images/read-me/css-validator.png)

- Website has an excellent Accessibility rating in Lighthouse.
![Accessibility Score](/assets/images/read-me/lighthouse-score.png)

- Tested the website works in Chrome, Brave & Edge without issues.
- All links open to an external page as intended.

### Unfixed Bugs
None found.

## Technologies Used
### Main Languages Used
- HTML
- CSS

### Frameworks, Libraries & Programs Used
- Bootstrap 4.5.3 was used to assit with the responsiveness and layout of the website.
- Google Fonts was used for the font families: Courgette Cursive, Josefin Sans Normal. Sans sarif used as the default font.
- GitHub used to store my repository.
- Am I Responsive? was used to ensure all pages were responsive and looked good over all devices.
- Code Anywhere was used to build my code before pushing to GitHub.
- Balsamiq was used to create Wireframes of my website.

## Deployment
The site was deployed to GiHub pages. The steps to deploy are as follows:

- In the GitHub repository, navigate to the Settings tab
- Under the Code and automation heading, select Pages
- From the Branch drop-down menu, select main
- Once the main branch has been selected and saved, the page will refresh and display a message to indicate the successful deployment
- The live link can be found [Here](https://sam92uk.github.io/Hickmans-Hideaway/index.html)

## Credit
### Code
- ![Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/): Bootstrap Library used throughout the project to keep the pages responsive and to help with the layout.

### Content
I took a lot of my inspiration from a previous website i had put together for a small course i did. I then adapted the content to suit my personal idea and implemented Bootstrap from the Mini Project in Code Institutes course to help get the layout exactly how i wanted it and to make the website responsive over all devices.

When i ran into the issue of a horizontal bar on my Menu & Contact page i tried a multitude of changes to fix this issue but ultimatly turned to google where i found a fix on ![Squarespace](https://forum.squarespace.com/topic/165148-unwanted-vertical-white-stripe-on-the-right/).

### Media
- 