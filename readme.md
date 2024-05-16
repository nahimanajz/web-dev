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
    padding" 23px;
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

## cloning  Guideline

- Open terminal in your vs code
- git clone REPOSITORY_URL
- cd project-name
- code .    // to open vs code instance with in newly cloned repository

Now you can finally see all the files from the cloned repository

## task 1 inline css
design the following shapes using inline, internal and external CSS

- steps 1: create a folder called shapes
- step 2: inside that folder create a file called index.html

step 3: inside `index.html` define a tag called <div> then use style attributes to add all the properties needed to have 3 nested shapes like you see them on shared design.

- step 3: create a file called styles

<div style="border:1px solid red;" > white, space for children boxes
     <div>Box 1</div> {curved border, white background, put space between border and text }
     <div>Box 2</div>
     <div>Box 3</div>
<div>
</head>