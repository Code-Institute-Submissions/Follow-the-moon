Test report
======

## General
The design goal was to make a clear, accessible, structured site so that visitors can get to the wanted information as quickly as possible. <br>
As a visitor I had a few goals I wanted to achieve, in my tests I've checked if these were achieved.
* Learn more about the influence the moon has on daily life.
    * When coming on the homepage it is clear what subject of the page is and if you like to know more / if you are curious there is a button you can click which will give more information. <img src="assets/images/TESTING images/subject.png" alt="Subject"/>The button directs you to the Daily life page where more information about the subject is displayed.
    Furthermore, after reading the content there is a button displayed which if you click on it shows a form where you can sign up for the newsletter if you would like. <img src="assets/images/TESTING images/sign_up_modal.png" alt="Sign up modal"/> 
   
* Find out on which day of the moon cycle we are today.
    * When you navigate to moon calendar in the navbar, you reach the moon calendar page. There it is explained that you can view the calendar or open an A4 version for downloading or printing. <img src="assets/images/TESTING images/moon_calendar_page.png" alt="Moon calendar page"/> 

* Learn what to do and what not to do in the present moon phase.
    * When you go to the moon phases page, you will see the eight different phases of the moon with explanation, and among others some do's and don'ts. <img src="assets/images/TESTING images/moon_phases_page.png" alt="Moon phases page"/> 

* Follow fitting meditations. <br>
     * If you want to relax and follow a meditation, you visit the last page, the meditation page. You can find six different meditations there, pick one that you think is fitting for you at this moment and enjoy. <img src="assets/images/TESTING images/meditations.png" alt="Meditations page"/> 

Overall, I think all my goals are achieved. <br>
I tested my site on the available DevTools phone and tablet sizes as well as on multiple responsive sizes and made sure that it looks good and works well on all. <br>
On my own devices which are an OnePlus Nord, an iMac (Retina 5K, 27-inch, 2017), a MacBook-Air (Retina M1, 13.3-inch, 2020) and a Samsung Galaxy Tab4 (10.1-inch 2014) I also tested everything and it works as it should.


## HTML
HTML code was tested with a [HTML](https://validator.w3.org/#validate_by_input) validator, all the pages were checked.
<img src="assets/images/TESTING images/no_errors.png" alt="No Errors"/>

It gives only an error for the iframes of the meditations.html: 
<img src="assets/images/TESTING images/meditations_page.png" alt="Meditations page"/>

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
I consulted with tutor assistance about it, a srcdoc attribute was tested, but then the iframe wouldn't load, so I left it the way it was.

## CSS
CSS code was tested with a [CSS](https://jigsaw.w3.org/css-validator/validator.html.en#validate_by_input) validator.

<img src="assets/images/TESTING images/css_validator.png" alt="CSS Validator"/>

As is shown above one failure remains, it says:
```
text underline offset property does not exist: 0.4em
``` 
I consulted with tutor assistance about it, and I left it this way because this is a functional CSS property, it does what it's supposed to do, it gives a little space between the underline and the active page in the navbar. I tested this on desktop and mobile devices on multiple browsers like Google Chrome, Safari, Microsoft Edge, Firefox and Brave.

## JavaScript
JavaScript was tested with a [JavaScript](https://nl.piliapp.com/javascript-validator/) validator.
<img src="assets/images/TESTING images/js_validator.png" alt="JS Validator"/>

## Lighthouse
I let all pages pass through Lighthouse in Chrome DevTools, the results for desktop can found here: 
<img src="assets/images/TESTING images/lighthouse_desktop_reports.png" alt="Lighthouse desktop reports"/>
and these are the results for the mobile versions:
<img src="assets/images/TESTING images/lighthouse_mobile_reports.png" alt="Lighthouse mobile reports"/>
I'm happy with the results and don't see the need for adjustments at this point.

## GTmetrix 
The site was tested with [GTmetrix](https://gtmetrix.com/) by my husband. This is the [first report](https://gtmetrix.com/reports/daph1986.github.io/CTWNdIKZ/). After that I compressed the images to reduce the page loading time. At the end I tested it again myself, this is the [report](https://gtmetrix.com/reports/daph1986.github.io/LZl138ub/) from that test.
I'm happy with the results.

## Color blindness 
Color blindness was tested on this [site](https://www.toptal.com/designers/colorfilter/) to ensure you would still be able to read my site when you have different types of color blindness. I added screenshot off the homepage test, but of course I tested all the pages.
<img src="assets/images/TESTING images/protanopia.png" alt="Protanopia"/>
<img src="assets/images/TESTING images/deutanopia.png" alt="Deutanopia"/>
<img src="assets/images/TESTING images/tritanopia.png" alt="Tritanopia"/>
<img src="assets/images/TESTING images/greyscale_achromatopsia.png" alt="Greyscale / Achromatopsia"/>


## Slack
I also put my project on [Slack](https://slack.com/intl/en-nl/) and there I was attend on a few things by Richard Lovett & Marina Pavlovic, among others the fact that my moon calendar modal could be viewed better when there is a difference in background with the base page and that the contrast for my text and background on my daily life page wasn’t enough. I decided to adjust this by changing the background of my modal a bit and to change the background color for my daily life page in order to get a could contrast and keep the consistency in text color. Richard also gave me the advice to run the CSS through an online Autoprefixer CSS.

## Colleagues / friends / family
I asked a lot of different people to check my project to ensure it works on different systems and devices. My site was tested on Samsung Galaxy TabA (10.1-inch 2019), OnePlus 5, Xiaomi Redmi Note 7, Xiaomi Redmi Note 8 Pro, Motorola G9, Motorola G5, Samsung S7, iPhone 6, iPhone 7, iPhone 12 and iPhone 12 Pro Max among others.
My colleague found a bug when you turn your iPhone in landscape mode. 
<img src="assets/images/TESTING images/ios_bug_1.jpeg" alt="iOS bug 1"/>
<img src="assets/images/TESTING images/ios_bug_2.jpeg" alt="iOS bug 2"/>
<img src="assets/images/TESTING images/ios_bug_3.jpeg" alt="iOS bug 3"/>
<img src="assets/images/TESTING images/ios_bug_4.jpeg" alt="iOS bug 4"/>
<img src="assets/images/TESTING images/ios_bug_5.jpeg" alt="iOS bug 5"/>
I did research and tried to solve it but didn't work out. It was really frustrating because when you turn iPhones in landscape in the DevTools online this bug doesn't get displayed.
I know it has to do with the "Notch" which is a safe area on iPhone as explained [here](https://css-tricks.com/the-notch-and-css/). It does this with more sites not only mine.
So, this will be something for the future to solve. <br>
#### Advices given after testing which I followed
1. The reason I put in a preload for jQuery is that a friend of mine, Benny, who works as a senior developer explained to me that this was a smart thing to do, so that the browser gets a hint of what is coming. He also suggested that it was better to give my redirect function on the homepage a more self-describing name for clarification and to make my email icon clickable and let it open in the default email.
2. It was my husband, Django, who suggested to put my JavaScript in a separate file.