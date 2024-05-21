css: it defined as cascadig style sheet
we use to change appearance of webpage

## types of CSS

---

Inline CSS: it is defined with in the tag with `style` atrribute

```
<tag style="property:value;"> </tag>
```

## internal CSS:

it is defined inside the opening and closing <head> tag by using <style> tag along with help of classes and selectors

**Syntax:**

```
<html>
<head>
    <style>
     selector {
    property: value;
}

    </style>

</head>
</html>
```

## External CSS:

We define these styling in the separate file later on we import it in our html source code using <link> tag with `rel` and `href` attributes full tag <link hfer="PATH_TO_MY_CSS_FILE" rel="stylesheet">

```
syntax: selector {
    property: valuue;
}
```
Today's work is to use external css 
------------------------------------
Design a page which has 
1. dark background and white text
2. page must have logo, and navigation links include home, about us, contact us
     a. logo can be text, or image
     b. no underline below menu links 
     c. links must leave space between them atleast 20px


3. nav menu  section must have underline which has grey color, 1px border
4. Whole page contents must be spaced left-right side with 64px and 0px on top and bottom
5. body contents must be paragraphs with random texts(hint: use type lorem23 in your editor then press enter)

Don't hesitate to ask Any problem 

 
task 4
-------------
- create two files one is aboutus.html and contactus.html
- embed the menu we had from index.html we created yesterday
- link the menu to navigate among our pages we build
- add hover effect on our menus, when user hovers on menu it has to have background of green, and text has to be white

n.b: I explain in few minutes for anyone who is not getting it.
others you can start
