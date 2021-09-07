# FLYBODY  

[View the main README file here](README.md)

[View the delopyed site](https://didisimmons.github.io/Flybody-gym/)

## TESTING 

### Validator Testing 
* [W3C CSS validation](https://jigsaw.w3.org/css-validator/): This is used to validate the CSS code used on all six webpages created. Our code is found to be error-free by the validator. Please see the screenshot below. 

![css_validation_cofirmation](css_validation.png)

* [W3C Markup Validation](https://validator.w3.org/): This is also used to check the validity of the html code for all the  six webpages created. Our code was found to be error-free by the validator. See screenshot below for all pages. 

![homepage ](assets/images/homepage_validation.png)

![rates validation](assets/images/rates_validation.png)

![timetable validation](assets/images/timetable_validation.png)

![instructors validation](assets/images/instructors_validation.png)

![joinus validation](assets/images/joinus-validation.png)

![thank you](assets/images/thanks_validation.png)

### User stories testing 

The most common path for our user through the website: 

* Rates > Timetable > Instructors > Login > Join Us 
 
An alert message appears at the top of the navigation bar and can be dismissed. We can test this by changing the screen width in Chrome Dev Tools, the alert message shrinks. Starting with the desktop view, it can be observed to be responsive when the screen width is reduced. The alert message is included on all five pages so that the user is aware of the new Covid guidelines before attending an in-class session.

The user can easily navigate to the next page from any of the sites by lingering over any of the required five webpages. The home page is represented by the FLYBODY logo. If the user clicked, they would be taken to the main page of the website.

The user may quickly sign up to FLYBODY gym using the call to action button on the hero image on the main page, which is the home page. They can quickly examine the amenities, benefits, team members, customer reviews, and a newsletter subscription button. If the user does not interact with the other pages, this is all on one page.

When the screen width is set to a desktop view, the FLYBODY logo on all devices takes the user to the homepage, and when the user hovers over any of the webpage links, it is highlighted with a light grey backdrop. The navigation bar on a tablet or mobile device is a hamburger icon that, when clicked, allows the user to hover over the five  webpages and see the grey highlight backdrop. 

-   ### Testing User Stories
  
  As a customer I want to 

    1. Easily navigate the site and get the information I need to take the necessary action

        1. All of the webpages contain a navigation bar with five clearly labelled weblinks that, when clicked, take the user to different activities and examine different information about FLYBODY.

        2. When the FLYBODY logo is clicked, it takes the user to the home page.

        3. The user can navigate down the webpage to see the perks, deals, and take various tasks, as well as learn more about the gym.

        4. All of the call to action buttons on the webpages either redirect the user to another page or open a form to be filled out, which notifies the user of the next action once completed.

        5. When any of the buttons on the website is clicked, it opens on a new window to avoid bad user experience .


    2. Be able to readily discover FLYBODY online on their social networks to ensure that the information and locations supplied are legitimate and trustworthy.

        1. FLYBODY has published their social media handles at the bottom of all webpages, which the user can easily click on and be sent to their social media accounts to validate legitimacy.

        2. In the about us part on the home page, a brief history of FLYBODY is offered, as well as the names and levels of competence of its team members. The user can simply check their legitimacy by researching their names/credentials online.

        3. The instructors website also includes information on all of the trainers, including their areas of specialization and years of experience. The user can readily authenticate the expertise of these teachers by researching them on their social media sites.

        4. To build trust with users, a reviews area has been included to display users feedback from real users from various industries to hear their thoughts on FLYBODY. This can have an impact on the users' trust in the brand.

        5. The footer of every pages includes a phone number and the location of the company's headquarters, which can be confirmed using Google Maps. To ensure validity, the phone number can also be contacted.


    3. Easily examine the gym's fees as well as their locations so that I can quickly determine if it fits my budget and is close by.

        1. On all webpages, the customer will see the rates pricing page, which displays all of the memberships offered by FLYBODY and allows them to choose one that meets their budget.

        2. The user can see other FLYBODY locations in the footer section and see if it is close to them. To confirm the address and costs, users can call the phone number. 


     4. View the class schedules and conveniently book/join classes online.

        1. There is a clearly labelled timetable page on the navigation bar on all webpages that provides the days and times for the classes offered at FLYBODY. The user may quickly hover over the classes to see the dates and timings.

        2. Instructions on how to book a class online and in person can also be found on the timetable page under the timetable. 
        
    5. Be able to easily locate a personal trainer online and learn more about them so I know what to expect.

        1.	On the navigation bar, which is accessible on all pages, there is a clearly visible instructor page that displays all of the trainers at FLYBODY.

        2.	The instructor page displays thumbnail photographs of the trainers along with their names, areas of specialization, and years of experience. This can affect the user's selection on which trainer they want to work with and, if necessary, research more about them or call in to arrange a session.
     
     6. The site should be visually appealing in order to keep me interested and present appealing offers on the site.

        1. Images have been used on all of the webpages to enhance the site and appeal to the experience that can be expected at FLYBODY. To make the site more visually appealing, icons have been utilized to convey certain information.

        2. When a user clicks on the FLYBODY logo and is redirected to the homepage, the user can view all of the services and perks provided by FLYBODY.

        3. When a user arrives at the home page, there is a call to action button tempting the visitor to sign up for a low cost with no deposit required. When the user clicks, a form appears for the user to fill out, which takes less than a minute and, when done, brings the user to FLYBODY's thank you page.

        4. The prices page on the navigation bar also offers inexpensive membership costs with packages that suit different people's budgets if they join FLYBODY.

    7.	Log in to my account quickly and easily to track my fitness goals, book classes, and engage with the rest of the fitness community.

        1. The navigation bar, which is visible on all pages, contains a clearly labelled login page that, when clicked, displays one column requesting the user for their login credentials to enter their portal.

        2.	In the future, after users log in to their portal, they will be able to track their fitness goals, book classes, and interact with other users via the fitness community.

    8. 	Find low-cost memberships that can be tailored to my needs without breaking the budget.  

        1. The user can view the many membership plans offered by FLYBODY and choose one that fits their budget on the pricing page (rates) , which is accessible via the navigation bar on all pages.


### TESTING OF ALL FEAUTURES AND ELEMENTS ON THE PAGE

To test the responsiveness of each of the webpages the Chrome dev tools were employed to test the pages by changing the screen sizes of the device

#### Homepage

 1. Navigation bar 

     1. Go to the Index page(Home)  on a desktop . 

     2. Change the desktop's screen size to that of a tablet device to ensure that the navigation bar is responsive and changes to a hamburger dropdown symbol when the medium break point is reached. The navigation bar should be positioned correctly, with the menu items in place.

    There was no overflow of the navbar or undesirable modifications to the menu items when testing the responsiveness of the navbar. The navigation bar changed to a hamburger dropdown symbol with the dropdown menu items in situ, as intended.

    3. Hover over the alert dismissive message button and make sure it does not create any undesirable changes to the navigation bar when exited.

     When tested on all devices, the alert dismissive button shuts without impeding the navigation bar. The navigation bar is still present, as expected.

    4. Hover your mouse over the navbar menu items and click on each link to ensure that it takes you to the relevant page.

    When tested on all devices , the menu links function as intended. Linking to the  appropriate sites.

    5. Click on the FLYBODY logo to ensure that it takes you to the home page when you click on it. 

    Testing this on all devices by adjusting the screen width it can be seen the brand logo “FLYBODY” links to the home page whenever clicked.

    6. Change the screen size to that of a tablet or mobile device and check that the hamburger icon appears. Also, make sure that the dropdown menu links from the hamburger icon have a background overlay when hovered over and that they all lead to the relevant pages.

    When the screen width of the navigation bar is changed to that of a tablet device, the navigation bar responds as expected, and the hamburger icon appears. When you click the hamburger icon, a dropdown menu emerges, displaying the menu links, which have a light grey background overlay when hovered and link to the proper pages when clicked. When the hamburger icon was pressed, the dropdown menu links were properly aligned. The menu items, however, have been centred to improve the appearance of the navigation bar on a tablet and mobile device.

    7. Hover over the menu items on a desktop to ensure that a light grey background overlay appears when hovered.

    When the effect was tested on a desktop device by hovering the mouse over the menu item in the navigation bar, the light grey backdrop appeared.

2. Hero image  

     1.	Go to the Home page which is the Index page here on a desktop. 

    2. Confirm that the hero image is visible and takes up the entire width of the screen.

    When tested on a desktop, the hero image occupies the full screen width with no overflow problems. Changing the screen size to a tablet /mobile device the same effect still takes place, the hero image occupies the full screen width . 

    3. When the alert dismissing message appears above the navigation bar, make sure the hero image is still visible with the text overlay on it. Check to ensure that the overlay does not obscure any functionalities.
    
    When tested on a desktop device, the hero picture fills the entire screen width, despite the presence of the navigation bar and the alert dismissing message above it. The alert message, on the other hand, extends down the navigation bar, blocking some text on the hero image. This is remedied by increasing the text's padding. This new fix has no effect on any of the other features.

    When doing the above-mentioned tests (iii) on a tablet and mobile device, when the alert dismissing message appears above the navigation bar. The alert message pushed down the navigation bar, obscuring some text, and the overlay on top of the image was overflowing. This was corrected by raising the height of the hero image on both tablet and mobile devices. Changing the height of the hero picture based on the device breakpoint

    4. When the alert dismissal message is exited above the navigation bar, check that the hero picture is still displayed on all devices.

     On a desktop device, the hero picture fills the entire screen, the overlay is in place, and the hero image text is well within the image.

    Running the same test on a tablet found out that the text on the hero image was so enormous that it was spilling over the edge of the image. This was corrected by adding classes to the hero image text and the call to action button to minimize the size of the elements when a specified breakpoint was reached. The font size and button size of the items on the hero picture were fixed by these classes. After implementing the patch, the hero image was still visible, with all of its components responsively and in the relevant places. 

    However, performing  the same tests on a mobile device discovered that the alert dismissive text above the navigation bar obstructed the view of the hero image message, and that when the navigation bar was exited, it blocked some parts of the hero image text, with the contents on the hero image appearing clustered. To address this issue, we previously adjusted the hero image height, assigning different values for different breakpoints to fit all banner elements (i.e. text, button), however this did not resolve the issue on all platforms, particularly mobile smartphones. 

    The hero picture button was overflowing on a specific mobile device (MOTOG4), and the header text was partially buried under the navigation bar. This was handled by removing the height set for the hero image at various breakpoints, leaving only two height breakpoints for the hero image. One is for a desktop computer, and the other is for a mobile device. Using these two hero image height breakpoints resolves the overflowing issue. As the height of the hero image on a mobile device is increased, there is more room for text and a button. Another solution that fixed the issue of overflow  was to reduce the font size and button size for various breakpoints in order for the hero image contents to fit and appear visually pleasing.

    After implementing these adjustments, the hero image, together with accompanying text and call to action button, responds correctly. When modified, the hero image and its contents adjust to different screen sizes, with all elements appearing visually appealing and in the proper spot.


    5. Confirm that the hero image text header and the call to action button have an animation effect when the home page (index page) loads on all devices, and that the header text "no hidden cost" is hidden on mobile devices.

    When tested on a desktop device, the image text header and the call to action button have a zoom in effect motion applied. The identical effect occurs on a tablet and mobile device, and the animation is likewise implemented as planned. On a mobile device, however, certain text in the header is hidden to keep the mobile screen clean and visually appealing. 


    6. Hover your mouse over the call to action button on the hero image to see if the hover colour changes.

        On a desktop device, this was originally tried by hovering the mouse over the SIGNUP button, which had a blue hover effect. When the screen size of the button was adjusted to a tablet device, the same result was obtained. On a mobile device, the button shrinks to fit the screen size, and the blue hover effect occurs when the mouse is hovered over the button.

    7. Click the Sign Up button on the main page and ensure that a modal form appears, requiring you to fill out all of the information accurately before submitting.

    Testing  this on a desktop device,  click on the Sign Up button, which opens a modal form that requests some personal information. When tested, all fields must be filled in order to submit the form; if not, an error notice displays requesting that you “please fill out the form.” This is also true for a tablet or mobile device; the form is responsive to screen size, as are the fonts and call to action buttons, which shrink in size based on the breakpoint.

    8. When the form is correctly filled, click the signup button to ensure that it takes you to the correct page, which is the thank you page. 

    When tested on all devices (desktop, mobile, and tablet), the sign Up button opens a form that needs the user to fill out some mandatory fields. When the form is completed and the submit button is pressed, the user is directed to the expected thank you page. The links function as intended.

3. About us section   

    1. Navigate to the Home page, which is the Index page on a desktop.
     
    2. On a desktop device, confirm that the about us image is placed next to the about us message, however when the screen size decreases, the about us image should be placed above the about us statement. The about us image should be hidden on mobile devices.

    Testing this on a  desktop device, the image appears beside the about us statement. As the screen size shrinks from desktop to tablet, the image remains beside the about us text with a small space beside it. As the screen size of the tablet is decreased further, the about us image appears above the text, with the font size of the text decreasing in size as the screen size reduces. On a small mobile device with a breakpoint less than 480 px, the image is hidden and only the about us text is displayed, as predicted, with the font size changing to the device to appear excellent across all device widths.

    3. Expand and collapse the width of the screen to ensure the above adjustments occur.
    
    By modifying the screen width, it is discovered that the about us section is responsive, adjusting to the screen size exactly as predicted, with the about us image concealed on a mobile device.

4. Facilities section 
   
    1. Navigate to the Home page, which is the Index page on a desktop.

    2.	Ascertain that the facility portion is divided into three equal columns with card container designs. The design of the card container should include a picture, a title, some engaging text, and a button. When lowered or enlarged, the three columns should be responsive and conform to the screen size. On a mobile device, each container should fill the width of the screen, resulting in the three columns collapsing to one column each.

    Testing on a desktop device first, the card container with the image, title, and persuasive text is present and responsive to the screen as it is altered in the dev tools. The text size is also responsive to the screen and the button. On a tablet device, the same effect occurs; the facilities section is separated into three columns that respond correctly and fit well on the screen. When viewed on a mobile device, the three columns compress to one column, which is clean and visually pleasing.

    3. Hover your mouse over the card container image to ensure that the alt text appears when you do.

    When tested on all devices, the alt text appeared when the mouse was hovered over the image.

    4. Hover over the “View more” button to ensure that the hover colour changes and that clicking it takes you to the home page.

    When the mouse is hovered over the view more button on all devices (tablet, desktop, and mobile), the hover colour changes. When the user clicks on one of the three card containers, the user is taken to the home page.


5. More facilities section

    1. Go to the Home page, also known as the Index page on a desktop, and scroll down to the More Facilities section. 

    2. Confirm that the four picture icons display and take up 80 percent of the screen width when viewed in desktop mode.

    When tested on a desktop device the image icons display in line and respond accordingly as you reduce the screen width size. 

    3. Confirm that the four picture icons display and take up 80 percent of the screen width when viewed in desktop mode.

    When tested on a tablet and a mobile device, the image icons display two images per row, with some bottom space between the images, as predicted. On various screen sizes, the picture icons respond correctly.

    4. On all devices, hover over the four image icons to see if the alt text appears.

    Testing on all devices, when the mouse is hovered over the image, the alt text appears as expected on all devices.

	5. Initially, the icons used in the lighthouse test were taken from Flaticon. According to the lighthouse report, the symbols slowed down the speed and caused cached images. The symbols used now  in the more facilities section were SVG images to enhance the speed index, as recommended by  lighthouse. This is because they are easy to scale to any size while maintaining resolution


6. Reviews section

    1. Go to the Home page (the Index page on a desktop) and scroll down to the Reviews section.
       
    2. Confirm that the three member testimonials are displayed in a slideshow with a previous and back arrow button.  

    When tested on a desktop device, a slideshow of member testimonials with their names and companies displayed. The previous and back buttons are visible. When the screen size of a tablet or mobile device is modified, the testimonials respond with the screen and its content reduces to fit the size of the screen. As expected, the font and button sizes shrink to fit the size of the screen.
     
    3. Ascertain that a backdrop image is placed behind the reviews section and that there is no text overflow.  

    The image is placed behind the testimonies on a desktop device. There is no text or image overflow. When the screen width is changed, the same thing happens, however on a mobile device, the testimonials offered overflow the backdrop image. This was corrected by increasing the background picture height to allow for more space for the testimonials. This is done so that the testimonial text is centred and looks well on all screen widths. The font size of the testimonials has also been lowered, resulting in the predicted lack of text overflow in the reviews area.


7. Why join us section 
