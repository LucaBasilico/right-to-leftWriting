# right-to-left Writing
##Arabian Navbar and HTML

If you want to translate a text into Arabian style, you have to use two options.

The first is an html addiction with a **dir="rtl"** tag.
In HTML5, the dir attribute can be used on any HTML element.

The second id a css addiction with a **orientation** tag. You have to add this script:
 direction: rtl
*Example:*
body{
  direction: rtl;
}

Otherwise **navbar** needs a Bootstrap changes.
Add into your html **pull-right** and **navbar-right**

Source:
https://css-tricks.com/almanac/properties/d/direction/
http://bootsnipp.com/snippets/r101E
