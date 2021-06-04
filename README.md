# Project Example Idea 1
### Build a website for a band (real or fictional)

 ## External user’s goal:
> ### The site's users are fans and potential fans who wish to learn more about the band's history and the band members, and possibly book them for shows.

## Site owner's goal:
> ### The band are interested in selling more of their music/merchandise and getting more gigs.

### Potential features to include:
  1. Showcase photos/gallery
  2. audio
  3. video clips
        - from the band's catalog.

  4. Publicise the band's upcoming shows and/or availability to perform at events such as weddings and corporate parties.

5. Provide links to external resources, such as the band's social media profiles (can point anywhere at all).

---

# The Real Faux Furs band website

The fictional band (I hope, I have checked and can't find one) The Real Faux Furs (sytle: unknown) want a bespoke website
to promote their assault on the upper reaches of the charts. They need to enthuse their support and generate both more
ticket sales and merchanising sales. They also want to increase the number of gigs they play.



---

## UX

> Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

> In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:

> As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. 
These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

1. Existing fan
    - As an existing fan, I want to find gig dates so that I can book tickets. I want to browse a shop so that I can purchase merchandise. I want to know more about the band members.
    ![Image of gallery](https://github.com/joffy69/band-milestone/blob/master/assets/pictures/screenshots/responsive-gigs.jpg?raw=true "Responsive gigs")
2. Potential fan
    - As a potential fan, I want to read about the band and browse photos, so that I can decide whether The Real Faux Furs are for me. I want to find gig dates, so that I can book tickets.
    ![Image of gallery](https://github.com/joffy69/band-milestone/blob/master/assets/pictures/screenshots/ipad-pro-gallery.jpg?raw=true "gallery gigs merchandise audio" )
3. Potential hirer
    - As a potential hirer, I want to read about the band/browse photos, so that I can decide whether the band is suitable for my event ie wedding/club night/festival/childrens party/school dance etc. 
    I need a contact form to allow initial contact to be made with the band.
    ![contact form](https://github.com/joffy69/band-milestone/blob/master/assets/pictures/screenshots/contactform.jpg?raw=true "contact form")

Wireframes 
=

[Faux furs wireframe](https://github.com/joffy69/band-milestone/blob/master/design/wireframes/rfauxfurs.pdf)

---

1. Strategy plane - what are you aiming for and for who
    - fans/potential fans
        - band member bios
        - band history
        - photos
        - video
        - audio
        - merchandise
        - gig list
    - the band
        - greater sales of merch
    - potential promoters
        - appeal for collaboration/what the band can do


 - You've got the focus: what's worth doing?
 - The definition: what are we creating?
 - And value: what value does it provide?

2. Scope plane - which features to include based on strategy
    - History of band
    - video/audio
    - gig pictures
    - shop
    - gig list
    - promoters/for hire

|   feature   |   importance   |   feasability   |   totals  |
|:------------|:---------------|:----------------|:----------|
|history      |4               |1                |4          |
|video/audio  |2               |2                |4          |
|gallery      |1               |1                |1          |
|shop         |1               |3                |3          |
|gig list     |1               |2                |2          |
|for hire     |2               |2                |4          |

3. Structure plane - how is info structured and logically grouped
    - history/gallery/video/audio are media 
    - shop is merchandise
    - giglist/forhire are info

4. Skeleton plane - info presentation
    - as in a3 and im one long page with page links, then links to gig page and shop

5. Surface plane - finished product look like- colors, typography design element
    - looking for a dark colour (not black) and a light colour (not white)
    - other colours will depend on the stock photos I can find
    - typography check whats popular at the moment on google fonts
    - remember three click rule
    - we want buttons to change colour on select/process
    
---
Features
> In this section, you should go over the different parts of your project, and describe each in a sentence or so.

Existing Features
==
Five features/sections and a landing page/image
contact form

- Landing page - a simple background picture and the bands name. 

- Feature "Meet the band" - showcase the band members to give a feel for the Real Faux Furs. Draw the viewer down the page.

- Feature "Gallery" - more images of the band in action.

- Feature "Gigs" Where, When, Buy, Buy, Buy

- Feature "Merchandise" viewers can browse a shop - probably just a drop-in one in reality

- Feature "Audio" users can listen and download sample music

- Feature "Contact" a contact form to allow users to contact the band

>Feature 1 - allows users X to achieve Y, by having them fill out Z

> For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

> In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

Features Left to Implement
=
- If video became available one could change audio to media
- Dropin Shop for merchandise
- Contact form to post to db/email

---

Technologies Used
=
- HTML, https://www.w3.org/html/
    - for creation of website.
- Css, https://www.w3.org/Style/CSS/Overview.en.html
    - for styling of website.
- JavaScript, http://www.ecmascript.org/
    - for popup behaviour in bootstrap 5.
- Bootstrap 5, https://getbootstrap.com/docs/5.0/getting-started/introduction/
    - framework for design
- Balsamiq wireframes, https://balsamiq.com/
    - wireframe for mockups
- Microsoft Excel, https://www.microsoft.com
    - used for testing.
- Vim, https://www.vim.org/
    - for writing commit messages.
- GitHub, https://github.com/
    - for version control
- Gitpod, https://www.gitpod.io/
    - development environment
- GitHub Pages, https://pages.github.com/
    - deployment.

---

Testing
>In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

> Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

> For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

>Contact form:
>Go to the "Contact Us" page
>Try to submit the empty form and verify that an error message about the required fields appears
>Try to submit the form with an invalid email address and verify that a relevant error message appears
>Try to submit the form with all inputs valid and verify that a success message appears.
>In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

>You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.
>If this section grows too long, you may want to split it off into a separate file and link to it from here.

Bugs
===
1. cant get aria controls working on nav dropdown menu
2. color of the dropdown menu is the same as the color of the merchandise background
3. the form on the contact page doesn't display well on x small devices (like iphonex)
4. The buttons are not functional at the moment - an info popover has been added
---

Deployment
>This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

>In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

>Different values for environment variables (Heroku Config Vars)?
>Different configuration files?
>Separate git branch?
>In addition, if it is not obvious, you should also describe how to run your code locally.

---

Credits

---
1. Content
- All the text on the site is my own work. Any resemblance to people (real or fictional, alive or dead) is accidental.

2. Media
- The photos used in this site were obtained from ...
    - https://thumbs.dreamstime.com/z/rock-band-jumping-4630443.jpg
    - https://i.pinimg.com/originals/3b/bd/e2/3bbde2a9d5fd6a3b3bdb6f9f45672473.jpg
    - https://i0.wp.com/www.healthfitnessrevolution.com/wp-content/uploads/2017/02/iStock-144220369.jpg?fit=1493%2C703
    - https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fthumbs.dreamstime.com%2Fb%2Fyoung-musical-band-8968794.jpg&f=1&nofb=1
    - https://thumbs.dreamstime.com/b/rock-band-stage-14119612.jpg
    - https://cdn1.vectorstock.com/i/1000x1000/53/20/rock-band-vector-35320.jpg
    - http://images.dailyhive.com/20161125133559/shutterstock_416610790.jpg
    - https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.pinimg.com%2Foriginals%2Fbb%2Faf%2Ffe%2Fbbaffe583e8a33567590ee84d417cbdb.jpg&f=1&nofb=1
    - https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.johnlund.com%2FImages%2F10003500346.JPG&f=1&nofb=1
    - https://www.johnlund.com/Images/10003500346.JPG
    - https://www.hairfinder.com/haircollections2/rock-star-hairstyle.jpg
    - https://images.esellerpro.com/2152/I/434/03/lrgEW-8112.jpg
    - http://clipartmag.com/images/rock-star-clipart-5.jpg

- The audio files used in this site were obtained from ...
    - https://www.zapsplat.com/sound-effect-category/dance-and-pop/
    - Sound from Zapsplat.com

    
3. Acknowledgements
    - I received inspiration for this project from https://designshack.net/articles/trends/best-website-color-schemes/
    - https://stocksnap.io/search/rock+band

4. Code 
    - https://blog.ekohordan.com/posts/full-viewport-height-css/
    - https://www.w3schools.com/Css/css_positioning.asp
    - https://www.sitepoint.com/community/t/css-drop-down-menu-is-going-off-screen-when-dropping-down/3300/2
    - https://stackoverflow.com/questions/28334845/changing-html-from-css-media-query
    - https://www.w3docs.com/snippets/css/how-to-place-a-div-in-the-middle-of-the-screen-when-it-is-smaller-than-the-page.html
    - https://css-tricks.com/almanac/selectors/v/valid/
    - https://www.w3schools.com/csS/css3_shadows.asp
    - https://www.tutorialspoint.com/How-to-add-an-audio-player-to-an-HTML-webpage
    - https://www.w3schools.com/html/tryit.asp?filename=tryhtml5_audio_all

    
    - dashlane work around
        - https://stackoverflow.com/questions/59939931/stop-dashlane-auto-fill-on-specific-input-fields  




NB 
===
Please also see:
- research.md 
- design.md 
- testing.md

Things to remember:
    - three click rule
    
colour scheme possibles






#A350A3 for clickable items
#C1436D for dark background
#C1436D for dark text
#e0a0b6 for light text
an off white for light bkground






action: on scroll

My password manager (Dashlane) has been injecting css into the site, using id/name ie emailaddress firstName etc 
work around rename to, say, emladdress - nb this doesn't work, it's just a difference between for="email"  and id="eml"

/*----https://css-tricks.com/almanac/selectors/v/valid/----*/
#inputEml input:invalid {
  background: hsla(0, 90%, 70%, 1);
}

#inputEml input:valid {
  background: green;
}








NB NO MEDIA QUERIES ON CONTACT PAGE YET


