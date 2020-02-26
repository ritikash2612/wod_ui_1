---
title: "WOD: Hard Rock Cafe"
published: false
morea_id: wod-1-hardrock
morea_type: experience
morea_summary: "Check your knowledge of Semantic UI" 
morea_sort_order: 1
morea_labels:
---

# WOD: Hard Rock Cafe Home Page

[The Honolulu Hard Rock Cafe](http://www.hardrock.com/cafes/honolulu/) is a popular local music venue. For this WOD, you will create a web page using Semantic UI inspired by their home page. When completed, it should look like this (click on image to see full size):

{% include medium-img.html url="wod-1-hardrock.png" %}

Note that you will find your code from the [Experience Island Snow practice WOD](experience-islandsnow-semantic.html) to be very helpful.

Here are the steps:

  2. Create a private GitHub repository called hardrock and clone it to your local file system.
    
  3. Create an IntelliJ project called hardrock in your repo, and two files within it: index.html and style.css.
    
  4. Load the Semantic UI and JQuery files into index.html following the instructions in [Semantic UI Hello World](reading-semantic-ui-hello-world.html). Also load your style.css file. 
    
  6. Create a menu at the top of the page following the screen image. Hints:
   
       * In your index.html, you might want to create a div with classes "ui topmenu menu" to encapsulate your menu code.
       * In your style.css, you might want to create a CSS selector ".ui.topmenu.menu", which sets the background-color of your menu to black, and the margin and border-radius to 0px.
       * The first item in the menu can use the classes "ui image item", where the "src"  is [http://courses.ics.hawaii.edu/ics314f17/morea/ui-frameworks/hard-rock-logo.png](http://courses.ics.hawaii.edu/ics314f17/morea/ui-frameworks/hard-rock-logo.png).
       * Use the class "right" on the second menu item to move the remaining items to the right side of the page.
       * The menu link (CAFES, HOTELS, etc) color is #ccc. 
       * The links do not need to work.

  8. Put the full-width image [http://www.hardrock.com/cafes/honolulu/files/2384/Honolulu_Entrance.jpg](https://www.hardrockcafe.com/location/honolulu/files/5390/9967882_ImageMediumWidth.jpeg) underneath the menu.  Hint:
  
      * You may find the classes "ui fluid image" to be helpful. 
  
  9. Put a one column footer with two centered rows underneath the image. Hints:
  
      * The footer background-color is #f96d21.
      * Increase the font size for the first row (HARD ROCK CAFE HONOLULU) to 25px. 
      * To icon names are: phone, mail, home, twitter, facebook f, instagram, pinterest, tripadvisor
      * To add space between the sections in the second row, just force three spaces using `&nbsp; &nbsp; &nbsp;`.
      * The icon links do not need to work.
  
  9. When you can preview your index.html file and it looks equivalent to the screen image above, commit your repo to GitHub.
  
  9. Check to make sure it is present on GitHub.

  10. Raise your hand to indicate you are done with this WOD.

{% include wod-times.html Rx="<20 min" Av="20-25min" Sd="25-45 min" DNF="45+ min" %}

### Submission instructions

{% include wod-submission-github.html assignment="UI Frameworks WOD" %}

{% include goo.gl.html url="h3ZLPW" %}
