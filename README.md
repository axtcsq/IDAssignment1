# Assignment 1
The user audience for this website is catered to employers who would like to have a look at my portfolio. The purpose of this website is to create a portfolio about me, such that the employer has a better idea about me, and for me to showcase it to my employer. After navigating through my website, one should have a better idea about me.

## Table of Contents
* [Design Process](https://github.com/axtcsq/assignment1#design-process)
  * [Uniformity and Simplicity](https://github.com/axtcsq/assignment1#uniformity-and-simplicity)
  * [Dark mode](https://github.com/axtcsq/assignment1#dark-mode)
  * [Pictures](https://github.com/axtcsq/assignment1#pictures)
  * [Mockups and Diagrams](https://github.com/axtcsq/assignment1#mockups-and-diagrams)
  * [Adobe XD](https://github.com/axtcsq/assignment1#adobe-xd)

* [Features](https://github.com/axtcsq/assignment1#features)
  * [Existing Features](https://github.com/axtcsq/assignment1#existing-features)
  * [Features Left to Implement](https://github.com/axtcsq/assignment1#features-left-to-implement)

* [Technologies Used](https://github.com/axtcsq/assignment1#technologies-used)

* [Testing](https://github.com/axtcsq/assignment1#testing)
  * [Different Browsers and Screen Sizes](https://github.com/axtcsq/assignment1#different-browsers-and-screen-sizes)
  * [Bugs and Problems](https://github.com/axtcsq/assignment1#bugs-and-problems)

* [Credits](https://github.com/axtcsq/assignment1#credits)
  * [Content and Media](https://github.com/axtcsq/assignment1#content-and-media)
  * [Acknowledgements](https://github.com/axtcsq/assignment1#acknowledgements)

## Design Process
For this assignment, this website has been designed to be simple, modern and aesthetically pleasing from the start. Personally as a user, I would like to navigate websites seamlessly with little clicks as much as possible. As employers tend to be busy with reviewing applicants and their portfolios, they would generally prefer so since it would reduce the time taken to review one's portfolio.

With that said, I had to think of what are the important pages and informations I should include on my site. By thinking through the perspective of what an employer would like to see, I have came up with Home, Educcation, Skills, Projects and Contact page. 

Previously a Reference page was also created, but I have since removed it since the employer or an average user would bother seeing it. Thus, I have moved it to a section and have also attached a Word document named "References". Doing so helps to make the navigation bar more simpler and clutter-free as well.

### Uniformity and Simplicity
As you navigate through the different pages, you would notice that there is strong uniformity in its design language and layout. Thinking from the perspective of an employer and a user, it would be much professional to keep it uniform and simple. Doing so helps to cut down on development time, as I could simply reuse the shell and modify accordingly to the page's requirements.

### Dark mode
All pages have been designed with dark mode in mind as well. As a user, if I were to view this at night or in a low-light environment, I would certainly prefer darker colours since it would not blind my eyes.

### Pictures
Multiple pictures have also been used to make the website look more modern and aesthetically pleasing. As a user, I would prefer a website with good aesthetics than those with terrible or no aesthetics, as it conveys a message to me that the developer bothered to put in the effort for even minor little details.

### Mockups and Diagrams
Attached here are my draft sketchup of how I envisioned each of my pages to look like when I started this assignment.

Link:
https://connectnpedu-my.sharepoint.com/:f:/g/personal/s10194188_connect_np_edu_sg/EhNtCriqZDVHoYsSgtuYW4wBOd0iwJAV1qLCt53YGbCQhw?e=3cjdg1

### Adobe XD
Attached here are my low-fidelity wireframes of my final design. The first link is to access the file, the second link is for desktop view, while the third link is for mobile view.

Files:
https://connectnpedu-my.sharepoint.com/:f:/g/personal/s10194188_connect_np_edu_sg/Ei1fXNloXKVLsQ8SnoEKio0BRR2beBPcdSnRlaQpmK478Q?e=yGq4b7

Desktop wireframe (Share URL):
https://xd.adobe.com/view/ece2933c-90d0-45de-9e9b-81b4f4be8a92-b9b1/?fullscreen

Mobile wireframe (Share URL):
https://xd.adobe.com/view/2d970b33-6685-4265-8c0a-4c2fac96db05-78c4/?fullscreen

### GitHub
Github repository:
https://github.com/axtcsq/IDAssignment1

Github pages:
https://axtcsq.github.io/IDAssignment1/

## Features
### Existing Features
* Flexboxes - Allows users to view website on different devices with different screen sizes.
* Form - Allows users to input text via textbox, select radio buttons, checkboxes and submit their response. Validations are implemented for any input that uses a textbox.
* Links embedded to picture when user hovers on it - Allows users to click on an image attached with a link. Links opens up in a separate tab. Doing so helps to make the website look cleaner and prevents browsing disruption to the user.
* Alt text - Allows users to see a description of the image should it fail to load.
* Title - Allows users to read a more detailed description when user hovers on the image.

### Features Left to Implement
Animated visuals and elements - Helps to bring life to the website.

## Technologies Used
* [HTML](https://www.w3.org/html/)
  * The project requires HTML to display content.
* [CSS](https://www.w3.org/Style/CSS/)
  * The project uses CSS to improve the aesthetics of the website, and is also used to make it into a responsive website.

## Testing
* All pages (Common elements):
    * Try to test if all images loads, if it fails verify that alt text appears as a failsafe method
    * Try to test if all images are displaying at full quality, then verify that it is.
    * Try to test if flexbox's width, layout changes and resizes accordingly to different screen resolution and verify that it succeeds
    * Try to test if there is margin and padding between text and flexbox, then verify that it succeeds.
    * Try to test if all text are properly displayed, then verify that it does.
    * Try to test if all links are linked correctly and working, then verify that it is successful
    * Try to test if all external CSS referenced have all loaded correct, then verify that it succeeds.
  
* Index page:
    * Go to the "index" page
    * Verify that everything is working well

* Education page:
    * Go to the "Education" page
    * Try to test if different title description appears when a user hover mouse on different images in the flexbox, then verify that it succeeds.
    * Try to test if clicking on an image attached with a link would open in a separate tab, then verify that it succeeds.
    * Verify that everything is working well

* Skills page:
    * Go to the "Skills" page
    * Verify that everything is working well

* Projects page:
    * Go to the "Projects" page
    * Try to test if same title description appears when a user hover mouse on different images in the flexbox, then verify that it succeeds.
    * Verify that everything is working well

* Contact page:
    * Go to the "Contact" page
    * Try to test if different title description appears when a user hover mouse on different images in the flexbox, then verify that it succeeds.
    * Try to test if user is able to input text in textbox, select radio buttons and checkboxes, then verify that it succeeds.
    * Try to test if validations are working for all inputs that use a textbox, then verify that it succeeds.
    * Try to test if submit button displays correctly and works partially, then verify that it does. If "HTTP ERROR 405" shows up, ignore as there is no where to redirect the submission yet.  
    * Verify that everything is working well

### Different Browsers and Screen Sizes
* When displaying the website on different browsers, all seems to work well thanks to "normalize.css".
* When displaying the website on different screen sizes, all seems to work well till the screen size goes lower than an iPhone X. More will be shared under bugs section.

### Bugs and Problems
* When the screen size is set to be lower than iPhone X, such as Galaxy Fold, the header section would no longer be centralise.
  * This issue starts to occur at a resolution of (339x818).
* When the screen size is set to be lower than Galaxy Fold, the website fails to display properly. A white sidebar would appear, the header section would no longer be centralise, while the navigation bar and flexboxes seems to be resizing accordingly well.
  * This issue starts to occur at a resolution of (249x818).
* Form elements such as radio buttons and checkboxes does not align properly.
* Adding either figure semantic element or setting the padding to beyond 110px to the header, causes the header to display off-centre when viewing on small screen sizes.
  * This issue has since been fixed by removing the figure semantic element and setting the padding to 100px.
* Unable to merge and link all external CSS files into one external CSS file.

## Credits
References can also be found in the attached Word document titled "References".

### Content and Media
All photos used in this project were obtained from:

Davies, Benjamin. (2017). person standing on gray high-rise rock formation at daytime 
    photo [Online image]. Unsplash. 
    https://unsplash.com/photos/P9BY2joAcwk

dDara. (n.d.). Key Skills free icon [Online image]. Flaticon. 
    https://www.flaticon.com/free-icon/key-skills_3095221?term=skill&page=1&position=10

Eucalyp. (n.d.). Resume free icon [Online image]. Flaticon. 
    https://www.flaticon.com/free-icon/resume_893505

Freepik. (n.d.). Mortarboard free icon [Online image]. Flaticon. 
    https://www.flaticon.com/free-icon/mortarboard_2987903?term=education&page=1&position=26

Freepik. (n.d.). Chat free icon [Online image]. Flaticon. 
    https://www.flaticon.com/free-icon/chat_2991633

Freepik. (n.d.). Code free icon [Online image]. Flaticon. 
    https://www.flaticon.com/free-icon/code_2920277?term=coding&page=1&position=5

Freepik. (n.d.). Message free icon [Online image]. Flaticon. 
    https://www.flaticon.com/free-icon/message_3062634?term=email&page=1&position=41

Freepik. (n.d.). Phone Call free icon [Online image]. Flaticon. 
    https://www.flaticon.com/free-icon/phone-call_561253?term=call&page=1&position=43

Freepik. (n.d.). Strategy free icon [Online image]. Flaticon. 
    https://www.flaticon.com/free-icon/strategy_3062796?term=project&page=1&position=68

Gallagher, Nicolas. (2018). Normalize.css. (Version 8.0.1). GitHub.
    https://necolas.github.io/normalize.css/

Hume, Christin. (2018). person sitting in front of laptop photo [Online image]. Unsplash. 
    https://unsplash.com/photos/mfB1B1s4sMc

Jeshoots. (2017). An open empty notebook on a white desk next to an iPhone and a MacBook 
    photo [Online image]. Unsplash. 
    https://unsplash.com/photos/pUAM5hPaCRI

Koloda, Vasily. (2018). group of fresh graduates students throwing their academic hat in 
    the air photo [Online image]. Unsplash. 
    https://unsplash.com/photos/8CqDvPuo_kI

Leon, Daniel. (2017). silhouette of mountains during nigh time photography photo [Online 
    image]. Unsplash. 
    https://unsplash.com/photos/v7daTKlZzaw

Loia, Domenico. (2017). Macbook Pro on table beside white iMac and Magic Mouse photo 
    [Online image]. Unsplash. 
    https://unsplash.com/photos/hGV2TfOh0ns

monkik. (n.d.). Skill free icon [Online image]. Flaticon. 
    https://www.flaticon.com/free-icon/skill_2405426?term=skill&page=1&position=64

Reyes, Alvaro. (2018). person working on blue and white paper on board photo 
    [Online image]. Unsplash. 
    https://unsplash.com/photos/qWwpHwip31M

Sikkema, Kelly. (2019). black ceramic mug beside white printer paper photo [Online image]. 
    Unsplash. 
    https://unsplash.com/photos/SiOW0btU0zk

Sikkema, Kelly. (2019). coffee mug near open folder with tax withholding paper photo    
    [Online image]. Unsplash. 
    https://unsplash.com/photos/wgcUx0kR1ps

Smashicons. (n.d.). Sign Form free icon [Online image]. Flaticon. 
    https://www.flaticon.com/free-icon/sign-form_1970023?term=forms&page=1&position=6

Spratt, Annie. (2018). woman browsing on the internet photo [Online image]. Unsplash. 
    https://unsplash.com/photos/g9KFpAfQ5bc

[Untitled illustration of a Bendemeer Primary School logo]. Bendemeer Primary School. 
    https://bendemeerpri.moe.edu.sg/about-us/school-crest-mission-vision-motto-values

[Untitled illustration of a Ngee Ann Polytechnic logo]. Ngee Ann Polytechnic. 
    https://www.np.edu.sg/Pages/default.aspx

[Untitled illustration of a Zhonghua Secondary School logo]. Zhonghua Secondary School. 
    https://www.zhonghuasec.moe.edu.sg/about-us

### Acknowledgements
I have referred to some additional resources for this project from:

W3Schools. (n.d.). CSS. W3Schools.
    https://www.w3schools.com/css/default.asp

W3Schools. (n.d.). How To Create a Top Navigation Bar. W3Schools.
    https://www.w3schools.com/howto/howto_js_topnav.asp

W3Schools. (n.d.). HTML. W3Schools.
    https://www.w3schools.com/html/default.asp