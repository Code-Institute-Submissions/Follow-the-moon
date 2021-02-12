Follow the moon
======
**[Code Institute](https://codeinstitute.net/)  Milestone Project 1: User Centric Frontend Development**

<img src="assets/images/README images/homepage.jpg" alt="Follow the moon"/>

Follow the moon is a fictional site about living with the flow of the moon that was set up for the first milestone project. The focus with this site is to combine what was learned in a previous course about the moon with what was learned this far about HTML, CSS and Bootstrap. The site’s goal is to share information, tips and tricks about living with the flow of the moon.

Demo
======

By clicking this [link](https://daph1986.github.io/Follow-the-moon/) a live demo version will be visible.

<img src="assets/images/README images/responsive_mockup.png" alt="Responsive image"/>

## Table of Contents ##
---
  * [User Experience (UX)](#ux)
  * [Features](#features)
  * [Technologies](#technologies)
  * [Bugs](#bugs)
  * [Testing](#testing)
  * [Deployment](#deployment)
  * [Credits](#credits)
---

User Experience (UX)
======
It is meant to be a B2C site which targets audience interested in moonology / yoga / spirituality.

**User stories**

##### Visitor Goals
* Learn more about the influence the moon has on daily life.
* Find out on which day of the moon cycle we are today.
* Learn what to do and what not to do in the present moon phase.
* Follow fitting meditations.

##### Site Owners Goals
* Provide information about moonology, influence of the moon on daily life.
* Share passion for the moon / yoga / spirituality.

**Strategy**

The design goal is to make a clear, accessible, structured site so that visitors can get to the wanted information as quickly as possible.

**Scope**

The site contains a printable moon calendar and information about do’s and don’ts during each moon phase, influence of the moon on daily life and fitting meditations for different moon phases. In later sprints things as a Spotify playlist, a moon cycle period tracker and a personal journal for setting goals can be added.

**Structure**

This site is structured as clear as possible, to get the wanted information as quickly as possible. The navigation bar will be visible at the left top side to easily navigate to other subjects. It ensures that the user knows what to do and what to expect.

**Skeleton**

Links to the wireframes can be found here:

* [Desktop version](https://github.com/Daph1986/Follow-the-moon/blob/master/assets/images/README%20images/desktop_wireframe.pdf)
* [Mobile version](https://github.com/Daph1986/Follow-the-moon/blob/master/assets/images/README%20images/mobile_wireframe.pdf)

**Surface**

The colors in the color pallet were found by using the homepage image and uploading it to an Adobe XD plugin [Color Designer](https://colordesigner.io/color-palette-from-image) and then select the option to get 10 colors. <br>
Additionally, during designing two more colors were added and used for the buttons and the text, these weren't  in the color pallet. The colors are #FAF7F7 and #4A3F46.

<img src="assets/images/README images/color_pallet.png" alt="Color pallet"/>
<img src="https://github.com/Daph1986/Follow-the-moon/blob/master/assets/images/README%20images/hex_color_%234A3F46.png" alt="Hex Color #4A3F46"/>
<img src="https://github.com/Daph1986/Follow-the-moon/blob/master/assets/images/README%20images/hex_color_%23FAF7F7.png" alt="Hex Color #FAF7F7"/> 

During development the website layout was restructured a little bit, because this seemed visually better.
What was changed is:
1. The homepage button was changed from "Follow me!" to "Curious to know more?" this seemed to make more sense. It was also made to redirect to the Daily life page.
2. The daily life page, the page position in the navbar was changed from fourth page to second page. This was more logical because the button on the homepage was changed to redirect to this page. A "Follow me!" button was added to this page, where you can sign up for the newsletter. 
3. On the moon calendar page the "Download me!" button has been changed into "View calendar!" so that the calendar appeared in a pop-up which was an advice given by my mentor. But because then it would not be responsive to get it into the original A4 size the decision was made to add a download link for if you would like to save it and print it.
4. The moon calendar, the background color has been changed from hex color #52547A to hex color #9E7B78. This was to create more unity with the moon calendar page.
5. The meditations page, the page has a lot less text than the moon phases page, that the decision  was made to change the layout into card decks. This resulted in a visually better oriented page.
6. With finalizing the project the address and phone number in the footer were removed, for this kind of site there is no need to have an address or phone number. A possibility to send an email is sufficient, though it is a fictive email address.

**Fonts & icons**

In Adobe XD there is a font, Avenir, which was found fitting for the website because of the clean and thin appearance. [Google Fonts](https://fonts.google.com/) was used to embed it in the code, unfortunately Avenir isn't a Google font, so a similar, Nunito, was chosen.

For the icons [Font Awesome](https://fontawesome.com/) was used.

Features
======
The navbar was changed into a mobile navigation menu which collapse to ensure it would function well on mobile devices. <br>
The call to action buttons work on mobile and desktop devices and the mediations that were made can be played on the site itself or on YouTube.

**Features for the future** <br>
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
+ VSCode: to write the code in.

Testing / Bugs
======
The testing has been done on multiple devices and browsers, eventually everything works as intended. Due to the fact that this subject contained more content as expected a separate page has been created. For more details on testing and bugs please view this [file](TESTING.md).

Deployment
======
To create a live version of the website VSCode was used together with GitHub Pages.
To deploy the website with GitHub pages you need to follow the next steps:
1. Log in on [GitHub](https://github.com/) 
2. Find Daph1986's [page](https://github.com/Daph1986)
3. Select repositories
4. Select the Follow-the-moon repository
5. Click on the link on the right side or on the link under "Demo"
By clicking that link the live demo version will be visible.
<img src="assets/images/README images/link_1.jpg" alt="Link 1"/>
<img src="assets/images/README images/link_2.jpg" alt="Link 2"/>

If you would like to run this website locally you can clone this repository in an IDE such as Cloud9 or VSCode.
You can clone it by following the next steps:
<img src="assets/images/README images/clone.jpg" alt="Clone"/>
1. Log in on [GitHub](https://github.com/) 
2. Find Daph1986's [page](https://github.com/Daph1986)
3. Select repositories
4. Select the Follow-the-moon repository
5. Click on the green "Clone" button
6. Copy the URL 
7. Open VScode or your preferred IDE, open the file in which you want to use the project and open a CLI terminal
8. Put the following command in the CLI terminal:
``` 
git clone https://github.com/Daph1986/Follow-the-moon.git
``` 

Credits
======
### Content
All content has been written by myself based on what was learned during the [Happinez moon course](https://www.happinez.nl/online-training/leef-met-de-maan/), during the enjoyed courses and lessons with [Yoga Maarssen](https://www.yogamaarssen.nl/) and the extra educational information about [gemstones](https://www.edelstenenenmineralen.nl/).


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

7. This is a licensed image downloaded with a paid [Adobe Stock](https://stock.adobe.com/) account:
* responsive_mockup image
    - AdobeStock_362054394

8. [Tiny png](https://tinypng.com/)
was used to compress the images

#### Music:
1. [YouTube Studio](https://studio.youtube.com/channel/UC991useTgs7W2PofwhpouBw/music)
    - Satya Yuga by Jesse Gallagher

2. [BigSoundBank](https://bigsoundbank.com/detail-1110-tibetan-bowl-struck.html)
    - Tibetan bowl struck by Joseph SARDIN

3. Meditation storyteller
    - Self (Daphne Heimgartner-Frankhuisen)

#### Code:
1. [W3schools](https://www.w3schools.com/html/html_youtube.asp) to help embed the YouTube videos in the code.
2. [Stackoverflow](https://stackoverflow.com/questions/37814508/order-columns-through-bootstrap4) to explain how to reverse the order of the moon phase cards on the mobile layout. 
3. [Autoprefixer CSS](https://autoprefixer.github.io/) to optimize the use of vendor extensions in the CSS code.

### Acknowledgements
+ My mentor from Code Institute, thank you Narender for your time and guidance.
+ My husband, thank you Django for taking care of our son more so I can work on my education and thank you for your patience!
+ Anna Greaves from Code Institute, thank you so much for your explanation [site](https://ajgreaves.github.io/bootstrap-grid-demo/index.html) about the bootstrap grid, it really helped me understand it a lot better.
+ Igor from Code Institute tutor assistance, thank you for your explanation and help with my validator errors and your ideas about my background image bug.
+ Special thanks to Gwendolyn Jo, Richard Lovett & Marina Pavlovic, my colleagues, my husband, friends and family for their support, tips, and for testing my website.

