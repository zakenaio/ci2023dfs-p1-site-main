# Testing

Return back to the [README.md](README.md) file.


### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files

![w3 HTML Validation](resources/w3valid-html.png "Valid w3 HTML")


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.
![w3 CSS Validation](resources/w3valid-css.png "Valid w3 CSS")


## UX Testing

Results of UX testing. 
Results of UX testing. 
#### **Navigation Bar:**
**Expected Behavior:** Clicking on each button should navigate to the corresponding parallaxed section divider with content directly underneath.
**Result: PASS**. The navigation bar functions as intended, providing a smooth transition to the targeted sections.

#### **Top-Return Button:**
**Expected Behavior:** The button should appear after scrolling 20px. Clicking it should smoothly scroll back to the top.
**Result: PASS.** The button appears as expected, and its functionality seamlessly returns users to the top of the page with a smooth scrolling effect.

#### **Member Form:**
**Expected Behavior:** The form should require inputs for first name, last name, and email. After submission, users should be directed to a confirmation page, which automatically returns to the main site after 10 seconds. A message prompting the completion of the first missing field should appear.

**Results:**
**Field Validation: PASS**. The form prompts users to fill in the first missing field.
**Submission: PASS.** Clicking the submit button successfully navigates to the confirmation page.
**Confirmation Page Auto-Return: PASS.** The confirmation page automatically returns to the main page after 10 seconds.

These positive outcomes affirm that the website's key features, including navigation, user interaction elements, and form submissions, align with the expected behaviors. This successful UX testing underscores the project's commitment to providing a user-friendly and reliable experience for visitors.

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Windows 11 | Edge | Brave |  |
| --- | --- | --- | --- |
| |![Win 11 Edge](resources/comp-edge.png "Win 11 Edge")|![Win 11 Brave](resources/comp-brave.png "Win 11 Brave")|   |
| Linux (EndevourOS) | FireFox | Brave | Thorium |
|Here shows that Linux lacks the default font and reverts to Arial |![Linux Firefox](resources/comp-lnx-firefox.png "Linux Firefox")|![Linux Brave](resources/comp-lnx-brave.png "Linux Brave")|![Linux Thorium](resources/comp-lnx-thorium.png "Linux Thoium") |
| MacOS Sonoma | Safari | Brave | Firefox |
| |![MacOS Safari](resources/comp-mac-safari.png "Linux Firefox")|![MacOS Brave](resources/comp-mac-brave.png "Linux Brave")| ![MacOS Firefox](resources/comp-mac-firefox.png "Linux Firefox")  |


## Responsiveness

| Device | Screenshot | Notes |
| --- | --- | --- |
| Mobile (DevTools) | ![screenshot](resources//responsive-mobile-dev.png) | Works as expected |
| Mobile Pixel 7 Pro | ![screenshot](resources//responsive-mobile-p7p.png) | Works as expected |
| Mobile Sony 1 ii | ![screenshot](resources//responsive-mobile-sony1ii.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](resources//responsive-tablet-dev.png) | Works as expected |
| Tablet (Samsung) | ![screenshot](resources//responsive-tablet-samsung.jpg) | Works as expected |
| Desktop 1080p | ![screenshot](resources//responsive-desktop-1080.png) | Works as expected |
| Desktop 1440p | ![screenshot](resources//responsive-desktop-1440.png) | Works as expected |


## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

Main page. 
| Desktop | Mobile |
| --- | --- |
|![Lighthouse](resources/lighthouse-desktop.png "Lighthouse Scores desktop")|![Lighthouse](resources/lighthouse-mobile.png "Lighthouse Scores mobile")|

Confirmation page.
Here I get a slightly lower accessibility score because of my use of a "refresh" tag. More info [here](https://dequeuniversity.com/rules/axe/4.8/meta-refresh "Information about refresh tag"). 
| Desktop | Mobile |
| --- | --- |
|![Lighthouse](resources/lighthouse-conf-desktop.png "Lighthouse Scores desktop")|![Lighthouse](resources/lighthouse-conf-mobile.png "Lighthouse Scores mobile")|
