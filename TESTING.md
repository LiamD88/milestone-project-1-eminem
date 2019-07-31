# Milestone Project 1 - Eminem 
---
[View webite on Github Pages](https://liamd88.github.io/milestone-project-1-eminem/)

[Main README File](https://github.com/LiamD88/milestone-project-1-eminem/blob/master/README.md)


## Testing user stories
---
1. As a huge eminem fan I appreciate the detailed biography to showcase where my hero has come from to reach his current position in music. I also enjoy the older eminem songs, its nice to visit    a website that has these songs available to listen to and now know I'm not the only person who has access to this. The fact these are available makes this worth revisiting.

        *The navigation bar is always displayed at the top of the page so user can access the biography page and music page with little effort.
        *The biography page is quite detailed given a full backdrop of the artists life and musical career to cater for the bigger fans.
        *The music page is clearly marked and the user can just scroll down to play any of the songs or youtube videos that are easily visible. 
        *The home page contains lyrics easily visible as soon as you land on the page and some obscure one the more hardcore fans can enjoy.

2. As a casual listener of eminem I like that they have a videos of some of his biggest hits I know and I can apply to win tickets to his upcoming shows. The biography seems very detailed, it       wouldnt be for me, but at least its on its own page and I can browse the other pages without getting into this.

        *The pages are clearly labelled for the casual listener and with a click of the competition page the form to fill in to win tickets is easily visible and easy to fill in.
        *The same with the music page being clearly labelled and easily accesible the user can listen to youtube videos of the artist with ease.


3. As a rap music enthusiast this seems like a nicely designed page with easy access to what I want. I can check out some of the Eminem songs I might not have heard yet and I like these tours       photos its good to see this rapper is still out there touring. The discography section is really good I don't have all of these albums, I'll be sure to check them out.

        *The home page is designed to be asthetically pleasing on the eye for this user and he can click on the easily visible tour page and enjoy the photos that are in a carousels at the top    of the page.
        *On the music page discography is easily clicked through at the top of the page and contains album covers with the name listed so they can look up the album with ease.

4. As a hip hop fan who enjoys going to rap concerts my google search brought me to the upcoming tour dates. I will definetely fill in the presale ticket form as I want to get these tickets.        Also very nice that they have a competition page to win tickets, maybe I wont even have to pay for my mine!

        *The tour page is visible on the navigation bar. There is form that is clearly visible on the bottom half of the screen to fill in to receive access to presale tickets.
        *The competition page is one most people could click on and this user will be happy to fill in the form easily visible to enter a competition for tickets to a concert, the reason they 
          where on the page originally.

5. As a general music fan I like the minimal design of this website it is really easy to navigate around. I can find the music on one page, the huge autobiography gives me an insight into the       artist, and I like these tour photos, there is a quite a few so this should could me engaged. Seems to be a competition for tickets, I might aswell apply because who wouldn't want to win free    tickets to see Eminem.

        *The navigation bar is visible for this user to browse the different webpages to find something they like.
        *The forms are easily filled in for competition.
        *Carousels are quite interactive and easy to use.


## Testing validity of code
--- 
*[W3C HTML Validator](https://validator.w3.org/)   -  This was used to validate my HTML for any errors.
*[W3C CSS Validator](https://jigsaw.w3.org/css-validator/) This was used to validate my CSS for any errors.

## Manual testing of all elements and functionality on every page.

#### Home page

1. The Navigation Bar 
    
    *Viewing the home page on desktop it was fine the colour of the background was not dark enough so I had to add my own class to the navbar to change this.
    *Each link was clicked to ensure they bring you to the correct page.
    *I added a class to target the active link so that when you are on this page the text would display in red to hightlight this, whilst the other pages are in white.
    *I checked the navbar in developer tools and initially in mobile view the burger menu icon would not display as I had deleted the original bootstrap dark class and input my own, it was        completely black like the navbar so I had what I done was I got the code again from bootstrap documentation. I used the bootstrap navbar dark and I then put my own class in with this and     it was now visible in mobile.
 
2. Hero Image

    *The hero image was added in CSS and placed on the page with a class as I felt this made it more responsive for what I wanted. On a larger screen the image stretches out and when i checked    on a mobile it became more centered and vertically displayed.

3. Lyric Text   
    
    *The text on bottom half of the page has an animation I ensured this worked on all screen sizes with developer tools. I also added a display block on smaller devices for some of the text so   only one would show up on a smaller device and not clutter the screen.
    *I checked the text on different screen sizes and had no issues with this.

4.  Footer

    *I had taken the footer code from the resume project and I added in my own colours to the css classes. I tested this by hovering over the links in desktop to see the colour change. The        colour wouldnt change in smaller screen sizes. I also tested the links added to ensure they worked when clicked on all devices sizes and had no issues.


#### Biography Page

1. Navigation Bar 

    *I ensured the navbar had the same code as the home page and I changed the active class so that bio text would be highlighted in red to show the page you are on.

2. Top Left Image

    *The image was originally placed on the right and used with a floating class, as the project progressed I put this image on the left hand side removed the float class and ensured it was       responsive on all devices with developer tools.

3. Paragraphs

    *I played around a lot with this positiong the paragraphs in different ways and testing the responsiveness through developer tools. I centered the text and changed the font style. It          displays perfectly in mobile view. I have an issue with it on larger screen sizes where it has left a small amount of space visible under the image at the top left of screen. 
    *I tested its responsiveness around the images and it fits nicely on all devices but again can have a slight issue on XL screen sizes.

4. Center image

    *This was added late in the project and was used to break up the paragraph text. I set it in a container and it fits nicely on the page and in other device sizes, checked again with           developer tools.

5. Bottom Right Image  

    *Again initially this was implemented with a float right class and I didn't like how it responded with different screen sizes. I ultimately placed it at the bottom of the paragraphs and       tested with developer tools and now fits nicely from mobile up. Opacticy was changed with a class as I felt it sat better on page.

6. Footer 

    *Ensured code was the same as the home page and tested links on all screen sizes.

#### Music Page     

1. Navigation Bar

    *Again checked code was the same as previous pages and changed the active class to highlight current page.

2. Discography Carousel

    *This worked fine initially with all images and text added, the only issue was it was too large on all device sizes and didnt look aesthetically pleasing. I added my own class to change the 
      margins, width and height. Now it sits nicely at the top of the page in the middle of the screen and doesnt take up too much real estate. Checked in developer tools all screen sizes.

3. Youtube Videos

    *The videos originally didn't work in my local IDE and I thought there was an error with this. With further testing the played in the github repository so they stayed. I tested on all         screen sizes and decided to place them on top of each other on mobile and 2 side by side on larger screens. Padding was removed so they would fill out to the side of the screen.

4. Music player

    *The music players never had any issues tested on all devices and developer tools. Decided to place on top of each other in mobile view as better experience.

5. Footer 

    *Again checked code was the same as before and the links all worked correctly, all screen sizes checked in developer tools.


####  Tour Page 

1. Navigation Bar 

     *Again checked code was the same as previous pages and changed the active class to highlight current page.

2. Carousels At Top 

    *I had a lot of issues trying to get the carousels to display correctly on all devices. Initally they displayed fine but when the next image came up the image would change in size causing a   bad user experience. On mobile devices the gaps where huge between the carousels. After a lot of testing on developer tools and with the different sizes I solved the problem by targeting     the carousel inner class with my own class to affect the height of the carousel. I then applied media queries for each device. Through a lot of testing in developer tools I was able to       apply 4 different media queries which allowed the carousels to display side by side with no jumps and on all devices. 

3. Tour Dates

    *I had no issues with this, tested in developer tools on all screen sizes to ensure displayed correctly.


4. Form For Tickets

    *Tested in developer tools on all screen sizes, no issues.

5. Footer

    *Again checked code was the same as before and the links all worked correctly, all screen sizes checked in developer tools.

#### Competition Page

1. Navigation Bar
         
    *Again checked code was the same as previous pages and changed the active class to highlight current page.

2. Hero Image

    *This was initally causing me problems as I just placed the image on the page and it just was too big. I fixed the issue by applying the same idea I had with hero image on the home page.
      The image was added to the page with a class and added on my css page. This allowed the image to stretch on larger screens and center on smaller devices. Tested again in developer tools and no issues.

3. Competition Text 

    *Tested in developer tools looks fine on all device sizes.

4. Competition Form 

    *Again no issues tested in developer tools for responsiveness.

5. Footer

    *Again checked code was the same as before and the links all worked correctly, all screen sizes checked in developer tools.