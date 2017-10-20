---
title: Before Selector
---
## Before Selector

The ::before selector inserts something before the content of each selected element(s).

Use the content property to specify the content to insert.

Use the ::after selector to insert something after the content.

```CSS

//before selector
::before {
    css declarations;
}

//after selector
::after {
    css declarations;
}
```
Example : Below css code will add the text/content "Read this -" before any ``` <p> ``` tag appearing in yout HTML. Apart from ``` content ``` property
You can have any other css properties as well like ``` backgorund-color ```, ``` color ```, ``` font-weight ```, etc.
  
````CSS

p::before { 
    content: "Read this -";
}

````
#### More Information:
You can check more on this <a href="https://www.w3schools.com/cssref/sel_before.asp">here</a>


