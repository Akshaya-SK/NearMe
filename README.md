# Ex04 Places Around Me
## Date: 28-10-2024

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
####map.html

```
<html>
    <head>
        <title>CHENNAI</title>
        <style>
            h1{
                font-family: Algerian;
                color: rgb(144, 5, 5);
                font-size: large;
                
            }
        </style>
    </head>
    <body>
        <h1 align="center">welcome to Chennai</h1>
        
        <centre>
            <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-10-28 102843.png" usemap="#mapnew">
            
            <map name="mapnew">
                <area target="" alt="Kapaleeshwarar Temple" title="Kapaleeshwarar Temple" href="KT.html" coords="296,253,596,337" shape="rect">
                <area target="" alt="Rippon Building" title="Rippon Building" href="RB.html" coords="310,210,50" shape="circle">
                <area target="" alt="Santhome Cathedral Basilica" title="Santhome Cathedral Basilica" href="SCB.html" coords="520,487,667,569" shape="rect">
                <area target="" alt="Museum Theatre" title="Museum Theatre" href="MT.html" coords="355,417,39" shape="circle">
                <area target="" alt="Thousand Lights Mosque" title="Thousand Lights Mosque" href="TML.html" coords="341,450,562,503" shape="rect">
                

            
        
            </map> 
        </centre> 
    </body>
</html>
```



## OUTPUT

#### map.html
![Uploading image.png…]()






## RESULT
The program for implementing image maps using HTML is executed successfully.
