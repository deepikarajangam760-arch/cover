# Ex.05 Book Front Cover Page Design
## Date:21-05-2026

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Book Cover</title>

<style>

body{
    margin:0;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    background:#f2f2f2;
    font-family:Georgia, serif;
}

.book-cover{
    width:400px;
    height:600px;
    background:rgb(166,216,112);
    border:2px solid black;
    padding:30px;
    box-sizing:border-box;

    display:flex;
    flex-direction:column;
    justify-content:space-between;
}

.title{
    text-align:center;
    font-size:30px;
    font-weight:bold;
}

.line{
    width:50px;
    height:2px;
    background:black;
    margin:10px auto;
}

.subtitle{
    text-align:center;
    font-style:italic;
}

.image{
    text-align:center;
    margin:30px 0;
}

.image img{
    width:100%;
    height:180px;
    object-fit:cover;
}

.author{
    text-align:center;
    font-size:22px;
}

</style>
</head>

<body>

<div class="book-cover">

<div>
<div class="title">The Soul of Life</div>
<div class="line"></div>
<div class="subtitle">The Rhythm Of Existence</div>
</div>

<div class="image">
<img src="soul.png" alt="Book image"></div>

<div class="author">
R.DEEPIKA
</div>

</div>

</body>
</html>

```


## OUTPUT:

![alt text](<Screenshot 2026-05-22 000430.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
