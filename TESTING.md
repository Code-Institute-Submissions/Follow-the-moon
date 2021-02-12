Test report
======
Table of Contents
======

  * [General](#general)
  * [HTML](#html)
  * [CSS](#css)
  * [JavaScript](#javascript)
  * [Lighthouse](#lighthouse)
  * [GTmetrix](#gtmetrix)
  * [Color blindness](#color-blindness)
  * [Slack](#slack)
  * [Colleagues / friends / family](#colleagues-friends-family)
  * [Bugs](#bugs)


## General
The design goal was to make a clear, accessible, structured site so that visitors can get to the wanted information as quickly as possible. <br>
As a visitor there were a few goals to achieve, in the tests it was checked if these were achieved.
* Learn more about the influence the moon has on daily life.
    * When coming on the homepage it is clear what subject of the page is and if you would like to know more / if you are curious there is a button you can click which will give more information.  <img src="assets/images/TESTING images/subject.png" alt="Subject"/>The button redirects you to the Daily life page where more information about the subject is displayed.
    Furthermore, after reading the content there is a button displayed which if you click on, it shows a form where you can sign up for the newsletter if you would like. <img src="assets/images/TESTING images/sign_up_modal.png" alt="Sign up modal"/> 
   
* Find out on which day of the moon cycle we are today.
    * When you navigate to moon calendar in the navbar, you reach the moon calendar page. There it is explained that you can view the calendar or open an A4 version for downloading or printing. <img src="assets/images/TESTING images/moon_calendar_page.png" alt="Moon calendar page"/> 

* Learn what to do and what not to do in the present moon phase.
    * When you go to the moon phases page, you will see the eight different phases of the moon with explanation, and among others some do's and don'ts. <img src="assets/images/TESTING images/moon_phases_page.png" alt="Moon phases page"/> 

* Follow fitting meditations. <br>
     * If you want to relax and follow a meditation, you visit the last page, the meditation page. You can find six different meditations there, pick one that you think is fitting for you at this moment and enjoy. <img src="assets/images/TESTING images/meditations.png" alt="Meditations page"/> 

It can be concluded that all goals have been achieved.  <br>
The website has been tested on the available DevTools for phone and tablet sizes as well as on multiple responsive sizes and it was made sure that it looks good and works well on all. <br>
The website was also tested on multiple devices among others an OnePlus Nord, an iMac (Retina 5K, 27-inch, 2017), a MacBook-Air (Retina M1, 13.3-inch, 2020) and a Samsung Galaxy Tab4 (10.1-inch 2014), everything works as it should.

## HTML
HTML code was tested with a [HTML](https://validator.w3.org/#validate_by_input) validator, all the pages were checked.
<img src="assets/images/TESTING images/no_errors.png" alt="No Errors"/>

It gives only an error for the iframes of the meditations.html: 
<img src="assets/images/TESTING images/meditations_page.png" alt="Meditations page"/>

```
Text not allowed in element iframe in this context.
``` 
This paragraph text could have just been skipped, but it is left in and the error was ignored, because this is what was learned in the HTML iframes section of the course: 
```
Some very old browsers do not support iframes. It is good practice to add a message to be displayed to users when the iframe will not load. This message goes between the opening and closing iframe tags like this:
```
```
 <iframe src="..."><p>Your browser does not support iframes.</p></iframe>"
```
After consulting with tutor assistance about it, a srcdoc attribute was tested, but then the iframe wouldn't load, so the paragraph text was left the way it was.

## CSS
CSS code was tested with a [CSS](https://jigsaw.w3.org/css-validator/validator.html.en#validate_by_input) validator.

<img src="assets/images/TESTING images/css_validator.png" alt="CSS Validator"/>

As is shown above two errors remain. <br>
First error:
```
Value Error : height Too many values or values are not recognized : intrinsic
``` 
This value was given to keep the image on the moon calendar page from getting pushed together on iPhone, it was one of the two suggestions given my mentor and it works as it should, because the image is pushed together on iPhone anymore.

Second error:
```
text underline offset property does not exist: 0.4em
``` 
Tutor assistance was consulted about it, and it was left this way because this is a functional CSS property, it does what it's supposed to do, it gives a little space between the underline and the active page in the navbar. It was tested on desktop and mobile devices on multiple browsers like Google Chrome, Safari, Microsoft Edge, Firefox and Brave.

## JavaScript
JavaScript was tested with a [JavaScript](https://nl.piliapp.com/javascript-validator/) validator.
<img src="assets/images/TESTING images/js_validator.png" alt="JS Validator"/>

## Lighthouse
All pages have passed through Lighthouse in Chrome DevTools, the results for desktop can found here: 
<img src="assets/images/TESTING images/lighthouse_desktop_reports.png" alt="Lighthouse desktop reports"/>
and these are the results for the mobile versions:
<img src="assets/images/TESTING images/lighthouse_mobile_reports.png" alt="Lighthouse mobile reports"/>
The results are satisfying, so at this moment there is no need for adjustments.

## GTmetrix 
The site was tested with [GTmetrix](https://gtmetrix.com/) by my husband. This is the [first report](https://gtmetrix.com/reports/daph1986.github.io/CTWNdIKZ/). After that the images were compressed to reduce the page loading time. At the end a final test was done, this is the [report](https://gtmetrix.com/reports/daph1986.github.io/XUnAX0rn/) from that test.

## Color blindness 
Color blindness was tested on this [site](https://www.toptal.com/designers/colorfilter/) to ensure you would still be able to read the website when you have different types of color blindness. Here you will find a screenshot off the homepage test, but of course all pages were tested.
<img src="assets/images/TESTING images/protanopia.png" alt="Protanopia"/>
<img src="assets/images/TESTING images/deutanopia.png" alt="Deutanopia"/>
<img src="assets/images/TESTING images/tritanopia.png" alt="Tritanopia"/>
<img src="assets/images/TESTING images/greyscale_achromatopsia.png" alt="Greyscale / Achromatopsia"/>

## Slack
On the 3rd of February the project was placed on [Slack](https://slack.com/intl/en-nl/) and there a few points were brought up by Richard Lovett & Marina Pavlovic, among others the fact that the moon calendar modal could be viewed better when there is a difference in background with the base page and that the contrast for the text and background on the daily life page wasn’t enough. The decision was made to adjust this by changing the background of the modal a bit and to change the background color for the daily life page in order to get a good contrast and keep the consistency in text color. Richard also gave the advice to run the CSS code through an online Autoprefixer CSS.

## Colleagues / friends / family
A lot of different people were asked to check the project to ensure it works on different systems and devices. The website was tested on Samsung Galaxy TabA (10.1-inch 2019), OnePlus 5, Xiaomi Redmi Note 7, Xiaomi Redmi Note 8 Pro, Motorola G9, Motorola G5, Samsung S7, iPhone 6, iPhone 7, iPhone 12 and iPhone 12 Pro Max among others.
My colleague found a bug when you turn your iPhone in landscape mode. 
<img src="assets/images/TESTING images/ios_bug_1.jpeg" alt="iOS bug 1"/>
<img src="assets/images/TESTING images/ios_bug_2.jpeg" alt="iOS bug 2"/>
<img src="assets/images/TESTING images/ios_bug_3.jpeg" alt="iOS bug 3"/>
<img src="assets/images/TESTING images/ios_bug_4.jpeg" alt="iOS bug 4"/>
<img src="assets/images/TESTING images/ios_bug_5.jpeg" alt="iOS bug 5"/>
Research was done and it was tried to solve but didn't work out. It was really frustrating because when you turn iPhones in landscape in the DevTools online this bug doesn't get displayed.
It has to do with the "Notch" which is a safe area on iPhone as explained [here](https://css-tricks.com/the-notch-and-css/). It does this with more sites not only this website.
So, this will be something for the future to solve. <br>
#### Advices given after testing which were followed
1. The reason a preload for jQuery was added, is that a friend of mine, Benny, who works as a senior developer explained that this was a smart thing to do, so that the browser gets a hint of what is coming and can prepare for loading the content. He also suggested that it was better to give the redirect function on the homepage a more self-describing name for clarification and to make the email icon clickable and let it open in the default email.
2. It was my husband, Django, who suggested to put the JavaScript in a separate file.

Bugs
======
#### Navigation menu
There was a problem with the navigation menu on the homepage, it was pushing the content down, that was not supposed to happen. <br>
<img src="assets/images/README images/menu_bug.png" alt="Menu bug"/> <br>
It was fixed by changing the CSS from:  
```
.navbar { 
    position: sticky; 
} 
```

to: 

```
.navbar { 
    position: fixed; 
    width: 100% 
} 
```
#### Homepage background
The homepage background image had a bug, when the screen was above about 1550px in width, a part of the moon was pushed under the footer, which didn't look very good.
Eventually this was solved by reducing the moon in Photoshop, so it was still partly displayed on mobile devices but on large sizes it wasn't push below the footer.
However with the final testing it cm to the attention that when turning the phone in landscape mode this gave a new problem. Namely that not the entire content was displayed and scrolling was not possible.
This was fixed by changes in the CSS code:

```
background: url("../images/homepage.jpg") no-repeat fixed;
  background-size: cover;
  max-width: 100%;
  position: fixed;
}
```
was changed to:
```
background: url("../images/homepage.jpg") no-repeat fixed;
  background-size: cover;
  max-width: 100%;
  position: absolute;
}
```
and the following was added:
```
#sm-landscape-fix {
  height: 110px;
}
```
The id "sm-landscape-fix" was added to the div were the "Curious to know more?" button is in, this resolved the issue and after retesting no other issues were found.

#### Moon calendar page
The image on the moon calendar page was pushed together, but this seemed only to happen on iPhones.
My mentor pointed my toward two solutions and after consideration, this solution seemed to work best for that page, adding the id of "calendar-image" to the particular image an setting it to:
```
#calendar-image {
  height: intrinsic;
}
```
<img src="assets/images/TESTING images/moon_calendar_image_bug.png" alt="Image bug"/>
This solves the problem as it puts the image at a natural height, which fixes this bug on the iPhone and it doesn't negatively affect the display on other devices. <br>

#### Printable moon calendar
There was a similar problem with the printable calendar on iPhone
<img src="assets/images/TESTING images/moon_calender_bug.png" alt="Calendar bug"/>
this was fixed by giving the image a width in CSS:

```
.modal-content img {
  width: 100%;
  height: auto;
}
```

#### YouTube videos
After uploading the meditations on [YouTube](https://www.youtube.com/) and embeding it in the code with an iframe they wouldn't play. By searching on [Google](https://www.google.com/) this [site](https://forum.freecodecamp.org/t/youtube-refused-to-connect/245262) was found where was explained how to fix it.



