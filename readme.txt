=== Rindby ===
Contributors: FlorianBrinkmann
Requires at least: 4.7
Tested up to: 4.9.6

== Description ==

The Rindby theme is a simple blogging theme without any extras.

== Changelog ==

= 2.0.3 – 14.05.2018 =

**Fixed**

* Styling of new comment cookie consent checkbox.

= 2.0.2 – 18.04.2018 =

**Fixed**

* Set content width to 956px (was 1147px before, but version 2.0.1 decreased the max font size and with that the max width of the layout).

= 2.0.1 – 17.04.2018 =

**Changed**

* Use Noto Serif instead of Droid Serif (for some reason, Droid serif is no longer available on Google Fonts).
* Bundle the font files into the theme instead of loading them from Google Fonts.

**Fixed**

* Small CSS fixes.

= 2.0.0 – 12.07.2017 =

**This version requires at least WordPress 4.7.**

It contains a larger reorganization of functions, so if you
made modifications to the functions.php in a child theme, check it before updating.

Furthermore, the HTML id attributes were changed to classes. So if you used them for
styling adjustments or JS, you have to switch to classes.

**Added**

* RTL styles

**Changed**

* switched to short array syntax []
* Doc improvements
* Reorganization of functions from functions.php into multiple files
* Content width is filterable via `rindby_content_width`
* Use classes for styling instead of ids.
* Removed time from post date.
* Removed author box (maybe better to use a plugin for that, so you will have the box
also after a theme switch).

**Fixed**

* Comments template fixes

= 1.1.3 – 17.01.2017 =

* updated screenshot
* changed font stack to Droid Serif



= 1.1.2 – 17.01.2017 =

* changed font to Droid Serif



= 1.1.1 – 17.01.2017 =

* switched theme and author uri…



= 1.1 – 17.01.2017 =

* changed font to Andada



= 1.0.4 – 16.01.2017 =

* escaping author url in footer.php



= 1.0.3 – 16.01.2017 =

* implemented requirements from theme review



= 1.0.2 – 15.08.2016 =

* corrected theme name in footer.php



= 1.0.1 – 15.08.2016 =

* added @version tag in file headers



= 1.0 – 14.08.2016 =

* initial release
