## CHEF AT HOME - First Milestone Project - Code Institute (https://codeinstitute.net/)
<img src="assets/images/mac-test.JPG" style="margin: 0;">

The aim of the project is to showcase my ability to design and build a static web page using HTML, CSS and Bootstrap for my First Milestone project at Code Institute, Full Stack Developer. 

The focus of the project is to build a website for the audience who would like to learn how to cook and invite them to join the workshops. This is a fictional website with a potential for a real business venture. In the future, this website can improve by incorporating the "how to/recipe demo" videos. It would also be advantagerous to have a "shopping basket" with online payment capabilities as well as user account for returning customers. 

## UX
The purpose of the website is to present the information about the workshops: 
1. what they are
2. who they are designed for
3. what you will learn and 
4. why we are doing this. 

I also wanted to make sure the website is intuitive, easy to navigate and not overloaded with too much unnecesary content. It was also very important to me that the user feels welcomed, wants to stay on the page, feels drawn to get to know us and book a workshop.

### User Stories
* As a parent, I want to make sure child friendliness.
* As a young professional, I don't want to waste my time I don't have for overcomplications.
* I am vegan/vegetarian and I want to make sure the workshops are tailored to suit my diet.
* As somebody who wants to "try before you buy" I want to have sample recipies to try at home before considering to booking a workshop.

## Features
### Existing Features
***Please note: some features of the site have improved in comparison to wireframe and initial documentation as the development of the website has progressed. The new solutions used instead were better suited for the purpose as well as to improve the features of the website, not forgetting the design and the layout.***

* __Header navigation buttons__ - Allows the user to navigate through pages back and forth: Home, Recipes, Workshop.
* __Home Page__ - Includes a brief introduction, a few images taken from previous workshops (assumed) as well as client testimonials (to build trust and add credibility).
* __Recipes Page__ - Page showcases an option to view and try some recipes at home. By clicking on the buttons BREAKFAST, LUNCH, DINNER the user triggers a modal, which displays recipes on a pop-up box. The user will navigate the pop-up box with the scroll button positioned on the right hand side. To exit the recipe: 1) click close icon (x) at the top of the page and 2) CLOSE button at the bottom of the page.
* __Workshop Page__ - This page showcases a form allowing the user to book a workshop. Form has Name and Email Address set as mandatory requirement. Also, the form will not allow submission if the consent button is not ticked. Two sections of the form (Workshop & Date and Select Party Size) allows the user to choose appropriate option for the booking. I have also included "Do we need to know anything else" section, for sharing any important information, if the party size is larger than the option given or they would like more tailored services. The text input area can be expanded/reduced to suit the user's preference. Once the form is complete, BOOK button is active to complete the booking.
* __Social links in the footer__ - This part of every page provides the user with the option to connect with us via social media platforms as well as send us an email directly. Each button will open up on a new browset window or email software on your machine if you select to send an email. 
### Features Left to Implement
* __Recipe Demo__ - This feature is for showcasing how to prepare the meals in a video format. 
* __Workshop Page__ - BOOK button to enable the user to physically book a session and pay online.
* __Basket__ - Feature allowing the user to select multiple workshops and add them to the basket to pay later.
* __Returning User__ - Allow the returning user to create their profile to keep on learning new skills.

## Technologies Used
1. **HTML (hyper text markup language):** Utilised to build all of the pages of the web site. More information on this language here: https://www.w3schools.com/html/default.asp 
2. **CSS (cascading style sheets):** Allows to style different elements of the page, such as color, fonts, size, etc. More information on this language here: https://www.w3schools.com/css/default.asp
3. **Bootstrap:** A pre-customised CSS templates, allowing the coder to quickly create responsive, mobile-first front-end websites. More information about this framework here: https://getbootstrap.com/
4. **GitHub:** A vendor providing a hosting for software development and its version control when you use Git. Read more here: https://github.4 
5. **Gitpod:** I have heavily utilised this online IDE to create and save code, which is run in a browser. You do not need to install the software onto your PC.  More information about this IDE here: https://www.gitpod.io/
6. **Git:** Allows to track and control changes made in source code during the development. Read more here: https://git-scm.com/
7. **Chrome DevTools:** I have heavily relied on using these web developer tools that are built into Google Chrome browser directly. These tools allowed me to quickly spot styling changes that need modification as well as trial new CSS before implementing it in the source code. You can find more information about this excellent bit of kit here: https://developers.google.com/web/tools/chrome-devtools
8. **W3C Markup Validation Service:** I used this website to validate my css and html at the end of the software development as a spotcheck for errors. More information here: https://validator.w3.org/#validate_by_input

## Testing
1. I have used http://ami.responsivedesign.is/ to see how the site would load on different Apple devices. I have also tested the site on iPhone X, Ipad mini and Ipad. Icons performed as anticipated. I have also used this website for a screenshot at the top of this document. 
2. Desktop

    * Google Chrome, Microsoft Edge; all pages and links on the pages work as anticipated, including on small, medium and lage displays. I also used developer tools on Chrome to test different viewpoint sizes. 
3. Mobile 

    * Used iPhone X, Huawei Pro 20 and Pro 20 Mate to test. All pages, links and icons performed well. 

4. Workshop form

    * Go to workshop.html page
    * Try to submit the form without a Name. Error message will appear asking you to input the info.
    * Try to submit the form without an email Address. Error message will appear asking you to input a correct email address.
    * Try to submit the form without ticking a consent box. Error message will appear asking you to provide consent.
    * Try to expand/reduce size of the comment box.

5. Footer 

    * Try to click on email icon. This should trigger default email programme on your device. The emails go to fake inbox currently. Please do not attempt to send the email at this stage.
    * Try to click on social media buttons. This should trigger a new browser window opening up home page links of the social media channels. 

6. Recipes Page

    * Try to click on the three buttons: BREAKFAST, LUNCH, DINNER. Separate recipes should be on display. Please note, the system can only dispaly one recipe at a given time.
    * Try scrolling down the recipe using the scroll button on the right side of the box (up and down)
    * To close the opened recipe, please try x at the top of the box or CLOSE button at the end of it. 

## Deployment
1. I created an account on GitHub: https://github.com/neringabickmore
2. I have used full Code Institute gitpod template (https://github.com/Code-Institute-Org/gitpod-full-template) and created the following repository: https://github.com/neringabickmore/MS1-project
3. To publish the project for public view I have followed below steps: 
        (1) Went to settings in the repository;
        (2) Scrolled to the heading "GitHub Pages";
        (3) The source settings have a drop down menu where I selected master branch for publishing, which I then saved;
        (4) My site was then published at: https://neringabickmore.github.io/MS1-project/
4. To run the code on your computer, follow the link for my repository (https://github.com/neringabickmore/MS1-project) where you will see the following:
<img src="assets/images/run-code-1.JPG" style="margin: 0;">
5. You can select to clone or download the code (clone with HTTP, open in descktop or download a zip file)
6. To clone the repository, you can: 
        (1) Open in Git Bash
        (2) Change the location where you want to re-direct the clone
        (3) Type up the git clone, paste the URL (https://github.com/neringabickmore/MS1-project.git) and press enter to create your local clone.


For more information on the process here: https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository 
###### *Gitpod Reminder: To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type: `python3 -m http.server`

## Credits
### Content
 1. HTML & CSS (and JS to activate modal) code templates identified on Bootstrap documentation (https://getbootstrap.com/docs/4.5/getting-started/introduction/)
 2. Modal inspiration: https://codepen.io/Eventyret/pen/ExVeOme?editors=1010 (Thanks to Simen Daehlin from Code Institute)
 3. I have identified font styles using Google Fonts: https://fonts.google.com/


### Media
1. All images are taken from: https://unsplash.com/photos/. I have used the following artists images: 

    (1) https://unsplash.com/@marius_dragne
    (2) https://unsplash.com/@catalinnp
    (3) https://unsplash.com/@minkmingle
    (4) https://unsplash.com/@calumlewis
    (5) https://unsplash.com/@anniespratt
    (6) https://unsplash.com/@danedeaner
    (7) https://unsplash.com/@sadswim
    (8) https://unsplash.com/@allentaylorjr
    (9) https://unsplash.com/@the_modern_life_mrs
    (10) https://unsplash.com/@miracletwentyone

2. I utilised Font Awesome for all social media icons: https://fontawesome.com/
3. Color paletts and mixers identified here: https://www.w3schools.com/w3css/w3css_color_generator.asp https://www.w3schools.com/colors/colors_mixer.asp
4. I have used my laptop's own MS Paint to compress jpg images.
5. I have used my laptop's own MS Edit with Photos to apply the same size (aspect ratio 10:8) and filter (Rouge) to all of the images used on the website. 
6. I used snippet tool for the screengrabs utilised in the README.md.

## Acknowledgements

1. Big thank you to Code Institute slack community: Simen Daehlin, Steve Pilcher, Richard Wells, Carlos R, Bim Williams, Simon Castagna and many other for listening to me and encouraging to keep at it and not to give up finding solutions!
2. Also, many thanks to Code Institute Slack Channels and their leads, mentors, alumni and users for encouragement, guidance througout the project (https://slack.com/intl/en-gb/)
3. I would like to thank my Mentor Ade Adegbenga (https://www.linkedin.com/in/adegbenga-adeye-14003635/) for website design improvement recommendations, support and good general advice as well as excellent reccomendation on README.md example (https://github.com/BobHerold/RobertHeroldportfolio/blob/master/README.md). 

