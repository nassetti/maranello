# Museo di Maranello

The Museo di Maranello, or Museum of Maranello in English is an entirely HTML and CSS project designed to showcase the history of Ferrari to those with limited knowledge of the brand. Organised by time period, the website has a simple to use navigation though limited content. 

# Purpose

The purpose of this website was to briefly introduce people to Ferrari. The goal was not to educate the well-versed or those already passionate about the world of Ferrari but to showcase some key facts about Ferrari. 

## Design, UI, and UX

In taking inspiration from Ferrari's principal colour schemes - the website was centred around the following colour pallete:
<img src="assets/ferrari-palette.png" width="100%">

I wanted this site to emulate and capture the feeling of entering a small fan-club with memorabilia across the walls. To capture this, I tried to use first person communication throughout the site as well as 

## Components

* Separate Pages
    * Website designed with five separate pages to provide information to users. Pages can be easily accessed using NavBar below logo. 

* Contact Form
    * Contact form with various text inputs and country selection for all global countries. 

<img src="assets/screenshots/contact-us.png" width=100%>



## Testing and Validation

* CSS Bugs
    * Scroll-Snapping 
        * Error: Scroll-Snapping could not be used with a track pad but worked with a mouse and keyboard arrows.
        * Solution: Appeared to be an issue with Firefox. Tested on Safari and Chrome and worked as desired. As a safety measure, added a conventional site without scroll-snap and recommended utilisation of keyboard arrows for guided site. 
    * Hamburger Menu Delay
        * Error: The nav menu that would pop up during the expansion of the hamburger menu would appear before the background occupied the full-screen. 
        * Solution: Nav and nav-items given transparent backgrounds. 
    * Nav Bar Links
        * Error 1: The nav items could still be clicked by accident in the background of the welcome section even though users could not see them and should not interact with them.
        * Solution: Changed visibility to hidden so functionality would be turned off unless clicked. 
        * Error 2: When clicking on nav-item, hamburger menu does not automatically close.
        * Solution: Resolved by making <ul></ul> visibility:hidden by default and visible when input:checked.
    * W3C CSS Validator
        * Tested in validator with no issues. 
* W3C HTML Validator: 
    * Error 1: Only text and input tags can be descendants of a label tag. 
    * Solution: Removed the hamburger menu nav bar and implemented a standard nav instead. 
    

## Deployment

    * This site was deployed to the web using GitHub pages. 


## References

[Markdown Guide](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links)

[Colour Palette Generator](https://coolors.co)

[Official Ferrari Website - UK](https://www.ferrari.com/en-GB)

[Ferrari Wikipedia](https://en.wikipedia.org/wiki/Ferrari)

[Ferro Rosso Font](https://www.dafont.com/font-comment.php?file=ferro_rosso&text=Museo+di+Maranello)

[Full Page Scroll Tutorial](https://www.youtube.com/watch?v=htw4iKMYzEc)

[Adding Fonts](https://www.geeksforgeeks.org/how-to-include-a-font-ttf-using-css/)

[CSS Variables](https://www.w3schools.com/css/css3_variables.asp)

[Pop-Up/Modal Box](https://www.w3schools.com/howto/howto_css_modals.asp)

[Keyboard Arrow Image](https://www.pngwing.com/en/free-png-pzfjk/download)

[Hamburger Menu](https://alvarotrigo.com/blog/hamburger-menu-css/)

[Grow on Hover](https://travis.media/how-to-make-an-item-grow-on-hover-with-css/)

[Pure CSS Photo Carousel](https://blog.hubspot.com/website/bootstrap-carousel-css)

[Timeline Feature on Home Page](https://www.w3schools.com/howto/howto_css_timeline.asp)

[Facts about Ferrari](https://interestingengineering.com/13-facts-about-ferraris-you-didnt-know)