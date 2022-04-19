# vermafarms

Tools: HTML5, CSS3, SASS, Jquery

This project is an organized SASS modular Architecture. It is more of a CSS file structure and useful for a large project with multiple developers working on it. 

Folders:

SASS > foundation - this folder contains all the default css settings, normalize, base and variables such as font sizes, color palette and etc.

SASS > component - this folder contains all the css that are reusable parts of the website like head titles, sub titles, buttons, cards and etc.

SASS > frame - this folder contains the css settings related to default dimension of width sizes, backgrounds, paddings of a parent frame of the website sections/parts.

SASS > project - this folder contains all the css files of unique parts of the websites like thumbnails, gallery, testimonials and etc.

SASS > common_header.scss - this sass file contains all the css settings related to the header part of the website such as logo, top navigation, hamburger and etc.

SASS > common_footer.scss - this sass file contains all the css settings related to the footer part of the website such as logo, footer menu navigation, contact details and etc.

SASS > style.scss - this sass file contains all imported sass file from each sass folders.


Class naming convention is also based on a BEM arrangement.
Reference: https://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/
Examples:
.block {}
.block__element {}
.block--modifier {}

For this project, my class naming uniformity are based on which sass folder this part belongs to. 
For example: A button, this part belongs to component folder because it is reusable to entire website. Class name should start with "c_" (stands for component folder) and connect to a unique name like "btn". So the outcome should be class="c_btn".
