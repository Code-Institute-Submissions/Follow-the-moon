Follow the moon
======
**[Code Institute](https://codeinstitute.net/)  Milestone Project 1: User Centric Frontend Development**

<img src="https://github.com/Daph1986/Follow-the-moon/blob/master/assets/images/README%20images/homepage.jpg" alt="Follow the moon"/>

Follow the moon is a fictional site about living with the flow of the moon that I set up as my first milestone project. The focus with this site is to combine what I learned in a previous course about the moon with what I learned this far about HTML, CSS and Bootstrap. The site’s goal is to share information, tips and tricks about living with the flow of the moon.

Demo
======

By clicking this [link](https://daph1986.github.io/Follow-the-moon/) a live demo version will be visible.

<img src="assets/images/README images/responsive_mockup.png" alt="Responsive image"/>

## Table of Contents ##
---
  * [User Experience (UX)](#ux)
    + [User stories](#user-stories)
        + [Visitor Goals](#visitor-goals)
        + [Site Owners Goals](#site-owner-goals)
    + [Strategy](#strategy)
    + [Scope](#scope)
    + [Structure](#structure)
    + [Skeleton](#skeleton)
    + [Surface](#surface)
    + [Fonts & icons](#fonts-&-icons)
  * [Features](#features)
    + [Features for the future](#features-for-the-future)
  * [Technologies](#technologies)
    + [Code languages and frameworks](#code-languages-and-frameworks)
    + [Wireframe](#wireframe)
    + [Others](#others)
  * [Bugs](#bugs)
    + [Navigation menu](#navigation-menu)
    + [YouTube videos](#youtube-videos)
  * [Testing](#testing)
  * [Deployment](#deployment)
  * [Credits](#credits)
    + [Content](#content)
    + [Media](#media)
        + [Images](#images)
        + [Music](#music)
        + [Code](#code)
    + [Acknowledgements](#acknowledgements)
---

User Experience (UX)
======
It will be a B2C site which targets audience interested in moonology / yoga / spirituality.

**User stories**

#### Visitor Goals
* Learn more about the influence the moon has on daily life.
* Find out on which day of the moon cycle we are today.
* Learn what to do and what not to do in the present moon phase.
* Follow fitting meditations.

#### Site Owners Goals
* Provide information about moonology, influence of the moon on daily life.
* Share passion for the moon / yoga / spirituality.

**Strategy**

The design goal is to make a clear, accessible, structured site so that visitors can get to the wanted information as quickly as possible.

**Scope**

The site will contain a printable moon cycle calendar and information about do’s and don’ts during each moon phase, influence of the moon on daily life and fitting meditations with different moon phases. In later sprints things as a Spotify playlist, a moon cycle period tracker and a personal journey for goals settings can be added.

**Structure**

This site will be structured as clear as possible, to get the wanted information as quickly as possible. The navigation bar will be visible at the left top side to easily navigate to other subjects. It ensures that the user knows what to do and what to expect.

**Skeleton**

Links to my wireframes can be found here:

* [Desktop version](https://github.com/Daph1986/Follow-the-moon/blob/master/assets/images/README%20images/desktop_wireframe.pdf)
* [Mobile version](https://github.com/Daph1986/Follow-the-moon/blob/master/assets/images/README%20images/mobile_wireframe.pdf)

**Surface**

The colors in the color pallet I got by using the homepage image and uploading it to an Adobe XD plugin [Color Designer](https://colordesigner.io/color-palette-from-image) and then select the option to get 10 colors. <br>
Additionally, during making the wireframe I stumbled upon 2 colors which I used for the buttons and the text which are not in the color pallet. These are #FAF7F7 and #4A3F46.

<img src="https://github.com/Daph1986/Follow-the-moon/blob/master/assets/images/README%20images/color_pallet.png" alt="Color pallet"/>
<img src="https://github.com/Daph1986/Follow-the-moon/blob/master/assets/images/README%20images/hex_color_%234A3F46.png" alt="Hex Color #4A3F46"/>
<img src="https://github.com/Daph1986/Follow-the-moon/blob/master/assets/images/README%20images/hex_color_%23FAF7F7.png" alt="Hex Color #FAF7F7"/> 

During development I restructured my website layout a little bit, because I saw that this was visually better.
What I changed was:
1. The homepage I changed my button to from "Follow me!" to "Curious to know more?" this seemed to make more sense. I also made it link to the Daily life page. 
2. The daily life page, I changed the page position in the navbar from fourth page to second page. This was more logical because the button on the homepage was changed and linked to this page. I then added the "Follow me!" button to this page, where you can sign up for the newsletter. 
3. The moon calendar page I changed the "Download me!" button into "View me!" so that the calendar appeared in a pop-up which was an advice given by my mentor. But because then it would not be responsive to get it into the original A4 size I decided to add a download link for if you would like to save it and print it.
4. The moon calendar, I decided to change the background color from hex color #52547A to hex color #9E7B78. This was to create more unity with the moon calendar page.
5. The meditations page, the page has a lot less text than the moon phases page, that is why I decided to change the layout into card decks. This resulted in a visually better oriented page.
6. I removed the transparent navbar and footer layer for the daily life, moon phases and meditations page, because otherwise when scrolling you would get difficulties reading the text and the toggler menu on the mobile version would not be readable.

**Fonts & icons**

In Adobe XD I saw a font, Avenir, which I found fitting for my website because of the clean and thin appearance. I used [Google Fonts](https://fonts.google.com/) to embed it in my code, unfortunately Avenir wasn’t a Google font, so I picked one that was similar to it, Nunito.

For the icons I used [Font Awesome](https://fontawesome.com/)

Features
======
I made the navbar change into a mobile navigation menu which collapse to ensure it would function well on mobile devices. <br>
The call to action buttons works on mobile and desktop devices and the mediations I made can be played on the site itself or on YouTube.

**Features for the future** <br>
<br>
The following items can be added: 
+ A custom made login
+ Moon cycle period tracker
+ Personal journal for setting goals 
+ Moon phases linked to zodiac sign
+ Birthday moon history tracker
+ Yoga exercises fitting to the current moon phase

Technologies
======

**Code languages and frameworks**
+ HTML5
+ CSS3
+ Bootstrap 4.4.1
+ JavaScript

**Wireframe**
+ Adobe XD

**Others**
+ Adobe Photoshop: to resize images that were too large to use and to create the combined homepage image.
+ Adobe Illustrator: to create part of moon calendar and toggler icon.
+ Adobe InDesign to make wireframes A3 pdf's and the menu bug image.
+ Adobe Premiere Pro: to make audio meditations.
+ VSCode: to write my code.

Bugs
======
#### Navigation menu
I had a problem with my navigation menu on the homepage, it was pushing the content down, that was not supposed to happen. 
<img src="https://github.com/Daph1986/Follow-the-moon/blob/master/assets/images/README%20images/menu_bug.png" alt="Menu bug"/> <br>
I fixed it by changing my ccs from:  
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

My homepage background image had a bug, when the screen was above about 1550px in width, a part of the moon was pushed under the footer, which didn't look very good.
Eventually I solved this problem by reducing my moon in photoshop, so it was still partly displayed on mobile devices but on large sizes it wasn't push below the footer.

#### YouTube videos
After uploading my meditations on [YouTube](https://www.youtube.com/) and putting it in my code with an iframe they wouldn't play. By searching on [Google](https://www.google.com/) I found this [site](https://forum.freecodecamp.org/t/youtube-refused-to-connect/245262) where was explained how to fix it.

Testing
======
+ Color blindness was tested on this [site](https://www.toptal.com/designers/colorfilter/) to ensure you would still be able to read my site when you have different types of color blindness.
+ CSS code was tested with a [CSS](https://jigsaw.w3.org/css-validator/#validate_by_input) validator, one failure remains, it says:
```
text underline offset property does not exist: 0.4em
``` 
I left it this way because this is a functional CSS property, it does what it's supposed to do, give a little space between the underline and the active page in the navbar. I tested this on multiple desktop browsers like Google Chrome, Safari, Microsoft Edge and Firefox.
+ HTML code was tested with a [HTML](https://validator.w3.org/#validate_by_input) validator, it gives an error for the iframes of the meditations.html: 
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

+ I also put my project on [Slack](https://slack.com/intl/en-nl/) and there I was attend on the 

Deployment
======

By clicking this [link](https://daph1986.github.io/Follow-the-moon/) the live demo version will be visible.

### GitHub Pages
To create a live version of my site GitHub Pages was used.
To deploy the site with GitHub pages you need to follow the next steps:
1. Log in on [GitHub](https://github.com/)
2. Create a new repository by clicking on "Repositories" and after that on the green "New" button.
3. Fill the showed fields out, give the repository a name, and if you want a description, leave it on "Public" and click the green "Create repository" button.
4. Within VSCode use the following commands in the  CLI terminal:
```
git init
git remote add origin https://github.com/Daph1986/Follow-the-moon.git
git branch -M master
git push -u origin master
```
5. Make sure you make an index.html landing page in order for the site to deploy on GitHub Pages.
6. Use the 
```
git add . 
git push 
```
command to send all your work to your GitHub Repository.
7. Go to "Settings" and scroll down to "GitHub Pages" and with "Source" select the master branch and with "Folder" root, hit the "save" button and your site will be deployed in a few minutes.





If you would like to run this site locally you can clone this repository in an editor such as Cloud9 or VSCode.
You can clone it by clicking the green "Code" button and copy the given link.

Credits
======
### Content
All content is written by myself based on what I've learned during the [Happinez moon course](https://www.happinez.nl/online-training/leef-met-de-maan/), during my enjoyed courses and lessons with [Yoga Maarssen](https://www.yogamaarssen.nl/) and the extra educational information about [gemstones](https://www.edelstenenenmineralen.nl/).

### Media 
#### Images:
1. [Pexels](https://www.pexels.com/) 
* homepage image is a _combined image_ 
    - _pink-clouds-background by Jack Anstey_
* Gratitude meditation image
    - Boy of Water Under Blue and Red Sky by Trung Nguyen

2. [Cleanpng](https://www.cleanpng.com/)
* homepage image is a _combined image_ 
    - _png-moon-png-54278 by Divasiri_
* meditation_pose image
    -  kisspng-buddhist-meditation-christian-meditation-buddhism by Doneasha

3. These images were downloaded with a trial [Shutterstock](https://www.shutterstock.com/) account:
* moon_phases image 
    - ID: 1090336661 by Eisfrei
* new_moon image
    - ID: 509457424 by THANAKRIT SANTIKUNAPORN
* waxing_gibbous_moon image
    - ID: 100023281 by Mihai-Bogdan Lazar
* third_quarter_moon image 
    - ID: 124266622 by Procy
* full_moon image
    - ID: 350316134 by TuiPhotoEngineer
* waning_gibbous_moon image
    - ID: 643273564 by Cristian Cestaro
* waning_crescent_moon image
    - ID: 742746820 by Lukasz Pawel Szczepanski
* full_moon_pink image
    - ID: 1611988528 by nednapa
* Intuition meditation image
    - ID: 511867600 by Triff

4. [Rawpixel](https://www.rawpixel.com/)
* waxing_crescent_moon image
    - id-440089 Original from NASA, digitally enhanced by rawpixel
* first_quarter_moon image
    - id-440197 Original from NASA, digitally enhanced by rawpixel

5. [Pikwizard](https://pikwizard.com/)
* Sleep meditation image
    - Sky Atmosphere Sun

6. [Unsplash](https://unsplash.com/)
* Confidence meditation image 
    - U-Kty6HxcQc by Benjamin Voros 
* Positivity meditation image 
    - oMpAz-DN-9I by Greg Rakozy 
* Body scan meditation image
    - FnKEsLuPQvI by Ingmar

7. This image is licensed with a paid [Adobe Stock](https://stock.adobe.com/) account:
* responsive_mockup image
    - AdobeStock_362054394

8. [Tiny png](https://tinypng.com/)
to compress my images


#### Music:
1. [YouTube Studio](https://studio.youtube.com/channel/UC991useTgs7W2PofwhpouBw/music)
    - Satya Yuga by Jesse Gallagher

2. [BigSoundBank](https://bigsoundbank.com/detail-1110-tibetan-bowl-struck.html)
    - Tibetan bowl struck by Joseph SARDIN

3. Meditation storyteller
    - Self (Daphne Heimgartner-Frankhuisen)

#### Code:
1. [W3schools](https://www.w3schools.com/html/html_youtube.asp)
To help me embed the YouTube videos in my code.
2. [Stackoverflow](https://stackoverflow.com/questions/37814508/order-columns-through-bootstrap4) to help me reverse the order of my moon phase cards on the mobile layout. 
3. [Autoprefixer CSS](https://autoprefixer.github.io/) to optimise the use of vendor extensions in my css.

### Acknowledgements
+ My mentor from Code Institute, thank you Narender for your time and guidance.
+ My husband, thank you Django for taking care of our son more so I can work on my education and thank you for your patience!
+ Anna Greaves from Code Institute, thank you so much for your explanation [site](https://ajgreaves.github.io/bootstrap-grid-demo/index.html) about the bootstrap grid, it really helped me understand it a lot better.
+ Igor from Code Institute tutor assistance, thank you for your explanation and help with my validator errors and your ideas about my background image bug.
+ Special thanks to Gwendolyn Jo, Richard Lovett & Marina Pavlovic, my colleagues, my husband, friends and family for their support, tips, and for testing my project.

