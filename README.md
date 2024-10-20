# Ex.06 Book Front Cover Page Design
## Date: 20-10-2024

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

book.css:
```

body {
  background-image: url("background.png");
  background-position : center;
  background-size: cover;
  background-repeat: no-repeat;
  margin-left: 100px;
  color:  white;
}

.edit {
  position: sticky;
  left: 0;
  font-size: 50px;
  color: orange;

  
  
    }

h1 {
  color: white;
  font-size: 50px;
}
p {
   
   font-size: 100px;
}

.direct {
  font-size: 50px;
}
img {
  bottom: 200px;
  margin-bottom: 100px;
  margin-right: 100px;
  float: right;
}
.create {
  position: fixed;
  right: 0;
  margin-bottom: 20px;
  margin-right: 100px;
  bottom: 100px; 
  color: white; 
}
```
book.html:

```
.name {
position: fixed;
left: 0;
margin-bottom: 150px;
margin-left: 100px;
bottom: 10px; 
color: white; 
font-size: 50px;

}

<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="book.css">
</head>
<body>
   

<h1>Expert insight</h1>
<hr>
<p align="center"><b>Responsive Web Design with HTML5 and CSS</b></p>
<div class="direct">
  Develop future-proof responsive websites using latest html and css techniques
</div>


<div class="edit">
  Third Edition
  <img src= "Author.jpg">
  <hr>
  
</div>
<div class="name">
  
  Ben Frain
</div>


</body>
</html>
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/f5ff655a-4cf6-40fb-b388-a4c78bbf0b00)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
