[Livepage](https://tthuva192.github.io/MS1--BTS-Band/) 

# BTS Band 

 The goal of this project is to create a website which serves as a promotional medium for the Pop-Band
 BTS. The aim of the Webpage is to provide users with Information about the Band,their music and their tours.

## User Experience 

The primary target audience for the website would be females aged between 12-30 
such as existing fans and new general users. However the website should be able to appeal
to anyone outside of the target audience as well.

### User Stories:

First Time User:

 * As a First time user I want to easily navigate to find Information

 * As a First time user I want Information on the Webpages to be clear and Clean

 * As a First time user I want to look at the Webpages on my phone screen

 * As a First time user I want the Website to be engaging and fun for me to keep browsing.


Developer :

* As a Developer I want to make an easy to use and understand website 

* As a Developer I want to make use of all the HTML and CSS that I learned to create a responsive website

* As a Developer I want the features of the website to be relevant and attention-grabbing 

## Design: 

### Balsamic-Framework 

Before beginning the coding and styling section of the project I created a simple design framework
using pencil and paper. The framework included the basic components, Features and Icons to be included in the website.
From the beginning the design plan was to keep the layout and structure of the webpages as simple and clean as possible
to avoid overload of information and clutter. However even so i found myself adding or changing designs I had included in the intitial stages of
the framework.
Below is the Balsamic framework i drew up for each webpage.

1. [Home](https://github.com/tthuva192/MS1--BTS-Band/blob/bf5581ec316a3afed1669e5a8e793864779bd6e5/assets/wireframes/MS1-Home%20page.png)

2. [About](https://github.com/tthuva192/MS1--BTS-Band/blob/bf5581ec316a3afed1669e5a8e793864779bd6e5/assets/wireframes/MS1-About%20page.png)

3. [Music](https://github.com/tthuva192/MS1--BTS-Band/blob/bf5581ec316a3afed1669e5a8e793864779bd6e5/assets/wireframes/MS1-Music.png)

4. [Gigs/Contact-us](https://github.com/tthuva192/MS1--BTS-Band/blob/bf5581ec316a3afed1669e5a8e793864779bd6e5/assets/wireframes/MS1-Gigs_contact%20us%20page.png)

#### Font: 

3 different fonts were used for this Website : ["Roboto"](https://fonts.google.com/specimen/Roboto?query=roboto), ["Playfair Display"](https://fonts.google.com/specimen/Playfair+Display?query=playfair+display)
and ["Merriweather"](https://fonts.google.com/specimen/Merriweather?query=merri); all which were taken from Google fonts and imported into the html file. 

Roboto is a quite commonly used font and goes well together with the other two. 
Playfair Display is a font appropriate to be used for websites designed for Bands and Games.
As the website is designed to be casual but not playful these fonts are quite in-line with the intention of the website.

#### Colour-palette: 

The [colour palette](https://coolors.co/ffcdb2-ffb4a2-e5989b-b5838d-6d6875) was chosen based of the Logo and the main hero-image to fit the colour-scheme.
To catch the attention of the user a contrast between white background pastel-colours were used. 

Colours:

* #b5838d,
* #e5989b,
* #ffb4a2,
* #6d6875,

The primary colour used for the website was #b5838d. It was used as background colour for the footer as well as the colour change for the menue items. As it is a darker
colour it is simple,eye-catching and goes well with a white background.
All the other colours were used throughout the websites as button backgroumd colours or as Heading colours
to highlight text. 

#### Logo & Hero-Image :

Both the logo and the hero-mage were taken off google Images and are the official logo and band picture.
The Logo comes in many versions and designs. This particular design was eye-catching and had a bright colour.
The Hero-Image was chosen for the bright pastel colours and the tone. Both the Logo and the hero-image were
first resized using the [picresize](https://picresize.com/en/results) online website before being put through tinyPNG 
for compressing the file size to the samllest size possible.

## Features 

* Feature 1 - The Navbar is very easy to navigate by clicking on the Navigation menu. When after
Menu Item is selected it is indicated to the user by the colour change of the text. Once the page is the 
one active the text-colour changes and remains as that colou until the user moves to another page,

* Feature 2 - Hyperlink Buttons are used on several of the webpages to either move the user from 
one page to another or to lead them to external links. Examples are the 'Order' and 'Buy tickets'
buttons.

* Feature 3 - A carousel slide allowing the user to view images by clicking on the next/previus button was added to 
catch the users attention and curiosity. It also allows to use multiple images without spreading them
out statically on the page.

Feature 4- A form where the user can fill in their details with their queries. It will only work if the 
user gives in a name and the correct email format together with text for the textbox area.


## Features Left to Implement

*  The Submit button of the form section does not actually link to any page or submit to anywhere.
It would be good to add a page where the submit button can link to.

* Adding an animation section to the main Home page to catch the viewers eye could maybe implemented 
in the future.

* An animation to the album-Images of the music.html page might be another feature that could be added.
The current Images are static and not very engaging,


## Technologies Used

* HTML language was used alongside Bootstrap framework for the structure of the website 

* CSS was used for the styling of the website 

* Some Imported Javascript and Jquery for styling and features.

## Testing 

1. Menu bar:
         
         i   Go to the menu bar and hover over the menu item
         ii  Menu items should change colour and become underlined
         iii Click on Menu item link, verify that it leads to the correct page and changes to bold colored lettering.

2. CTA buttons:

         i  Go to button and hover over the link.
         ii Make sure the button changes styling/colore
         iii click the link and verify that it proceeds to the correct webpage.

3. Carousel:

            i click the carousel link and verify that it changes images 
            ii verify image size is correct and buttons on carousel are centred.

4. Embedded Videos: 
          
                 i   Go to  music.html page with embedded videos 
                 ii  click on video to verify the link is working and that the video will play

5. Hyperlink Images:
  
                    i Go to music.html page with the hyperlink album-covers
                   ii click on the images and verify the link is working and connects to the correct page.
            
6. Contact form:  

                   i Go to contact-us page 
                   ii submit form with no name and verify if error message occurs
                   iii submit form with no email address and verify if error message occurs
                   iv sumbit form with no text message in box and verify if error message occurs

Project looks and works well on desktop and larger screens. However the home screen
does not fit correctly into smaller window screens. As there is two rows side by side 
below the hero image the elements do not seem to be aligning properly.

## Deployment:

This Project was developed on gitpod. To move the website from its developmental stage on gitpod to a live website on github pages the following steps were taken:

1. Open GitHub browser
2. Login to account using username and password and navigate to repository section.
3. From repository page click on settings  
4. In Settings under GitHub pages choose a publishing source (e.g None/your main-branch source )
5. from the Drop-down menu choose a folder as publishing source.
6. Amend name of file if required and save. 

## Credits:

### Media 

The images used in this project were mostly taken from Google image search:

1. Hero Image- http://images.summitmedia-digital.com/cosmo/images/2019/04/17/bts-big-hit-entertainment-1555468185.jpg-Hero Image
2.   http://mimgnews2.naver.net/image/433/2018/06/17/0000045993_001_20180617084832865.jpg
3.   http://mimgnews1.naver.net/image/433/2018/06/20/0000046054_001_20180620081031815.jpg
4.   http://mimgnews1.naver.net/image/433/2018/06/18/0000045997_001_20180618084431949.jpg
5.   http://mimgnews2.naver.net/image/433/2018/06/19/0000046024_001_20180619083433965.jpg
6.   https://i2.wp.com/mimgnews1.naver.net/image/433/2018/06/15/0000045954_001_20180615091334861.jpg
7.   http://mimgnews2.naver.net/image/433/2018/06/16/0000045973_001_20180616083832528.jpg
8.   https://www.allkpop.com/upload/2020/01/content/081321/1578507669-3deovndp5l941.jpg
9.   https://thevisionmsms.org/wp-content/uploads/2018/08/oofsies-900x900.jpg
10.  https://www.allkpop.com/upload/2020/08/content/211833/1598049204-btsdynamite.jpg
11.  https://nekosia.com/wp-content/uploads/2016/05/BTS-The-Most-Beautiful-Moment-in-Life-Young-Forever-Special-Album-320kbps-www.kstar-mp3.us_.jpg
12.  https://i.pinimg.com/originals/20/5d/c4/205dc4a2444020591560683a2d185169.jpg
13.  https://thatgrapejuice.net/wp-content/uploads/2020/09/bts-be-album-tgj-600x600.jpeg
14.  https://cdn2.thelineofbestfit.com/images/made/images/remote/https_cdn2.thelineofbestfit.com/media/2014/btsmap_600_600.png
15.  https://img585.imageshack.us/img585/3096/373047.jpg
16.  https://ih1.redbubble.net/image.592218934.6917/flat,750x1000,075,t.jpg
17.  https://www.scoutmag.ph/wp-content/uploads/13646696_10208407348393868_1760498610_o.jpg


### Content

1. Navbar code taken from [Bootstrap](https://getbootstrap.com/docs/4.5/components/navbar/)

2. Jumbotron code taken from [Bootstrap](https://getbootstrap.com/docs/4.5/components/navbar/)

3. Carousel code taken from  [Bootstrap](https://getbootstrap.com/docs/4.5/components/navbar/)

4. Embedded youtube video idea taken from [W3schools](https://www.w3schools.com/html/html5_video.asp)

5. Striped Table code taken from [Bootstrap](https://getbootstrap.com/docs/4.5/components/navbar/)

6. Alert button taken from [Bootstrap](https://getbootstrap.com/docs/4.5/components/navbar/)

7. Mail-to code taken from [W3schools](https://www.w3schools.com/tags/tag_address.asp)

### Acknowledgemnt:

I have received ideas and inspirations for this project from these sources:

1. w3schools

2. stackoverflow

3. [KatyPerry](https://www.katyperry.com/) Website

4. Fellow students from Slack