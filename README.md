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
        <title>Book cover</title>
        <style>.bookpage{
            width:400px;
            height:600px;
            color:black;
            margin-left:auto;
            margin-right:auto;
            padding:20px;
            font-family:'Cambria, Cochin, Georgia, Times, 'Times New Roman', serif';
            background-image:url("https://i.pinimg.com/originals/44/40/44/444044981fdea35dc8b38ccf9e142439.jpg");
            background-size:cover;
        }
        .insight{
            color:rgb(210, 108, 35);
        }
        .hrstyle{
            width:100px;
        }
        .author{
            display:inline;
            position:relative;
            color:rgb(198, 55, 108);
            top:190px;

            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size:medium;
        }
        .booktitle{
            color:azure;
            font-family:fantasy;
            font-size:medium;
            text-align:center;
            position:relative;           
            top:30px;
        }
        .id{
            width:400px;
            position:relative;
            top:180px;
        }
        .pub{
            color:black;
            font-size:medium;
            position:relative;
            top:155px;
            left:275px;
        }
        .ed{
            color:lightseagreen;
            font-size:medium;
            font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            position:relative;
            top:85px;
        }
        .subtitle{
            color:black;
            font-family:Roquen;
            font-size:large;
            position:relative;
            top:30px;
        }
        .mypic{
            position:relative;
            top:145px;
            left:270px;
            width:60px;
            height:70px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
            <div class="bookpage">
                <div class="insight">
                    TECH  INVERORS 
                    </div>
                    <div class="hrstyle">
                        <hr style="color:blanchedalmond">
                        </div>
                        <div class="booktitle">
                            <h1 style="font-family:cursive;color:rgb(229, 28, 112);">WOMEN OF COLOR IN TECH</h1></div>
                            <div class="subtitle"style="text-align:center;color:blacj;">
                                  "A Blueprint for Inspiring and Mentoring the Next Generation of Technology Invertors"
                                </div>
                            <div class="subtitle"style="text-align:centre;">
                            BEST SELLER OF 2024
                            </div>
                            <div class="mypic">
                                <img src= "mypic.jpg" width="125 px" height="110px">
                            </div>
                            <div class="id">
                               <hr style ="color:blanchedalmond">
                            </div>
                            <div class="author">
                                <p><b>NIKILA D</b></p>
                            </div>
                            <div class="pub">
                                HARISH DEVARAJ
                            </div>
                            <div class="ed">
                                <b>EXTENDED EDITION  </b>    
                            </div>
                            </div>
 </body>
```

## OUTPUT:
![alt text](<Screenshot (62).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
