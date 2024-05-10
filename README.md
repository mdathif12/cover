# Ex.06 Book Front Cover Page Design
## Date:

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
<html>

<head>
    <title>Book Cover Design</title>
    <style> 
        .wrapper {
            background-color: rgb(188, 217, 218);
            height:100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: rgb(17, 209, 123);
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image:url(https://t3.ftcdn.net/jpg/05/14/95/12/360_F_514951224_2dxMLbIw5qNRdPGD003chpbVcxWtcp7K.jpg) ;
            background-size: cover;
        }
            
        
        .insight{
            color: rgb(32, 99, 167);
        
        }
        
        
        .hrstyle{
            width: 100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: lightblue;
            top: 270px;
            font-family: Georgia;
            font-size: medium;
            padding-bottom: 20px;
        }
        .booktitle{
            color: rgb(251, 50, 0);
            font-family: 'Courier New', Courier, monospace, bold;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width: 400px;
            position: relative;
            top: 280px;
            
        }
        .pub{
            color: rgb(20, 128, 128);
            font-size: medium;
            position: relative;
            top: 235px;
            left: 330px;
        }
        .ed{
            color: rgb(28, 120, 120);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 190px;
        
        }
        .subtitle{
            color:gold(24, 38, 78);
            font-family: unicorn;
            font-size: larger;
            position: relative;
            top: 15px;
        }
        .subtitle2{
            color: rgb(188, 204, 255);
            font-family: Arial, Helvetica, sans-serif;
            font-size: small;
            position: relative;
            top: 250px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size: contain;
        }
    </style>
</head>
<body>
    <div class="wrapper">
        <div class="bookpage">
            <div class="insight">
                <b>WEB DEVELOPMENT</b>
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1><b>WEB DEVELOPMENT</b></h1></div>
            <div class="subtitle">
                 <b>FUNDAMENTAL OF WEB Development</b> 
            <div class="subtitle2">
                <b>>> creating web application using different tools</b><br>
                <b>>> Bridging front and back end </b><br>
                <b>>> Ensuring  Quality</b><br>
            </div>     
            </div>
            <div class="mypic">
                <img src="WhatsApp Image 2024-05-10 at 08.41.26_1fbc2a28.jpg" width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(208, 205, 255)">
            </div>
            <div class="author">
               <p><b>Mohamed Athif Rahuman J(212223220058)</b></p>
            </div>
            <div class="pub">
               
            </div>
        </div>
    </div>
</body>
</html>
```

## OUTPUT:

![image](https://github.com/mdathif12/cover/assets/149365313/75285ee0-2218-4071-9345-36ee4ddf8d99)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
