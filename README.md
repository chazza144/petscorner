# Pets Corner
Stream One Project: User-Centric Frontend Development - Code Institute 

This is my child friendly website advertising and providing information for Pets Corner, a farm in Harlow, Essex. The site covers general information about the farm, the prices regarding venue hire and information on how to become a volunteer, including a contact form. 


## Demo
Github link [here](https://chazza144.github.io/petscorner/)


## UX
My goal in the design was to be child friendly and easily legible. I wanted to include lots of pictures to showcase the animals at the farm and the surrounding park. 
I decided on the sky blue background and white foreground to represent a sunny day with white fluffy clouds, which I think gives it a friendly welcoming colour scheme. 
I also wanted to keep the design simple and clean and to not overcrowd the information users are searching for. 

During my research I discovered a lot of children’s sites, and farm sites, had large buttons/hyperlink images to navigate the sites so I wanted to include the same on my Pets Corner design. I believe the buttons are clear and it’s easy to select what you’re looking for. 
As the buttons would take up too much real estate on smaller screens, I decided to hide them completely and instead have a collapsible navbar next to the Pets Corner title for mobile/tablet views. 

Also in my research, farm websites have high res, large photos to grab the user’s attention which is something I wanted to implement. As the mobile view in my wireframes didn’t initially have any large photos, I changed this and made the slideshow visible on all media. 

The farm runs mainly from donations and volunteers so I wanted to ensure that there was clear advice and information for anyone who wants to volunteer/help out themselves. 
Also, children’s parties and corporate events are another good way of raising money for the animals care so, although not included in my original wireframes, I added a page dedicated to venue hire. 


## Technologies
1. HTML
2. CSS
3. Bootstrap (4.3.1)
4. Javascript (for the Navbar)


## Features
1.	Bootstrap Grid Layout to create the clean sections. 
2.	The site has a contact button within the footer on all pages which directs the user to the contact form within the About us page. 
3.	Image slider on the home page using animation-delay.
4.	Font awesome Icons within the Menu buttons, with ease-in-out transition. 
5.	Contact form with added hover effect and focus colour change. 


### Features Left to Implement
I would like to add a ‘Fun’ page for children which would include some games to play. And perhaps more information of the breeds and names of the animals on the farm. 
Change the Contact Form to a pop up form accessible on all pages. 
I'd like to make the PETS CORNER title text into a link which takes you back to the home page


## Testing
Syntax – HTML & CSS
1.	Using https://validator.w3.org I checked:
a.	index.html
b.	whatson.html
c.	venuehire.html
d.	farmfriends.html
e.	aboutus.html

2.	Using https://jigsaw.w3.org/css-validator/ I checked
a.	style.css


If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit. 

All PDF links will open in a new tab using 'target="_blank"' and the email link will open up the email of your choice to send. All href links have been manually tested to ensure that they are pointing to the correct destination.

This site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile devices (iPhone 4, 5, 7: Chrome and Safari, iPad, Samsung Galaxy) to ensure compatibility and responsiveness. I created a chart using excel to track my testing, please see [here](https://github.com/chazza144/petscorner/blob/master/Pets%20corner%20-%20tests.pdf)

While testing the ‘Whats on’ page on iPhone 5 device, I noticed the event images were not centered so I reduced the size of the image on the media query which fixed the problem. 


## Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.

To run locally, you can clone this repository directly into the editor of your choice by pasting `git clone https://github.com/chazza144/petscorner.git' into your terminal. To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.


## Credits

### Content
All written content on Farm Friends, About Us and Venue Hire pages was found on the Harlow Council website [here](https://www.harlow.gov.uk/pets-corner)

Flyers and Event information was found on Pets corner’s Facebook page (https://www.facebook.com/PetsCornerHarlow/)


### Media
All image slider images were taken by myself using my mobile. I also photographed the reindeer calve and the park image on the Farm Friends page.
Other photos of the animals were found on Pets Corner’s Facebook. 
The images of the children were found on google images. 

### Acknowledgements

While browsing sololearn, I got the idea for my menu buttons from [here]( https://code.sololearn.com/WuaOAVLRWMyu/#html), then altered and amended the code to how I wanted the buttons to look.

I found the image slider [here]( https://www.hyde-design.co.uk/joomla-bites/80-create-a-css-slideshow-no-javascript-required) and then amended the size and photos to suit the Home page. 


