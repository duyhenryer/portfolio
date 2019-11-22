# My Portfolio

<div align="center">

[![Build Status](https://travis-ci.org/duyhenryer/portfolio.svg?branch=master)](https://travis-ci.org/duyhenryer/portfolio)

[![Netlify Status](https://api.netlify.com/api/v1/badges/2e7d817d-4db5-4b7b-aceb-0493dc718a93/deploy-status)](https://app.netlify.com/sites/duyhenryer/deploys)

</div>

This repo contains an easy-to-customize personal dev portfolio template that was created with Sass and JavaScript.

 It is lightweight and fully responsive, as well as comes with the Bootstrap grid system and loaded with Font Awesome. The site is static and comes production ready if you just want to add your information and go. 
 
 Alternatively, you can edit styles, colours, and scripts fairly easily. The site was built as modular as possible to make it easy to shift around styles and content.

## Live Demo

To view a live demo, [click here]( https://duyhenryer.github.io/portfolio/).

### Making Edits / Customizing the Template

To setup, simply fork the repo and run `npm install` in order to get all the Gulp dev dependencies. Next, run `Gulp watch` to compile the Sass and minify the JavaScript. Alternatively, if you don't have Gulp installed globally, you can run the npm script `npm run watch`. Any changes done to the JavaScript (js/scripts.js) or Sass (sass/styles.scss) will be autocompiled and ready to go.

All scripts are within `js/scripts.js` and get minified to `js/scripts.min.js`. All styles are in `sass/styles.scss` and get compiled to `css/styles.css`. Both the minified scripts file and compiled CSS file are what is loaded on the page by default.

At this point, the page is ready to go and you can begin to add your own information and make any needed changes. The sections below  contains a quick breakdown of each of the default sections and how they work.

### Using The Template As Is

If you wish to use the template as is (i.e. how it's seen in the demo), then all that's required is the `css`, `images`, `js`, `libs` folders and the `index.html` file. You would then add your content to `index.html` as needed and you're good to go!

## Directory Structure
```bash
│
├── css
│   ├── styles.css
│   ├── bootstrap.min.css
│   └── **/*
├── images
│   ├── favicon.ico
│   ├── project.jpg
│   └── **/*
├── js
│   ├── constellationel.js
│   ├── scripts.js
│   ├── scripts.min
│   └── **/*
├── node_modules
│   └── **/*
├── pdf
│   ├── resume/cv.pdf
│   └── **/*
├── libs
│   ├── font-awesome
│   └── **/*
├── scss
│   ├── styles.scss
│   └── **/*
├── .gitignore
├── package.json
├── index.html
└── README.md
```
## Donation

If this project help you reduce time to develop, you can give me a cup of coffee.

You can donate on [Coinbase](https://commerce.coinbase.com/checkout/e5bf28c8-63cc-42bd-9576-a24d111dde4b) or [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg?logo=paypal&style=flat-square)](https://www.paypal.me/duyhenryer)&nbsp;
