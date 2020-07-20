# [Genuine Panama](https://grinnfandango.github.io/Genuine-Panama/)

## Table of Contents
1. [**UX**](#ux)
    - [**User Stories**](#user-stories)
        - [**Wireframes**](#wireframes)

2. [**Features**](#features)
    - [**Design**](#design)
        - [**Color Scheme**](#color-scheme)
        - [**Icons**](#icons)
        - [**Typography**](#typography)
        - [**Libraries/Framework Used**](#Libraries/-framework-used)

2. [**Languages Used**](#languages-used)
    - [**Front-End Languages**](#front-end-languages)

3. [**Testing**](#testing)
    - [**Validators**](#validators)

4. [**Deployment**](#deployment)
    - [**Local Deployment**](#local-deployment)
    - [**Remote Deployment**](#remote-deployment)

5. [**Credits**](#credits)
    - [**Content**](#content)
    - [**Media**](#media)
    - [**Acknowledgements**](#acknowledgements)

***

![Genuine Panama device view](amires.png)

---
## UX

The purpose of this site is to create a webpage based platform for existing and potential fans and viewers to keep up to date and possibly book this band whilst also being able to sell more merchandise, music and show tickets. 

### User Stories

* As a fan, I want to find out when and where this band will be playing. I would also like to find out where I can purchase merchandise. To do this, I had created timeline on the 'showdates.html' page to show the locations and dates of each upcoming show. I had also created a '_blank' link to an external page so visitors and fans can potentially buy the bands merch.

* As a visitor, I would like to find out some information about this band, what their music sounds like and how I can further follow them on social media sites. To do this, social media links have been added to the footer of each page and an embed link has been added to the 'index.html' page so users can listen to a snippet of their 'Latest Single'.

* As an agent, I would like to be able to contact this band so I can find out whether I can book them for any shows. In order for this to happen, I had added a contact form on the 'booking.html' page that could be used to get in touch with the band, as well as adding their contact details to the footer of each page.

#### Wireframes

![Wireframe image](GPWireframe.png)

***

## Features

### Existing Features

  * __Home page (index.html)__ -A page that gives users information about who this band is, with images to familiarise users with this band and images of this band perfoming. There is also a section to highlight this bands 'latest single' so users can hear a sample of the music produced by the band. 

  * __Merch (external link)__ -This page links to an external page, so that users can potentially buy this bands merchandise.

  * __Show Dates (showdates.html)__  -This page allows users to view where and when the band will be performing next.

  * __Book Us (booking.html)__  -This page allows users to potentially book this band and contact them, should they need or want to.

### Design

#### Colour Scheme 
* ![#dddcd9](https://placehold.it/15/dddcd9/dddcd9) body background
* ![#2f528c](https://placehold.it/15/2f528c/2f528c) accent colour and booking form font
* ![#535353](https://placehold.it/15/535353/535353)![#dcd8cd](https://placehold.it/15/dcd8cd/dcd8cd) font
* ![#dcd8cd](https://placehold.it/15/dcd8cd/dcd8cd) header and navbar
* ![#dfdfdf](https://placehold.it/15/dfdfdf/dfdfdf)![#808080](https://placehold.it/15/808080/808080)![#2f528c](https://placehold.it/15/2f528c/2f528c) footer social links
* ![#535353](https://placehold.it/15/535353/535353) footer
* ![#dddcd9f2](https://placehold.it/15/dddcd9f2/dddcd9f2)![#2f528c](https://placehold.it/15/2f528c/2f528c)![#fff](https://placehold.it/15/fff/fff) booking submit button
* ![#dddcd9f2](https://placehold.it/15/dddcd9f2/dddcd9f2) text container
* ![#535353](https://placehold.it/15/535353/535353)![#2f528c](https://placehold.it/15/2f528c/2f528c) showdates timeline

###### Icons
- [Font Awesome 5.14.0](https://fontawesome.com/)
    - Four *Font Awesome* icons were used on the footer of the website on each page created.
      - [Facebook](https://fontawesome.com/icons/facebook-f?style=brands)
      - [Twitter](https://fontawesome.com/icons/twitter?style=brands)
      - [Instagram](https://fontawesome.com/icons/instagram?style=brands)
      - [YouTube](https://fontawesome.com/icons/youtube?style=brands) -glyph now updated-

#### Typography

- Two [*Google Fonts*](https://fonts.google.com/) were used across the site:
    - [Montserrat](https://fonts.google.com/specimen/Montserrat) : Main text.
    - [Quicksand](https://fonts.google.com/specimen/Quicksand?query=quicksand) : Headings


#### Libraries/ Framework Used
- [Bootstrap 4](https://getbootstrap.com/)
- [jQuery](https://jquery.com/download/)
- [jsDelivr](https://www.jsdelivr.com/)

###### [back to top](#table-of-contents)
---
## Languages Used

### Front-End Languages
__My site was built with__
- ![HTML5](https://img.shields.io/static/v1?label=HTML&message=5&color=E34F26&logo=html5&logoColor=ffffff)
    - [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) - Used as the base for markup text.
- ![CSS3](https://img.shields.io/static/v1?label=CSS&message=3&color=1572B6&logo=css3&logoColor=ffffff)
    - [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3) - Used as the base for cascading styles.

---
## Testing
I have validated all files using online validation sites cited bellow and checked across differents browsers and devices.

### Validators 

#### HTML
* [W3C HTML Validator](https://validator.w3.org/) - `Document checking completed. No errors or warnings to show.` 

-- Unavoidable errors in 'index.html'- `Error: The allowtransparency attribute on the iframe element is obsolete.` `Error: The frameborder attribute on the iframe element is obsolete. ` (From line 97, column 15; to line 102, column 15) as Spotify embed code requires these html attributes inorder to function correctly, so were left in original code. 

-- Adding css folder to assets folder removes the usage of styling.


#### CSS
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - `Congratulations! No Error Found.`

---
## Deployment

My [UCFED Genuine Panama repository](https://grinnfandango.github.io/Genuine-Panama/) was developed locally using **Repl.it** as well as **Gitpod**, and all commits were pushed to **GitHub** using **Git**.

This website was deployed on GitHub pages built from the Master branch to publish the project.
To run this project locally, download the files and navigate through the index.html to start.

### Local Deployment

To run this project locally on your own system, you will need to clone this repository and need to have [GIT](https://www.atlassian.com/git/tutorials/install-git) installed and any suitable IDE.

Next, to proceed with local deployment, you can...

- **Download** this GitHub repository
    - by clicking the green "*Clone or download*" button above,
    - select *Download Zip*,
    - this will download the project as a zip-file (*remember to unzip it first*).

### Remote Deployment

This site was deployed using [GitHub Pages](https://pages.github.com/) using the **master branch**.

Deployed Site:
- [https://grinnfandango.github.io/Genuine-Panama/](https://grinnfandango.github.io/Genuine-Panama/)

Once you have the project setup locally, you can proceed to deploy it remotely with the following steps:

1. Navigate to your GitHub repository:
    - `https://github.com/USERNAME/REPO`
2. Click on the **Settings** tab at the top:
    - `https://github.com/USERNAME/REPO/settings`
3. Scroll down on that page to the **GitHub Pages** section.
4. The first drop-down field should be **Source** with *None* preselected.
5. Select **master branch** from the list.
6. The page should refresh.
7. Scroll back down to the **GitHub Pages** section.
8. You should now have a deployed link:
    - `https://USERNAME.github.io/REPO`

**IMPORTANT NOTE**:
- Please allow a few minutes to pass before opening your newly deployed link! Clicking this link too quickly may result in a failure to build the site, causing an Error 404 page instead.

Congratulations! Your project should be deployed successfully on GitHub Pages!

---
