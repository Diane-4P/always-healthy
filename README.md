# Always Healthy Website

[View Always Healthy deployed site here.](https://diane-4p.github.io/always-healthy/)

![Home page of Always Healthy gym website with Worcester Cathedral in the background](/readme-images/mochups-website-always-healthy-gym.png)

****

## Introduction

Our main goal at Always Healthy is to encourage new users to visit the gym and join to get healthy on a physical and spiritual level. It targets not only the young and professional to join the gym to use the equipment but also encourages the mature and elderly to do Yoga, Pilates or meditation, for the well being of the people who attend the gym. The simple design helps to give users the basic information needed to answer their initial questions, plus helps them to look further into the classes and to contact us for information or to book session.

****

## Table of Contents

- [User Experience](#user-experience-ux)
- [Designs](#design-choices)
- [Wireframes](#wireframes)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Deployment](#deployment)
- [Credits](#credits-references)
- [Acknowledgements](#acknowledgements)

****

## User Experience (UX)

## Strategy

### Gym Owners Goals

The client is interested in attracting new users to join the gym and to continue to use the facilities. The client wants to encourage and retain current gym clients. Also, the client wants more senior citizens to join the gym looking for low-impact exercises for mobility, strength and balance. 

The gym has no membership fees, but there is a monthly fee to encourage new and repeat users to use the gym regularly. We also offer reduced prices for the money conscious and pensioners, with a variety of classes available to appeal to the younger and more mature clients to partake in. If users have any questions then they can always contact us, where we will be happy to give them further information.

- ![Home page of Always Healthy site](/readme-images/home-page-owner-goals.png)

## Scope

### User Stories
- 
| As a visitor to the gym, I want to know when the gym is open so that I know when I can use the gym. | As a first time user of the website, I want to know what the membership and joining fees are so that I can compare them to other gyms. | As a pensioner, I want a place that is friendly and does exercise suited to my age and that is affordable. | As a first time visitor to the gym, I want to use the gym but I have no idea how to use the equipment. Where do I start. |
|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|
| The opening times shows the days of the week, and opening and closing times of the gym. | The user can see that there are no joining fees, but for a monthly fee where they can use the gym or classes at anytime. | The concession price for pensioners and the image of a mature couple meditating shows something that they can do. | With the tour available you can see all the facilities plus learn how to use the equiment properly and safely. |
| ![Gym Opening Times](/readme-images/gym-opening-times.png) | ![Membership and Joining Fees](/readme-images/membership-no-fees.png) | ![Standard and Concession Prices](/readme-images/standard-concession-prices.png) | ![Tour of the Gym](/readme-images/tour-gym-first-time.png) |
- 
| As a middle aged woman, I want a place to go where I don't feel intimidated when I exercise and ladies only events.  |
|----------|
| There is a ladies only event, which includes an instructor for groups or singles. Also, outfits are available to cover you more appropriately. |
| ![Ladies only with Instructor if wanted](/readme-images/ladies-only-instructor.png) ![Long-sleeved top and leggins](/readme-images/ladies-long-sleeved-top-leggins.png) ![T-shirt and leggins](/readme-images/ladies-tshirt-leggins.png) |

| As a user of the site, I want to know what classes are available and book them. |
|----------|
| There is a ladies only event, which includes an instructor for groups or singles. Also, outfits are available to cover you more appropriately. | Classes timetable with times, class, where held and images, descriptions of classes and the ability to contact the gym. |
| ![Classes Timetable](/readme-images/classes-timetable.png) ![Gym Classes and description](/readme-images/classes-image-description.png) |

### What a User may want

- As a new visitor to the site I want tobe able to see what other people say about the gym.
- As a new user of the site I want to see the gyms social media pages to see what the gym is like.
- As a user of the site I want to be able to purchase any clothing or equipment I need online.

## Structure

The website originally had 3 separate pages of Home, Gallery and Contact but this was changed to split the Gallery and include the images within the Classes and Shop pages.

- The Home page is made up of a Welcome, Opening Times, Monthly and Pay As You Go payment methods.
- The Classes page is of pictures of the people using and doing the classes that are described below each image. It also, shows a Timetable of when the classes are available.
- The Shop is showing images of clothing, footware and drinks bottles that are available at the gym.
- The Contact page is a form in which you can contact the gym with questions or to book classes.

****

## Design Choices

## Surface

### Colour

The colours chosen were obtained from a sample of the blue on the Home page hero image and put into a pallet picker from [mycolor.space](https://mycolor.space/) where I chose the matching gradient pallet with blues and purples. These were converted into RGB by using [Rapid Tables](https://www.rapidtables.com/convert/color/hex-to-rgb.html?hex=97406a) so that the transparency coould be used and to obtain the names for the colours I used [colornamer.robertcooper.me](https://colornamer.robertcooper.me/) (Shiva Blue rgb(148, 216, 251), Electric Eel rgb(140,188, 237), Portage rgb(143, 158, 217), Lavender Purple rgb(151, 126, 187), Bermuda Onion rgb(155, 95, 150), and Dynamo rgb(151, 64, 106))

![Matching Gradient colours from mycolor.space](/readme-images/color-design-matching-gradient.png)

### Typography

For the fonts I used [Google Fonts](https://fonts.google.com/). The Montserrat was used for the main font on the website with Sans-serif as its fallback font, just in case the main font does not get imported to the website correctly. Montserrat is used frequently in programming due to its clean look. The headings had the Rubik font for a subtle different look, which also has the Sans-serif as the fallback font. For the logo the Rouge Script was used for its decorative properties, with the Serif font as its fallback.

The following code was imported into the top of my style.css file:

```
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Rouge+Script&family=Rubik:ital,wght@0,300..900;1,300..900&display=swap');
```

### Imagery

The main image on the Home page is a photo of Worcester's Cathedral and as a land mark of the town, it shows the city the gym is located in, with a banner that immediately lets the user know what the site is about. As the website is for a project and I had no images to use, but I wanted to show that users of the gym were happy while working out at the gym. All the other images were sourced from [Pexels](https://www.pexels.com/), [Unsplash](https://unsplash.com/), [Stockvault](https://www.stockvault.net/), [Pixaby](https://pixabay.com/), [Pikwizard](https://pixabay.com/) and [Technogym](https://www.technogym.com/en-INT/omnia-class/). You can find the full list of each individual image in the [credits](#credits-references). All images have **alt tags** with text for screen readers to describe the image, or if the image fails. I resized the images using [Tiny WOW](https://tinywow.com/image/resize), compressed them to make the file size smaller with [TinyPNG](https://tinypng.com/) and [Image Compressor](https://imagecompressor.com/), and then I finally changed the format of the images from jpg to webp, using an extension to Chrome of **Convert WebP to JPG**.

****

## Skeleton

## Wireframes
These were the original look of the site and the Gallery was exchanged for a Shop page which in the future will enable users to purchase online.
- Home
    - [For Mobile](/readme-images/Wireframes/Home/home-mobile-wireframe.png)
    - [For Tablet](/readme-images/Wireframes/Home/home-tablet-wireframe.png)
    - [For Desktop](/readme-images/Wireframes/Home/home-desktop-wireframe.png)
- Classes
    - [For Mobile](/readme-images/Wireframes/Classes/classes-mobile-wireframe.png)
    - [For Tablet](/readme-images/Wireframes/Classes/classes-tablet-wireframe.png)
    - [For Desktop](/readme-images/Wireframes/Classes/classes-desktop-wireframe.png)

- Gallery
    - [For Mobile](/readme-images/Wireframes/Gallery/gallery-mobile-wireframe.png)
    - [For Tablet](/readme-images/Wireframes/Gallery/gallery-tablet-wireframe.png)
    - [For Desktop](/readme-images/Wireframes/Gallery/gallery-desktop-wireframe.png)
- Contact
    - [For Mobile](/readme-images/Wireframes/Contact/contact-mobile-wireframe.png)
    - [For Tablet](/readme-images/Wireframes/Contact/contact-tablet-wireframe.png)
    - [For Desktop](/readme-images/Wireframes/Contact/contact-desktop-wireframe.png)

****

## Features

### Universal across the site

Each page has a **header** with the responsive **logo**, linking to the Home page with a title of "Link back Home" to inform the users where the link goes, in the top left hand corner. A responsive **navigation bar**, linking to all the pages on the website (Home, Classes, Shop, Contact) to the top right. The navigation bar is fixed in position and when you hover over the page titles a line appears underneath. The page that is active has a fixed line so that users can see which page they are on. Each page has a separate title so you can tell from the tab which page you are on.

The **footer** includes the **social media icons** of **Facebook, Twitter and Instagram,** linking them to their respective home pages, which opens in a new page, due to the **target="_blank"**. The footer also includes the **copyright information** and the **registered address** of the company. All buttons on each page change colour when you **hover** over them to click the link or send infomation to the gym via the contact form.

### Home

The Home page features a **hero image** of the **Worcester Cathedral** with a text overlay with the text **"Always Healthy, Keeping healthy in Worcester, Come and join us in an atmosphere that will keep you fit and healthy"** to encourage users to join the gym. The overlay has a transparent background so the the view of the Cathedral is still visible, but does not impose on the words to give maximum impact when landing on the page. The image is still showing a 5 second load time which is impacting on the performance of the mobile.

There is a welcome to the site with information on how to join, opening times and various payment methods. There are images of various people enjoying and using the gym, which shows that the gym is a happy enviroment for all age groups to exercise and become healthier. There are also **call to action buttons** guiding the user to go look at the classes that are available or to contact the gym if they wish to join a class or ask for more information. Each card originally had both buttons but did not look right on one page so I changed this to just one button of each call to action button.

- ![Home page of Always Healthy site](/readme-images/home-page-owner-goals.png)

### Classes

The Classes page features 10 images of the classes that are available, so that you can see from the photos and the description below what the class entails and whether it would be suitable for the young or mature members of the gym. There is also a **call to action button** below the classes descriptions to join and book one of the classes via the Contact page. This page had a **Contact Us button** on each class but was also removed to just a single button at the bottom, which makes the look of the page more simplistic.

- ![Gym Classes and description](/readme-images/classes-image-description.png)

To help keep people informed of classes there is a timetable at the bottom of the page showing what time, the type of class and where the class is held. The Timetable was created using a **table** for uniformity and its 2 tone colours of Portage and Lavender Purple with transparency, so that the colours didn't overwelm the text. 

- ![Classes Timetable](/readme-images/classes-timetable.png)

### Shop

The Shop page is laid out in columns with the image and a small description of the product and the price, to show that there is clothing, trainers, and drinks bottles available for new or recurring members of the gym, whether young or mature. On the mobile the design choice of 2 columns wide was chosen to show more items on the smaller screen so that users would not get discouraged by seeing one product at a time. This page will be changed in the future so that the products can be purchased online.

- ### Clothing
    - ![Clothing products](/readme-images/all-clothing-products.png)
- ### Footware
    - ![Footware products](/readme-images/all-footware-products.png)
- ### Bottles
    - ![Bottles products](/readme-images/all-bottles-products.png)

### Contact

The Contact page features a **contact form**, which requests an enquirers first and last names, email address and phone number. You also have a box to put details of your message, whether its to join the club, join a class or ask questions for further details etc. There is also a **send button** at the bottom of the form. The form has a transparent background so that you can see the full page image of a woman using the dumbbells. This image shows what the gym is like and to encourage users to join the gym. All the information input onto the form is **required** so if any field is left empty then a message appears to let the user know that the details are required. There is also **placeholer text** to show what format the input text needs to be in. Once the form is fully filled in then you can use the **call to action** button and **send the message** to the gym.

![Contact Us page](/readme-images/contact-us-page.png)

## Features to Implement in the Future

- Set up social media pages for Facebook, Twitter and LinkedIn to encourage more people to join.
- Add a checkout basket and to receive payments to the shop, so can purchase products online.
- Add testimonials to the Home page to let users see how other gym members are enjoying the gym.
- Add FAQ table with drop down answers to the Home page so users get answers to their questions quicker.
- Login for users of the gym to enable them to book classes online.
- Change the send button on the Contact page to have a pop-up to show the message has been received.
- Add GDPR compliant pop-up to approve of using personal data and to comply with data protection law.

****

## Technologies Used

### Languages
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/CSS)

### Frameworks, Libraries and Programs used
- [Code Institute CDN](https://codeinstitute-ide.net)
    - Gitpod workspace was used for writing the code to building the website. Within Gitpod a beautifier was used to format the html code layout.
- [Bootstrap v5.3.3 CDN via jsDelivr](https://getbootstrap.com/)
    - Used for styling and make it more responsive.
- [Google Fonts](https://fonts.google.com/) 
    - To import font Montserrat, Rubik and Rouge Script onto the style.css file to be used on all pages. Also, Sans-serif and Serif were used as their fallbacks. 
- [Font Awsome](https://fontawesome.com/)
    - Icons were added were added to all pages of the website for aesthetic and UX purposes.
- [Git](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)
    - Version Conrol System used to track changes in source code using the Gitpod terminal to commit messages and push to GitHub.
- [GitHub](https://github.com/)
    - GitHub was used to store the website after being pushed from Git.
- [Tiny PNG](https://tinypng.com/)
    - To compress all images to smaller file size.
- [Image Compressor](https://imagecompressor.com/)
    - The Image Compressor was used to compress the Opening Times image as the files size was too big for Tiny PNG.
- [Tiny Wow](https://tinywow.com/image/resize)
    - Used to resize images
- [Convert webp to jpg](chrome-extension://lioppfcbaohgghplacfgajfhbpmlhnbc/src/action/index.html) - an extension on Chrome
    - Used to convert jpg images to webp images
- [Deque University](https://dequeuniversity.com/rules/axe/4.10/color-contrast)
    - Checking the colour contrast of my Shop page.
- [Beautifier](https://beautifier.io/)
    - To uniform the layout by formating the code for CSS and HTML.
- [Balsamic Wireframes](https://balsamiq.com/)
    - Create wireframes for the layout of the site.

### Testing
- [W3C Markup validator](https://validator.w3.org/)
    - Testing the validity of html files.
- [W3C CSS validator](https://jigsaw.w3.org/css-validator/)
    - Testing the validity of css files.
- [Am I Responsive](https://ui.dev/amiresponsive)
    - Checking the responsiveness of the website.
- Lighthouse tab within Chrome Developer Tools
    - Testing the Performance, Accessibility, Best Practices and SEO of the site.

****
## Testing Performed

[View TESTING.md file](/TESTING.md)

****

## Deployment

### GitHub Pages

The site was deployed to GitHub Pages using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/).
2. Navigate to the "Settings" of the repository, located at the top of the page in the menu.
3. On the left hand side is a menu, and click on the "Pages" from the Code and Automation section.
4. Under "Branch" click on the dropdown menu called "None" and select "Main".
5. On the dropdown menu next to "Main" select "Root" and click the "Save" button.
6. Navigate to the "Code" of the repository, located at the top of the page in the menu.
7. On the right hand side is an "About" section and below that is the "Deployments" which shows the GitHub pages thats deployed.

The live link can be found [here](https://diane-4p.github.io/always-healthy/).

The site is hosted using GitHub pagaes and is deployed via the main branch. The deployed site uses a Version Conrol System to track changes in the source code using the Gitpod terminal to commit messages and push then to GitHub. This will update the repository automatically when GitHub receives these commits in the main branch. The main landing page of the site has to be named index.html in order for the site to be deployed correctly, as the search engines are looking for this document to load the site onto the web.

### Cloning

To run the site locally, you can clone the repository into the code editor of your choice by pasting the git clone https://github.com/Diane-4P/always-healthy.git (using the https) into your terminal. To then stop using the repository and cut ties with it you type 'git remote rm origin' into the terminal.

### Forking

When you fork a GitHub repository you will make a copy of it, which can be put into your own account and you can make changes without affecting the original repository.

1. Log into GitHub and locate the GitHub Repository you want to fork.
2. At the top of the repository to the right, under the menu, there is a "Fork" button.
3. You should have a copy of the original repository in your own GitHub account.

****

## Credits (references)
- ### Code
- Table
    - [StackOverflow post No.169](https://stackoverflow.com/questions/20825211/bootstrap-table-striped-how-do-i-change-the-stripe-background-colour)
        - Was used to override stripes to change Bootstraps colours to the colours of the website and the colours were then made transparent.
        ```
        .table-striped>tbody>tr:nth-child(odd)>td, 
        .table-striped>tbody>tr:nth-child(odd)>th {
        background-color: red; // Choose your own color here
        }
        ```

- Bootstrap and W3 Schools
    - [Bootstrap v5.3.3](https://getbootstrap.com/) library and [W3 Schools](https://www.w3schools.com/css/default.asp) was used throughout the production of the site to make it responsive on all devices.
        - Cards (adapted to suit the site I was creating)
        ```
        <div class="card" style="width: 18rem;">
        <img src="..." class="card-img-top" alt="...">
        <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        </div>
        <ul class="list-group list-group-flush">
            <li class="list-group-item">An item</li>
            <li class="list-group-item">A second item</li>
            <li class="list-group-item">A third item</li>
        </ul>
        <div class="card-body">
            <a href="#" class="card-link">Card link</a>
            <a href="#" class="card-link">Another link</a>
        </div>
        </div>
        ```
        ```
        <div class="card" style="width: 18rem;">
        <img src="..." class="card-img-top" alt="...">
        <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
        </div>
        ```
        - Form (adapted to suit the site I was creating)
        ```
        <div class="row">
        <div class="col">
            <input type="text" class="form-control" placeholder="First name" aria-label="First name">
        </div>
        <div class="col">
            <input type="text" class="form-control" placeholder="Last name" aria-label="Last name">
        </div>
        </div>
        ```
        ```
        <form>
        <label for="phone">Enter your phone number:</label>
        <input type="tel" id="phone" name="phone" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}">
        </form>
        ```

- ### Content
    - All content was written by the developer.
    - Colours
        - [mycolor.space](https://mycolor.space/?hex=%2394D8FB&sub=1) 
            - Is a colour pallet that was used to create a pallet for the design.
        - [Rapid Tables](https://www.rapidtables.com/convert/color/hex-to-rgb.html?hex=97406a)  
            - Colours originally were in Hexidesimal colour values and I needed to convert them into an RGB format so that I could use RGBA for the alpha channel to change the opacity of the colours used on the website.
        - [colornamer.robertcooper.me](https://colornamer.robertcooper.me/)  
            - Name of colours was obtained on Colornamer as I made a note of the colours next to the CSS styling to describe what the Hex or RGBA values were.
    
- ### Images
    - Favicon image used came from the [Code Institute](https://codeinstitute.net/) Love Running project in their Full Stack Developer course.
    ```
    <link rel="apple-touch-icon" sizes="180x180" href="assets/favicon/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="assets/favicon/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="assets/favicon/favicon-16x16.png">
    ```
    - Home page
        - Hero - [Pixaby](https://pixabay.com/photos/worcester-england-cathedral-church-172391/) (2013)
        - Welcome - [Pixaby](https://pixabay.com/photos/woman-gym-person-1730325/) (2016)
        - Opening Times [Unsplash](https://unsplash.com/photos/woman-using-dumbbells-3jAN9InapQI) 2019 by Cathy Pham
        - Monthly - [Unsplash](https://unsplash.com/photos/a-row-of-exercise-machines-in-a-gym-ndr4vtteVGw) (2021) by Craig Lovelidge
        - Pay As You Go - [Pexels](https://www.pexels.com/photo/a-man-and-woman-lying-down-on-yoga-mats-7500662/) (2021) by Mikhail Nilov
    - Classes page
        - Pilates - [Pexels](https://www.pexels.com/photo/group-of-woman-doing-yoga-868483/) (2018) by Andrea Piacquadio 
        - Yoga - [Pexels](https://www.pexels.com/photo/three-woman-doing-an-exercises-868757/) (2018) by Andrea Piacquadio 
        - Step Aerobics - [Pikwizard](https://pikwizard.com/photo/dynamic-aerobics-class-learning-step-exercises-with-dumbbells/5ef588aab82cc96b05af2a5c9b916624/)
        - Over 50s - [Unsplash](https://unsplash.com/photos/people-exercising-Vz0RbclzG_w) (2019) by Anupam Mahapatra
        - Wellness - [Pexels](https://www.pexels.com/photo/elderly-women-lying-on-yoga-mats-8436545/) (2021) by Yan Krukau
        - Zumba - [Pexels](https://www.pexels.com/photo/group-of-people-in-a-fitness-class-5936039/) (2019) by David Awokoya
        - Pump Workout - [Pexels](https://www.pexels.com/photo/women-having-exercise-using-dumbbells-903171/) (2018) by Andrea Piacquadio 
        - Ladies Only - [Stockvault](https://www.stockvault.net/photo/203704/lifting-weights) (2016) Author Pixaby and Licence Creative Commons
        - Spinning - [Unsplash](https://unsplash.com/photos/women-taking-exercise-on-black-stationary-bikes-in-front-of-gray-concrete-wall-A_ftsTh53lM) (2018) by Trust Tru Katsande
        - Omnia HIIT - [Technogym](https://www.technogym.com/en-INT/omnia-class/) from their website
    - Shop page (images in order of website)
        - Clothing
            1. [Pexels](https://www.pexels.com/photo/woman-and-man-posing-in-gym-clothing-17917176/) (2023) by Bamboo Ave
            2. [Pexels](https://www.pexels.com/photo/two-mature-women-wearing-black-gym-clothes-8374555/) (2021) by Darina Belonogova
            3. [Pexels](https://www.pexels.com/photo/man-and-woman-stretching-together-4852749/) (2020) by Ketut Subiyanto
            4. [Pexels](https://www.pexels.com/photo/couple-practicing-yoga-6787501/) (2021) by Marcus Aurelius
            5. [Pexels](https://www.pexels.com/photo/muscular-man-in-sportswear-20400652/) (2024) by Jaime Blanchart
            6. [Pexels](https://www.pexels.com/photo/smiling-young-black-sportswoman-warming-up-before-training-6311255/) (2020) by Monstera Production
            7. [Pexels](https://www.pexels.com/photo/happy-woman-holding-a-tennis-racket-6250893/) (2020) by Anna Shvets
            8. [Pexels](https://www.pexels.com/photo/woman-drinking-water-from-reusable-bottle-6283505/) (2020) by Anna Shvets
        - Footwear
            1. [Pexels](https://www.pexels.com/photo/colorful-fashioned-pair-of-sports-shoes-1456706/) (2017) by Ray Piedra
            2. [Pexels](https://www.pexels.com/photo/close-up-of-a-woman-tying-her-shoe-26088459/) (2023) by Marcus Silva
            3. [Pexels](https://www.pexels.com/photo/black-under-amour-sneakers-163535/) (2016) by Pixabay
            4. [Pexels](https://www.pexels.com/photo/red-and-white-sport-footwear-on-a-ground-16539682/) (2023) by the mole
        - Drinks Bottles
            1. [Pexels](https://www.pexels.com/photo/white-water-bottle-and-basketball-ball-5274535/) (2020) by Cottonbro Studio
            2. [Pexels](https://www.pexels.com/photo/a-man-drinking-from-a-tumbler-4853115/) (2020) by Ketut Subiyanto
    - Contact page - [Unsplash](https://unsplash.com/photos/woman-standing-surrounded-by-exercise-equipment-CQfNt66ttZM) (2018) by Danielle Cerullo

****

## Acknowledgements
- My Mentor - Brian Macharia - for his helpful feedback.
- Inspiration for the website came from looking at other gyms website in the area.

## Disclaimer

This site and content are for educational purposes only.
