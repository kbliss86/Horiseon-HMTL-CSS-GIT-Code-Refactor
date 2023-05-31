# Bootcamp Module 01 Challenge - Refactoring Landing Page Code

## Description
This is a landing page for a marketing company specializing in "SEO" or "Search Engine Optimization" - it is part of the sample code provided by the northwestern coding bootcamp, the original code can be found: https://github.com/coding-boot-camp/urban-octo-telegram

The goal of this excercise was to adjust the HTML/CSS code to ensure that it is AA compliant. The starter code was enough to make the website "appear" correct, but it was not coded properly for use with "assistive technologies" and needed to be adjusted so that it contained "Semantic Elements".

I was able to input the correct elements and replace the "div" elements that were the primary element on the page. I added alt names to all the images including the background image in the "hero" section. I also added a proper "title" to the page. 

For the hero section on the web page, i made that into a "figure" since it was a self contained image that was independent of the other webstite content. I added a "figcaption" to the figure section and created a .css code block to make the caption appear invisible using:
    .hero figcaption {
    visibility: hidden;
    }
This way, an assistive technology can read the caption but it will not interfere with the "look" of the iamge.

I changed the footer element and changed the "h2" to "h4" so that any assistive technology would not have difficulty telling that header section apart from the main content section!

I fixed an issue with the "Search Engine Optimization" link not working properly due to a missing id in the main content section.

I noted in the code that there were Classes assigned to elements in the "main content" and "Benefits" sections that were not neccessary, The CSS required for those sections does not need to utilize "classes" other than the ones associated with the images for Left/right float. I kept the classed in for future scalability of the project!

I adjusted the CSS code to be in line sequentially with the HTML by moving all the "benefits" class CSS below the "content" class CSS but above the "footer" CSS. This was done to make it easier for other developers in the future to make adjustments.

I Adjusted the code for several classes  to be more "universal" for the section of code they were in, this resulted in the removal of 12 code blocks from the CSS file, which should make it easier for future developers to manage!

## How to install and run the project
To view the web page you can go to: https://kbliss86.github.io/bootcamp-challenge-01/ or you can clone the repository onto your local drive and view it in preview mode there by visting the repository here: https://github.com/kbliss86/bootcamp-challenge-01.

## Use of the project
The use of this project is for educational purposes only on how to properly set up a web page to be AA compliant.

## Credits
This project starter code was provided by Northwest coding bootcamp and all comments and edits were made by me

## Screenshots
![Website header and nav bar with "hero" section](../assets/images/Horiseon%20SC%20-01.PNG)
![Website main and sub content](../assets/images/Horiseon%20SC%20-02.PNG)
![Website Footer Content](../assets/images/Horiseon%20SC%20-03.PNG)
