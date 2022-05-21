# DESK YOGIS

---

Deskyogis.com is a site for people who send several hours per day sitting still in front of a screen.
Site visitors will find exercises for both body and mind. 
Yoga exercises for the body that can be preformed sitting down at a desk.
And guided meditations for the mind that also can be preformed sitting at a desk.
Visitors can also sign up for our newsletter to get more guided meditations and yoga exercises. 

## Features

- Navigation and header
    - The navigation can be found on in the header section the top of the page to the right in the header.
    - The page you are on is underlined.
    - The Title of the page is to the left in the navigation header. 
    - Other links can be found in the text blocks on all pages when references to other sections is mentioned.
    - The navigation header is white on all pages to differentiate it from the rest of the page.

- Hero image and cover text
    - hero image is a woman stretching at a desk to convay what the site is about in one picture.
    - An animation emerges to catch the visitors eye with what can bu found on the site
    - Under the hero image a banner is shown with a fact that shows how important breaks are.
    - Colors from the hero picture fades in to the banner underneath.

# Site content section and about us
 - Site content section consist of:
    - About us "Make the most of your break" Which explains what visitors can find on the site.
    - Info about desk yoga exercises and why they are useful
    - Info about guided meditations and why they are useful and what the benefits can be
 

# Newsletter section
- Contains a sign up form so visitos can submit their email adress
- No server is set up to receive the email adresses yet so an error is returned. 
- The newletter brings value to visitors by sending them new exercises and guided meditations

# Contact section
- The contact section shows users how they can get in contact with us via email, instagram, twitter, facebook and youtube
- All links opens in a new browser tab. Except for the email symbol that opens a mail client installed on the operating system of the visitor
- The contact section creates value for the visitor because it shows how to get in touch, get more information and join our community  on other platforms
- The Contact section does not have any text just icons that clearly show what visitors can expect if clicked.

# Testign
- The site is tested that is looks good on: Safari, Chrome and Fire fox
- All internal links are tested. And all external links are tested that they opens in new tabs
- The sign up form is tested that it only accepts a correct email adress
- Responsiveness:
    - I have confirmed that the all pages are responsive on all standard screens using dev tools device toolbar
    - Index.html and exercises.html have their pictures that belong to the text to the right. When screen width goes under 950px they all become block elements instead and show underneath each other.
    - The header with navigation will show the nav-links underneath the page title when screen is under 950px. Instead of to the right on wider screens

# Bugs
   
## Solved Bugs
- The footer with the contact section did not show on the other pages only index.html
    - Fix: I did not import the script from font awsome on the other pages. And because the contact section consist only of icons it did not show anything.
- I couldn´t get the iframes to the you tube videos to show anything:
    - Fix: I inserted the url to the you tube clip in the src="" atribute but I later realized that I had to paste the entire imbeded code from the "Share" function on you tube 
- The wrapper for the text section on index.html was either to long or to short for its content
    - Fix: I contacted a CI tutor and he said to add display: flex ; to the wrapper and height 100% to the divs inside to make it the same height and responsive    


## Unfixed bugs
- No unfixed bugs

# Validator testing

- HTML validator
    - No erors returned using W3C validator "https://validator.w3.org/"
    

- Css validator
    - No error returned using Jigsaw "https://jigsaw.w3.org/"

- Lighthouse and Accessibility
    - Passed throug lighthouse test with good score in every category





---

# Deployment

- The site was deployed on git hub pages via settings --> pages --> Choose main branch under source drop down then press save and the link is produced.
- This is the link to the site: https://mtssamsioe.github.io/desk-yogis/index.html

# Atribution

- Css and html help
    - https://www.w3schools.com
- Yoga videos Goodful channel on you tube https://www.youtube.com/c/Goodful



## Content
- Footer and navigation header are inspired by walk through project CI "Love running"
- Text about mindfulness
    - https://www.mayoclinic.org/tests-procedures/meditation/in-depth/meditation/art-20045858

## Media
- Imgages are taken from https://www.shutterstock.com/
- Icons are taken from font awsome
- Font are taken from google fonts. I used Antonio fo the headers and Arvo font-weight 400 and 700 for the text.



![test2](assets/images/lighthouse_test.png)
