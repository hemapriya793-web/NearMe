# Ex04 Places Around Me
## Date: 22.09.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html
<html>
    <head>
        <title></title>
    </head>
    <body>
        <h1 align="center"> thiruthani</h1>
        <h2 align="center"> hemapriya(25017270)</h2>
        <img src="Screenshot 2025-09-22 092420.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="thiruthani murugan temple" title="thiruthani murugan temple" href=" temple.html" coords="1013,472,811,334" shape="rect">
    <area target="" alt="hotel skanda palace" title="hotel skanda palace" href="palace.html" coords="1153,203,1227,268,1357,263,1354,118,1239,122" shape="poly">
    <area target="" alt="grt engineering collage" title="grt engineering collage" href="grt.html" coords="1402,40,78" shape="circle">
    <area target="" alt="vr guest house" title="vr guest house" href="guest house.html" coords="1133,536,1334,609" shape="rect">
    <area target="" alt="bus stand" title="bus stand" href="bus stand.html" coords="1098,335,113" shape="circle">
</map>
    </body>

</html>

temple.html
<html>
    <head>
        <title></title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">thiruthani</h1>
        <h2 align="left ">murugan temple</h2>
        <p>murugan temples are hindu shrines dedicated to the god murugan
        the six most sacred abodes of murugan </p> 
        
    </body>
</html>
 
 palace.html
<html>
    <head>
        <title></title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">thiruthani</h1>
        <h2 align="left ">skanda palace </h2>
        <p>skanda palace in thiruthani is a popular 3 star hotel with neat rooms,restaurant,and parking facilities </p> 
        
    </body>
</html>

grt.html
<html>
    <head>
        <title></title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">thiruthani</h1>
        <h2 align="left ">grt engineering collage</h2>
        <p>grt collage in thiruthani is an anna university-affiliated institute offering engineering and pharmacy courses.it is know for good infrastructureand quality education </p> 
        
    </body>
</html>

guest house.html
<html>
    <head>
        <title></title>
    </head>
    <body bgcolor="#ffd700">
        <h1 align="center">thiruthani</h1>
        <h2 align="left ">vr guest house</h2>
        <p>A comfortable and affordable stay option in thiruthani,offering clean rooms and friendly service </p> 
        
    </body>
</html>

bus stand.html
<html>
    <head>
        <title></title>
    </head>
    <body bgcolor="peach">
        <h1 align="center">thiruthani</h1>
        <h2 align="left ">bus stand</h2>
        <p>A major transport hub connecting thiruthani to nearby towns and cities provides frequent buses and easy accessibility for travelers</p> 
        
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (39).png>) ![alt text](<Screenshot (34) - Copy.png>) ![alt text](<Screenshot (34).png>) ![alt text](<Screenshot (35).png>) ![alt text](<Screenshot (36).png>) ![alt text](<Screenshot (37).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
