# Ex.06 Book Front Cover Page Design
## Date: 06.10.2025

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
cover.html

<html>
    <head>
        <title>Special Edition </title>
        <link rel="stylesheet" href="cover.css">
    </head>
    <body class="bod">
        <div class="whole">
            <div class="border">
                    SEC Insights 
                    <br>  
                    <br>
                    <div class="tl"><b>MASTERING BOOTSTRAP</b></div>
                    <br>
                    <div class="st">
                        "Bootstrap your way to brilliance, where responsive design meets effortless style!"<br>
                        Top Seller of 2025
                    </div>
                    <div class="footer">
                        <div class="Edition">
                                <b class="se">SPECIAL EDITION</b>
                                <img src="img2.jpeg" class="img">
                        </div>
                        <hr class="hr">
                        <div>
                           Iswarya-S(25016326)
                           <div class="sec">SEC</div> 
                        </div>

                    </div>
            </div>
        </div>
    </body>
</html>

cover.css


.whole{
    background-image: url(bgimg.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    position: center;
    height: 600px;
    width: 400px;
    padding: 10px;
    margin-top: 50px;
}
.border{
    height: 570px ;
    width: auto;
    padding: 10px;
    border: 3px solid black;
}
.bod{
    display: flex;
    justify-content: center;
    
}
.st{
    margin-top: 10%;
    font-style: italic;
    font-size: 25px;
}
.tl
{
    font-size: 38px;
    text-align: center;
    font-style: italic;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.footer{
    display: flex;
    flex-direction: column;
    margin-top: 40%;
}

.img{
    height: 100px;
    float: right;
    justify-content: space-between;
}
.sec{
    float: right;
}
.hr
{
    width: 380px;
}

```

## OUTPUT:
![alt text](<Screenshot (33).png>)
![alt text](<Screenshot (34).png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
