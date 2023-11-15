# Ex.06 Book Front Cover Page Design
## Date:28.10.23

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color: rgb(0, 0, 0);
            margin-left: auto;
            margin-right: auto ;
            padding: 20px;
            font-family: 'Tahoma';
            background-image: url('./bc.png');
            background-size: cover;
        }
        .insight{
            color:rgb(0, 0, 0);
        }
        .hrstyle{
            width: 100px;
        }

        .author{
            color: white;
            display: inline;
            position: relative;
            color: rgb(0, 0, 0);
            top:190px;
            font-family:'Tahoma';
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;

        }
        .id{
            width: 400px;
            position: relative;
            top:180px;
        }
        .pub{
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;

        }
        .ed{
            color:rgb(9, 9, 9);
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top:85px;

        }
        .subtitle{
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: large;
            position: relative;
            background-color: rgb(213, 205, 205);
            top: 40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover</title>
        </head>
        <body>
            <div class="bookpage">
                <div class="insight">
                    SEC INSIGHT
                </div>
                <div class="hrstyle">
                    <hr style="color: rgb(0, 0, 0);">
                </div>
                <div class="booktitle">
                    <h1> Responsive Web Design with HTML5 and CSS </h1></div>
                <div class="subtitle" >
                    Develop future-proof responsive websites using the latest HTML5 and CSS techniques
                </div>
                <div class="mypic">
                    <img src="pic.png" width="127" height="155" alt="">
                </div>
                <div class="id">
                    <hr style="color:rgb(22, 0, 96)213, 182, 4">
                </div>
                <div class="author">
                    <p><b>NAVIN KUMAR J</b></p>
                </div>
                <div class="pub">
                    SEC
                </div>
                <div class="ed">
                    <b>Seventh Edition</b>
                </div>
            </div> 
        </body> 
</html>
```

## OUTPUT:
![Screenshot 2023-11-15 192448](https://github.com/swetha1510/cover/assets/120623583/c3ad3670-41ba-430e-9589-83c96b112a11)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
