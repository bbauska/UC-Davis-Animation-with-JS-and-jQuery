### How to use.  Add the following to your html file utilizing the jquery code.

```
<head>
  <script src="jquery-3.7.1.min.js"></script>
</head>
```

### OR,

```
<head>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
</head> 
```

### Functions In a Separate File

#### If your website contains a lot of pages, and you want your jQuery functions to be easy to maintain, you can put your jQuery functions in a separate .js file.

#### When we demonstrate jQuery in this tutorial, the functions are added directly into the <head> section. However, sometimes it is preferable to place them in a separate file, like this (use the src attribute to refer to the .js file):

### Example

```
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
<script src="my_jquery_functions.js"></script>
</head>
```

### Example

#### And in the my_jquery_function.js I might use the following example; a user clicks on a button, the elements with class="test" will be hidden:

### Example

```
$(document).ready(function(){
  $("button").click(function(){
    $(".test").hide();
  });
});
```

#### More Examples of jQuery Selectors

#### Syntax 	Description 	Example

```
$("*") 	Selects all elements 	
$(this) 	Selects the current HTML element 	
$("p.intro") 	Selects all <p> elements with class="intro" 	
$("p:first") 	Selects the first <p> element 	
$("ul li:first") 	Selects the first <li> element of the first <ul> 	
$("ul li:first-child") 	Selects the first <li> element of every <ul> 	
$("[href]") 	Selects all elements with an href attribute 	
$("a[target='_blank']") 	Selects all <a> elements with a target attribute value equal to "_blank" 	
$("a[target!='_blank']") 	Selects all <a> elements with a target attribute value NOT equal to "_blank" 	
$(":button") 	Selects all <button> elements and <input> elements of type="button" 	
$("tr:even") 	Selects all even <tr> elements 	
$("tr:odd") 	Selects all odd <tr> elements 	
```

#### Use our jQuery Selector Tester to demonstrate the different selectors.

##### For a complete reference of all the jQuery selectors, please go to our jQuery Selectors Reference.

