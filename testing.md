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

|   location                |   feature        |   pass/fail     |   notes    |
|:--------------------------|:-----------------|:----------------|:-----------|
|index/div id="drop-d-menu">|drop down         |pass             |7 drop downs|
|drop-d-menu anchor home    |href=#frontpage   |pass             |            |
|drop-d-menu anchor history |href=#history     |1                |1          |
|drop-d-menu anchor photo   |href=#photo       |3                |3          |
|drop-d-menu anchor gig     |href=##gig        |2                |2          |
|drop-d-menu anchor shop    |href=#shop        |2                |4          |
|drop-d-menu anchor audio   |href=#audio       |   |
|drop-d-menu anchor contact |href=#contact.html|   |


| locaton                                 | feature                         | question                                                                                             | pass/fail | notes                        |                                                     |
| --------------------------------------- | ------------------------------- | ---------------------------------------------------------------------------------------------------- | --------- | ---------------------------- | --------------------------------------------------- |
| index/div id="drop-d-menu"              | drop down                       | Does the drop down dropdown?                                                                         | pass      | 7 dropdowns                  |                                                     |
| drop-d-menu anchor home                 | href=#frontpage                 | Does the anchor open the home page in the same window                                                | pass      |                              |                                                     |
| drop-d-menu anchor history              | href=#history                   | does the anchor open the history section in the same window                                          | pass      |                              |                                                     |
| drop-d-menu anchor photo                | href=#photo                     | does the anchor open the photo section in the  same window                                           | pass      |                              |                                                     |
| drop-d-menu anchor gig                  | href=##gig                      | does the anchor open the gig section in the same window                                              | pass      |                              |                                                     |
| drop-d-menu anchor shop                 | href=#shop                      | does the anchor open the shop section in the same window                                             | pass      |                              |                                                     |
| drop-d-menu anchor audio                | href=#audio                     | does the anchor open the audio section in the same window                                            | pass      |                              | Does the Contact link navigate to the Contact page? |
| drop-d-menu anchor contact              |  href=#contact.html             | does the anchor open the contact page in a new window                                                | pass      | target=\_blank               | Does the Contact form allow empty input?            |
| index/a role=button buy tickets         | data-bs-content="Not Working"   |                                                                                                      | ???       | might change this to a post? | Does the Contact form submit correctly?             |
| index/a role=button buy tickets         | data-bs-content="Not Working"   |                                                                                                      | ???       | might change this to a post? | Do the social links open in a new tab?              |
| index/li sick and tired                 | audio controls                  | do the audio controls play sound                                                                     | pass      |                              |                                                     |
| index/li natalia                        | audio controls                  | do the audio controls play sound                                                                     | pass      |                              |                                                     |
| index/li sheesh                         | audio controls                  | do the audio controls play sound                                                                     | pass      |                              |                                                     |
| index/footer/span id =contact           | link href contact.html          | does the span link open the contact page in a new window                                             | pass      | target=\_blank               |                                                     |
| index/footer/span id = social           |                                 |                                                                                                      |           |                              |                                                     |
| twitter                                 | link https://www.twitter.com    | does the twitter icon link to twitter in a new page                                                  | pass      | target=\_blank               |                                                     |
| facebook                                | link https://www.facebook.com   | does the facebook icon link to facebook in a new page                                                | pass      | target=\_blank               |                                                     |
| pinerest                                | link https://www.pinterest.com  | does the pinerest icon link to pinerest in a new page                                                | pass      | target=\_blank               |                                                     |
| instgram                                | link https://www.instagram.com  | does the instgram icon link to instgram in a new page                                                | pass      | target=\_blank               |                                                     |
| soundcloud                              | link https://www.soundcloud.com | does the soundcloud icon link to soundcloud in a new page                                            | pass      | target=\_blank               |                                                     |
| contact/div id="drop-d-menu"            | drop down                       | does the contact drop down dropdown                                                                  | pass      | 7 dropdowns                  |                                                     |
| drop-d-menu anchor home                 | href=#frontpage                 | Does the anchor open the home page in the same window                                                | pass      |                              |                                                     |
| drop-d-menu anchor history              | href=#history                   | does the anchor open the history section in the same window                                          | pass      |                              |                                                     |
| drop-d-menu anchor photo                | href=#photo                     | does the anchor open the photo section in the  same window                                           | pass      |                              |                                                     |
| drop-d-menu anchor gig                  | href=##gig                      | does the anchor open the gig section in the same window                                              | pass      |                              |                                                     |
| drop-d-menu anchor shop                 | href=#shop                      | does the anchor open the shop section in the same window                                             | pass      |                              |                                                     |
| drop-d-menu anchor audio                | href=#audio                     | does the anchor open the audio section in the same window                                            | pass      |                              |                                                     |
| drop-d-menu anchor contact              |  href=#contact.html             | does the anchor open the contact page in a new window                                                | pass      | target=\_blank               |                                                     |
| contact/footer/span id =contact         | link href contact.html          | does the contact/footer/span id =contact icon link to contact/footer/span id =contact in a new paage | pass      | target=\_blank               |                                                     |
| contact/footer/span id = social         |                                 |                                                                                                      |           |                              |                                                     |
| twitter                                 | link https://www.twitter.com    | does the twitter icon link to twitter in a new page                                                  | pass      | target=\_blank               |                                                     |
| facebook                                | link https://www.facebook.com   | does the facebook icon link to facebook in a new page                                                | pass      | target=\_blank               |                                                     |
| pinerest                                | link https://www.pinterest.com  | does the pinerest icon link to pinerest in a new page                                                | pass      | target=\_blank               |                                                     |
| instgram                                | link https://www.instagram.com  | does the instgram icon link to instgram in a new page                                                | pass      | target=\_blank               |                                                     |
| soundcloud                              | link https://www.soundcloud.com | does the soundcloud icon link to soundcloud in a new page                                            | pass      | target=\_blank               |                                                     |
| contact form                            | action =       method= post     | does the contact form submit correctly                                                               | fail      |                              |                                                     |
| input id=inputName                      | test for entry??                | does the contact form disallow empty input?                                                          | fail      |                              |                                                     |
| input id=inputEmail                     | test for entry??                | does the contact form disallow empty input?                                                          | fail      |                              |                                                     |
|                                         |                                 | does the contact form test for correct email structure                                               |           |                              |                                                     |
| textarea id=message-box                 | test for entry??                | does the contact form disallow empty input?                                                          | fail      |                              |                                                     |
| select id=fanprojour                    | drop down                       | Does the drop down dropdown?                                                                         | pass      |                              |                                                     |
| input checkbox id=gridCheck1            | test for entry??                | is there a warning to remind one to check the checkbox                                               | fail      |                              |                                                     |
| contact/anchor role button type= submit | method  = post                  | does the form submit correctly                                                                       | fail      |                              |                                                     |