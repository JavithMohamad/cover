# Ex.06 Book Front Cover Page Design
## Date:28/10/23

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
### cover.html
```html and css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        
*{
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh; 
    margin: 0; 
    background-color:whitesmoke;
}

.container
{
    display: flex;
    height: 98vh;
    width: 30%;    
    justify-content: center;
    align-items: center;
    border-color: black;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
    overflow: hidden;
    background-image: url(nature.jpg);
    background-repeat: no-repeat;
}

.head{
    position: absolute;
    color:purple;
    top: 150px;
    font-size: 18px;
}

.word1{
    position: absolute;
    color: violet;
    top: 15px;
    left: 560px;
}

.word2{
    position: absolute;
    top: 60px;
    left: 540px;
}

.word{
    position:absolute;
    top: 550px;
    left: 560px;
    color:white;
}

.word3{
    position: absolute;
    top: 610px;
    left: 540px;
}

.author{
    position: absolute;
    top: 630px;
    left: 560px;
    color:brown;
}

.pic img{
    height: 100px;
    width: 90px;
    position: absolute;
    top: 560px;
    left: 870px;
}
        

    </style>
   
</head>
<body>
    <div class="container">
        <div class="head">
            <h1>IKIGAI</h1>
            <p>The Japanese Secret To a Long and Happy Life</p>
        </div>
        <div class="word1">
            <h3>EXPERT INSIGHT</h3>
        </div>
        <hr class="word2" width="210px">
        <div class="word">
            <h3>FIRST EDITION</h3>
        </div>
        <div class="author">
            <h3>AFZARATHAGSIN JS</h3>
        </div>
        <hr class="word3" width="170px">
        <div class="pic">
            <img src="afz.jpg">
        </div>
    </div>
</body>
</html>

```

## OUTPUT:
![image-1](https://github.com/JavithMohamad/cover/assets/121215951/28200fab-8540-43c1-9070-6ab107294fbf)
![283319079-b02aa8f6-6cbf-4c41-ac9d-9ee95d5b3c05](https://github.com/JavithMohamad/cover/assets/121215951/f4c3c5c0-ffa2-4f89-bbd0-9afe92819bff)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
