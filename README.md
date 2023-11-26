# qb-menu
Menu System for the QBCore Framework

This is a modified version of **[QB-Menu](https://github.com/qbcore-framework/qb-menu)** by **[Artmines](https://github.com/Artmines)**


This Css edit is made for a survival theme server, this is pretty simple but nice to have some difference.

In the Css file you can add your background image texts!  Look for .button . title .buttonhover and .disabled in qb-menu/html/css.lua  to change the theme to fit yours. 
--[[
ex:
.disabled {
  background-image: url('https://this_will_be_your_image.jpg'); /* Replace with your grunge texture URL */
  background-repeat: no-repeat; /* Ensure the background image doesn't repeat */
  background-position: center; /* Center the background image */
  background-size: cover; /* Make sure the background image fits within the button */
 cursor: default;
}
--]]
For hover effects on buttons with background images, you can use various CSS properties to create engaging visual changes. Here are a few hover effect ideas you can implement:

Opacity Change: Alter the opacity to create a subtle transition on hover.

css
Copy code
.button:hover {
  opacity: 0.8; /* Change the opacity on hover */
}
Scale Effect: Scale the button slightly on hover to give a zoom effect.

css
Copy code
.button:hover {
  transform: scale(1.1); /* Scale up the button on hover */
}
Gradient Overlay: Add a semi-transparent overlay on hover to create a color blend effect.

css
Copy code
.button:hover::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.3); /* Adjust the overlay color and opacity */
}
Color Change: Alter the background color or text color on hover.

css
#Copy code
.button:hover {
  background-color: #ff0000; /* Change the background color on hover */
  color: #ffffff; /* Change the text color on hover */
}
Border Effect: Adjust the border or create a border on hover.

css
Copy code
.button {
  border: 2px solid transparent; /* Set a transparent border initially */
}
.button:hover {
  border-color: #000000; /* Change the border color on hover */
}
Choose one or combine multiple effects to create a unique hover experience for your buttons. Adjust the colors, timings, and other properties to match your desired design.



# License

    QBCore Framework
    Copyright (C) 2021 Joshua Eger

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>
