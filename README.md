![scrrenshot of Code Kidz logo](/assets/screenshots/cn..webp)


The Code Kidz website is a page for parents and children looking for more information about coding clubs for kids. This website listing main benefits for kids development while having fun coding and all their workshops are free of charge. 

Users of this website can find out more about clubs Founder biography, the way the club delivers customized program for their pupils and also feedback from other parents. Calendar for upcoming summer month is available for the user, as well as contact information and sign up form.

This website targets parents and children who want to learn more about coding. 

![screenshot of media responsivnes](/assets/images/Screenshot_iamresposnive.webp)

#

## Features

* Navigation

     - Featured at the top of the page, the navigation shows the club name in the left corner : Code Kidz and Logo of the club that links to the top of the page.
     - Right navigation links: Home, About Us, Sign Up which link to different sections of the same page.
     - The navigation bar positioning is fixed which makes it accessible while scrolling down the page and easy to navigate in each section.
     - The naviagtion is in font color white and makes good contrast with the dark background color.

![screenshot of navigation bar](/assets/screenshots/screenshot.logo%20-%20Copy.webp)


* The Header

     - The header shows the name of the club, using cyber animation background image. Background image is animated with zoom effect backwards.
     - Two text containers are featured in that section, first container about course approach for learning which is fun, intuitive and gamified, and second text container explains for who is this club and why should users join the club.
     - At the bottom of the Coding Club For Kids text container is calendar bottom with link taking to calendar section.
     - Those two text container are animated with zoom effect forward.
     - This section is linked with navigation bar / Home    

![screenshot of primary image section](/assets/screenshots/Screenshot_primaryimage.webp)


* The Main / The Reason Why Section

     - This section is divided to 3 parts: left, right and center.
     - The Reason Why Section is listing some of positive effects on kids development while learning how to code in the left and the right part.
     - At the center is placed circle container with background image off kids with computer.

![screenshot of reason why section](/assets/screenshots/Screenshot_reasonwhy.webp)


* The Main / About Us Section 

     - The About Us section is divided to four parts: About Us, Our Team, Feedback and Why Us?.
     - Each part explains why should user join the club, informs that classes are for free and teachers are recruited from best universities. Also in Feedback part is short opinion of the club from one of the parent, and in Why Us? part is more information about approach used in teaching kids of how to code.
     - This section is linked with navigation bar / About Us 

![screenshot of about us section](/assets/screenshots/Screenshot_aboutus.webp)


* The Main / About Us Section / Founder

     - The Founder is additional information of The About Us Section.
     - It contains flip-card: front side - image of the founder, and back side- name of the founder and her life motto.
     - On the right side from the founder image is more biography information of the founder.

![screenshot of founder](/assets/screenshots/Screenshot_founder.webp)


* The Main / Calendar Section

     - This section is accessible from text container in primary image.
     - It shows summer month August where user can choose a day when to join club.
     - Calendar is not responsive to user as Javascript language is not required for this project.

![screenshot of the calendar](/assets/screenshots/Screenshot_calendar.new.webp)


* The Main / The Sign Up Form

     - The sign up section has a form to collect details from child's guardian, so they can sign up to the Code Kidz club.
     - The sign up form is valuable to the user as it gives them ability to sign up to join the Kids Code club.
     - The SIGN UP header has infinite bounce animation.
     - The Sign Up form is accessible from the navigation bar.
     

![screenshot of sign up section](/assets/screenshots/Screenshot_form.webp)


* The Footer
   
     - The Footer contains information for the user how to get in touch with the club.
     - The footer contains social media icons so users can find the Code Kidz club on Facebook, Instagram, Twitter and YouTube.
     - The contact section is valuable to the user as it gives the ability to find and contact the Code Kidz club if they need to. 

![screenshot of the footer](/assets/screenshots/Screenshot_footer.webp)


### The Thank You for submission page

* This page is linked to Submit buttom in Sign up form and it confirms to user that form was filled and sent.
* This page contains navigation bar with links taking user back to the main page.
* This page contains footer with Contact information and links to social media.

![screenshot of the thankyou.html](/assets/screenshots/Screenshot_thankyou.webp)

## Testing 

* I tested that this page works in different browsers: Chrome, Microsoft Edge, Firefox, Safari.
* I confirmed that this project is responsive, looks good and functions on all standard screen sizes using the devtools device toolbar.
* I confirmed that navigation, primary image, about us, sign up and contact text are all readable and easy to understand.
* I have confirmed that the form works: requires entries in every field, will only accept an email in the email field, and the submission bottom works.

### Bugs

#### Solved Bugs

* When I deployed my project to GitHUb Pages I discovered my projecet's favicon was not showing as website icon.
     - I discovered this was because I had absolute file path such as this in my code.
     - Removing the starting / fixed the problem.

      <link rel="icon" type="image/x-icon" href="/assets/images/favicon.png" style="border-radius:50%;">

* After adding thankyou.html page confirming form submision, new page was not loading.
     - I discovered this again was absolute file path such thi in my code below.
     - Removing / fixed the problem.

      <form action="/thankyou.html" id="sign_up">

* After adding thankyou.html page and coping head and footer the favicon and logo was not responsive. 

     - I discovered i needed to change path by adding / before the assets and href="./index.html" instead of #praimary_image.

      <link rel="icon" type="image/x-icon" href="assets/images/favicon.webp" style="border-radius:50%;">

      <a href="#primary_image" aria-label="Go back to the top of the page">


      
### Validator Testing

* HTML 
     - No errors were returned when passing through the official W3C validator.

* CSS 
     - No errors were found when passing through the official (Jigsaw) validator.
 
 * Accessibility 
     - I confirmed that the color and fonts chosen are easy to read and accessible by running it through Lighthouse in devtools:

![ecreenshot of the lighthouse accessibility](/assets/screenshots/Screenshot_lighthouse.webp) 

### Unfixed Bugs

No unfixed bugs.

#

## Deployment

* The site was deployed to GiHub pages. The steps to deploy are as follows:
     - In the GiHub repository, navigate to the Settings tab.
     - From the source section drop-down menu, select the Master Branch.
     - Once the master branch has been selected, the page provided the link to the completed website.

The live link can be found here - 
[Code Kidz](https://adamolnar.github.io/Portfolio_1_CodeDino/).

## Credits

### Content 
* The layout of the website and content of README file was based on Ci [PP1 Sample Project](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+CSSE_PAGPPF+2021_Q2/courseware/66cf361c769a41d496f5001fae6f9be7/3b5cd5dc8313462aa5975a3c9b9a1a3c/).
* The code to make the Header, Reason Why and social media link was inspired on the CI [Love Running](https://github.com/Code-Institute-Solutions/love-running-2.0-sourcecode/blob/main/08-responsive-elements/05-responsive-gallery/index.html) Project.
* The code for flip-card was based on [W3S](https://www.w3schools.com/howto/howto_css_flip_card.asp).
* Animation for Sign Up text was taken from [Animate.css](https://animate.style/)
* The code for sign up form was taken from [W3S](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_signup_form)
* The code for the calendar was taken from [W3S](https://www.w3schools.com/howto/howto_css_calendar.asp)

### Media
* The image for the favicon and logo icon was taken from [microsoft.com](https://www.microsoft.com/en-gb/p/like-a-dino/9nlpr8kqzz7c?activetab=pivot:overviewtab)
* The image in the header was taken from [123RF](https://www.123rf.com/clipart-vector/code_kids.html)
* The background image fot the Reason Why section was taken from [iStock](https://www.istockphoto.com/de/search/2/image?mediatype=illustration&phrase=blue+chalkboard+background)
* The background of middle circle part from Reason Why section was taken from [iStock](https://www.istockphoto.com/de/vektor/schulkinder-lernen-programmieren-im-naturwissenschaftlichen-klassenzimmer-vektor-gm1199512978-343227386)
* The image for the founder was taken from [Adobe Stock](https://stock.adobe.com/at/search/images?filters%5Bcontent_type%3Aphoto%5D=1&filters%5Bcontent_type%3Aillustration%5D=1&filters%5Bcontent_type%3Azip_vector%5D=1&filters%5Bcontent_type%3Avideo%5D=0&filters%5Bcontent_type%3Atemplate%5D=0&filters%5Bcontent_type%3A3d%5D=0&filters%5Bcontent_type%3Aaudio%5D=0&filters%5Binclude_stock_enterprise%5D=0&filters%5Bis_editorial%5D=0&filters%5Bfree_collection%5D=0&order=relevance&serie_id=296903736)
* Image for the Calendar background was taken from [Google image serch](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcQ0pWbb77bp3XKW0nyJ2ZOLqVWcxV6cnX8FFSOF2VvBGDY-faiO)



