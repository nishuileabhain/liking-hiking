# Liking Hiking
This project is a frontend website for the fictitious hiking club “Liking Hiking”
The main focus for the website is to get people to join the club and to allow existing members to check on available routes and weather and covid alerts.
The website serves as a portal for information about the club and provides links to information on upcoming restrictions, as well as an email link for specific questions.
It also has links to Facebook, Instagram, Twitter and Meetup.


## UX
The target audience for this website is both club members who want to check when the next meetup is or suggest a new one, and potential members looking for more information about the club.

### User Stories
Potential hikers:
- First time users need to navigate the website easily.
- As a first time user, I want to find information about the group and its ethos.
- As a first time user, I want to find out when the next events are and look at maps of the available routes.
- I want to be able to easily contact the club organisers if I need to ask any other questions.

Club members:
- As a member, I want to follow the club, and stay up to date with the latest events
- As a hiker, I want to make sure I am up to date on any restrictions or cancellations
- I want to be able to easily contact the club organisers if I need to ask any questions or make any suggestions

Organiser goals:
- As the club organisers we want to attract new members.
- We want our existing members to have access to the information they need
- We want hikers to be already aware of the hiking routes and dressed weather-appropriately
- We want to ensure due diligence is done when warning members about restrictions
 
General information about the club is both easily achieved and important so this took top priority. This was provided via content, links and a contact email address.
A gallery of images was considered to be of lesser importance but easily accomplished since the club organisers already had original photos so this was implemented.
Social media promotion and a presence on the meetup site was considered important since many hikers find clubs via those routes. This was easily included via external links.
The option to leave comments on the page was not enabled at this time because such features are already provided in social media and the likelihood of such a feature going unused directly on the site would outweigh the effort of implementing it.
While the current site gives an email link only, if the volume of emails increases it may be worth creating a web form to submit more structured queries.
As the number of events increases, maps of more popular hikes may be included directly on the website.
A user gallery and comment board will not be implemented but links to a private social media group will be provided instead.
 
Initial wireframes made in balsamiq are included as a pdf file in a directory in the project itself. They can be found at 
<a href="../wireframes/liking-hiking.pdf">../wireframes/liking-hiking.pdf</a>. 

## Features

### Features Implemented

The index page provides a main description of the club and reminds hikers that all events are subject to certain conditions.
Links are provided to verify up-to-date details.
As with all pages it also includes links to the club's social media pages.
As with all pages it also features a collapsable menu linking to the other three pages.
There is  a banner photo of a hiking landscape which is consistent across all pages, but the descriptive overlay test changes so that this image serves as a title.

The 'How' page actually provides more specific information about how to join a hike. This leverages external site meetup.com which provided the functionality of an event calendar.
An email link is also given in case the hiker needs to ask for further details.

The 'Hikes' page gives a generic overview of the kinds of places where the club has been hiking and the maps there. The page content also suggests suitability.

Finally there is a 'Gallery' page with some photos taken while hiking to inspire new members.


### Features Left to Implement
In the future some of the external references features such as the map or the event calendar could be implemented directly within the site if the membership grows enough to make this viable.
While the current site gives an email link only, if the volume of emails increases it may be worth creating a web form to submit more structured queries.

## Technologies Used

-  HTML - https://html.com/html5/
-  CSS - https://www.w3.org/Style/CSS/
-  BOOTSTRAP - -https://getbootstrap.com/
The bootstrap gallery code used in this project was originally taken from an article at https://mdbootstrap.com/docs/standard/extended/gallery/ and modified as required.
The rows and columns used to separate content are bootstrap and the navigation menu at the top of each page is a bootstrap feature
- FONT AWESOME - https://fontawesome.com/ This was used to implement all icons for headings and social media, using the <i> tag.
- GOOGLE FONTS - https://fonts.google.com/  This was used to import the 'Oswald' and 'Special Elite' fonts.

## Testing

### Performance
After trying out the site on another computer it became apparent that the images were loading much too slowly.
To fix this I made optimised copies of the images I needed by uploading them to https://tinypng.com/ and then I uploaded them again to gitpod.
I moved the original (now redundant) images into a different folder called 'old'. On testing again I found that one of my image descriptions was wrong, so I renamed the description and optimised and imported the correct picture.

### W3 Code Validation
On testing my code in the W3 validator some minor changes were made such as extra dashes in comments and some unused tags were removed.
https://validator.w3.org/nu/?doc=https%3A%2F%2Fnishuileabhain.github.io%2Fliking-hiking%2F

After adding some alt tags to social media links to try and make the site more accesable, the W3 validator showed it as an error so I removed them again.


The method of testing is to open the https://validator.w3.org/ page and enter the url of pages to be checked. It is important to first push all changes via git and make sure that the most up-to-date version of the page, as hosted on github, is being tested.
The site is hosted at https://nishuileabhain.github.io/liking-hiking/index.html.
The method of saving changes to be tested was using the terminal in gitpod.
1. save changes in edited file using save command or ctrl + s
2. use the terminal to enter git commit -a -m "commit message"
3. use the command 'git push' to update the website

### Accessibility
When I tested site accessibility using  Wave (https://wave.webaim.org/) it reported that the contrast was not good so I changed the background colour and the colours of the links.
Also it reported that the social media links which had been icons without any text description were problematic.
To fix this I added text but then each item was too big and no longer scaled correctly when I narrowed the page.
In the end I removed the unordered list from the html and instead made a bootstrap row with three columns using the method exemplified in the code institute resume project (https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/616289d66b5641a3808cc43e53842695/b51f7b8b815c4bcd9979d2281b6d97a9/).

The method of testing is to open the page at https://wave.webaim.org/ and enter the url of pages to be checked. It is important to first push all changes via git as noted above to make sure that the up-to-date page is being tested.


## Deployment
This website was deployed to GitHub following these steps:
1.	Go to GitHub.com and on the left side click on the repository: nishuileabhain/liking-hiking.
2.	In the repository click on the ‘Settings’-tab at the top.
3.	Under ‘GitHub Pages’, select ‘master branch’ Under ‘Source’
4.	Click ‘Save’ to view the public URL (‘Source’) of the website 


## Credits

### Content
All content is original.
### Media
The photos used in this site were all taken by myself, Carol Lucille O'Sullivan.
### Acknowledgements
I would like to thank the CI tutors and my mentor Mo Shami for helping me, as well as my colleagues from the 'In It Together' Slack channel.
