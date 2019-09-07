# Jakub Lemiszewski Bio Page Presentation

This project is a simple HTML and CSS page about myself.

Includes bio and CV information.

## Improvments

The page luck of the basics of responsive design.
Changing the resolution of the device where the page is open makes some alligment issues.

Possible solutions is to build cusom made media queries like:

```css

@media only screen and (max-width: 600px)  {...} 
/* We target until the width of the device hit 600px after that new styles are applied */

@media only screen and (min-width: 600px)  {...} 
/* We target from the width of the device hit 600px. On 599px we apply certain style and on 600px we switch to new defined styles starting from there*/

@media only screen and (max-width: 600px) and (min-width: 400px)  {...}
/* We target a range where we apply a specific style before or after the range other styles are applied */

```

With media queries we can target a specific device resolution, a range and mobile devises and the style values included under a specific media queries will be only visaible if the page is open in that defined range.

More improvments quality of the CSS with better solutions to avoid positioning, alligment and design issues.

Better naming for Classes and Ids.
