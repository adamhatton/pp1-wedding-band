# Testing for The Wedding Crashers

## W3C Validation

I passed each page of the website through the W3C validator. After the first pass the below error was highlighted:

<details><summary>Button Error</summary>

![button error screenshot](button-error.jpg)

</details>

I fixed this by removing the buttons from the anchor tabs and restyling the anchor tabs to appear as buttons. The only other issue following the first pass was a warning that a section on "The Band" page did not have a heading, as it only contained images. After consideration I changed this to be a div instead as I didn't believe the images to be a section semantically.

After fixing these issues I passed the pages through a second time and there were no issues. After my final session with my mentor I added a favicon to my site along with a link to it in my HTML head. I passed each page through the W3C validator again and there were no issues as shown in the below screenshots:

<details><summary>Home page</summary>

![home w3c screenshot](home-results-w3c.jpg)

</details>

<details><summary>Prices page</summary>

![prices w3c screenshot](prices-results-w3c.jpg)

</details>

<details><summary>The Band page</summary>

![band w3c screenshot](band-info-results-w3c.jpg)

</details>

<details><summary>Enquire page</summary>

![enquire w3c screenshot](enquire-results-w3c.jpg)

</details>

## Jigsaw Validation

I passed the website through the Jigsaw validator and this returned no errors:

![css jigsaw screenshot](css-results-jigsaw.jpg)

## A11Y Contrast Checker

I passed each page of the website through the a11y contrast checker and no errors were found:

<details><summary>Home page</summary>

![home a11y screenshot](home-results-a11y.jpg)

</details>

<details><summary>Prices page</summary>

![prices a11y screenshot](prices-results-a11y.jpg)

</details>

<details><summary>The Band page</summary>

![band a11y screenshot](band-info-results-a11y.jpg)

</details>

<details><summary>Enquire page</summary>

![enquire a11y screenshot](enquire-results-a11y.jpg)

</details>

## Lighthouse Analysis

I passed each page through the Lighthouse tool produce a report for both desktop and mobile performance. All results were 90+ except for the homepage performance on mobile which was 89. As I had already reduced the file sizes of the images as much as possible I decided to leave this due to it being so close to 90. The results are below:

<details><summary>Home page</summary>

![home desktop lighthouse screenshot](home-desktop-lighthouse.jpg)
![home mobile lighthouse screenshot](home-mobile-lighthouse.jpg)

</details>

<details><summary>Prices page</summary>

![prices desktop lighthouse screenshot](prices-desktop-lighthouse.jpg)
![prices mobile lighthouse screenshot](prices-mobile-lighthouse.jpg)

</details>

<details><summary>The Band page</summary>

![band desktop lighthouse screenshot](band-desktop-lighthouse.jpg)
![band mobile lighthouse screenshot](band-mobile-lighthouse.jpg)

</details>

<details><summary>Enquire page</summary>

![enquire desktop lighthouse screenshot](enquire-desktop-lighthouse.jpg)
![enquire mobile lighthouse screenshot](enquire-mobile-lighthouse.jpg)

</details>

## Manual Testing

I performed manual testing on all of the pages to ensure the following:

- All internal links work and go to the correct page
- All external links work, go to the correct page, and open in a new tab
- The styles on :hover pseudo-classes work
- The video on "The Band" page operates as intended (i.e. no auto-play, controls work)
- The styles on the contact form :focus pseudo-class work
- The contact form fields accept input
- The submit button does not work unless all required fields are populated
- Responsive elements are activated at the relevant breakpoints

These tests were completed on 3 different browsers on a desktop: Chrome, Edge and Firefox. The tests were also carried out on a Samsung Galaxy s21.

A full breakdown of the tests completed can be seen in the below screenshots. The testing file can be found [here](wedding-crashers-testing.xlsx) but please note it is a .xlsx file.

<details><summary>Home page</summary>

![home manual testing screenshot](home-manual-testing.jpg)

</details>

<details><summary>Prices page</summary>

![prices manual testing screenshot](prices-manual-testing.jpg)

</details>

<details><summary>The Band page</summary>

![band manual testing screenshot](band-manual-testing.jpg)

</details>

<details><summary>Enquire page</summary>

![enquire manual testing screenshot](enquire-manual-testing.jpg)

</details>

Additionally, after my final session with my mentor I added a favicon to the site. I manually tested that this appears in Chrome, Edge and Firefox, but have not updated the testing spreadsheet to reflect this.