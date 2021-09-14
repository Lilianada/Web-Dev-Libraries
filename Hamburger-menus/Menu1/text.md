How to create a Hamburger menu animation with 3 lines of Javascript
- First create your logo, and nav list
- Secondly, create a div called "menu__bars" as a conatiner for your actual menu bars.
- Then inside the menu__bars, create 3 empty divs and give then a class= "bar" and an additional class="b1", "b2" & "b3" to style the 3 bars individually.
- Also, give the 3 divs with class of "bar" an Id with "bar1", "bar2", & "bar3" so you can style the bars after writing your javascript codes individually.

* Style your "menu__bars", give it a width, height, bk-grnd color and cursor-pointer.
* Style your "bar" too. Remember, the style you're giving to the "bar" is a general styling for all 3 bars.
* "b1, b2, b3" will all have different style now. So, style only "b1" and "b3". Give them a transform property as seen in the code. 
The reason you're not styling "b2" is because it's in the middle,soit doesn't have to move. But "b1" & "b3" will transform to move up and move down respectively.

#JavaScript#
Those line of javascript mean that:
function onClickMenu(){
    * You're giving a function to ( <div class="menu__bars" onclick="onClickMenu()" id="menu">) the onClick tag in the html.
    * The function states that the script should get the element Id "menu" and that when one clicks on the menu, it should toggle and then change. That "change" should now be styled so that when it switches/toggles, something new happens.
    (Toggle meaning to switch or alternate between two positions.)

- Style your navigation links make it display none.
- Come to your javascript and repeat the second line of code but change the Id name to that of the nav links container.
- Now, it should only appear when you toggle. 

This is how to create your basic hamburger menu with just 3 lines of javascript. Every other thing is just added styling or functionality.
Thanks