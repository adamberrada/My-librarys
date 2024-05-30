# jQuery
The most Javascript tool of all the time is jQuery so before everything we need to add a `script` element pn top of our page :
```html
<script>
$(document).ready(function() {});
</script>
```
and the `document ready function` is so impotant cause without it the code may run before our HTML is rendered`(is the process of  converting code into viewable and interactive web content)`,which will casue bugs.

---

All jQuery functions start with a `dollar` sign operator or as `bling`.
jQuery often selects an HTML element with a selector then does something to that elenent.

so to bounce a button element or any element we use this code:
```html
<script>
$("button").addClass("animated bounce");
</script>
```
---
Using the `addClass() `functionm in jQuery allows us to add classes to elements.
Note jsut like Css declerations,we type `.` before class name like :
```html
<script>
$(".text-primary").addClass("animated shake");
</script>
```
And also for `Id`are the same like : 
```html
<script>
$("#target3").addClass("animated fadeOut");
</script>
```
---
In jQuery has a function called `.css()` that allows you to change the CSS of a element.
to change color from red to blue here how :
```html
<script>
$("#target1").css("color", "blue");
</script>
```
Also jQuery has function called `.prop()` that allow to adjust the properties of elements.
like if you want to disable a button, it will become greyed-out and can no longer be clicked.
```html
<script>
$("button").prop("disabled", true);
</script>
```
jQuery has a functions called `.html()` that lets you add HTML tags and text within an element.
```html
<script>
$("h3").html("<em>jQuery Playground</em>");
</script>
```
And in jQuery has a function called `remove()` that remove all the HTML of an slected element.

```html
<script>
$("elment-.class-#id").remove();
</script>
```
Appending in jQuery is moving elments to another element , and it called `appendTo()`. 
```html
<script>
$("button").appendTo("div"
);
</script>
```
Tp copy an element to another container or something we use `.clone()` and we append it to the container.
```html
<script>
$("#target2").clone().appendTo("#right-well");
</script>
```
As it noticed that this involving sticking two jQuery functions together and it called <em>`function chaining` </em>and it's convenient to get things done with jQuery.

--- 
Every HTML elment has a parent element from wich it inherits properties.
`parent()` function allow you to acess the parent of whichever the element is seleced.

```html
<script>
$("#left-well").parent().css("background-color", "blue")
</script>
```
Also it has the `children()` funtion that target all the children element insider the mother container.

```html
<script>
$("#rightt-well").children().css("color", "blue")
</script>
```
---
jQuery has some tricks for targeting the right elements, id the `target:nth-child(n)` CSS selector allows to select all the nth elements with the target class or element types.

```html
<script>
$(".target:nth-child(3)").addClass("animated bounce");
</script>
```

We can also target elements based on thier positions using `:odd` and `:even` selectors.
Note that jQuery is zero-indexed it start the first selection in position 0 for even, but odd it start for 0 + 1 and so on.
 ```html
<script>
$(".target:odd").addClass("animated shake");
</script>
```