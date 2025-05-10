

# *How T0 Use HTML Boilerplate?*
![HTML TAG](https://www.freecodecamp.org/news/content/images/size/w2000/2021/07/jackson-so-_t-l5FFH8VA-unsplash.jpg)

When you are building a ***new website*** , it is **important** to have a good starting foundation. In this article, I will explain what an HTML 5 boilerplate is and how to create a basic template to use in your ***projects***.

## 1. What is an HTML 5 boilerplate?
According to **Wikipedia**,

*boilerplate* code or just *boilerplate* are **sections** of code that are repeated in multiple places with little to no variation.

A *boilerplate* in ***HTML*** is a template you will add at the **start** of your***project***. You should add this *boilerplate* to all of your **HTML** pages.

***Example*** of HTML5*boilerplate*

Let's take a look at a basic **example**.
```HTML
  <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HTML 5 Boilerplate</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <script src="index.js"></script>
  </body>
</html> 
```
## 2. What is a doctype in HTML?
The **first line** in your ***HTML*** code should be the doctype declaration. A doctype tells the browser what version of ***HTML*** the page is written in.

```HTML 
<!DOCTYPE html>
```

## 3.What is the HTML root element?
The ***html*** tag is the top level element of the HTML file. You will nest the ***head*** and ***body*** tags inside of it.

```HTML 
<!DOCTYPE html>
<html lang="en">
  <head></head>
  <body></body>
</html>
```
## 4.What are head tags in HTML?
The ``` <head>``` tags **contain** information that is processed by machines. Inside the ```<head>``` tags, you will nest metadata which is data that describes the document to the machine.

```HTML
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HTML 5 Boilerplate</title>
    <link rel="stylesheet" href="style.css">
</head>
```




