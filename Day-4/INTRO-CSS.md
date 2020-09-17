# INTRO-CSS

If HTML is marking and structuring text using elements. CSS is styling the elements. You use CSS to add color, add space make the font a little bigger, hiding and showing them, add a round border, make the border thinner / thicker etc.

Let me just show you. Here is some HTML markup:

    <!DOCTYPE html>
    <html>
	    <head>
	    	<title>HTML example</title>
	    </head>
	    <body>
		    <h1>My First CSS Example</h1>
		    <p>This is a paragraph.</p>
	    </body>
    </html>

It looks like this when rendered (in browser)

![rendering of the html markup above it](https://raw.githubusercontent.com/Team-FCB/Assets/master/html_simple_markup.png)

Let's add some CSS

    <!DOCTYPE html>
    <html>
	    <head>
		    <title>HTML example</title>
		    <style>
			    body {
			      background-color: purple;
			    }
			    h1 {
			      color: white;
			      text-align: center;
			    }
			    p {
			      color: white;
			      font-family: verdana;
			      font-size: 20px;
			    }
		    </style>
	    </head>
	    <body>
		    <h1>My First CSS Example</h1>
		    <p>This is a paragraph.</p>
	    </body>
    </html>

And this is how it looks now:

![HTML rendering with CSS](https://raw.githubusercontent.com/Team-FCB/Assets/master/html_simple_render.png)

We changed the background, text colors and also centered the header (h1) element.
