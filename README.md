# HTML/CSS Derivita Challenge

## Instructions:
* Write HTML and CSS to implement the design specification (https://xd.adobe.com/spec/04af9ee7-b732-4532-66df-fd5051b61d9b-729e/)
* Make sure the content centers itself vertically and horizontally as you resize the window
* Add an image of your choice in the box that says "Insert Image Here"
* Install the font from Google Fonts (https://fonts.google.com/specimen/Roboto)
* Use icons from https://material.io/resources/icons/
* Create a Readme file. Provide a short description of what you built,  and any comments you have on the assignment.

## Notes:

* These two cards are designed according to the spec here: https://xd.adobe.com/spec/04af9ee7-b732-4532-66df-fd5051b61d9b-729e/.

* I've used rem rather than px units to improve adaptive behavior (although most modern browsers zoom by pixel these days). I've implemented flexbox for each card. The font is Roboto, downloaded from Google Fonts, and the 'edit' icon is from Material Design at https://material.io/resources/icons. 

* The photo is from unsplash, optimized to load quickly and pre-sized to the correct dimensions. If photos of different sizes were to be fetched from an api and displayed, I would refactor the CSS to hide overflow so that they fit nicely, or allow the card to resize to accomodate different aspect ratios. 

* I've used semantic html tags such as header, section, button, h1, h2, to make the cards more accessible to devices such as screen readers. 

* If these cards were part of a larger project, I would expect to use SCSS and define variables such as color in a separate file. Given more time, I would also like to implement media queries for screen sizes smaller than the cards' width, and add hover states in a secondary color for the buttons.
