Testing Follow the moon
======

## HTML
HTML code was tested with a [HTML](https://validator.w3.org/#validate_by_input) validator, all the pages were checked.
<img src="assets/images/README images/no_errors.png" alt="No Errors"/>

It gives only an error for the iframes of the meditations.html: 
<img src="assets/images/README images/meditations_page.png" alt="Meditations page"/>

```
Text not allowed in element iframe in this context.
``` 
I could have just skipped the paragraph text, but I choose to leave it in and to ignore this error, because this is what I learned in the HTML iframes section of the course: 
```
Some very old browsers do not support iframes. It is good practice to add a message to be displayed to users when the iframe will not load. This message goes between the opening and closing iframe tags like this:
```
```
 <iframe src="..."><p>Your browser does not support iframes.</p></iframe>"
```
I consult with tutor assistance about it, a srcdoc attribute was tested, but then the iframe wouldn't load, so I left it the way it was.

## CSS
CSS code was tested with a [CSS](https://jigsaw.w3.org/css-validator/#validate_by_input) validator.

<img src="assets/images/README images/css_validator.png" alt="CSS Validator"/>

As is shown above one failure remains, it says:
```
text underline offset property does not exist: 0.4em
``` 
I left it this way because this is a functional CSS property, it does what it's supposed to do, it gives a little space between the underline and the active page in the navbar. I tested this on desktop and mobile devices on multiple browsers like Google Chrome, Safari, Microsoft Edge, Firefox and Brave.

## JavaScript
JavaScript was tested with a [JavaScript](https://nl.piliapp.com/javascript-validator/) validator.
<img src="assets/images/TESTING images/js_validator.png" alt="JS Validator"/>

## Lighthouse
I let all pages pass through Lighthouse in Chrome developer tools, the results for desktop can found here: 
<img src="assets/images/TESTING images/lighthouse_desktop_reports.png" alt="Lighthouse desktop reports"/>
and these are the results for mobile:
<img src="assets/images/TESTING images/lighthouse_mobile_reports.png" alt="Lighthouse mobile reports"/>
I'm happy with the results and don't see the need for adjustments at this point.

## GTmetrix 
The site was with [GTmetrix](https://gtmetrix.com/) by my husband. This is the [first report](https://gtmetrix.com/reports/daph1986.github.io/CTWNdIKZ/). After that I compressed the images to reduce the page loading time. At the end I tested it again myself [second report](https://gtmetrix.com/reports/daph1986.github.io/LZl138ub/).
I'm happy with the results.

## Color blindness 
Color blindness was tested on this [site](https://www.toptal.com/designers/colorfilter/) to ensure you would still be able to read my site when you have different types of color blindness. I added screenshot off the homepage test, but of course I tested all the pages.
<img src="assets/images/TESTING images/protanopia.png" alt="Protanopia"/>
<img src="assets/images/TESTING images/deutanopia.png" alt="Deutanopia"/>
<img src="assets/images/TESTING images/tritanopia.png" alt="Tritanopia"/>
<img src="assets/images/TESTING images/greyscale_achromatopsia.png" alt="Greyscale / Achromatopsia"/>


## Slack
I also put my project on [Slack](https://slack.com/intl/en-nl/) and there I was attend on a few things by Richard Lovett & Marina Pavlovic, among others the fact that my moon calendar modal could be viewed better when there is a difference in background with the base page and that the contrast for my text and background on my daily life page wasn’t enough. I decided to adjust this by changing the background of my modal a bit and to change the background color for my daily life page in order to get a could contrast and keep the consistency in text color. Richard also gave me the advice to run the CSS through an online Autoprefixer CSS.

## Collegues / friends / family
I asked a lot of different people to check my project to ensure it works on different systems and devices. Everything seems to work, only my colleague found out a iOS bug when you turn your iPhone in landscape mode. 
<img src="assets/images/TESTING images/ios_bug_1.jpeg" alt="iOS bug 1"/>
<img src="assets/images/TESTING images/ios_bug_2.jpeg" alt="iOS bug 2"/>
<img src="assets/images/TESTING images/ios_bug_3.jpeg" alt="iOS bug 3"/>
<img src="assets/images/TESTING images/ios_bug_4.jpeg" alt="iOS bug 4"/>
<img src="assets/images/TESTING images/ios_bug_5.jpeg" alt="iOS bug 5"/>
I searched and tried to solve it but didn't work out. It was really frustrating because when you turn iPhones in landscape in the developer tools online this bug doesn't get displayed.
I know it has to do with the "Notch" which is a safe area on iPhone as explained [here](https://css-tricks.com/the-notch-and-css/). It does this with more sites not only mine.
So, this will be something for the future to solve.