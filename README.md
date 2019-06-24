<div align="center">
	<a href="https://dugudugu.github.io/chris-harms-web/">
	<img src="https://github.com/dugudugu/chris-harms-web/blob/master/media/image/slider4.jpg"/></a>
</div>


## Introduction

This webpage has been created as a base for a Chef named Chris Harms. He is a professional chef and been cooking for over 10 years.
Chris wants to share his experience an knowledge with everybody. He hopes that with this page that he can motivated people to cook or bake. The recipes given on the page can be done by everybody. 


[View webpage in GitHub Pages](https://github.com/dugudugu/chris-harms-web)

## UX

Altough a professional chef has allot of experience for these recipes, you will only need to know the basics.
To help you out, there is a video include for all the recipes. 

There are a total of 6 [recipes](https://dugudugu.github.io/chris-harms-web/recipe.html) which are:
* Tuna Tataki
* Sweet Potato Soup
* Rigatoni Al Segreto
* Aubergine Parmigiana
* Tiramisu
* Chocolate Lava Cake

These recipes are not only delicious, but they are also easy to make. And if you may have any questions or suggestions please feel free to [contact us](https://dugudugu.github.io/chris-harms-web/contact.html).

<div align="center">
	<a href="https://dugudugu.github.io/chris-harms-web/">
	<img src="https://github.com/dugudugu/chris-harms-web/blob/master/media/image/about2.jpg"/></a>
</div>




## Features

This webpage features a responsive *navigation bar*. The color of the navigation bar make the nav-links stand out.
Each page has an footer, which contains; *social media icons, quick links, contact information and **copyright information**.

Here are the **features** that can be found on the site and a short description of the pages;
 - [Home](https://dugudugu.github.io/chris-harms-web/index.html)
 - [About](https://dugudugu.github.io/chris-harms-web/about.html)
 - [Recipes](https://dugudugu.github.io/chris-harms-web/recipe.html)
 - [Contact](https://dugudugu.github.io/chris-harms-web/contact.html)

#### Home Page
The home page is a welcoming page, that has a few pictures of dishes that were prepared by the chef. For the desktop experience there is a carousel that shows three different *images*. 
For the all the other pages and mobile users the carousel has been repaced by one single image. There is than an inspiration qoute and to end that page a footer. 

#### About 
In the about section, I wanted to tell you a little abou the chef, kept it short and straight to the point. 
The about section cointain a picture of the chef, and right next to it *three paragraphs* of information about the chef. 

#### Recipes
The recipe section has a nummerous repeat of almost the same layout, thus I will only explain this once. The diffrent between the layout is where the video is placed in comparrison with the text. 
The recipe section contains in total **six** recipes, these recipes are **not** from the Chef, and all the credits have been included in the used links. 
An example for the layout of the first recipe, [Tuna Tataki](https://dugudugu.github.io/chris-harms-web/recipe.html):
For the **desktop** user:
The text is on the left side which includes; a short intro to the dish, the ingredients needed and pictures of 3 main ingredients.
There is also a video that is display for the recipe on the right hand side. 

For the **tablet** user:
The layout of the page has been changed; the short recipe into is now centered, followed by the ingredients. 
The pictures of the ingredients are shown, and has been centered. And the video is showned lastly which has also been centered. 

For the **mobile** user:
The short description is shown first, followed by the ingredients and lastly thr video. For this device the chooice was made not to show the pictures of the main ingredients. 
This was done to keep it user friendly, and no to clutter the display. 

#### Contact Us
The contact us page I have created a form, where you are able to fill in a form to contact the chef. To submit the form the user is required to fill in all the input sections. 
When the submit button is clicked, the page just refresh to an empty form once again.


## Future Features

For future development of this webpage I would like to add/make following change:
1. Add an How To section to the webpage
2. Insert a Mega-Menu into the nav-bar for the recipes and the how to
3. Change all the current recipes to recipes from the chef
4. Include more pictures into the carousel 
6. Add CAPTCHA to contact form 
7. Add a Thank You message to the contact form after submitting the form


## Technologies Used

The technologies I used are:
* HTML5 is the markup language used for rendering the webpage.
[HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)

* Google Fonts is used to style the webpage fonts.
[Google Fonts](https://fonts.google.com/)

* Font Awesome is used for icons shown in the footer.
[Font Awesome](https://fontawesome.com/)

* CSS3 is the style sheet language used to style the HTML webpage.
[CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)

* CSS Matic is used for styling images.
[CSS Matic](https://cssmatic.com/)

* Bootstrap 4 Framework for the mobile responsiveness and grid layout of the webpage. 
I also used Bootstrap's core CSS for most of the styling and layout, buttons and forms.
[Bootstrap 4](https://getbootstrap.com/).

* Material Design for Bootstrap for the core JavaScript of the carousel (image gallery slider).
[Material Design for Bootstrap](https://mdbootstrap.com/).


## Testing

- Used [HTML Validator](https://validator.w3.org/) to check the markup on each page. "Document checking completed. No errors or warnings to show."
- Used [CSS3 Validator](https://jigsaw.w3.org/css-validator/) to check CSS3 for any errors. "Congratulations! No Error Found. This document validates as CSS level 3 + SVG !"
- I ran my page on [web.dev](https://web.dev/) and this is the [report](https://lighthouse-dot-webdotdevsite.appspot.com/lh/html?url=https://dugudugu.github.io/chris-harms-web/).

- The tabs on the Navbar works as intended:
   1. When clicking on the about, you will be send to the [About](https://dugudugu.github.io/chris-harms-web/about.html) page.
   2. When clciking on the recipes, you will be send to the [Recipes](https://dugudugu.github.io/chris-harms-web/recipe.html) page.
   3. When clicking on the contact us, you will be send to the [Contact](https://dugudugu.github.io/chris-harms-web/contact.html) page. And the contact form work as intended.
      * If the user doesn't type a fist name, last name the user will get a reminder, "Please fill out this field"
      * Email needs to include @ sign and a domain name for the email address. If user clicks submit without an @ sign, user will get a message, "Please include an '@' in the email address. 'user's input' is missing an '@'.
      * User also needs to enter a domain name for email address. If user forgets to type domain name after '@' sign, there will be a reminder saying, "Please enter a part following '@'. 'userinput@ is incomplete"
      * If user does not type anything at the text area field, user will also be prompted to type something. User will get a reminder, "Please fill out this field".
   4. When clicking on the [Chris Harms](https://dugudugu.github.io/chris-harms-web/index.html) icon you will be send to the home page.
 - The webpage is responsive on majority of mobile devices. 
 - Images are gettin squashed depending on the screen size. I still haven't figured out how to fix it.
      According to [this Slack post](https://code-institute-room.slack.com/archives/C7J2ZAVHB/p1557486039163800) I should give the div of the images the size that I want. And in the CSS I should style the
      `background-size: cover;` or `background-size: contain`.


## Deployment
This project has been build in [Cloud9 IDE](https://aws.amazon.com/cloud9/), committed to Git and than pushed to [GitHub](https://github.com/).
- This site can be deployed at github [Chris Harms](https://github.com/dugudugu/chris-harms-web)
- There is no difference between the deployed version and the developed version
- Just click on the [link](https://github.com/dugudugu/chris-harms-web) to view the webpage


## Credits

#### Content
- The text for the Home page was coppied from [Arden Campbell]https://twitter.com/ardencampbell/status/770667561335808000
- The text fot the About page was written by [Cindy Marchena](https://www.linkedin.com/in/cindymarchena/) for [Chris Harms](https://www.linkedin.com/in/chris-harms-b99322104/).
- The recipes used in the Recipes page are from:
   - Tuna Tataki, [Corbeil Électroménagers](https://www.youtube.com/embed/erzs6-lWmPY)
   - Sweet potato and coconut milk soup, [Recipe30](https://www.youtube.com/embed/8eKqFJmRYh4)
   - Rigatoni Al Segreto, [Food Wishes](https://www.youtube.com/embed/o1xg1ntqSHU)
   - Authentic Italian Aubergine Parmigiana, [Mile Zero Kitchen](https://www.youtube.com/embed/B9L3IMOIQ90)
   - How to Make Tiramisu, [Food Wishes](https://www.youtube.com/embed/t9EAm1-Y2q0)
   - Chocolate Lava Cake, [Home Cooking Adventures](https://www.youtube.com/embed/F3jJVS3NHf8)

#### Media
- The images used for the *home page* and *about* were provided by the [Chef](https://www.linkedin.com/in/chris-harms-b99322104/)
- Images displayed on the *recipes* and *contact us* page were from diffrent sources; which inclued the following:
   - For the recipes header; [Great British Chef](https://gbc-cdn-public-media.azureedge.net/img25977.1423x711.jpg)
   - For the video contents, please look at the above section named **Content** for the sources.
   - For the images of the ingredients, please look at the CSS file named [recipe.css](https://github.com/dugudugu/chris-harms-web/blob/master/css/recipe.css) for the sources.
   - For the contact us header; [The Hampstead Kitchen](http://thehampsteadkitchen.com/application/themes/thk/images/home-slider/landingSlider_01.png) 

### Code
- For the Nabar, the original code was taken from [Material Design for Bootsrap](https://mdbootstrap.com/snippets/jquery/mdbootstrap/102606?action=full_screen_mode) and then edited.
- For the Carousel, the original code was taken from [Material Design for Bootsrap](https://mdbootstrap.com/docs/jquery/javascript/carousel/) and then edited.


### Acknowledgements

My partner, the Chef, has been there for me in every step and adventure that I taken. I wanted to do something special for him. 
He is trully a great chef, and he always wanted to have a site of himself. As I'm learning how to do this, I wanted to use this opportunity to do this for him. 

I would like to give thank


- I received inspiration for this project from my own experience of building and maintaining a WordPress webpage for this business in the past years. 
- My mentor Simen Daehlin guided me towards attempting the special responsive header on the Home page.

#### Disclaimer

The content of this webpage is for educational purposes only.

The genre of music I listen to are metal, rock and classical music. 
I chose this band because I figured most people would find the songs from this band to be more agreeable than the others I like.
I hope I did them justice and my webpage concept fits their music and ideals.

Thank you to everyone that gave me feedback to make this webpage better - my mentor, Chris Z, Rachel, Simen, Shane, Jeroen, and Sipo all gave me constructive criticism that made my project better.

My eternal gratitude to my supportive hubby that picked up my slack while I dedicated myself to this project. :heart_eyes:

And my little missy that has been my inspiration to give my 100% in everything I do