# Tests 

Tests are carried out first on the largest screen size and then updated regularly for smaller screens.

## Navigation Bar: 
  1. Hover over navigation bar with cursor
  2. Check to see if the toggler works on mobile screens
  3. Ensure that the navbar is semi-transparent at the start of the main page and becomes transparent as you scroll down 
  4. Check to see if the links work and bring you to the right sections/html files
  5. Check to see if the navbar toggler/hamburger is visible
   
Comments - Large Screens:

- Bug encountered with JS file, scrolling to the very top would make the navbar transparent
- Fixed Bug by changing class names in the script.js File, although, unclear if the script.js code will work.
- Changed the script.js code for the mean time 
- Instead of coloring the navbar toggler to become visible, I instead used an icon from font awesome to show represent it and colored it.

## Hero Section: 
1. Check to see if AOS animations are working
2. Check to see if social links work 
3. Check to see if captions are blocking profile picture image
4. Check if social icons vanish when on mobile screen
5. Check if there is a small underline after the social icons
   
Comments - Large Screens: 

- When hovering over social icons, there is a bug where there is a small underline next to the icons. 

![SocialLink-error-Demo](assets/tests/social-link-error.png)

- Annoying underline has been debugged using the following css: 
    .social-icons a {
    text-decoration: none;
}

- The Captions are positioned akwardly on smaller screens - will have to create media queries and style them accordingly.