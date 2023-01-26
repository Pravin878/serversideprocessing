# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

### Step 1:

Desing your website for calculation using wireframe work.

### Step 2:

Then to execute the wireframe work desing use html,css

### Step 3:

Use views.py to execute the coding in serverside.

### Step 4:

Mention the path of the website in urls.py.

### Step 5:

save all the process

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Math Calculation</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    
</head>
<style>
    *{
        box-sizing: border-box;
        font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
    }

    body{
    background-color: rgb(231, 21, 21);
    }

    h1 {
        font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    .container{
    width: 1080px;
    height: 500px;
    margin-top: 100px;
    margin-left: auto;
    margin-right: auto;
    border-radius: 30px;
    border: 10px solid darkgrey;
    box-shadow: inset 0 0 15px darkgrey;
    background-color: rgb(25, 236, 131);
    }
    h1{
        text-align: center;
        padding-top: 15px;
    }
    .calculate{
        padding-top: 40px;
        padding-bottom: 10px;
        padding-left: 10px;
        padding-right:20px;
        text-align: center;
        font-size: 20px;
    }
</style>
<body>
    <div class="container">
        <h1>AREA OF A TRIANGLE</h1>
        <form method="POST">
            {% csrf_token %}
            <div class="calculate"> 
                Base:<input type="text" name="base" value={{b}}></input><br/>
            </div>
            <div class="calculate">
                Height:<input type="text" name="height" value={{h}}></input><br/>
            </div>
            <div class="calculate">
                <input type="submit" value="Calculatearea"></input><br/>
            </div>
            <div class="calculate">
                Area:<input type="text" name="area" value={{area}}></input>
            </div>
        </form>
    </div>
    
</body>
</html>
```

## OUTPUT:
![output](./pic.jpeg)

### Home Page:
![output](./pic.jpeg)

## Result:
A website to perform mathematical calculations in server side is created.

