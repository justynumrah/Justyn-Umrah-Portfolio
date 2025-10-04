Justyn Umrah Web and Script Portfolio

Project Overview

This is a self-built portfolio website using HTML5 and CSS3, consisting of four pages. The Home, About Me, Projects, and Contact Me pages. It showcases my skills, projects that I have worked on and personal information about who I am. The site is fully responsive using fluid design and media queries, and it uses a custom color scheme and linear gradient headers.
__________________________________________________________________

1. Responsive Design

Approach

- The site uses fluid design with relative units for widths, paddings, and margins to adjust the content according the sizes of the screen.

- Media queries are used through separate CSS files for each viewport:

Device             Width(px)        CSS File     Explanation
------------------------------------------------------------------
Mobile             0 - 600          mobile.css   Mobile: navigation links are stacked vertically, smaller logo, and compact spacing.
Tablet             601 - 1024       tablet.css   Tablet: Medium spacing, horizontal links with bigger gaps, and larger text.
Laptop/Desktops    1025+            laptop.css   Laptop/Desktop: Larger margins and padding, horizontal navigation bar, full-size logos, and text.
__________________________________________________________________

2. Linear Gradients

- A diagonal linear gradient is used in the About Me page and Project Header

ABOUT ME CSS
header {
    background: linear-gradient(45deg, white, black); /* diagonal gradient */
    color: white;
    padding: 15px;
    text-align: center;
}

PROJECT CSS
header {
    background: linear-gradient(45deg, black, white); /* diagonal gradient */
    color: white;
    padding: 15px;
    text-align: center;
}

- This creates a smooth transition from black to white and vice versa at a 45 degree angle which makes the header more visually appealing.
___________________________________________________________________

3. Color Scheme

Element                                          Purpose & Location
-------------------------------------------------------------------------------
white                                            Used as the main background color across most pages and for the contact form container.

black                                            Used for the main texts and as part of the gradient header background.

rgb(57, 57, 57)                                The navigation bar background color for all pages.

#333                                           Used for footers, video borders, and some borders to give depth.

rgb(73, 73, 73)                                Used as an image border color on the About Me page.

#555                                           Used for paragraph text inside project descriptions.

#ddd                                           Used as a light border color on project cards.

rgb(244, 244, 228)                             Used as the background color for the Contact page and gives it a light beige tone.

lightblue                                        Used for footer email links, adding a bright accent against dark footers.

blue                                             Used for the Contact page’s submit button background.

beige                                            Used for the “Contact Me” button on the About Me page.

rgb(49, 48, 48)                                Used for project titles on the Projects page.

rgba(0, 0, 0, 0.1) & rgba(0, 0, 0, 0.15)     Used for card shadows and hover effects on the Projects page.
_________________________________________________________________________________

4. Other Notes
- No flexbox was used. The layouts rely on inline-block, block, and CSS grid

- The Project page uses a CSS grid to arrange project cards responsively

- The Contact page includes a form with validation, a CAPTCHA field, and a submit button

-Footer styling is consistent across all the pages and it adapts to the different viewports (mobile, tablet, laptop/desktops).
_________________________________________________________________________________

## References / Resources

- **W3Schools** – Used for learning HTML and CSS syntax, examples, and best practices.  
  [https://www.w3schools.com/](https://www.w3schools.com/)

- **Can I Use** – Used to check browser compatibility for HTML and CSS features.  
  [https://caniuse.com/](https://caniuse.com/)
__________________________________________________________________________________
END