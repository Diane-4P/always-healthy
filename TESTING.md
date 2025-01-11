# Always Healthy Website - Testing details

[View README.md file](/README.md)

[View Always Healthy deployed site here.](https://diane-4p.github.io/always-healthy/)

## Testing

### Browser Compatability

When testing the site in multiple browsers (Chrome, Firefox, Edge and Safari) they all showed lagging in opening up onto the landing page. All browsers also showed a white edge on the right hand side of the Home screen indicating the width was wider than the larger viewports as the scroll bar appeared at the bottom and not on the smaller screens. Due to the lagging all the images were re-sized, the hero image with a aspect ratio of 16:9, other Home and Classes images with a ratio of 3:2, Shop images were made square (1:1) at 800px x 800px, and the Contact page's image already had a 3:2 aspect ratio. All new image sizes were changed from jpg to webp format to allow all the pages to be more responsive, which you can see in the Lighthouse performance results below.

### Responsiveness

During testing on multiple mobile devices (iPone 5(SE), iPhone 12 Pro, iPad mini, Galaxy S20 ultra), there was a good response on all devices within **Chrome developer tools** but I found that on the iPad mini showed that the Registered Address title was bigger on the Classes and Contact pages. When checking the Lighthouse performance it showed that the headings elements were not in a sequentially-descending order so when I changed this I made the heading for the footer on these pages a h3 and with a class of h4 from Bootstrap but the font-weight was higher. To make them respond in the same way as the Home page I added the selector of '#registered-marks h3' to the h4 on the stylesheet to achieve this.

When I created a mochup of the website on **Am I Responsive**, the **Navbar** on the mobile appeared on 2 lines, which happens when the screen is less than 300px. This was fixed by adding a **@media query** for mobile with a screen size smaller than 315px (it is slightly smaller than the most commonly used small screen of the iPhone 5 at 320px). This will remove the home link from displaying, which will not cause any problems as the logo has a link to the home screen which people are aware of nowadays. When testing this out on a Galaxy fold although I had added the @media query and an id="home-link" to the home page I forgot about the other pages so have now included it and it is working correctly.

Within Chrome's developer tools I also tested the larger screens of 4K screen of 2560px and the iMac Pro of 5120px which showed the site taking up about 30% of the screen. As there is a lot of real estate to take up I created a maximum width of 2400px and to centralise the view of the site. The 4K screen has about 10% of white space on either side on all the sites pages, with 5% at the bottom on the Home screen, the classes and the Shop page about the same but doesn't stand out as much because the background is white, but the Contact page shows no white space at the bottom. The 5K screen shows about 30% of white screen on either side of the site for all the pages, but with the Home page there is approximately 50%, the Classes page shows 1/3, Shop page about 5% and the Contact page has no white space at the bottom of the site. While testing the responsiveness of the site on the large screens I also noticed that the navbar menu was disappearing to the right, so a max-width was put on the header as well, so you could see the menu within the bounds of the sites screen width.

### Validators

- [W3C Markup validator](https://validator.w3.org/)
    - ### index.html
    - ![Results of html checker showing an error on line 178](/readme-images/testing/index-html-validator-result-error.png)
    - ### Once the error was corrected this was the result of the checker.
    - ![Results of html checker showing no errors or warnings](/readme-images/testing/index-html-validator-result-no-errors.png)
    - ### classes.html
    - ![Results of html checker showing an error on line 356](/readme-images/testing/classes-html-validator-result-error.png)
    - ### Once the error was corrected this was the result of the checker.
    - ![Results of html checker showing no errors or warnings](/readme-images/testing/classes-html-validator-result-no-errors.png)
    - ### shop.html
    - ![Results of html checker showing errors on lines 224, 51 and 263](/readme-images/testing/shop-html-validator-result-errors.png)
    - ### Once the errors was corrected this was the result of the checker.
    - ![Results of html checker showing no errors or warnings](/readme-images/testing/shop-html-validator-result-no-errors.png)
    - ### contact.html
    - ![Results of html checker showing errors on lines 122, 57, 61 and 75](/readme-images/testing/contact-html-validator-result-errors.png)
    - ### Once the errors was corrected this was the result of the checker.
    - ![Results of html checker showing no errors or warnings](/readme-images/testing/contact-html-validator-result-no-errors.png)
- [W3C CSS validator](https://jigsaw.w3.org/css-validator/)
    - ### style.csss
    - ![Results of css checker showing an error on line 212 with a warning on line 2](/readme-images/testing/style-css-validator-result-error-warning.png)
    - ### The error was corrected but nothing was done about line 2 as it was an imported style sheet that couldn't be comfirmed by this checker and this was the result of the checker.
    - ![Results of css checker showing no errors but still 1 warning](/readme-images/testing/style-css-validator-result-no-errors-warning.png)

After making further adjustments to the site I retested the HTML and CSS with the validators again and they showed no errors.

- ### Lighthouse

When looking at the performance, accessibility, best practices and the SEO of the website, I used **Lighthouse** in Google's development tools. The main downfall of the site is in it performance as the photos were not of the correct size in both height and width, in megabytes, and format. They also need to be more responsive over the different sizes of screens. This has caused lagging on the site when loading and linking to the other pages.
    - This still needs to be corrected.

There was also a small problem, on all the pages, with the ordering of the headings elements not being in a sequentially-descending order, but this has been rectified. On the shop there was another problem with the background and foreground colors not having a sufficient contrast ratio. When I looked at [Deque University's](https://dequeuniversity.com/rules/axe/4.10/color-contrast) site of color contrast for the colour I was using it came back with a blue colour, which was very bright and did not go with the colour design of my site, so I chose a colour from my pallet and I think that the contrast looks better than the blue they chose.

The results of the performance for the Home, Classes and Shop pages scored between 30-40 and the Contact page scored 71 for desktop but for the mobile it was 63. With accessability all of the pages scored 100 except for the Shop page with a score of 95 and with best practices and the SEO all pages getting a score of 100. 

![Lighthouse score for Always Healthy website for the Contact page on desktop](/readme-images/testing/contact-performance-71-score.png)
![Lighthouse score for Always Healthy website for the Shop page on desktop](/readme-images/testing/shop-performance-33-score.png)

After modifying the images on the site and further adjustments and styling to the pages, I re-analysed the performance, accessibility, best practices and the SEO of the website, which gave the following results:

- ### Home
- Mobile results - ![Lighthouse score for Always Healthy website for the Home page on mobile](/readme-images/testing/home-performance-mobile-score.png)
- Desktop results - ![Lighthouse score for Always Healthy website for the Home page on desktop](/readme-images/testing/home-performance-desktop-score.png)

- ### Classes
- Mobile results - ![Lighthouse score for Always Healthy website for the Home page on mobile](/readme-images/testing/classes-performance-mobile-score.png)
- Desktop results - ![Lighthouse score for Always Healthy website for the Home page on desktop](/readme-images/testing/classes-performance-desktop-score.png)

- ### Shop
- Mobile results - ![Lighthouse score for Always Healthy website for the Home page on mobile](/readme-images/testing/shop-performance-mobile-score.png)
- Desktop results - ![Lighthouse score for Always Healthy website for the Home page on desktop](/readme-images/testing/shop-performance-desktop-score.png)

- ### Contact
- Mobile results - ![Lighthouse score for Always Healthy website for the Home page on mobile](/readme-images/testing/contact-performance-mobile-score.png)
- Desktop results - ![Lighthouse score for Always Healthy website for the Home page on desktop](/readme-images/testing/contact-performance-desktop-score.png)

### Testing user defined stories from the UX section of README.md

- As a visitor to the gym, I want to know when the gym is open so that I know when I can use the gym.
    - The Home page has the opening times which includes the days the gym is open with 2 call to action buttons to the Classes or Contact Us page.
    - The Classes page can be view to check on the times the classes are run with the Timetable at the bottom of the page.
    - The Contact Us page can be filled in to book classes or enquire further.

- As a first time user of the website, I want to know what the membership and joining fees are so that I can compare them to other gyms.
    - The Home page shows details of monthly, daily and concession fees available.
    - The Home page also gives details that there is no membership, joining fees or contracts.

- As a pensioner, I want a place that is friendly and does exercise suited to my age and that is affordable.
    - The Home page gives the concession prices for pensioners.
    - From the prices there are call to action buttons to take him to the Classes page.
    - The Classes page shows all the different classes available with photos and descriptions for him to see what is suitable.
    - Classes for Over 50s and low-impact exercises are shown on the Classes page.
    - From the Classes page a call to action button takes you to the Contact Us page to book a class or ask further questions.
    - The Timetable at the bottom of the Classes page gives the times of each class.

- As a first time visitor to the gym, I want to use the gym but I have no idea how to use the equipment. Where do I start.
    - On the Home page there are details of a tour of the gym and showing how to use the equipment.
    - A call to action button takes you to the Contact page to book a visit to the gym.
    - He can get further information on the classes and see what the gym looks like from the photos on the Classes page.

- As a middle aged woman, I want a place to go where I don't feel intimidated when I exercise and ladies only events.
    - From the Home page you can navigate to the classes to look at classes that are suitable.
    - On the Classes page you can see that there is a ladies only class available.
    - The Timetable at the bottom of the Classes page will gives times of classes available.
    - You can navigate to the Shop page and see that there is clothing suitable for ladies who may want to be more comfortable while at the gym.

- As a mew user of the site, I want to be able to see what other people say about the gym.
    - Testimonials will be added to the Home page in the future.

- As a user of the site, I want to know what classes are available and book them.
    - The user can navigate to the Classes page from the Home page.
    - On the Classes page you can click on the call to action button to book a session.
    - At the bottom of the Classes page is a Timetable of all available classes and times.

### Manual testing and Functionality on each page
- ### Home Page:
    - Navigation bar
        - Clicked on each menu item (Classes, Shop, Contact) to verify that it goes to the correct page from the Home screen.
        - Clicked on the logo to see that it goes back to the Home screen.
        - Hover over logo for responsiveness on laptops and desktops. 
            - There is no explanation as to why it is a link, so I have added a title attribute to the logo to remedy this.
        - Check when hovered over the text "Link back Home" appears.
        - Hovered over each page in the menu to see that the responsiveness line appears when the curser is over the text.
        - Check the page shows the active line under the page that you are currently on.
        - Verify the responsiveness of the navigation bar on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools.
            - On the 4K and 5K screens as the header is fixed the menu went to the far right of the page outside of the sites width, so a max-width was added to fix this.
        - Verify the responsiveness of the menu not showing on mobiles smaller than the 320px per the Google's developer tools (Galaxy fold 270px).
    - Hero image and cover text
        - Verify the responsiveness of the image and text on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools.
        - Check the cover text moves from the left on mobiles, to the right on tablets and laptops, to more central on screen 1800px and higher.
    - Main section
        - Verify the responsiveness of the images and text on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools, from single column on mobiles, 2 columns on tablet, 3 columns on smaller laptops, 4 columns on larger laptops and larger screens.
            - On the 4K and 5K screens the site only covered about 30% of the screen, so a max-width was added to fix this.
        - Click on the buttons (See Classes and Contact Us) to check that they go to the correct page from the Home screen.
        - Hover over each call to action button to check the responsiveness and that they change colour.
    - Footer
        - Click on each icon to see that they go to the link address.
        - Make sure that each icon clicked opens up in a new window.
        - Hover over the icon to its responiveness on laptops and desktops.
        - Verify the responsiveness of the navigation bar on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools.
        - Verify the responsiveness of the menu not showing on mobiles smaller than the 320px per the Google's developer tools (Galaxy fold 270px).
- ### Classes Page:
    - Navigation bar
        - Clicked on each menu item (Home, Shop, Contact) to verify that it goes to the correct page from the Home screen.
        - Clicked on the logo to see that it goes back to the Home screen.
        - Hover over logo for responsiveness on laptops and desktops. 
            - There is no explanation as to why it is a link, so I have added a title attribute to the logo to remedy this.
        - Check when hovered over the text "Link back Home" appears.
        - Hovered over each page in the menu to see that the responsiveness line appears when the curser is over the text.
        - Check the page shows the active line under the page that you are currently on.
        - Verify the responsiveness of the navigation bar on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools.
        - Verify the responsiveness of the menu not showing on mobiles smaller than the 320px per the Google's developer tools (Galaxy fold 270px).
    - Main section
        - Verify the responsiveness of the images and text on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools, from single column on mobiles, 2 columns on tablet, 3 columns on smaller laptops, 4 columns on larger laptops, 6 columns on 1800px screen width, 7 columns on larger screens.
        - Verify the responsiveness of the Timetable on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools. 
        - Click on the button Contact Us to check that they go to the correct page from the Classes screen.
        - Hover over the call to action button to check the responsiveness and that they change colour.
    - Footer
        - Click on each icon to see that they go to the link address.
        - Make sure that each icon clicked opens up in a new window.
        - Hover over the icon to its responiveness on laptops and desktops.
        - Verify the responsiveness of the navigation bar on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools.
        - Verify the responsiveness of the menu not showing on mobiles smaller than the 320px per the Google's developer tools (Galaxy fold 270px).
- ### Shop
    - Navigation bar
        - Clicked on each menu item (Home, Classes, Contact) to verify that it goes to the correct page from the Home screen.
        - Clicked on the logo to see that it goes back to the Home screen.
        - Hover over logo for responsiveness on laptops and desktops. 
            - There is no explanation as to why it is a link, so I have added a title attribute to the logo to remedy this.
        - Check when hovered over the text "Link back Home" appears.
        - Hovered over each page in the menu to see that the responsiveness line appears when the curser is over the text.
        - Check the page shows the active line under the page that you are currently on.
        - Verify the responsiveness of the navigation bar on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools.
        - Verify the responsiveness of the menu not showing on mobiles smaller than the 320px per the Google's developer tools (Galaxy fold 270px).
    - Main section
        - Verify the responsiveness of the images and text on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools, from 2 columns on mobiles and tablet, 4 columns on laptops and larger screens.
            - The text is a Shiva Blue colour on the Dynamo background colour, but failed on the contrast of colours. Found that the site was picking up on Bootstraps colour Blue Raspberry and not mine and to get the better contrast I changed all the font colours to white.
    - Footer
        - Click on each icon to see that they go to the link address.
        - Make sure that each icon clicked opens up in a new window.
        - Hover over the icon to its responiveness on laptops and desktops.
        - Verify the responsiveness of the navigation bar on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools.
        - Verify the responsiveness of the menu not showing on mobiles smaller than the 320px per the Google's developer tools (Galaxy fold 270px).
- ### Contact Us Page
    - Navigation bar
        - Clicked on each menu item (Home, Classes, Shop) to verify that it goes to the correct page from the Home screen.
        - Clicked on the logo to see that it goes back to the Home screen.
        - Hover over logo for responsiveness on laptops and desktops. 
            - There is no explanation as to why it is a link, so I have added a title attribute to the logo to remedy this.
        - Check when hovered over the text "Link back Home" appears.
        - Hovered over each page in the menu to see that the responsiveness line appears when the curser is over the text.
        - Check the page shows the active line under the page that you are currently on.
        - Verify the responsiveness of the navigation bar on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools.
        - Verify the responsiveness of the menu not showing on mobiles smaller than the 320px per the Google's developer tools (Galaxy fold 270px).
    - Main section
        - Verify the responsiveness of the image and form on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools.
        - Hover over the call to action button to check the responsiveness and that they change colour.
        - Input details into the form and miss out one field to see if the pop-up message of 'Please fill out this field' appears.
        - Fill in the email details incorrectly to see if the pop-up message of 'Please include the @ in the email address' appears..
        - Click the submit button to see that the information is received by Code Institute (see image below).
    - Footer
        - Click on each icon to see that they go to the link address.
        - Make sure that each icon clicked opens up in a new window.
        - Hover over the icon to its responiveness on laptops and desktops.
        - Verify the responsiveness of the navigation bar on mobiles, tablets, laptops, 4K and 5K screens on Google's developer tools.
        - Verify the responsiveness of the menu not showing on mobiles smaller than the 320px per the Google's developer tools (Galaxy fold 270px).

### Further testing
- I viewed the site on my own mobile (Huawei P30 Pro: Chrome) and the Navigation bar appeared in full and there was only the lagging of the photos on each page. When I tested it again (after the image changes) I found that I had no propblems with clicking on the links and the loading of the pages.

### Known bugs discovered

When the site was deployed the **Social Media links** did not work but the **Navbar links** did. The closing 'a' tag did not include the icon, therefore the website address was separate from the icon. Once this was moved to enclose the website address and icon, all social media network links worked.

When the fields on the Contact Us form was filled in no pop-up messages appeared to make sure that the user input information into all the boxes. I included the **required** attribute to all the fields on the form so that the pop-up message to prompt the user to fill all the field in appears and that the email address is filled in correctly in the right format. Once the user completed the form what was sent to the gym includes everything the gym needs to contact them. 

- ### Information received by the gym from the **Contact Us form**.
- ![Email information sent to Code Institute](/readme-images/testing/email-info-code-institute-received.png)

The browsers Chrome, Edge and Firefox shows a white edge on the right hand side of the Home screen indicating the width was wider than the larger viewports as the scroll bar appears at the bottom and not on the smaller screens.
- This still needs to be looked into.

The Navbar on the mobile screen of less than 300px shows on 2 lines and maybe needs to be changed to a burger bar and dropdown menu.
- Instead it was decided that the home link could be removed as the logo can be used to get back to the home screen. A **@media query** for mobile screens smaller than 315px was used to hide the Home link on the Navbar and once it was included on all pages the response on the smaller device of the Galaxy fold showed it working correctly.

- ### Media query applied.
```
    - /* Media query; mobiles smaller (315px and down) - hide the home link */
    @media screen and (max-width: 315px) {

        /* Header */
        #home-link {
        display: none;
        }
    }
```

When on larger screens of 4K and 5K the website only covered about 30% of these large screens.
- To make the site look aesthetically better a max-width of 2400px was included on the main body and header of the website.

When hovering over the logo to take back to the Home screen, although I new that I had linked it back to the Home screen other users may not know. 
- There is no explanation as to why it is a link, so I have added a title attribute to the logo of "Link back Home" to remedy this.