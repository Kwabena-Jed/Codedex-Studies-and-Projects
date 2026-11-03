12. Invitation

# Congrats!

Well done on making it to the end of the chapter! 🚀

We covered a lot in this one, so let's recap what we've learned:

Color can be implemented in various ways, including by name, by rgb() function, and by hexadecimal.
Elements can be sized with properties like width and height, using absolute and/or relative units.
CSS supports five font families: cursive, fantasy, monospace, serif, and sans-serif.
We can format our text in CSS, including alignment and decoration.
Colors and images can be applied to the background of elements.
We can combine common properties into one line with shorthand properties.
Let's use our newly-learned knowledge to put together a party invitation!

Instructions
First, go ahead and start a new index.html file. Then, copy and paste the following:

<!DOCTYPE html>
<html lang="en">
  <head>
    <link href="styles.css" rel="stylesheet" />
    <title></title>
  </head>
  <body>
    <div id="invite-wrapper">
      <h1>You're Invited!</h1>
      <div id="invite-text">
        <p>
          Come join us for a night of fun, laughter, and good company at the most exciting party of the year! We're thrilled to invite you to our exclusive soirée, where
          you'll rub shoulders with the city's most interesting and influential personalities.
        </p>
        <p>
          Expect an unforgettable night filled with live music, delicious drinks, and mouthwatering hors d'oeuvres. The dress code is cocktail attire, so put on your most
          stylish outfit and get ready to mix and mingle with some of the brightest minds and biggest hearts around.
        </p>
        <p>We can't wait to see you there!</p>
      </div>
      <p id="itinerary">
        Date: <br />
        Time: <br />
        Location: <br />
        RSVP by <span><!-- DATE HERE --></span> to let us know you'll be joining!
      </p>
      <p>Sincerely,</p>
      <span><!-- YOUR NAME --></span>
    </div>
  </body>
</html>

For the HTML comments in the <span> elements, replace them with the date of the event and your name.

Next, go ahead and create a new styles.css file.

Be as creative as you want with the fonts and colors, but make sure to do the following:

Select #invite-wrapper:
Assign a width that uses a percentage in the 25%-75% range.
Set the padding property to 25px.
Add a background-color that uses either rgb() or hexadecimals.
Color the text with a color property that uses either rgb() or hexadecimals.
Select h1:
Give this a font-family property that has at least one desired font and one backup font (from one of the five font families).
Align the text in the center with the text-align property.
Select #invite-text and give it a width between 75% and 90%.
Select #itinerary and align its text in the center.
When finished, feel free to screenshot your invitation and Tweet it with the button below!
