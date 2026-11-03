11. Shorthands

# Shorthand Properties

Some properties in CSS, whether we realize it or not, can actually be broken down into separate, more specific properties.

The border property, for example, is actually a shorthand for three additional properties: width, style, and color!

span {
border-width: 3px;
border-style: dashed;
border-color: #ff0000;
}

The rule above can be expressed with the shorthand border property!

span {
border: 3px dashed #ff0000;
}

Either of these will render the same result:

Rendered border around 'I love CSS!'

Remember when we learned about the different properties for fonts? Here’s what those properties look like:

span {
font-family: Georgia, serif;
font-weight: 800;
font-size: 12px;
}

All of these can be expressed with a single, shorthand font property!

span {
font: 800 12px Georgia, serif;
}

The shorthand font property must at least have a value for the font-family and font-size properties. Everything else is optional, but the font-weight must go before the font-size (e.g., 800 12px).

Note: Be aware that some shorthand properties may not be compatible on all browsers, or inconsistently available (e.g., text-decoration property on Safari). Therefore, it's a good idea to test shorthands on multiple browsers.

Instructions
Let’s practice using shorthands!

Copy and paste the following HTML into the index.html file:

<h1>Favorite Song</h1>
<p><!-- Favorite song/artist here. --></p>

Go ahead and replace the HTML comment with your favorite song and artist!

Next, paste the following in the styles.css file:

h1 {

}

p {

}

For the h1 heading element, add a shorthand border property that includes values for width, style, and color.
For the p paragraph element, let's add a shorthand font property with values for the size, weight, and font-family.
Note: No matter which font-family you choose, always remember to include a fallback font like sans-serif or cursive!
