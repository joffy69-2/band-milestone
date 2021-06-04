On deploying to github pages, none of the assets appeared - my paths were wrong (assets/ not ../assets)

all links work as expected

resizing works as expected

the social media links have moved up!  id social needed margin:30px not margin-right: 30px
Then the home link moved up! float-start not float-left

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
1. Can't get aria controls working on nav dropdown menu.
2. Color of the dropdown menu is the same as the color of the merchandise background.
3. The form on the contact page doesn't display well on x small devices (like iphonex).
4. The buttons are not functional at the moment - an info popover has been added.
5. Dashlane bug. My password manager, Dashlane, injects custom css and html into elements it thinks are form elements. This might be a good idea, but I would like to switch it off for development.
---