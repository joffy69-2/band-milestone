Testing
=
On deploying to github pages, none of the assets appeared - my paths were wrong (assets/ not ../assets)

resizing works as expected

the social media links have moved up!  id social needed margin:30px not margin-right: 30px
Then the home link moved up! float-start not float-left

Please see linked excel spreadsheet

[real-faux-furs.xlsx](https://github.com/joffy69/band-milestone/blob/master/assets//test-assets/real-faux-furs.xlsx)
 
I have used chrome devtools to test the site for it's ability to correctly render on different devices. Errors are noted below.

Have tested all links. Please see excel spreadsheet/linktesting.

Bugs
===
1. Can't get aria controls working on nav dropdown menu.
2. Color of the dropdown menu is the same as the color of the merchandise background.
3. The form on the contact page doesn't display well on x small devices (like iphonex).
4. The buttons are not functional at the moment - an info popover has been added.
5. Dashlane bug. My password manager, Dashlane, injects custom css and html into elements it thinks are form elements. This might be a good idea, but I would like to switch it off for development.
---

|   location                |   feature      |   pass/fail     |   notes    |
|:--------------------------|:---------------|:----------------|:-----------|
|index/div id="drop-d-menu">|drop down       |pass             |7 drop downs|
|drop-d-menu anchor home    |href=#frontpage |pass             |            |
|drop-d-menu anchor history |href=#history   |1                |1          |
|drop-d-menu anchor photo   |href=#photo     |3                |3          |
|drop-d-menu anchor gig     |href=#frontpage |2                |2          |
|drop-d-menu anchor shop    |href=#frontpage |2                |4          |
|drop-d-menu anchor audio   |href=#frontpage
|drop-d-menu anchor contact |href=#frontpage