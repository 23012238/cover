# Ex.06 Book Front Cover Page Design
## Date:5-04-2024

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
<html>
<head>
    <title>Book Cover</title>
    <style>
      body {
        margin: 0;
        padding: 0;
        background-color:black;
      }
  
      .book-cover {
        width: 500px;
        height: 700px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        background-image: urL(ccc.jpg);
        margin: 50px auto;
        
        position: relative;
      }
      
      .book-cover .insight {
        position: absolute;
        top: 20px;
        left: 20px;
        font-size: 24px;
        font-weight: bold;
        color: azure;
      }
      .book-cover .line1
      {
        position: absolute;
        top: 40px;
        left: 10px;
        width: 250px;
      }
      .book-cover .title1 {
        position: absolute;
        top: 130px;
        left: 70px;
        font-size: 40px;
        font-weight: bold;
        color: brown;
      }
      .book-cover .title2 {
        position: absolute;
        top: 180px;
        left: 35px;
        font-size: 30px;
        font-weight: bold;
        color:  rgb(251, 248, 248);
      }
  
     
      .book-cover .subtitle2 {
        position: absolute;
        top: 240px;
        left: 20px;
        font-size: 16px;
        font-weight: bold;
        color: yellow;
      }
     
      .book-cover .line2
      {
        position: absolute;
        top: 220px;
        left: 20px;
        width: 460px;
      }
      .book-cover .line3
      {
        position: absolute;
        bottom:38px;
        left: 20px;
        width: 460px;
      }
      .book-cover .edition{
        position: absolute;
        bottom:50px;
        left:20px;
        font-size: 20px;
        color:blue;
      }
  
  
      .book-cover .author {
        position: absolute;
        bottom: 10px;
        left: 20px;
        font-size: 18px;
        color: rgb(0, 255, 221);
      }
  
      .book-cover .end {
        position: absolute;
        bottom: 10px;
        right: 30px;
        font-size: 18px;
        color:azure;
      }
      .book-cover .mypic
      {
        position: relative;
        top:530px;
        left: 370px;
        width : 8px;
        height: 8px;
        background-size:fit;
      }
  
  
     
    </style>
  </head>
  
  <body>
    <div class="book-cover">
     
      <div class="insight">WEB DEVELOPMENT</div>
      <div class="line1"><hr style="color:blanchedalmond"></div>
      <div class="title1">Learning Web Design:</div>
      <div class="title2">THE COMPLETE REFRENCE</div>
      <div class="line2"><hr style="color:blanchedalmond"></div>
      <div class="subtitle2">A BEGINER'S GUIDE TO HTML,CSS,JAVA SCRIPT AND WEB GRAPHICS</div>
      <div class="line3"><hr style="color:blanchedalmond"></div>
      <div class="mypic"><img src="MY PIC.jpg"width="120" height="120" ></div>
      <div class="end">NAVEEN</div>
      <div class="edition">SPECIAL EDITION</div>
      <div class="author">S.L.NARASIMHA REDDY</div>
  
    </div>
  </body>
  
  </html>

```

## OUTPUT:
![alt text](<book cover....png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
