# Readme:
## 1. Purpose of the project
This project aimed to build a static front-end site to present helpful information to users, using all the technologies I learned in the HTML and CSS course with CodeInstitute so far. Specifically, in this project, the static front-end site represents a group of three people who are interested in the Metaverse and want to share their passion and love about its latest updates by subscribing to their newsletter with other users.

Metaverse Lovers is a site that hopes to provide the latest news regarding Metaverse and communicate the difference between real-life and virtual reality. The site will be targeted toward tech-savvies interested in Virtual Reality and Metaverse.

Link to the site: https://van-essa.github.io/Project1_Metaverse/index.html

## 2. User Stories
In this section, the usage of its page is explained.

Navigation Bar
Featured on all four pages, the full responsive navigation bar includes links to the Home, About Us and Sign Up page and is identical on each page to allow for easy navigation.
This section will allow the visiting user to easily navigate from page to page across all devices without reverting to the previous page via the 'back' button.
The navigation bar will change to the column when featured on the mobile version to create a better user experience.

The landing page image
The landing to each page includes a photograph with text overlay to allow the visiting user to see precisely which location this site would apply to.
The landing page image introduces the visiting user to Metaverse Lovers with an eye-catching animation to grab their attention.

### Home Page
On the Home page, as a visiting user, the visiting user will get a complete picture of what Metaverse is and its involved sectors. The visiting user will land on a page where the first paragraph will explain what Metaverse is and then provide a list of the involved sectors.
The Why Metaverse section will allow the visiting user to see the impact Metaverse has in our lives and its involved sectors.
Metaverse's list of sectors will allow the visiting user to see the sectors Metavetse is involved in explaining the how.
As a visiting user on the Home Page, they will see the value of signing up for the Metaverse Lovers Newsletter.

### About Us Page
On the About Us page, as a visiting user, they will learn more about the profiles of the site's owners. That occurs by providing a small introduction about the owners, goals, vision and purpose.
This section is valuable to the visiting user due to the better picture of the purpose of this site, the owners' vision and identity.

### Sign Up Page
The Sign Up page will allow the visiting user to get signed up to Metvarese Lovers Newsletter.
As a visiting user, they will be asked to submit their full name and email address.

### Thank You Page
As visiting user, they will land on the Thank You Page when they have submitted their information in the Sign-Up form for the Metaverse Lovers Newsletter.
This section is valuable to the visiting user as they will get the subscription confirmation with an eye-catching video and a thank you message to boost the engagement.
This section is only visible after submitting the form, and they cannot land on that page otherwise.

### The Footer
The footer section includes links to the relevant social media sites for Metaverse Lovers. In this case, the links will land to Code Institute social accounts since the Metaverse Lovers page does not exist in reality. The links will open to a new tab to allow easy navigation for the user.
The footer section is featured on all four pages.
The footer is valuable to the visiting user as it encourages them to keep connected via social media.
The footer page will be visible at the end of each page and look the same on a desktop, iPad and mobile display.

## 3. Future features what would like to add in the future
Future features shall include a blog page, where a comments section will be available to the visiting user and can express any questions, concerns or thoughts on the topic. 
The future feature shall include more immersive animation to engage th visiting user and communicate the world of Metaverse with immersive videos.

## 4. Typography and colour scheme
The Typography used on the site was Bellota Text Light 300 and was taken from Google Fonts: https://fonts.google.com/specimen/Bellota+Text?category=Display,Monospace
The scheme of the colours used for the site is this:

## 5. Technology
After studying the HTML and CSS essentials course with Code Institute, this project was created in Git pod using HTML and CSS languages.

## 6. Testing
**Code validation**
**_HTML_**
Two errors were returned when passing through the official W3C validator https://validator.w3.org/nu/?doc=https%3A%2F%2Fvan-essa.github.io%2FProject1_Metaverse%2F
![Error_1](https://myoctocat.com/assets/ReadMeImages/HTML Checker.png)     

When coding the subject list on the Home Page, being featured in the same line was not the aim, rather than having points 1-3 to the first row and 4-5 to the second row. The only way it could be achieved was by adding the <br> element between them. Hence this bug was not fixed due to difficulties finding another way.

Error nr.2:
 Stray start tag script.

From line 121, column 1; to line 121, column 80

wesome-->↩<script src="https://kit.fontawesome.com/5712c7d5d7.js" crossorigin="anonymous"></scri

This Error looked so strange due to misunderstanding the bug. The code was rewritten, checking online any similar issues, checking spelling mistakes, but no answer seemed to be valuable for this bug. The code was not removed since the fontawesome script had to be mentioned in the code.
CSS
No errors were found when passing through the official (Jigsaw) validator, but 5 Warnings were pointed: https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvan-essa.github.io%2FProject1_Metaverse%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en

266      -webkit-linear-gradient(to right,#FFAFBD,#C9FFBF) is a vendor extension
272      -webkit-linear-gradient(to right,#ff9472,#f2709c) is a vendor extension
278      -webkit-linear-gradient(to right,#ffc500,#c21500) is a vendor extension
284      -webkit-linear-gradient(to right,#0ABFBC,#FC354C) is a vendor extension
290      -webkit-linear-gradient(to right,#FFAFBD,#C9FFBF) is a vendor extension

After checking online what the problem is and what this warning wants to communicate, the outcome was that the style sheet code did not respect the syntax of CSS and that there is nothing to do about this since those errors will help support browser compatibility efforts. Hence, the code is still there since the eye-catching list on Home Page would not be visible otherwise.

7.Test cases
It is tested by filling the Newsletter form, ensuring that the required information is filled and the message pops up if it is not filled in.
The Newsletter form requires the Full Name of the Visiting User and the email address. If the visiting users do not share this information, then the visiting user can not subscribe.
Testing filling the form in both Desktop and Mobile this is what happens:
   -When the visiting user does not fill in their name
   -When the visiting user does not fill in their surname
   -When the visiting user does not fill in their email address
   -When the visiting user fills in all required information

8.Unfixed Bugs
The Unfixed bugs are Error 1 and Error 2 mentioned in teh code validation.
   
9.Supported screens and browsers 
The Chrome simulator was used from my mobile and desktop devices.
It was tested in Chrome simulator for both Mobile and Desktop
It was tested in Microsoft Edge simulator for Desktop
It was tested in Safari simulator for mobile 
The screen size on mobile was on iPhone 11 Pro, namely 5.8 inches, 84.4 cm2 (~82.1% screen-to-body ratio)
The screen size on the Desktop was 2560x1440.

10.Deployment
The site was opened via Gitpud to check its process. The step to open that site is as follows:
Go to terminal 
Git command: python3 -m http.server
A pop-up message will appear on the right-hand side where Open Browser should be clicked.
A new page opens where the site is available.

The site was deployed to GitHub pages. The steps to deploy are as follows:
In the GitHub repository, navigate to the Settings tab
From the source section drop-down menu, select the Master Branch
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
The live link can be found here - https://van-essa.github.io/Project1_Metaverse/

11. Credits

Content
The text for the Home page was taken from Virtual Speach Article https://virtualspeech.com/blog/vr-applications
The scroll left feature on Follow Us on Social Media was taken from this open Code source https://www.html.am/html-codes/marquees/html-scrolling-text.cfm
The Metaverse list was inspired and used the code from this other open code source https://codepen.io/vikassingh1111/pen/xBPmbL
The icons in the footer were taken from Font Awesome
Instructions on how to implement the HTML and CSS code using GitHub was taken from the HTML and CSS course from Code Institute

Media
The same photo used on the Home, About Us and Sign Up page are from This Open Source site https://pixabay.com/photos/woman-headset-virtual-reality-vr-6882918/
The image used on the About Us page was taken from this other open source Content creation site https://www.canva.com/
The video used on the Thank You page was taken from this other open source Content creation site https://www.canva.com/