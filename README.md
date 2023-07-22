# Welcome to my portfolio

It is difficult for me to correctly show all my capabilities in a single CV, therefore, I decided to create a portfolio with all my working experience and hobbies with which I can make a living, or could be useful for the visitors of the webpage interests.

![The portfolio, shown on a range of devices](assets/images/devices_render.png)

[View My Portfolio on Github Pages](https://parbelaez.github.io/p1-html-css/)

![GitHub last commit](https://img.shields.io/github/last-commit/parbelaez/p1-html-css?color=red)
![GitHub contributors](https://img.shields.io/github/contributors/parbelaez/p1-html-css?color=orange)
![GitHub language count](https://img.shields.io/github/languages/count/parbelaez/p1-html-css?color=yellow)
![GitHub top language](https://img.shields.io/github/languages/top/parbelaez/p1-html-css?color=green)
![W3C Validation](https://img.shields.io/w3c-validation/html?color=blueviolet&targetUrl=https://parbelaez.github.io/p1-html-css/)

## UI / UX Concept

As the portfolio is eclectic, it should be as clear and simple as possible.

The logo was inspired by an AI-generated one, from [LOOKA](https://looka.com/), but created manually using Google fonts and [Fontawesome](https://fontawesome.com/) icons

The color scheme is based on different shades of grey, except for the tiles, which were thought of as pastel-color items, so their inherent opacity matches the seriousness of the header and the footer.

### Fonts

Google Fonts is the source of the typography:

[Poppins](https://github.com/itfoundry/poppins) is a geometric sans serif typeface developed by Indian Type Foundry and Jonny Pinhorn.

### Icons and images

Icons were used directly from [Fontawesome](https://fontawesome.com/).

Images were obtained from my archive and [Pexels](https://www.pexels.com/)

---

## Content Pages

### index.html -landing page-

I chose to use a tiling system in the index to be similar to a mobile app, with an icon, title, catchphrase, and a brief description. And, that's the main reason behind the decision to use a back-to-menu button, instead of a list of links.

The footer is composed as well of icons of my normally used social networks that could help the user know more about my work.

#### Hamburguer Menu

To avoid using JavaScript for this project, it was decided to create a hamburger menu by only using HTML and CSS. The ideas came from the YouTubers: Kevin Powell and Web Dev Simplified.

[Basic, Intermediate & Pro animated hamburger icons](https://www.youtube.com/watch?v=R00QiudbD4Y).

[How To Build An Animated Hamburger Menu With Only CSS](https://www.youtube.com/watch?v=dAIVbLrAb_U).

As can be seen, the hamburger consists of 3 SVG creating the bars, and a non-visible checkbox to be used as a button. If a button were used instead, JavaScript would have been needed to catch the click event.

### Engineering

This one was used to practice the usage of the background image, and the hover displaying an image on the word: probe.

![Before the hover](assets/images/no_hover.png)

![Hovering](assets/images/hovering.png)

#### Used Technologies

All the previous, plus some snippets from [Codepen](https://codepen.io/wall-e/pen/zvvgBe).

### Writing

This is an only-text webpage. It is not meant to have more information than that until the book is published or the scripts are ready.

### Film

For this page, YouTube iframes were used, so the visitor can check part of my multimedia work.

### Music

For this page, Spotify iframes were used, along with a copyrighted photo with its corresponding mention.
Some audio clips can be inserted in the future, as the work on the album progresses.

### Photography

A set of personal photos. Some of them are not part of my Instagram account.
Flexbox was used to create the matrix.

## Deployment & Local Development

### Deployment

The GitHub Pages feature was used to deploy the live website. The instructions to achieve this are below:

1. Log in (or sign up) to Github.
2. Find the repository for this project, _p1-html-css_.
3. Click on the Settings link.
4. Click on the Pages link in the left-hand side navigation bar.
5. In the Source section, choose main from the drop-down select branch menu. Select Root from the drop-down select folder menu.
6. Click Save. Your live Github Pages site is now deployed at the URL shown.

### Development

All development was done in [Code Anywhere](https://app.codeanywhere.com/).

### Local Development

No local development was carried out.

#### How to Fork

To fork the p1-html-css repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, parbelaez/p1-html-css.
3. Click the Fork button in the top right corner.

#### How to Clone

To clone the p1-html-css repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, parbelaez/p1-html-css.
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

## Bug reports and errors

### Known bugs

None so far

### Fixed bugs

- Images not loading due to the wrong path.
- "a" attribute is given mistakenly to the image contained in it.
- Resizing issues due to the min-max height threshold not being defined.

### HTML Errors

- The w3c html validation is considered to be OK, as the errors are coming directly from the iframes given by the YouTube and Spotify codes.

YouTube: *"Error: The frameborder attribute on the iframe element is obsolete. Use CSS instead."*

Spotify: *"Error: Bad value 100% for attribute width on element iframe: Expected a digit but saw % instead.*

### CSS Errors

- The w3c html validation is considered OK, as the errors are coming directly from the fonts and icons imports from Google Fonts and Fontawesome.

## Credits

[Engineering image](https://www.pexels.com/de-de/foto/person-die-das-gerat-verwendet-132700/)

[Musician [Image](https://www.linkedin.com/in/julian-gaviria-29584272/?originalSubdomain=co) image was directly given to me by Julián Gaviria for personal use.

---

## Testing

All links (internal and external) were tested, as well as the interaction with the languages.
