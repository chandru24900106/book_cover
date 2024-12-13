# Ex.06 Book Front Cover Page Design
# Date:13/11/2024
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
<html>
    <head>
        <title>book cover</title>
    </head>
    <style>
        *{
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
        }
        .book{
            width: 45%;
            background-image: url('../destroy//backup.jpg');
            background-size: cover;
            background-position: center;
            height: 100vh;
            color: white;
        }
        .one{
            position: relative;
            font-size: 80px;
            right: 60px;
        }
        .two{
            position: relative;
            font-size: 70px;
            right: 220px;
            top: 20px;
        }
        .three{
            position: relative;
            font-size: 50px;
            right: 270px;
            top: 20px;
           

        }
        .four{
            position: relative;
            font-size: 70px;
            right: 130px;
            top: 30px;

            }
        .five{
            position: relative;
            top: 420px;
            left: 230px;

        } 
        .six{
            position: relative;
            top: 440px;
            right: 260px;

        } 
        hr{
            position: relative;
            top: 350px;
        }
        .on{
            position: relative;
            top: 200px;
        }  

    </style>
    <body>
        <center>
        <div class="book">
        <h1 class="one">Introdution to</h1>
        <h1 class="two">HTML</h1>
        <h1 class="three">And</h1>
        <h1 class="four">CSS styling</h1>
        <h1 class="five">EDITION-1</h1>
        <h1 class="six">chandru V</h2>
        <p class="on">Lorem ipsum dolor sit amet consectetur adipisicing elit. Non provident quia eius fuga distinctio commodi perferendis, doloremque nemo reiciendis praesentium.</p>
            <hr>
        </center>
     </div>
    </body>
   ```     
# OUTPUT:
![alt text](<Screenshot (7).png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
