# HTML: Instructions #

*Background info*
- In 1989, Tim Berners-Lee invented the web with Hypertext Markup Language (HTML) as its publishing Language
- It was based on SGML (Standard Generalised Markup Language): an internationally agreed upon <mark>method for marking up text into structural units such as paragraphs, headings, list items and so on.</mark> See: [A History of HTML](https://www.w3.org/People/Raggett/book4/ch02.html).

## Code-along

*You will need a text editor. I recommend atom (download [here](https://atom.io/), install guide [here](https://flight-manual.atom.io/getting-started/sections/installing-atom/))*.

### Set up ###

1. Make a folder called 'uca-code-day'
2. In the folder, make a file called index.html
3. In index.html, copy-paste the [boilerplate](./boilerplate.html)
4. Save your changes
5. Open index.html in a web browser (I recommend Chrome)
6. View the results!
7. Right click on the page to 'inspect' or 'inspect element'
8. Change the title to your name and the body text to 'Hello World!'
9. Save/refresh/view

:speech_balloon:

### Elements ###

- HTML is made up of [elements](https://www.w3schools.com/html/html_elements.asp)
- Comprehensive list of elements [here](https://www.w3schools.com/tags/)
- Elements are usually defined by start and end tags which *nest*
---
E.g. Paragraph tag with italics tag nested inside:

`<p> I am a <i>paragraph</i></p>`
<p> I am a <i>paragraph</i></p>
---
- Most beginner tutorials get you to add content elements first (text, images, etc). You end up with a cluttered page.
- I advocate a structural approach...
---
10. Inside your `<body>` tags, add:
    - a `<nav>` element
    - three `<section>` elements
    - a `<footer>` element
11. Nest placeholder text within each element
12. Save/refresh/inspect

:speech_balloon:

13. Add [headings](https://www.w3schools.com/html/html_headings.asp) to each of your sections
14. Change the section titles to something more informative
15. Add a paragraph of [Lorem ipsum](./lorem-ipsum.md) beneath the headings for your first two sections
16. Add an `<address>`, a telephone link `<a>` and an email link `<a>` to your Contact section. (You could also use [formspree.io](https://formspree.io/) to create a functioning form)
17. Keep saving/refreshing/viewing
18. How do you make sure the address doesn't appear on one line?

:speech_balloon:

### Navigation ###

- We are going to add a menu to the nav bar
- The main menu is a list element in html
- There are 2 types: ordered list (1,2,3) and unordered (bullet points)

---
18. Inside the nav tag, add an unordered list `ul` with three items nested inside `li`
19. Name each list item after your three sections.
20. Let's also add a list to our portfolio section, under the paragraph

:speech_balloon:

### Add media content ###

21. Choose an image to represent you (it will go in the About section)
22. Make an 'images' folder within 'uca-code-day'
23. Save your chosen image in that folder
24. Above the About paragraph, add your `img` element
25. Review your work so far

---

#### WELL DONE! ####

:clap:
<i>We have all the structural elements we need for our website. Let's move on to CSS to fix the clunky layout...</i>
