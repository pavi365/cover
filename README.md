# Ex.06 Book Front Cover Page Design
## Date:29-04-2024

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
## book.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>RESPONSIVE WEB DESIGN</title>
        
        <style>
            body{
    color:rgb(24, 23, 23);
    font-family: Helvetica, sans-serif;
    background-color: #f8f1f1
}

.book{
    width: 726px;
    height:891px;
    margin:auto;
    position: relative;
    background-image: url(image..png);
    background-repeat: no-repeat;
    background-size:cover;
    background-position: bottom 0px center;
    top: 90px;
}
h1{
    font-size:65px;
    margin:60px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:50px;
    font-size: xx-large;
    font-weight:10px;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    color:rgb(241, 131, 63)

}
h4{
    font-size:20px;
    margin:60px;
   margin-top:10px;
   width:430px;
}
#head{
    padding:30px;
    position: relative;
    top: 35px;
    font-size: 20px;

}
footer{
    position: absolute;
    bottom: 50px;
    color: aliceblue;
    padding-top:0px;
    width:726px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.photo{
            position: relative;
            top: 185px;
            left: 550px;
            width: 100px;
            height: 120px;
            background-size: cover;
        }
.book{
    color: #f8f1f1;
}
#HASH {
    display: flex;
    justify-content: space-between;
}
  #HASH span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
  }
  #end{
    padding-right:90px;
    
  }
        </style>
    </head>
    <body>
        <section class="book">
            <span id="head">EXPERT INSIGHT</span>
            <h1>RESPONSIVE WEB DESIGN WITH HTML5 AND CSS</h1>
            <h4>Develop future-proof responsive websites using the latest HTML5 AND CSS techniques</h4>
            
            <h3>Third Edition</h3>  
            
     
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>Pavithra</span>
                    <span id="end"><u>SEC</u></span>
                </div>
            </footer>
            <div class="photo">
                <img src="pavi.jpg" width="160px" height="160" padding="50px">
            </div> 
    </section>
    </body>
</html>
```


## OUTPUT:
![alt text](<Screenshot (38).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
