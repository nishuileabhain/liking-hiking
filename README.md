##Liking Hiking
This project is a frontend website for the fictitious hiking club “liking hiking”
The main focus for the website is to get people to join the club and to allow existing members to check on available routes and weather and covid alerts
The website provides information on upcoming restrictions, it has the option to sign up for a mailing list of upcoming events
It also has links to facebook Instagram and twitter and meetup


UX
The target audience for this website is:
•	Group members who want to check when the next meetup is or suggest a new one
•	Potential members looking for more information about the club

User stories:
First time users:
•	As a first time user, I want to navigate easily across the website.
•	As a first time user, I want to find information about the group and its ethos
•	As a first time user, I want to see some maps of the available routes
•	I want to be able to easily contact the club organisers if I need to ask any questions or make any suggestions

Returning/regular users:
•	As a member, I want to follow the club, so I stay up to date with the latest events
•	As a user, I want to make sure I am up to date on the government restrictions and weather warnings
•	I want to be able to easily contact the club organisers if I need to ask any questions or make any suggestions

Owner goals:
•	As the owners we want to attract new members.
•	As the owners we want our existing members to have the information they need
•	As the owners we want users to be already aware of the maps
•	As the owners we want hikers to be prepared and dressed adequetely
•	We want to ensure due diligence is done when warning members about restrictions
 
Scope level
Combining the user needs and owner goals gives the following requirements with their respective importance and viability/feasibility displayed in a trade-off equation:
	importance	feasibility
a. provide general information about the club	5	5
b. provide information about routes	5	5
c. option to join mailing list	3	5
d. option to leave comments	1	3
e. providing a gallery	2	3
f. social media promotion	3	4
g. provide contact information	5	5
A user gallery and comment board will not be implemented but links to a private social media group will be provided instead.		


wireframes made in balsamiq are included as a pdf file in the project itself (in an separate directory)
../wireframes/liking-hiking.pdf

Features ---
The index page provides a main description of the club and reminds hikers that all events are subject to certain conditions.
Links are provided to verify up-to-date details.
As with all pages it also includes links to the club's social media pages.
As with all pages it also features a collapsable menu linking to the other three pages.
There is  a banner photo of a hikig landscape which is consistent across all pages, but the descriptive overlay test changes so that this image serves as a title.

The 'How' page actually provides more specific information about how to join a hike. This leverages external site meetup.com which provided the functionality of an event calendar.
An email link is also given in case the hiker needs to ask for further details.

The Hikes page gives a generic overview of the kinds of places where the club has been hiking and the maps there. The page content also suggests suitability.

Finally there is a gallery page with some photos taken while hiking to inspire new members.

In the future some of the externally references features such as the map or the event calendar could be implemented directly within the site if the membership grows enough to make this viable.

Features Left to Implement
Another feature idea
Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

Testing

After trying out the site on another computer it became apparent that the images were loading much too slowly.
To fix this I made optimised copies of the images I needed by uploading them to https://tinypng.com/ and then I uploaded them again to gitpod.
I moved the original (now redundant) images into a different folder called 'old'. On testing again I found that one of my image descriptions was wrong, so I renamed the description and optimised and imported the correct picture.

On testing my code in the W3 validator some minor changes were made such as extra dashed in comments and some unused tags were removed.
https://validator.w3.org/nu/?doc=https%3A%2F%2Fnishuileabhain.github.io%2Fliking-hiking%2F

After adding some alt tags to links, the W3 validator showed this as an error so I removed them again.

When I tested for site accessibility using wave

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment
This website was deployed to GitHub following these steps:
1.	Go to GitHub.com and on the left side click on the repository: nishuileabhain/ liking-hiking.
2.	In the repository click on the ‘Settings’-tab at the top.
3.	Under ‘GitHub Pages’, select ‘master branch’ Under ‘Source’
4.	Click ‘Save’ to view the public URL (‘Source’) of the website 


In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
The bootstrap gallery code was originally taken from an article at https://mdbootstrap.com/docs/standard/extended/gallery/ and modified as required.
The
Media
The photos used in this site were all taken by myself, Carol Lucille O'Sullivan.
Acknowledgements
I would like to thank the CI tutor and my mentor for helping me.