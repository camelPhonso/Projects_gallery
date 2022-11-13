# projects_gallery

## Purpose
This project asks us to set up a gallery to display projects we are working on. One of the requirements is that we use flexbox to display the different project tiles.

## Learnings
This project is mostly HTML and CSS, though I did use minimal javascript to toggle the display of information cards. The most interesting lesson in this project for me was probably using flex (the shorthand for flex-grow, flex-shring and flex-basis) to create a display that is interesting but also responsive.

I set up the flex property so that each tile will attempt to keep the basis width of 20rem, but is allowed to grow as needed in order to fill the width of the gallery if ever there aren't enough tiles to line up side by side.

This means that the display of this gallery automatically meets the criteria of showing only one tile per line when viewed on a mobile device but also that, should the number of tiles keep growing over time, the display will continuously adapt to the number of projects uploaded. This creates a continuously changing and visually interesting display, and is all achieved with one simple CSS property, making the code base clean and effective.
