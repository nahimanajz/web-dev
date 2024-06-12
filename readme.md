# Descriotion
 This repository is for web development purposes from absolutely no prior experience about programming 
 class was held in Nyabiheke camp between April 2024 to June 07, 2024 yet a student can review most of the work done inclass 
 within this repository various directories


# Some techninal explanations 

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

tasks       
-----------
- CSS grid
- media query
- animations 
- git&github

## Git Revision
 you can either clone by `git clone github.com/your_name/your_repo.git` or follow guidelines below to associate your git remote repository with your local repository
## Step by step adding remote repository to your local respoistory

 ``` 
 git init  // initialize local repository/ project
 git add .  // stages files to track
 git commit -m "Your commit message goes here"
 git remote add origin your_repository_url  //to associate local with remote repository
 
 git pull origin branch_name //  bringing remote changes to your local repository
 
 git pull origin branch_name --allow-unrelated-histories // incase previous pull didn't work due to th changes which don't know each other
 i.e: at this stage your should see remote changes to your local repository

git push origin branch_name
 
 ```
# Task 6
--------
Design anything you want but consider these CSS positioning technique
sticky, fixed, absolute, relative and static
Remember default CSS positioning on every HTML element is static

hint
----
``` 
selector{
    position: absolute | relative | sticky | fixed | static
}

```

# Animation

``` 
animation-name: my-anim
animation-duration: 2s
animation-iteration-count: 4
animation-delay:3s
animation-timing-function: ease | ease-in | ease-out| ease-in-out

@keyframes my-anim{
    from{
        properties
    },
    to{
        properties:
    }
}
```

transform: translate(-50%, -50%)
transform: scale(2, 0.5)
transform: scaleX(2, 0.5) scaleY(2)

# Resources

1. Css animation from [Scrimba](https://www.youtube.com/watch?v=LCEgHntqBps&ab_channel=Scrimba)
2. CSS framework [freecodecamp](https://www.freecodecamp.org/news/learn-tailwind-css/) 
 click [here for video](https://www.youtube.com/watch?v=ft30zcMlFao&t=3637s&ab_channel=freeCodeCamp.org)
3. Javascript from 0 to 100 documentation (https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
4. Javascript from 0 to 100 video (https://www.freecodecamp.org/news/full-javascript-course-for-beginners/)

 [more projects](https://github.com/nahimanajz)

# prepared BY Janvier Nahimana
