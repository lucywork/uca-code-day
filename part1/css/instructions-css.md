# CSS: Instructions #

*Background info*
- CSS stands for Cascading Style Sheets
- CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc. Source/Further reading [here](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/How_CSS_works).

## A. Set up ##
1. In your folder, make a file called 'styles.css'
2. In your index.html file, add a link to your css file
3. How? Inside your head tags, add this line `<link rel="stylesheet" href="styles.css">`

## B. How to select and edit elements ##
1. Let's change the navigation bar to silver
`nav {
  background-color: silver;
  }`
2. Save/refresh/view
3. Hmmm... what about the margin?
4. Can we add a style the whole body element to remove that margin?
5. Save/refresh/view

:speech_balloon:

## C. Specificity: id and class attributes ##
1. Let's select our image element by giving it a unique [id](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/id) in the html file.<em>
An id allows us to add custom styles to one unique html element (as opposed to all the images, in this case). See [class](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/class) to differentiate.</em>
2. Now we can create a css style that only effects that image, e.g. `#profile-pic {max-width: 25%;}`

:speech_balloon:

## D. Layout ##
- [CSS layout](http://learnlayout.com/toc.html) can be tricky at first. We probably won't have time to cover it today.
- Keep it [<i>responsive</i>](https://developers.google.com/web/fundamentals/design-and-ux/responsive/). Remember that your layout needs to work on mobile screens too.
---
1. Rather than allowing our content to travel to spread across the display from edge to edge, let's add a maximum width
2. You need to create a [div](https://www.w3schools.com/tags/tag_div.asp) in the html file, nested within the body tags but excluding the nav and footer
3. Give your div the id 'container'
4. In your css file, make the #container max-width: 960px and the margin: 0 auto
5. Save, refresh, review
6. Now give your section elements a height of 80vh ([See CSS Units > Relative Lengths](https://www.w3schools.com/cssref/css_units.asp))

:speech_balloon:

## E. Relative sizing ##
1. The contact form looks bunched up
2. Let's give its input fields a margin of [1em](https://css-tricks.com/confused-rem-em/) so they can breathe

## F. Main navigation menu ##
1. Now let's fix the navigation menu
2. How are you going to only style the list in the menu, and not the list in the portfolio/section 2?
3. Make the list-style: none
4. Now style the `nav ul li` element to make it [inline-block](http://learnlayout.com/inline-block-layout.html) so it lists horizontally


## G. Independent progress

:clap: Congrats! You made it through the CSS code-along!

- Now you have reached this stage, you can start to implement the following changes by researching solutions solo.
- Remember: Google has the answer to most web dev questions and even senior devs are used to researching answers online.
---
1. Change the default font to one you like
2. Edit the layout of each section (refer back to learnlayout.com or see [flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/))
3. Add a favicon
4. Balance out the whitespace (look up: margin, border, padding)
5. Add a unicode copyright symbol in the footer
6. Implement a colour scheme using hex or RGB
7. Make the image into a circle (use border radius)
8. Give the image a border
9. [Make the menu items link](https://way2tutorial.com/html/html_internal_links.php) to the corresponding sections
10. Create a [photo gallery](https://www.w3schools.com/howto/howto_css_portfolio_gallery.asp) instead or in addition to the portfolio

---

#### Resources cited ####
- [How CSS Works](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/How_CSS_works), MDN
- [Learn CSS Layout](http://learnlayout.com/toc.html), Learn Layout
- [HTML `<div>` tag](https://www.w3schools.com/tags/tag_div.asp), W3 Schools
- [rem vs em](https://css-tricks.com/confused-rem-em/), zellwk
- [CSS Units > Relative Lengths](https://www.w3schools.com/cssref/css_units.asp)
- [Responsive Web Design Basics](https://developers.google.com/web/fundamentals/design-and-ux/responsive/), Web Fundamentals, Google
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/), CSS tricks
