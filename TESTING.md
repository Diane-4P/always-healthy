# Always Healthy Website - Testing details

[View README.md file](/README.md)

[View Always Healthy deployed site here.](https://diane-4p.github.io/always-healthy/)

## Testing

### Browsers

When opening the site in the browsers Chrome, Firefox and Edge, they all showed lagging in opening up onto the landing page. All 3 browsers also showed a white edge on the right hand side of the screen indicating the width was wider than the large viewports as the scroll bar appeared at the bottom and not on the smaller screens.

When I created a mochup of the website on **Am I Responsive**, the **Navbar** on the mobile appeared on 2 lines, which happens when the screen is less than 300px.

### Validators

- [W3C Markup validator](https://validator.w3.org/)
    - ### index.html
    - ![Results of html checker showing an error on line 178](/assets/images/testing/image-3.png)
    - ### Once the error was corrected this was the result of the checker.
    - ![Results of html checker showing no errors or warnings](/assets/images/testing/image-4.png)
    - ### classes.html
    - ![Results of html checker showing an error on line 356](/assets/images/testing/image-5.png)
    - ### Once the error was corrected this was the result of the checker.
    - ![Results of html checker showing no errors or warnings](/assets/images/testing/image-6.png)
    - ### shop.html
    - ![Results of html checker showing errors on lines 224, 51 and 263](/assets/images/testing/image-7.png)
    - ### Once the errors was corrected this was the result of the checker.
    - ![Results of html checker showing no errors or warnings](/assets/images/testing/image-8.png)
    - ### contact.html
    - ![Results of html checker showing errors on lines 122, 57, 61 and 75](/assets/images/testing/image-9.png)
    - ### Once the errors was corrected this was the result of the checker.
    - ![Results of html checker showing no errors or warnings](/assets/images/testing/image-10.png)
- [W3C CSS validator](https://jigsaw.w3.org/css-validator/)
    - ### style.csss
    - ![Results of css checker showing an error on line 212 with a warning on line 2](/assets/images/testing/image-11.png)
    - ### The error was corrected but nothing was done about line 2 as it was an imported style sheet that couldn't be comfirmed by this checker and this was the result of the checker.
    - ![Results of css checker showing no errors but still 1 warning](/assets/images/testing/image-12.png)

- ### Lighthouse

When looking at the performance, accessibility, best practices and the SEO of the website, I used **Lighthouse** in Google's development tools. The main downfall of the site is in it performance as the photos were not of the correct size in both height and width, in megabytes, and format. They also need to be more responsive over the different sizes of screens. This has caused lagging on the site when loading and linking to the other pages.
    - This still needs to be corrected.

There was also a small problem, on all the pages, with the ordering of the headings elements not being in a sequentially-descending order, but this has been rectified. On the shop there was another problem with the background and foreground colors not having a sufficient contrast ratio. When I looked at [Deque University's](https://dequeuniversity.com/rules/axe/4.10/color-contrast) site of color contrast for the colour I was using it came back with a blue colour, which was very bright and did not go with the colour design of my site, so I chose a colour from my pallet and I think that the contrast looks better than the blue they chose.

The results of the performance for the Home, Classes and Shop pages scored between 30-40 and the Contact page scored 71 for desktop but for the mobile it was 63. With accessability all of the pages scored 100 except for the Shop page with a score of 95 and with best practices and the SEO all pages got a score of 100. 

![Lighthouse score for Always Healthy website for the Contact page on desktop](/assets/images/testing/image-13.png)
![Lighthouse score for Always Healthy website for the Shop page on desktop](/assets/images/testing/image-14.png)

### Testing user defined stories from the UX section of README.md

- As a visitor to the gym, I want to know when the gym is open so that I know when I can use the gym.
    - On the Home page there are opening times and the days the gym is open with 2 call to action buttons to the Classes or Contact Us page.
    - The Classes page can be view to check on the times they run with the Timetable at the bottom of the page.
    - The Contact Us page can be filled in to book classes or enquire further.

- As a first time user of the website, I want to know what the membership and joining fees are so that I can compare them to other gyms.
    - The Home page shows details of monthly, daily and concession fees available.
    - The Home page also states that there is no membership, joining fees or contracts.

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
    - He can get further information on the classes and see what the gym looks like from the photos.

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

### Further testing

- I have tested that the Navbar and the Logo links worked correctly and that they go to the correct page and the active line and the hover works when doing this.
- I have tested that the Social Media links work and they open up in a new tab on all pages.
- I have tested that the Contact Us buttons work on the Classes page by going to the Contact page and the buttons change when hovered over.
- I have tested that the Contact Us form has all the input fields filled out before the user can submit the form. When one of the fields is empty the message 'Please fill out this field' appears when the first and last names, telephone and the message fields are empty. If the email address is input incorrectly then the message 'Please include the @ in the email address'.


### Known bugs discovered

When the site was deployed the **Social Media links** did not work but the **Navbar links** did. The closing 'a' tag did not include the icon, therefore the website address was separate from the icon. Once this was moved to enclose the website address and icon, all social media network links worked.

When the fields on the Contact Us form was filled in no messages appeared to make sure that the user input information into all the boxes. I included the required attribute to all the fields on the form so that the what was sent to the gym included everything needed from the user to contact them again in relation to their enquiry. 

- Information received by the gym from the **Contact Us form**.
- ![Email information sent to Code Institute](/assets/images/testing/image-15.png)