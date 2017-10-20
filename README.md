# Right to left  - what to do
## Right to left writing: Navbar and HTML

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
**BDI** stands for Bi-Directional Isolation and it puts inside html. It's so helpful when you don't know the direction of text.

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

---------------
# Arabian Table
When you HTML page contains a table, or many tables, you have to change the direction. For this reason you have to put **direction: rtl** inside you table tag:
> *Example:*
 <table style="direction="rtl";">
  <tr>
    <th>Firstname</th>
   <th>Lastname</th>
 </tr>
  <tr>
    <td>Luca</td>
    <td>Basilico</td>
  </tr> 
 </table>

---------------
#Exisisting page
If you want to change a HTML page, you have to change these elements:
1. Float
2. Right/Left
3. Text-align

Another important aspect is to change two elements as *padding* and *margin* because you should reset images.
