# Ex.06 Book Front Cover Page Design
## Date:18-04-2024

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
cover.html
```
<!DOCTYPE html>
<html>

<head>
    <title>Book Cover Design</title>
    <style> 
        .wrapper {
            background-color: rgb(210, 199, 187);
            height:100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: black;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image:url(bkkj.jpg) ;
            background-size: cover;
        }
            
        
        .insight{
            color: rgb(4, 232, 236);
        
        }
        
        
        .hrstyle{
            width: 100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(57, 176, 216);
            top: 270px;
            font-family: Georgia;
            font-size: medium;
            padding-bottom: 20px;
        }
        .booktitle{
            color: rgb(248, 243, 242);
            font-family: 'Courier New', Courier, monospace, bold;
            font-size:large;
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
            color: rgb(22, 227, 227);
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
                <b>A Modern Approach to Software </b>
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1><b>A Modern Approach to Software</b></h1></div>
            <div class="subtitle">
                 <b> the Digital Landscape in the 21st Century</b> 
            <div class="subtitle2">
                <b>>> Agile Methods, DevOps Practices, and Beyond</b><br>
                <b>>>Harnessing  Software Solutions</b><br>
                <b>>> Strategies for Collaboration, </b><br>
            </div>     
            </div>
            <div class="mypic">
                <img src="harshiniphoto.png" width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(208, 205, 255)">
            </div>
            <div class="author">
               <p><b>HARSHINI R(212223220033)</b></p>
            </div>
            <div class="pub">
                SEC 27'
            </div>
        </div>
    </div>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot 2024-04-24 155158.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
