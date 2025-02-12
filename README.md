﻿# Rxguestudio
Rxgue studio was created for a barbershop based in the center of Worcester city, it has a strong instagram and tiktok profile but no website.
The owner is looking to simplify there booking process and have something more professional then just social media.

![Rxgue studio website show over a range of devices](<responsive 600px.png>)

[Rxgue studio website](rxgue studio website shown on a range of devices)

## USER EXPERIANCE (UX)

### Initial Discussion

Rxgue studio would like to reach out to potential new clients with a website. They are looking to make a better customer experiance and bring in new business.
They would also like there booking system online instead of people having to call or text message the barbers

### Key information for the website.

* The ethos of the shop
* Being able to book in
* Opening hours
* Locaion
* Gallery of images showing the skill level of haircut they offer

### USER STORIES

#### Owner goals
* To be able to view the site on various devices
* To add ease of access to booking
* User friendly
* Allow customers to see services and prices

#### FIRST TIME CUSTOMER GOALS
* I want to find out what rxgue studio offers
* I want to be able to navigate the site easilly to find information
* I want to be able to find social media for the shop
* I want to be able to book a haircut or shave
* I want to know where the shop is

#### RETURNING CUSTOMERS
* I want to book online instead of calling the shop
* I want to fine current and up to date pricing
* I want to be able to easilly follow the shop on social media for hair inspiration ideas

## DESIGN

### Colour Scheme
![a image of jet gray, black and white smoke as a pallete](<rxgue color palette.png>)

This website uses a pallete of; black, dark grey and off white. the shop has a bright but certain asthetic they wish to maintain.
The colour palette was created using the [Coolors](https://coolors.co/) website.

### TYPOGRAPHY

i have used googlefonts and inter, its a sans serif font.<br>
![Image of inter font](image.png)

### Imagery

All imagery used within the Gallery is of the shop or taken within the shop.
The hero image has been used from (https://www.pexels.com/)
(https://cloudinary.com/) for changing to webp file

# WIREFRAMES

## wireframes for laptop, tablet, and mobile.

### Laptop
![home page for rxgue](<laptop home.jpg>)
![gallery page for rxgue](<laptop gallery.jpg>)
![booking page for rxgue](<laptop booking.jpg>)

### Tablet
![home page for rxgue](<tablet 600.jpg>) 
![gallery page for rxgue](<tablet  gallery.jpg>) 
![booking page for rxgue](<tablet booking 600.jpg>)

### Mobile
![mobile home](<mobile home.jpg>) 
![mobile gallery](<mobile gallery.jpg>) 
![mobile booking](<mobile booking.jpg>)

## FEATURES
the website has a homepage, gallery and booking page.
![alt text](<site map 700.png>)

### Genral features on each page
* A favicon in the browser tab
![screenshot of favicon](<assets/images/readme images/favicon screenshot.png>)

* all pages to have a rouge 'R' to the left and nav bar links on the right
![header for laptop](<header laptop.png>) ![header on anything smaller](<header smaller.png>)

* a footer to show social media links, rxgue studio has Facebook, X (twitter), Youtube and Instagram
![footer for website](<footer 600.png>)


* Home page
* To show a image of the shop and its asthetic
* A why us section showing why the customer would want to chose this shop
* Opening hours
* image of amap showing location
* Pricing
* contact information 

* gallery
* Images of products and recent haircuts

* Booking
* To send a booking for of name/email/service

### FUTURE IMPLEMENTATIONS
* link the website to a booking database to help save customers details
* create a log-in for customers 
* show live calender availibility with email confirmation
* intergrate a platform called booksy for a sleek booking experiance

### ACCESSIBILITY
* I have used alt attributes on images
* I have used a hover state on buttons to make it clear if they are being hovered over
* I have used semantic HTML. 
* I have made sure there is colour contrast on the site. 

## TECHNOLOGYS USED

### languages
* html 5
* css 3

frameworks
* [Figma](https://www.figma.com/) - Used to create wireframes.
* [Git](https://git-scm.com/) - For version control.
* [Github](https://github.com/) - To save and store the files for the website.
* [visual studio](https://code.visualstudio.com/) - IDE used to create the site.
* [Google Fonts](https://fonts.google.com/) - To import the fonts used on the website.
* [Favicon.io](https://favicon.io/) To create favicon.
* [Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on a range of devices.
* [Google Developer Tools](https://developers.google.com/web/tools) - To troubleshoot and test features, solve issues with responsiveness and styling.
* [pexels](https://www.pexels.com/) - for hero image
* [cloudinary](https://cloudinary.com/) - for image conversion to webp
* [lucid](https://www.lucidchart.com/) - for site map diagram
* [w3c validation](https://www.w3.org/) - for validating code

## Deployment & Local Development

### Deployment

Github Pages was used to deploy the live website. The instructions to achieve this are below:

1. Log in to Github.
2. Find the repository for this project, rxguestudioprojectfinal.
3. Click on the Settings button.
4. Click on the Pages button in the left hand side bar.
5. In the Source section, choose main from the drop down select branch menu. Select Root from the drop down select folder menu.
6. Click Save. Your live Github Pages site is now deployed at the URL shown.

### Local Development

The local development section gives instructions on how someone else could make a copy of your project to play with on their local machine. This section will get more complex in the later projects, and can be a great reference to yourself if you forget how to do this.

#### How to Fork

To fork waggytaillodge repository:

1. Log in to Github.
2. Go to the repository for this project, danielkepinski/rxguestudioprojectfinal
3. Click the Fork button at the top of the page between Watch and Starred.

## Testing

Testing has been on going throughout the build with Chrome developer tools.

My mentor on our mid project meeting discussed: 
* My hero image even though i had changed file type to something smaller it was still too big so resized the image and website ran better
* not over complicating my code and creating errors beacuse of code 'fighting' each other
* also recomended not using a iframe and using a picture of a map instead
* my mentor also showed me lighthouse with he used to explain why my page wa smaybe a little slow
![lighthouse score](<lighthouse score.png>)


### w3c Validator
I used w3c validator to check and validate all my pages on for my website. This was also used to validate my CSS in style.css file

*i had some errors due to extra tags and ">" that had found themselves stray in the code. this have been corrected
![screenshot with erros](<index with error.png>) - showing it had errors
![the errors](<the errors.png>) - the errors to be fixed
![passed](index.png) - passed!
![css pass](css.png) - css passed

### Solved bugs
1. i couldnt get the copyright to sit nicely in the footer, because i had it inside the list. put in its own div and was then able to be sytled to where i wanted it
2. had a issue were on laptop cover text on image floated around on smaller devices, spoke to client and he preffered it without

### Known bugs
i cant adjust map to be same size as pricelist or services list, this is something to work on!


### Testing user stories
* I want to find out what rxgue studio offers
    * a services list is highlighted on home page
* I want to be able to navigate the site easilly to find information
    * site navigation is clear at top of the page and open where the mouse clicks
    ![shows website header](<header laptop.png>)
* I want to be able to find social media for the shop
    * ![footer for website](<footer 600.png>)
* I want to be able to book a haircut or shave
    * ![booking button](<book now screen.png>)
* I want to know where the shop is
    * ![map of location of the shop](maprxgue.png)

### RETURNING CUSTOMERS
* I want to book online instead of calling the shop
    * ![booking button](<book now screen.png>)
* I want to fine current and up to date pricing

* I want to be able to easilly follow the shop on social media for hair inspiration ideas
    * ![alt text](<assets/images/readme images/footer 600.png>)