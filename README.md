# Ex.06 Book Front Cover Page Design
## Date:08.10.2025

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
book.html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Book Cover</title>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background: #f0f0f0;
    font-family: Arial, sans-serif;
  }

  .book-cover {
    width: 400px;
    height: 600px;
    position: relative;
    background: linear-gradient(135deg, skyblue, pink);
    border: 3px solid #000; 
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    border-radius: 5px;
    padding: 40px 20px 20px 20px;
    box-sizing: border-box;
    text-align: center; 
  }

  .title {
    font-size: 36px; 
    font-weight: bold;
    color: darkblue;
    margin: 0;
  }

  .subtitle {
    font-size: 18px; 
    color: darkblue;
    margin-top: 10px;
  }

  .author {
    position: absolute;
    bottom: 20px;
    left: 20px;
    font-size: 24px;
    font-weight: normal;
    color: darkblue;
  }

  .photo {
    position: absolute;
    bottom: 20px;
    right: 20px;
    width: 100px;
    height: 120px;
    border-radius: 5px;
    object-fit: cover;
    border: 2px solid #fff;
  }
</style>
</head>
<body>

<div class="book-cover">
  <div class="title">Future of Technology</div>
  <div class="subtitle">A glimpse into tomorrow's technological landscape</div>
  <div class="author">Pavithira</div>
  <img src="pavi.jpg" alt="Book Photo" class="photo">
</div>

</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (63).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
