Testing Follow the moon
======

## HTML
HTML code was tested with a [HTML](https://validator.w3.org/#validate_by_input) validator, it gives an error for the iframes of the meditations.html: 
```
Text not allowed in element iframe in this context.
``` 
I choose to ignore this, because this is what I learned in the HTML iframes section of the course: 
```
Some very old browsers do not support iframes. It is good practice to add a message to be displayed to users when the iframe will not load. This message goes between the opening and closing iframe tags like this:
```
```
 <iframe src="..."><p>Your browser does not support iframes.</p></iframe>"
```
I did try consult with tutor assistance about it, a srcdoc attribute was tested, but then the iframe wouldn't load.

## CSS
CSS code was tested with a [CSS](https://jigsaw.w3.org/css-validator/#validate_by_input) validator, one failure remains, it says:
```
text underline offset property does not exist: 0.4em
``` 
I left it this way because this is a functional CSS property, it does what it's supposed to do, give a little space between the underline and the active page in the navbar. I tested this on multiple desktop browsers like Google Chrome, Safari, Microsoft Edge and Firefox.

## Lighthouse

## [GTmetrix](https://gtmetrix.com/)

## Color blindness 
Color blindness was tested on this [site](https://www.toptal.com/designers/colorfilter/) to ensure you would still be able to read my site when you have different types of color blindness.

## Slack
I also put my project on [Slack](https://slack.com/intl/en-nl/) and there I was attend on a few things, among others the fact that my moon calendar modal could be viewed better when there is a difference in background with the base page and that the contrast for my text and background on my daily life page wasn’t enough. I decided to adjust this by changing the background of my modal a bit and to change the background color for my daily life page in order to get a could contrast and keep the consistency in text color. 
