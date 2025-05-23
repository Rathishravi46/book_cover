
# Ex.06 Book Front Cover Page Design
# Date:22-04-2025

# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>THE COMPLETE NOVELS OF SHERLOCK HOLMES</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="bookcover.css" />The Complete Novels of Sherlock Holmes refers to the collected full-length stories written by Sir Arthur Conan Doyle, featuring the iconic detective Sherlock Holmes and his companion Dr. John H. Watson.</p>
    </div>
</head>
<body>
  <div class="column column-left">
    <div class="content">
      <h2>About the Book</h2>
       <p><em>The Complete Novels of Sherlock Holmes refers to the collected full-length stories written by Sir Arthur Conan Doyle, featuring the iconic detective Sherlock Holmes and his companion Dr. John H. Watson.</p>
      <p><em>THE COMPLETE NOVELS OF SHERLOCK HOLMES</em> </p>
  </div>

  <div class="column column-center" id="book">
    <div class="book-info">
      <h1>Sir Arthur Conan Doyle </h1>
      <h3>By </h3>
    </div>

  </div>

  <div class="column column-right">
    <div class="content">
    </div>
  </div>
</body>
</html>body {
    margin: 0;
    padding: 0;
    display: flex;
    height: 100vh;
    font-family: 'Poppins', sans-serif; 
    color: white;
  }
  
  .column {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 40px;
    box-sizing: border-box;
    overflow-y: auto;
    text-align: left;
  }
  
  .column-left {
    background-color: #1e1e2f;
  }
  
  .column-right {
    background-color: #2f1e1e;
  }
  
  .column-center {
    background-image: url(king.png); 
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    flex-direction: column;
    background-color: #000; 
    text-align: center;
    min-height: 100%;
    position: relative;
  }
  
  .content {
    max-width: 400px;
  }
  
  h1 {
    font-size: 36px;
    margin-bottom: 10px;
    color: aqua;
    font-weight: 600;
  }
  
  h2 {
    font-size: 28px;
    margin-bottom: 15px;
    color: #fdd835;
  }
  
  h3 {
    font-size: 18px;
    font-weight: normal;
    color: #ffcc80;
    margin-top: 5px;
    font-style: italic;
  }
  
  .book-info {
    background-color: rgba(0, 0, 0, 0.7);
    padding: 20px 30px;
    border-radius: 10px;
    position: absolute;
    top: 20px; 
    left: 50%;
    transform: translateX(-50%); 
    width: 90%; 
  }
  
  .column-left, .column-right {
    background-color: rgba(0, 0, 0, 0.7);
    padding: 30px;
    border-radius: 10px;
  }
  
  h2, h3 {
    font-weight: 500;
  }
  
  p {
    font-size: 16px;
    line-height: 1.6;
    margin-bottom: 15px;
  }
```
# OUTPUT:
![Screenshot 2025-05-13 111307](https://github.com/user-attachments/assets/40295b43-d7b6-4630-bd27-a60a5744c79e)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
