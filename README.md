# DOJO CLUB STOCKHOLM
## AIMs:
The goal for this project was to create a webpage of a fictional DOJO Club in Stockholm, using HTML and CSS. The page uses semantic HTML and ARIA elements and is a responsive website across different screen sizes. A blue color palette was chosen for this project. The main aim is to invite new users to their code DOJO club, give some basic information about DOJO programing, invite users to participate and sign their newsletter. 


![Imgur](https://i.imgur.com/DAZZwUA.png)

---

## Features

* The landing page shows the club's name using a clear h1 element, and the navigation elements are positioned in the upright corner. 
* The informative box highlight what DOJO is and invite the reader to participate in the club
* The footer element has links to social media pages from the club.
* This basic layout is kept over different pages for consistency. The links are underlying on the active page to help the user to know which page they are visiting.

![Imgur](https://i.imgur.com/4HyszF9.png)

---
* The page 2 explains what DOJO programming is and describes how is a DOJO section set up, and includes an image from a DOJO section.
* It  also describes the DOJO flow  with text and has a schematic a draw explaining the DOJO flow (not seen in the image below)
* The navigation and footer elements are in the same positions for consistency across the pages. 

![Imgur](https://i.imgur.com/xXBkGH6.png)

---

* Page 3 describes the hours, address, and types of DOJO sections in the club
* It explains the days and the type of language studied at specific DOJO sections and provides an additional orientation to the user interested in participating.
* The navigation and footer elements are in the same positions for consistency across the pages. 

![Imgur](https://i.imgur.com/Dj7iehF.png)

--- 

* The signup page invites interested participants to sign up for the club newsletter and ask the language interests of the users.
* The form validates empty input or lack of email and also provide a reset button 
* The navigation and footer elements are in the same positions for consistency across the pages. 

![Imgur](https://i.imgur.com/BdlynOy.png)

---

## Testing

The page was tested in the following browsers:
* Chrome, Edge (PC)
* Safari (Ipad)

The responsiveness for the page was tested using the dev tools and  in the following devices:
* Xiaomi Mi 10T-Lite - responsive and clear reading
* Huawei p20 pro -  responsive and clear reading
* Ipad 8th generation - responsive and clear reading

The form also works perfectly in these devices, including the validation for email and empty inputs.

---

## Bugs

### Solved bugs

1. CSS not loading for all pages:
After deployment, I realized that the CSS in some pages was not loading, and thus the style was not present. I figured out that it was due to an extra "/" in the begin of my CSS link.

The error:

 * link rel="stylesheet" href="/assets/css/style.css">

The corrected link:

 * link rel="stylesheet" href="assets/css/style.css">


2. Poor performance the lighthouse test:

The lighthouse test was given a very low score for the page performance:

The panel “a” shows the initial report after deployment. It was due to the very large images used in the initial project. To solve it, I  resized down all the photos from the project and added a missing aria element in a link on page placesandhours.html. It improved the score but still presented a poor performance, as you may see in panel “b.” Finally, I figured out that browser chrome had an extension installed that was down-performing the page load. I uninstalled the extension, and the lighthouse test reached a high score, as seen in panel “c”

![Imgur](https://i.imgur.com/6XcaFYT.png)

## Unsolved bugs:

I found that the user still can submit numbers or special characters as input in the text fields in the newsletter formulary.

---

## Deployment

The page was deployed in the github pages following the instructions from github.

The link to access is below:
[DOJO CLUB IN STOCKHOLM](https://mmarmelomartelo.github.io/coding-dojo-stockholm-club/index.html)

