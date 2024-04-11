# Class-20-Activity-Snippets

## Practice with Snippets Notes

Here are notes to help coding and troubleshooting the cookie banner and thumbnail gallery 

### Snippets

[Project 3 Snippets](https://pages.github.coecis.cornell.edu/info1300-2024sp/info1300-2024sp-documents/assignments/project3/p3-interactivity-snippets.html)

### JS Setup

Be sure you have all the jQuery and JS files setup and included in the HTML properly.

1.  Check that the jquery .js file at the bottom of all the HTML pages - this is already in your scripts sub-directory:
   
     `<script src="scripts/jquery-3.7.1.js"></script>`

### Cookie Banner

1. Live Preview the site and open the **console** to be able to check for errors
   
2. Review the HTML and CSS for the cookie banner.
   
   HTML:  note the ID's and classes used<br>
   CSS:  note the .banner classes created

3. Check that the cookie-banner.js is added below the jQuery on **every** page.

     `<script src="scripts/cookie-banner.js"></script>`


4. Code the interactivity for the cookie banner using these snippets:

    Console Messages - 

        `console.log("TODO: Add informative debugging message")"`

    Listen/Respond to Events on an Element - 

        $("TODO: CSS Selector").click(function() {
        
            /* TODO: JavaScript+jQuery code to respond to "click" event */
        
        });

    Add CSS Class - 

        $("TODO: Selector").addClass("TODO: class name");



### Thumbnail Gallery

The thumbnail image gallery is on the **popular.html** page.

1. Live Preview the site and open the **console** to be able to check for errors
   
2. Review the HTML and CSS for the gallery.
   
   HTML:  note the ID's and classes used<br>
   CSS:  note the .thumbnail-gallery classes created

3. Check that the **gallery.js** is added below the jQuery on **popular.html** page.

     `<script src="scripts/cookie-banner.js"></script>`

4. Code the interactivity for the thumbnail image gallery using these snippets:

    Console Messages - 

        console.log("TODO: Add informative debugging message")"

    Listen/Respond to Events on an Element - 

        $("TODO: CSS Selector").click(function() {
        
            /* TODO: JavaScript+jQuery code to respond to "click" event */
        
        });

    Add/Remove CSS Class - 

        $("TODO: Selector").addClass("TODO: class name");

        $("TODO: Selector").removeClass("TODO: class name");

