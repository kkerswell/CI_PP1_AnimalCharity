# **<center>Cymru Animal Shelter</center>**

![picture alt](/assets/readme/images/site-design.png)

## User Story

Build a website that allows the owners of an animal shelter to advertise animals available for adoptions and also their fundraising events.

### External user’s goal ###
* Visit a website to view animals available for adoption.
* Visit the website to see any fundraising events.
* Visit the website to contact the shelter.
* Visit the website to find how where the shelter is located.

### Site owner's goal ###

* Attracting people who want to adopt an animal.
* Have a page describing the shelter and its purpose
* Have a gallery of all animals currently available for adoption.
* Have a page dedicated to advertising annual fundraising events.
* Provide a method for users of the website to contact the shelter to express interest in an animal. 
* Provide information on the gym's location

------

## User Experience (UX)

* First Time Visitors
* Design
    * Colour Scheme
        * Create a modern colour scheme with soft tones
        * Primary background of the website will be white, so this would need to form part of the palette.
        * The goal is to choose gender-neutral colours.
        * Final palette colours that were chosen were #F4F9F4 #C4E3CB #8AAE92 #616161
        * Source: https://colorhunt.co/palette/f4f9f4c4e3cb8aae92616161
    * Typography
    * Imagery
* Wireframes

## Features

List of features

------

## External Sources ##

* https://commonmark.org/help/
* https://colorhunt.co/
* https://www.w3schools.com/css/css3_variables.asp
* https://unsplash.com/
* https://fontawesome.com/
* https://fonts.google.com/
* https://stackoverflow.com/
* https://colorhunt.co/

- - - -

## Development ##

### Building and Maintaining ##

GitHub was used as version control software to maintain, upload and share code with other developers.

GitPod was used to write the code.

#### Commits ####

I kept track of updates by using commits in Git.  The terminal commands for these were:

* git add .
* git commit -m "Description of change"
* git push

### Deployment ###

The website was deployed to GitHub Pages.

The public URL for my website is: https://kkerswell.github.io/CI_PP1_AnimalCharity/

To complete this action I completed the following process:

1. Navigated to my site repository

    https://github.com/kkerswell/CI_PP1_AnimalCharity

2. Clicked on "Settings" within the top navigation area

    ![picture alt](/assets/readme/images/github-deploy-1.png)

3. Clicked on "Pages" within the side navigation area

    ![picture alt](/assets/readme/images/github-deploy-2.png)

4. Clicked the dropdown box under "Source" and choose "main"

    ![picture alt](/assets/readme/images/github-deploy-3.png)

5. Clicked on the "Save" button

    ![picture alt](/assets/readme/images/github-deploy-4.png)

6. Once saved, the url is then provided

    ![picture alt](/assets/readme/images/github-deploy-5.png)

## Problems ##

* spacing the a links in the nav bar.  I originally tried to add margin and padding but this was having an undesired effect.  I got arround this by adding line-height to the nav a section.
* When Adding a h1 to the header, the alignment of both h1 and nav changed to an undesired style. I struggled to get the h1 to align left and the nav to align right.  I then changed both to display inline but the nav was then aligned right next to the h1 on the right side of the page, when I wanted it on the left. I overcame this by adding float right to the nav.
* When hosting page on GitHub pages, the site did not work correctly.  I had to change all file paths to relative in order for this to work.
* When re-sizing the "Our Animals" page, the animal-nav element would not centre align and would instead move to the left. This placement would move further to left the smaller the screen became.  I tried different align options in CSS but this did not work. I finally obtained an answer by asking in the course's slack community, who advised that I needed to ................

---

## Testing

### HTML Validation

https://validator.w3.org/ was used to validate HTML.

1. index.html

![Picture](/assets/readme/images/index.png)

2. about.html

![Picture](/assets/readme/images/about.png)

3. animals.html

![Picture](/assets/readme/images/animals.png)

4. fundraising.html

![Picture](/assets/readme/images/fundraising.png)

5. contactus.html

![Picture](/assets/readme/images/contactus.png)

### CSS Validation

https://jigsaw.w3.org/css-validator/ was used to validate CSS.

![Picture](/assets/readme/images/css.png)

### Accessibility

https://wave.webaim.org/ was used to test accessibility.

The results were as follows:

1. Errors
    * 3 x Errors for broken links. However, these were for the three social links in the footer and is currently expected behaviour.
2. Contrast Errors
    * Where I had grey text on a green background, I had warnings for low contrast. However, I felt the colours worked well and decided to keep them.
3. Alerts
    * 1 x Alert for HTML5 video or audio. However, this was only for video with audio and the site recommended providing synchronized captioning and a transcript, the video I used did not have any audio included.

### Performance

https://developers.google.com/web/tools/lighthouse was used to test performance.

![Picture](/assets/readme/images/lighthouse.png)

### Responsiveness

http://ami.responsivedesign.is was used to test responsiveness.

