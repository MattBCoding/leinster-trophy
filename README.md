# Leinster Trophy 
## Introduction
Leinster Trophy is a site all about the history of the Leinster Trophy and the people who have successfully competed in the motor race for which the trophy is awarded. The site is targetted towards people with an interest in the history of the race, the trophy, and previous winners. Leinster Trophy will be useful as a reference for those seeking information about the trophy or past race winners.

![Responsive Screenshot Mockup](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/ss-homepage.png)

<div align="center">
[View the live website on GitHub Pages](https://mattbcoding.github.io/leinster-trophy/index.html)
</div>

## UX
### Leinster Motor Club:
The trophy is the crown jewel of the Leinster Motor Club, who currently have a website in development. The Leinster Motor Club organise and run multiple motorsport based events each year, covering a variety of classes across both motorcar and motorbike disciplines. Therefore the Leinster Trophy race needs a site of its own to aid in the promotion of the signature event. 

### User Stories
* As a user I want to easily find information about the next race.
* As a user I want to easily find information about past winners of the race wherever I am.
* As a user I want to easily find out about the history of the trophy.
* As a user I want to easily contact someone about the race.
* As the organisation we want to promote the trophy and increase its prestige.
* As the organisation we want to promote our social media channels.
* As the organisation we want to be able to market directly to interested parties in a cost effective manner.

### Opportunities
arising from user stories Insert oppotunities table, opportunities/Importance/Viability/Feasibility
|Opportunities | Importance | Viability / Feasibility
|-----|:------:|:-----:|
|**Promote the next race** | 5 | 5 |
|**Provide reference details for past winners** | 5 | 5 |
|**Provide reference material for trophy history** | 5 | 5 |
|**Responsive site suitable for mobile and tablets** | 5 | 5 |
|**Highlight key information on past winners to increase prestige** | 5 | 5 |
|**Provide standalone online presence**| 5 | 5 |
|**Provide single point of reference and contact for the trophy and race**| 5 | 5 |
|**Promote cost effective marketing channels** | 4 | 5 |
|~~Enable users to search past race records~~ | 2 | 1 |


## Wireframe mockups
Initially I utilised Balsamiq to produce low fidelity wireframes to organise the site structure, potential content placement locations and test the size of each page.

* [Home page wireframe](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/wireframes/wireframe-home.png)
* [Trophy page wireframe](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/wireframes/wireframe-trophy.png)
* [Winners page wireframe](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/wireframes/wireframe-winners.png)
* [Gallery page wireframe](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/wireframes/wireframe-gallery.png)
* [Contact page wireframe](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/wireframes/wireframe-contact.png)

Once the overall structure for each page had been established, I moved into Figma to produce a full colour mockup to test the colour scheme and font selection. Once I was happy with the colours and font selection I also created a colour card to aid with the build process. To select the colours used I utilised the Adobe colour selector to pull the colours out of the hero image. As the hero image is of a racecar in a well known colour scheme, it allowed me to utilise it through out the site and keep on the theme.

* [Home page full colour mockup](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/wireframes/figma-home.png)
* [Colour card](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/wireframes/figma-color.png)

## Features
In this section go over the different parts of the project, and describe each in a sentance or so. Explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things. 
### Common Features 
* Navigation Bar

  * The navigation bar features a common design across all five pages in keeping with convention with a logo on the left hand size and the navigation links on the right.
  * The navigation bar includes links on the logo, Home, Trophy, Winners, Gallery and Contact. The various title links head to their respective pages for easy navigation. The logo links back to the homepage as a typical shortcut users will likely be familiar with.
  * The navigation bar is fully responsive, for smaller screens, the format of the bar changes to a column orientation with the logo at the top centered on the page and the title links vertically aligned underneath. For tablets and screens in between there is a staggered change through the use of media queries in order to maximise its size.
  * A horizontal line appears under the current page as a visual indicator to the user as to which page they are currently on. With a line appearing underneath the text on hover to visually indicate to users that they are clickable.

![Nav Bar](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-nav.png)

* Hero image

  * Each page includes a hero image with a text overlay which further indicates to the user exactly which section of the site they are on.
  * The image was careful chosen due to the historic race car within the image along with the iconic colour scheme as a visual reminder that the Leinster Trophy race is an event with a rich and long running history. The same colour scheme as the vehicle in the image was utilised throughout the site.

![Hero Image](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-hero.png)

* Footer - Top

  * Each page includes a common footer split into two sections.
  * The top section of the footer includes a navigation shortcut back to the top of the page to provide easy navigation around the site for users.
  * There is also a call to action for the user to subscribe to the newsletter. This provides the users with an opportunity to keep on top of the latest information about the Leinster Trophy, whilst providing the Leinster Motor Club with additional subscribers.

![Footer Top](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-footer-top.png)

* Footer - Bottom

  * The lower section of the common footer includes logo links to each of the social media platforms that the Leinster Motor Club is present on. This provides the user with a visual call to action to prompt them into visiting the organisations social media profiles.
  * These links offer an unintrusive method of promoting the social media channels to the user, providing benefits to the organisation by the way of increased social media following.
  * The lower footer section also includes the copyright notice.

![Footer Bottom](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-footer-bottom.png)

### Home Page Features

* Next race banner

  * The home page includes a banner providing details of the next Leinster Trophy race to occur. It includes the important details of which event it is, when it will happen and where it takes place.
  * There are two buttons included in the banner. They are indicated as Entry and Tickets. The entry button takes the user to the race entry website which is provided by the race venue Mondello Park. The ticket button takes the user to the ticket purchasing site which is provided by Irish Championship Circuit Racing. Both links open in new windows.
  * The banner also includes an image of two modern racecars competing on track as a visual indicator to the user that it is modern racecars that compete during the event.

![Next Race](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-next-race.png)

* Statistics section
  
  * The main information section of the homepage provides the users with highlight statistics about the achievements of past competitors, reminding users that the Leinster Trophy race has launched the careers of some of the worlds greatest drivers.
  * For desktop and tablet layouts, the statistics are presented in the shape of a staggered motorsport grid. With each of the four cards lining up in position as would the racecars about to start a race. This format is reinforced by the yellow horizontal start line positioned at the start of the section, along with the grid box markings surrounding the cards.
  * The statistic cards provide easy access to some of the historical facts regarding the Leinster Trophy race.

![Statistics Grid](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-statistics.png)

### Trophy Page Features

* Trophy History Article
  
  * The main section of the Trophy page includes an article about the history of the Leinster Trophy. It provides the users with a detailed history of the trophy itself and highlights of notable winners.

![History Article Top](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-history-top.png)

  * The article also includes details of the errors that have appeared on the trophy over the years. These are also summarised in a table to enable the users to access the information quickly and easily.

![History Article Bottom](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-history-bottom.png)

### Winners Page Features

* Winners and podium finishers table

  * The main section of the Winners page includes a data table providing users with the complete list of podium finishers for each year that the Leinster Trophy race has been held.
  * The table includes the year of the race, the name of the winner, the winning car, the name of second and third place competitors.

![Winners Table](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-winners-top.png)

  * A link to a larger data file has been provided to users who might wish to access more detailed records for each race. The link opens a pdf file in a new window which provides users with the ability to save the information locally.

![Winners Table Bottom](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-winners-bottom.png)

  * The layout of the table is adjusted for users on smaller screens. This ensures that the information is easily visable regardless of device.

  * The table borders group each decade and zebra striping was utilised to provide users with an improved ability to navigate the table contents.

* Gallery Page Features

  * The gallery page allows users to access high quality video and pictures of past events. This allows the users to easily identify the types of racecars competing within the event each year along with those of prior years.

  * The embedded video provides users with high quality produced footage of past events. This allows the user to experience the scale and the excitement of the race.

![Video Player](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-gallery-top.png)

  * The image gallery also provides users with images of prior years to further promote the heritage and prestige of the competition.

![Image Gallery](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-gallery-bottom.png)

* Contact Page Features

  * The contact form provides users with the ability to contact the Leinster Motor Club directly with any queries or comments they may have. The user is asked for their full name, email address, a message subject and the content of their message.

![Contact Form](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-contact-form.png)

* Hidden Pages

  * Two hidden pages were created to display thank you messages to users that submit one of the forms.
  * A thank you for subscribing message is displayed to users who subscribe to the newsletter. This provides the user with confirmation that they have successfully subscribed, whilst also providing reassurance regarding the frequency of the newsletter emails.
  * A response to the contact form submission is displayed to users who send a message to the organisation through the website. This provides the user with confirmation that their message was successfully sent, whilst also providing them with an expectation as to response times.
  * The form submit response message also includes a call to action for the user to consider subscribing to the newsletter or the social media channels, further promoting them for the organisation.

![Newsletter Subscriber Thank You](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-newsletter-thankyou.png)

![Form Submission](https://github.com/MattBCoding/leinster-trophy/blob/master/assets/media/leinster-trophy-form-submit.png)

## Feature left to implement

* Filter and Search on Winners Table
  * The data table included on the winners page is currently a static display of the information. It would be beneficial to users to enable the data to be filtered or searched. 
  * Unfortunately at this time the technology limitations of HTML and CSS only do not allow this to be implemented.

## Testing
Here you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your projects features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals. In addition, you should mention in this section how your project looks and works on different browsers and screen sizes. 

* Interesting Bugs
  * One interesting bug found was not a bug within my CSS code exactly, but a limitation of the Jigsaw CSS Validator. The statistics cards on the homepage have a yellow grid slot bar behind them. This was achieved by using a linear gradient on the card container element. The CSS code was written as background: linear-gradient(#ffc702 20%, #f5f5f5 20% 100%) this performed exactly as expected, shading the container element with the yellow colour until the 20% mark, then shading with the white for the remainder. However when the code was run through the Jigsaw validator it produced an error. After a lot of frustrating research I discovered that the Jigsaw validator does not recognise the multiple color stops syntax which is defined in level 4 of the CSS image module. I therefore had to change the code to background-image: linear-gradient(#ffc702 20%, #f5f5f5 20%, #f5f5f5 100%) which is the level 3 syntax to remove the error. The code is noted in the CSS file with a comment explaining the error and providing the rational for not utilising the shorthand code.

## Validator Testing 
* HTML 
  * No errors were returned when passing through the official W3C Validator.
    * [Home page](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmattbcoding.github.io%2Fleinster-trophy%2Findex.html)
    * [Trophy page](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmattbcoding.github.io%2Fleinster-trophy%2Ftrophy.html)
    * [Winners page](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmattbcoding.github.io%2Fleinster-trophy%2Fwinners.html)
    * [Gallery page](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmattbcoding.github.io%2Fleinster-trophy%2Fgallery.html)
    * [Contact page](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmattbcoding.github.io%2Fleinster-trophy%2Fcontact.html)
    * [Newsletter thank you page](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmattbcoding.github.io%2Fleinster-trophy%2Fnewsletter-submit.html)
    * [Form submission page](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Fmattbcoding.github.io%2Fleinster-trophy%2Fform-submit.html)
* CSS
  * No errors were returned when passing through the official (Jigsaw) Validator [Link to results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmattbcoding.github.io%2Fleinster-trophy%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

## Unfixed bugs
you will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed.

## Deployment 
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 
* The site was deployed to GitHub pages. the steps to deploy are as follows: 
  * in the GitHub repository, navigate to the settings tab
  * select the pages link from the setting menu on the left hand side 
  * Under the GitHub Pages from the source section drop-down menu, select the master branch 
  * One the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 
  
The live link can be found here - (include link to live site)

## Credits

### Content 
* The text for the homepage 
* The trophy history article was adapted from an article written by Brian Manning with permission 
* The reference material on HTML and CSS provided by [w3schools.com](https://www.w3schools.com/) was utilised to implement flexbox and grid and as general reference material for other areas. 
* The icons used for the logo, bookmark link, download button and in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media 
* The images used for hero image on each page and for the next race banner were taken by Chris Peeters and provided royalty free through [pexels.com](https://www.pexels.com/photo/timelapse-photography-of-green-and-white-racing-vehicle-on-lane-12801/)
* The images included in the trophy history article and reproduced in the gallery were taken from an article written by Brian Manning with permission.
* Additional images used for the gallery page were taken by Cregor Elliott at the 2019 Leinster Trophy weekend and were provided with permission.
* The embedded video of the 2018 Leinster Trophy race was taken from youtube with the permission of the content producer Leo Nulty of [motorsport.ie](https://motorsport.ie/)
* The embedded video HTML code was generated by [YouTube](https://www.youtube.com/)
* Instruction and code on how to make an embedded YouTube video responsive was adapted from an article written on [Avex Designs](https://avexdesigns.com/blog/responsive-youtube-embed)
* The Favicon, links and meta code were generated by [Realfavicongenerator.net](https://realfavicongenerator.net)

