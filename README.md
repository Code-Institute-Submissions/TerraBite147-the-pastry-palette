# The Pastry Palette

## Introduction

Welcome to The Pastry Palette's official website!
This virtual space has been carefully crafted with both new and cherished customers of The Pastry Palette in mind. Here, we invite you to explore the world of heavenly aromas, irresistible flavors, and artisanal creations that define our bakery's essence.

Link to site : [The Pastry Palette](https://terrabite147.github.io/the-pastry-palette/)

![Am I Responsive](./assets/images/Readme/am-i-responsive.webp)

## Contents

- [Introduction](#introduction)
- [User Experience](#user-experience)
    - [Intended Users](#intended-users)
    - [Wireframes](#wireframes)
- [Design](#design)
- [Features](#features)
    - [Nav](#nav)
    - [Home](#home)
    - [Menu](#menu)
    - [About Us](#about-us)
    - [Survey](#survey)
- [Testing](#testing)
    - [Desktop](#desktop)
    - [Mobile](#mobile)
    - [Browsers](#browsers)
        - [Edge](#edge)
        - [Chrome](#chrome)
        - [Firefox](#firefox)
- [Credit](#credit)
    -[Images](#images)
    -[Code](#code)
    -[Extensions](#extensions) 
    -[Other](#other)

#

## User Experience
### Intended Users
This site is intended for:

- New Customers
- Existing Customers
- Customers wanting to see what is available and where to find The Pastry Palette
<!-- Add User stories -->
### Wireframes

 Desktop - Home :
 The below displays the layout of the Header, Hero Section, Call to action and Menu Section.

![Desktop Home](./assets/images/Readme/TPP-1.png)

Desktop - Information Section :
The below displays the layout of the About us, Contact Section and Footer.

![Desktop Menu](./assets/images/Readme/TPP-2.png)
Desktop - Survey : The below displays the layout of the Survey page.

![Desktop Menu](./assets/images/Readme/TPP-S.png)

Mobile - Home :
The below displays the layout of the header, Hero and Call to Action scaled to 320px.
![Mobile Home](./assets/images/Readme/TPP-mobile-home.png)

Mobile - Menu :
The below displays the layout of the header, Hero and Call to Action.
![Mobile Menu](./assets/images/Readme/TPP-mobile-Menu.png)

### Design
<!-- Needs more info -->

- Font
    - Rock Salt was used for the title of The Pastry Palette.
    - git was used for the Header, footer and all text.
    - sans-serif was used as the secondary font for all text.

- Color scheme

    The Color Scheme was based off of the [Hero Image](https://www.freepik.com/premium-photo/horizontal-photo-homemade-chocolate-cookies-dark-table_2654616.htm) 

    ![#000000](https://placehold.it/150x40/000000/FFFFFF?text=000000)
    ![#362D29](https://placehold.it/150x40/362D29/ffffff?text=362D29)
    ![#FAEBD7](https://placehold.it/150x40/FAEBD7/000000?text=E1E2E7)
    ![#DADADA](https://placehold.it/150x40/DADADA/000000?text=DADADA)
    ![#F5F5F5](https://placehold.it/150x40/F5F5F5/000000?text=F5F5F5)

#
## Features
- ### nav
    - The header consists of a fix nav bar intended to stay at top of the screen during navigation. A logo or title was not necessary as the title is visible of the Hero section.
    - The nav font size will scale down with the screen size to make it clear and responsive at all sizes.
    - The links will change from ![#DADADA](https://placehold.it/150x40/DADADA/000000?text=DADADA) to ![#FAEBD7](https://placehold.it/150x40/ffffff/000000?text=FFFFFF) when hovered over to indicate a clickable link.
![Nav](assets/images/Readme/header.jpg)
- ### Home
    - The home section consists of the Hero image, a call to action to click on the survey link and an award given to the bakery.
    - This section aims to be inviting and show the quality and style of The Pastry Palette.
    ![Home](assets/images/Readme/home.jpg)
- ### Menu 
    - The menu section is presented to the user to show what type of products The Pastry Palette offers.
    - The menu section consists of 3 columns each with their own category of product.
    - Each product has a title and a short description to better showcase the product.
    ![Menu](assets/images/Readme/menu.jpg)

    - At medium resolutions the menu section will form a column  and the content will form a row.
    ![Menu Med](assets/images/Readme/medium-res.jpg)

    - At mobile resolutions the menu section will form a column and the content will be in a column.
    ![Mobile Menu](assets/images/Readme/mobile-res.jpg)
- ### about us 
    - The about us section is designed to show customers the people behind The Pastry Palette, a brief history of the bakery and the location(s).

    -  The google map has been added to assist with directions and the hours and contact info is shown for enquires.
    ![About Us](assets/images/Readme/about-us.jpg)

    - The About us section is designed to form a single column at mobile resolutions.

        ![Mobile About Us](assets/images/Readme/mobile-about-us.jpg)

- ### Survey
    - The Survey section is designed to gather feed back and potential online ordering feasibility 
    - The Head and Footer follow the same lay-out as all other pages.
    - The Survey consists of a welcome message and a form section.
        - The form has five input sections
            - Name and Email : text fields (required)
            - A bakery location dropdown with 4 options (required)
            - A radio section containing 4 options (required)
            - A Feedback text field if the users would like to leave feedback (not required)
        - A submit button that will direct the user to the thank-you page.
        ![Survey](assets/images/Readme/survey.jpg)

### Survey Thank you
- The Thank you 
    - Once on the thank you page the user will be greeted with a thank you message and more info on the competition.
![Thank you](assets/images/Readme/survey-thank%20you.jpg)


## Testing

**TEST** | **ACTION** | **EXPECTATION** | **RESULT** 
----------|----------|----------|----------
Index  	            | Size to 320px using Edge , Chrome and Firefox Dev Tools	| Elements look good @ 320px    | Works as expected
Index	            | Size to 1920px using Edge , Chrome and Firefox Dev Tools  | Elements look good 1920px     | Works as expected
Survey              | Size to 320px using Edge , Chrome and Firefox Dev Tools	| Elements look good @ 320px    | Works as expected
Survey	            | Size to 1920px using Edge , Chrome and Firefox Dev Tools  | Elements look good 1920px     | Works as expected
Thank-you  	        | Size to 320px using Edge , Chrome and Firefox Dev Tools	| Elements look good @ 320px    | Works as expected
Thank-you	        | Size to 1920px using Edge , Chrome and Firefox Dev Tools  | Elements look good 1920px     | Works as expected
Index survey button | Click "We want your feedback button                       | Direct to Survey.html         | Works as expected
Survey form         | Click send button without data in form fields             | Cannot submit form            | Works as expected
Survey form         | Click send button with data in form fields                | Redirected to thank-you.html  | Works as expected
Nav bar - Index     | Click nav buttons| That each nav element takes me to the correct page site page           | Works as expected
Nav bar - Survey    | Click nav buttons| That each nav element takes me to the correct page site page           | Works as expected
Nav bar - Thank you | Click nav buttons| That each nav element takes me to the correct page site page           | Works as expected
Footer              | Click social media links | That each link opens a new page to the correct site            | Works as expected


### Lighthouse results 
![Lighthouse](assets/images/Readme/lighthouse.jpg)

### w3c code Validator  
- HTML
    - index.html
        - Document checking completed. No errors or warnings to show.
    - survey.html
        - Document checking completed. No errors or warnings to show.
    - thank-you.html
        - Document checking completed. No errors or warnings to show.
- CSS
    - style.css
        - No errors, 2 warning about imported style sheets not being checked, can be ignored as these are font imports.

## deployment
- GitHub pages was utilized for deployment 
  - Log in to GitHub and locate the GitHub Repository 
  - At the top of the Repository click on "Settings" Button on the menu. 
  - click on "Pages".
  - Under "Source", click the dropdown called "None" and select your master branch. 
  - On the right hand side of the page, under "Environments", you will see a link to the deployed site.

## Credit

### Images


[Hero Image](https://www.freepik.com/premium-photo/horizontal-photo-homemade-chocolate-cookies-dark-table_2654616.htm)

[5 Stars](https://pixabay.com/illustrations/five-stars-stars-feedback-review-7292866/)

[Wholemeal](https://pixabay.com/photos/ciabatta-bread-baked-baker-food-1589083/)

[Sourdough](https://pixabay.com/photos/bread-baker-crafts-food-oven-eat-2667075/)

[French Coarse](https://pixabay.com/photos/french-coarse-country-bread-bread-1613878/)

[Macaroons](https://pixabay.com/photos/macaroons-macro-cookies-dessert-3311851/)

[Pain Au Chocolat](https://pixabay.com/photos/chocolate-bread-breakfast-croissant-5087206/)

[Cinnamon Rolls](https://pixabay.com/photos/cinnamon-rolls-bread-spiral-baking-1417494/)

[Blue Berry Cheesecake](https://pixabay.com/photos/blue-berry-cheese-cake-blue-berry-4547988/)

[Tiramisu](https://www.pexels.com/photo/close-up-shot-of-tiramisu-cake-14766327/)

[Assorted Cupcakes](https://www.freepik.com/premium-photo/close-up-muffins-with-piece-chocolates_2518241.htm)

[Bakery](https://pixabay.com/photos/bakery-breads-assorted-assortment-1868925/)

[Spice](https://stock.adobe.com/images/Spice-up-your-winter-dessert-with-anise-generated-by-AI/606085312?as_campaign=TinEye&as_content=tineye_match&clickref=1101lxHTUiDt&mv=affiliate&mv2=pz&as_camptype=backlink&as_channel=affiliate&as_source=partnerize&as_campaign=tineye)


### Code

- [Flex](https://youtu.be/phWxA89Dy94) - This tutorial help me understand flex which was utilized through the project.
- [Responsive Lay-out](https://www.youtube.com/watch?v=S0a7PEOi0do) - This tutorial assisted with responsive lay-out.
- [Markdown Guide](https://www.markdownguide.org/cheat-sheet/) - Assisted with markdown styling.

### Extensions :
- [WAVE](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh) : website evaluation tool used for testing.
- [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln) : Assisted with finding overflow issues.

### Other
- [Figma](https://www.figma.com/) - Utilized for wire frames.
- [Gimp](https://gimp.com) - used for editing images.
- [VS CODE](https://code.visualstudio.com/) - Used for creating and editing code.