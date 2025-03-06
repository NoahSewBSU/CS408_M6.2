If you want to make the right impression, writing a letter on nice letterheaded paper can be a really good start. In this assessment we'll challenge you to create an online template to achieve such a look.

Starting Point
To get this assessment started, you should:

Make local copies of the HTML and CSS — save them as index.html and style.css in your GitHub repository.
Save local copies of the top, bottom, and logo images in the same directory as your code files.
Project Brief
You have been given the files needed to create a letterheaded paper template. You just need to put the files together. To get there, you need to:

The Main Letter
Apply the CSS to the HTML
Add a background declaration to the letter that:
Fixes the top image to the top of the letter
Fixes the bottom image to the bottom of the letter
Adds a semi-transparent gradient over the top of both of the previous backgrounds that give the letter a bit of texture. Make it slightly dark right near the top and bottom but completely transparent for a large part of the center.
Add another background declaration that just adds the top image to the top of the letter as a fallback for browsers that don't support the previous declaration.
Add a white background color to the letter.
Add a 1mm top and bottom solid border to the letter in a color that is in keeping with the rest of the color scheme.
The Logo
To the h1Links to an external site., add the logo as a background image.
Add a filter to the logo to give it a subtle drop shadow.
Now comment out the filter and implement the drop shadow in a different (slightly more cross-browser compatible) way, which still follows the shape of the round image.
The Body
The body of the page should be in a two column format like what is shown in the picture. When working on design you sometimes need text to fill out the page while you are working on it. You can use a Lorem IpsumLinks to an external site. generator to quickly generate text.
You need to include a radio check box and a button somewhere on the document. When you click the button you should call the alert() function in JavaScript and display the text from what ever radio button was selected.
 

Hints and tips
Remember that you can create a fallback for older browsers by putting the fallback version of a declaration first, followed by the version that works across newer browsers only. Older browsers will apply the first declaration and ignore the second one, whereas newer browsers will apply the first one and then override it with the second one.
Feel free to create your own graphics for the assessment if you wish.


## References

For browser-friendly shadow:

https://www.w3schools.com/css/css3_borders.asp


For Gradients:

https://www.w3schools.com/css/css3_gradients.asp

https://www.w3schools.com/cssref/sel_before.php

https://developer.mozilla.org/en-US/docs/Web/CSS/::after

Creating Body Text:

https://www.w3schools.com/css/css3_multiple_columns.asp

https://stackoverflow.com/questions/7948333/css-position-text-in-the-middle-of-the-page






