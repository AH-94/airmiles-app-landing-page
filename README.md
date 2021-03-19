# airmiles-app-landing-page
A concept design that I built for work in order to update the airmiles brand.

We created this page to showcase what we could do for the brand in order to help improve their digital presence and increase signups to their app.

The page has a dynamic language switcher in the top right which uses a seperate languages.js file to dynamically translate the page from english to arabic without the need to reload the whole page. The languages.js file is an array of objects that the javascript loops over when one of the buttons is clicked to show the correspnding language on the page.

in the center of the page is the USP section that detials the features of the app. On desktop this uses CSS grid combined with event listeners that dynamically show the user the corresponding app image when they hover over each card. On mobile this section is replaced with an Owl Carousel for an improved user experience on smaller screens.
