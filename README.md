# The Monkees #

I created a website for the band The Monkees.  The website consists of the landing page and 5 additional pages made up of:
* About
* Booking Events
* Contact Us
* Music Videos
* Events 

The idea of the landing page is to have a scrolling menu with a fixed menu navbar at the top.  This navbar also shows at the top of every other page as it makes
for easy navigation throughout the whole website.  When scrolling down the landing page, each section mentioned above is represented
by a seperate clickable menu item.  These menu items were designed using photo's of the band with overlay text.  At the bottom of each page there are links to the bands facebook,
youtube and twitter.

As this is my first ever project I wanted to do as much of the website from scratch, rather than just copying code from other websites.  Of course the standard HTML and CSS code were used.
In this case Bootstrap v3.3.7 was used.

## User Experience ##
The Monkees is a well known band to the older generation of music lovers.  They have a number of golden oldies and are still big favourites of an older generation.
Because of this I wanted to create a website that is easy to use, easy to see and read, and simple to understand.  I wanted to make it easy for users of the page to navigate from anywhere to anywhere.
The landing page has very large clickalbe main menu items and provides access to The Monkees' social media at the bottom of each page.
I've given fans of The Monkees the ability to read more about the band and see the faces of the band members, book the band for an event, easily see where the band will be playing next,
and also the ability for them to contact the band.  

For instance:

* As a fan of The Monkees and a keen concert goer I want to see where the band is going to perform next.  I access the website, scrool down to "Events", click on "Events", and the user is taken to a calendar 
  showing all of the events coming up.
* As someone doing research on the band I'd like to know more about them.  I access the website, click on About and viola.  From knowing more about the band I would like to contact them therefore
* I click on the "Contact Us" menu item at the top of the "About" page where it takes me directly to the "Contact Us" page.  There the user will fill in their details and click submit.
* Not having had a lot of exposure to video material of the band as a massive fan I'd like to access some of their music videos.  I access the website, click on "Music Videos" of which I'm taken to the "Music Videos" page.  There I am presented with four album covers representing four of The Monkees' most popular songs.  
  By clicking on each of the album covers I'm taken to YouTube where the music video of that specific song automatically starts playing.

The wireframe for the design of the website can be found by going to the following link 

https://balsamiq.cloud/sk7srff/ph1fys3 



## Features ##

### Landing Page ###

The landing page is made up of six individual menu items.  The landing page has been designed as a scrolling page for easy access to the main menu items further down on the page.
Photos from Google have been used to represent each of the main menu items on the landing page.  The menu has been divided as follows:
About and Events 
Music videos, Book Events, and Contact Us

At the bottom of the page there are three clickable social media icons for Facebook, Twitter, and YouTube which will take you directly to each of these social pages.

At the top of the landing page is a static menu.  This has been included to make navigation to other areas on the website as easy and user friendly as possible.

### About Page ###

The "About" page has been created to provide historical backgroun on the band.  There are also photos of the band members at the bottom of the page.
There are no special features on this page.  As with everyone of the other pages there is a static menu bar at the top of the page for easy navigation.
There's also the three social media icons at the bottom of the page.

### Events Page ###

The Events Page is simple page designed so that users can see when and where events will be taking place.  
The page incorporates a straight forward Google calendar plug-in to do this.  Please note that there are no active events in the calendar.
As with everyone of the other pages there is a static menu bar at the top of the page for easy navigation.
There's also the three social media icons at the bottom of the page.

### Music Videos Page ###

The Music Videos page is made up of a main heading followed by four pictures of album covers.  Each one of the album covers represents one of 
the bands most famous songs.  When you click on an album cover you are taken directly to a YouTube page where the song will start playing.
The idea is to add additional clickable album covers going forward so that we can include as many of the bands famous songs as possible.
As with everyone of the other pages there is a static menu bar at the top of the page for easy navigation.
There's also the three social media icons at the bottom of the page.

### Book Event Page ###

This is a straight forward page where users have the opportunity to get in touch with the band to book them for an event.  The "Book Event"
page and the "Contact Us" page use the same code with a slight change on the Book Event page.  Here we as for the name, surname and event details.
The submit button is functional however please note that an error will come up when clicking the submit button as it's not linked to an email address or submit reference.
As with everyone of the other pages there is a static menu bar at the top of the page for easy navigation.
There's also the three social media icons at the bottom of the page.

### Contact Us Page ###

This is a simple page where users have the opportunity to get in touch with the band.  As mentioned the "Contact Us" and "Book Event" page usethe same 
code.  In the Contact Us page it asks for the name, surname and details of message.  The submit button is functional however please note that an error will come up when clicking the submit button as it's not linked to an email address or submit reference.
As with everyone of the other pages there is a static menu bar at the top of the page for easy navigation.
There's also the three social media icons at the bottom of the page.


## Testing ##

As this is my very first project I am/was not aware of the availability of automated testing, nor am I au fait with how it works.

For this reason all of my testing has been done manually over a couple of months, during the build and progression of my website.

To build my website I used a number of technologies:
- Bootstrap 3.3.7
- CSS
- Font awesome

The above mentioned are plug-ins I decided to use as not to reinvent the wheel.  As mentioned before I wanted to make as much of this
website my work, rather than copying and pasting code from other websites, as I felt this would be the best way to learn.

I designed the website with mobile first in mind.  This didn't always go as well as planned.  As and when I finished a particular
part of the website I would use the inspect tool to see how it reacts to different screen sizes.  Sometimes I got it right first time
around and often not.  It was probably one of the biggest frustrations I experienced during the creation of my website, not being
able to get elements to respond to multiple devices as I planned.  Needless to say this has now been addressed.

With regards to the manual testing, the following was done:

Clicked on "About" in the scrolling menu
Were taken to the About page successfully
Clicked on "Home" in the static menu bar at the top and were taken back to the landing page successfully
Clicked on "Events" in the scrolling menu
Were taken to the Events page successfully
Scrolled successfully through the different months on the calendar in the Events page 
Clicked on "Home" in the static menu bar at the top and were taken back to the landing page successfully
Clicked on "Music Videos" in the scrolling menu
Were taken to the Music Video page successfully
Clicked on each on of the album covers that you can see in the Music Video page and were successfuly 
taken straight to YouTube where the relevant song automatically starts playing
Clicked on "Home" in the static menu bar at the top and were taken back to the landing page successfully
Clicked on "Book Event" in the scrolling menu
Were taken to the Book Event page successfully
Filled in my name, surname, contact details and details about the venue etc., and clicked submit
The submit button works however the form was not submitted as it's not linked to a submit reference therefore an error message came up
I have deliberately not linked the submit button to a submit reference as I don't have anywhere to send that informaton.
Clicked on "Home" in the static menu bar at the top and were taken back to the landing page successfully
Clicked on "Contact Us" in the scrolling menu
Were taken to the Contact Us page successfully
Filled in my name, surname, contact details and reason why I'm getting in touch and then clicked submit.
The submit button works however the form was not submitted as it's not linked to a submit reference therefore an error message came up
Clicked on "Home" in the static menu bar at the top and were taken back to the landing page successfully
At the bottom of every single page there are three social media icons.  Facebook, Twitter, and YouTube.  I clicked on each of these
in every single page and were successfully taken to the relevant social media pages.



Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
The text for section Y was copied from the Wikipedia article Z
Media
The photos used in this site were obtained from ...
Acknowledgements
I received inspiration for this project from X
