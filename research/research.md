# Compare and contrast three band websites from different genres
1. Alabama 3 https://www.alabama3.co.uk/
- genre sweet country acid house music
- pros things i like 
    - the single pixel bottom to indicate more scrolling
    - a simple vertical arrangement of information makes the site look good on all media
    - simple colour theme dark/light/dark/light/dark with red buttons and headlines in opposite
    - I like the transition used for the menu viz falls down from top
    - navbar is v simple
- cons
    - the menu is very big
    - not obviously alabama3 except for title

- wireframe
    - [Alabama3 wireframe](https://github.com/joffy69/band-milestone/blob/master/research/alabama3-1.png)

---
2. Iron Maiden https://www.ironmaiden.com/
- genre heavy metal
- pros
    - they get a lot of information onto the screen
    - visually arresting
    - maintains the band ?ethos?brand?
    - they've also got the dark/light/dark/light/dark thing going
- cons
    - very complicated

- wireframe
    - [iron maiden wireframe](https://github.com/joffy69/band-milestone/blob/master/research/iron-maiden.png)

---
3. Royal Philhamonic Orchestra https://www.rpo.co.uk/
- genre classical
- pros 
    - a lot of info on one page
    - mobile looks better than desktop
    - nice spiral design on desktop
    - lots of donate buttons
- cons
    - very trad design
    - not much visual interest (maybe intentional)
    - maybe too much on one page

- wireframe
    - [royal philharmonic wireframe](https://github.com/joffy69/band-milestone/blob/master/research/rpo.png)
---

I think I'll be going for restrained and elegant - Iron maiden are definitely neither.


e CSS you will need is simply

.img-container {
    width: 200px; /* whatever set width */
    height: 100px;
    display: inline-block; /* or you could float them */
    overflow: hidden;
}
.img-container img {
    width: 100%;
}
Share
Improve this answer
Follow
answered May 22 '12 at 13:38

Ana
33.5k66 gold badges7474 silver badges119119 bronze badges
Add a comment

1

Put the images in a wrapping element, such as a DIV, with a defined height and width and use overflow:hidden.