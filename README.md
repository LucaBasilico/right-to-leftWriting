# right-to-left Writing
##Arabic Navbar and HTML

If you want to translate a text into Arabic style, you have to use three options.

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

Last but not least, another bdi tag.
BDI stands for Bi-Directional Isolation and it puts inside html. It's so helpful when you don't know the direction of text.

> *Example:*
> <ul>
>  <li>Test <bdi>alba</bdi></li>
>  <li>Test <bdi>rtrs</bdi></li>
>  <li>Test <bdi>إيان</bdi></li>
> </ul>
***advice for this exercise***
The code inside bdi tag has a different orientation

Source:
+ https://css-tricks.com/almanac/properties/d/direction/
+ http://bootsnipp.com/snippets/r101E
