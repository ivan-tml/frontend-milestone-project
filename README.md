# User Centric Front End Development
<hr>

For the first project of the Code Institutes Full Stack Developers course I have decided to build a website dedicated for the rock band from the 1960s Fleetwood Mac.

## Technologies Used
<hr>

* HTML5
* CSS3
* JavaScript 
    * Used to create functional Popover for Social media button on the website.
* Bootstrap v4.3.1
    * Used to create layout.
    * Make the website responsive.
    * Create collapsible navbar.
    * Modal containing track list.
    * Carousel with captions and indicators.
    * Popover for Social media button.
* Font Awesome 5.9.0
* Popper.js
    * Installed in order for popover to function as desired.
* Google fonts
* color.adobe.com 
    * Used to create pallet of colours to be used through the website.
* Chrome and Firefox developer tools
    * Used for live-testing.
* Git / GitHub
    * Used to keep track of the project's evolution with frequent commits and informative messages.
* Cloud 9 
    * Used as a main editor.
* Balsamiq
    * Used to build the wireframe.

## Testing 
<hr>

The responsiveness, functionality and fluidity of each page was tested on all the Chrome, Firefox and Edge responsive tool's available devices.
Additionally, every page was numerously loaded on multiple devices in order to identify possible malfunctions and misbehaving elements.

## Content
<hr>

* Landing page - index.html
    * Welcome screen with Tour announcement.
    * Description of the new compilation album.
    * Modal with track list.
    * Album cover.
    * Embedded Spotify player with complete playlist.
    * Purchase options.
    * Official music video.
* Tour
    * Dates and locations of upcoming tour with individual buttons to buy tickets.
* The Band
    * Band history and two carousels containing three images each.
    * Subscription form (not functional due to JavaScript not being used).
* Albums
    * List of all the album covers with links to the Wikipedia pages.
* Social
    * Popover with icons to visit social media sites.

## CSS File Management 
<hr>

Complete CSS styling is managed in one file named main.css.

## Project Approach
<hr>

Wireframe:

Started the project with building the wireframe with the Balsamiq tool. 
Although the wireframe was only shows desktop version, the website was created with the mobile first approach.

Nav: 

I've began creating the website with the Navbar with contains 5 buttons. I have used Bootstrap grid to create layout, collapsible nav, 
and Popper.js library to get popover on Social button to access the social media buttons.

Footer: 

Footer was built with bootstrap grid, containing copyright and social media buttons for which I have used Font Awesome icons. 
Social media icons change from light gold to their official colour once hovered over.

Main page (index.html):

Main page is divided into three sections. 
Top part is dominated by the image and text announcing new tour. 
Second part of the page is the description on the latest album compilation and here I have decided to add modal containing track list. 
Third part is extension of the second part and contains a cover of the new album, Spotify player which I have added using iframe, 
and option to listen samples of all the tracks on the album. Below Spotify player I have created four buttons that take user to an external link 
to purchase promoted album. In this part I have been playing with ::before and ::after classes to get the lines on the left and right of the title text. 
Below the Buy now section I have once again used iframe to embed YouTube player with official music video.

Tour (tour.html):

This page was again built completely with bootstrap. I have created a row for each date of the show with three columns. 
First containing the date, second location and the third Ticket button that takes user to the official ticket seller.

The Band (tehband.html):

Here I have copied the history of the band from the Wikipedia Fleetwood Mac page and added two carousels with three images each. 
Every carousel represents different era of the band, first one early stages, and second one images from the recent times.
In the middle of the page I have left empty space between two paragraphs in which as you scroll you can see the background image 
which is a back cover of their most successful album "Rumours".
Below the bands history I have added the subscription form with two input fields, first for the name, and second with email.

Albums (albums.html):

Albums contains a grid of 18 images each representing a studio album. Each image is created with the fading overlay effect on hover and the album name 
with the release year that once clicked onto takes user to the Wikipedia page of picked album.

Social:

Last button on the navbar is hidden when the menu is collapsed, but when extended over 767px and clicked on, shows a popover which I have created using 
Popper.js library. It required me to add script tag into HTML of every page in order for popover to work. 
To make my idea of the popover containing Font Awesome icons in form of buttons work, I had to go to the Stack Overflow to find inspiration, 
as I could not find any technical documentation on how to solve my problem.

## Project Deployment 
<hr>

The final version of the project was deployed to Github.com using its free hosting feature "GitHub Pages" and can be viewed live at https://ivan-tml.github.io/frontend-milestone-project/index.html
