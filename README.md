# Dashicons

Dashicons-nextgen, the ClassicPress admin icon font. For the official documentation, please refer to the [WordPress Developer Resource](https://developer.wordpress.org/resource/dashicons/).


### Icon requests

The Dashicons-nextgen project accepts icon requests and contributions.


### WordPress Bugs

For any bugs that appear within ClassicPress Core, please [create a new ticket on WordPress Trac](https://core.trac.wordpress.org/newticket). Use the "Administration" component and the "ui" focus when creating the new ticket, and be sure to include "Dashicons" somewhere in the text of the ticket.


## Setup

To build Dashicons-nextgen, make sure you have <a href="https://nodejs.org">Node JS</a> installed. Then type `npm run build` on the commandline to generate the minified SVG files and sprite.


## Adding an icon

Once you're installed, to add an icon, save an SVG in the `sources/svg` folder, then run the `npm run build` command on the commandline.

If you want to add your icon to the Dashicons-nextgen library, open a new Pull Request here with the new SVG icon, and wait a review.


## License

Dashicons-nextgen is licensed under [GPLv2](http://www.gnu.org/licenses/gpl-2.0.html), or any later version with [font exception](http://www.gnu.org/licenses/gpl-faq.html#FontException).
