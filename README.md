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
#### map.html

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

#### KT.html
```
<head>
    <title>Kapaleeshwarar Temple</title>
</head>
<body >
    <h1 align="center">KAPALEESHWARAR TEMPLE</h1>
    <p>
        Kapaleeshwarar Temple, located in Mylapore, Chennai, is an iconic Hindu temple dedicated to Lord Shiva. 
        It reflects classic Dravidian architecture, with a towering, intricately adorned gopuram (gateway tower) depicting scenes from Hindu mythology. 
        Originally built by the Pallavas in the 7th century and reconstructed in the 16th century by the Vijayanagar rulers, the temple is steeped in history and legend. 
        Devotees revere Kapaleeshwarar (Shiva) and Karpagambal (Parvati) here. Festivals like Panguni Peruvizha draw thousands for vibrant celebrations. 
        This temple is not only a place of worship but also a cultural landmark that embodies the spiritual heritage of Chennai.
    </p>

        
</body>
</html>
```

#### RB.html

```
<html>
    <head>
        <title>Ripon Building</title>
    </head>
    <body >
        <h1 align="center">RIPON BUILDING</h1>
        <p>
            The Ripon Building in Chennai, a fine example of Neoclassical architecture with Indo-Saracenic elements, serves as the headquarters of the Greater Chennai Corporation. 
            Completed in 1913 and named after Lord Ripon, then Viceroy of British India, the building symbolizes colonial-era architecture in India. 
            Its distinctive white façade, Corinthian columns, and clock tower, affectionately known as "Westminster Chiming Clock," make it an iconic landmark. 
            The Ripon Building spans over 9,000 square feet and houses government offices, symbolizing Chennai's administrative heritage. 
            Renovations have preserved its historic charm, blending the city's colonial past with modern governance.
        </p>

            
    </body>
</html>
```

#### MT.html
```
<html>
    <head>
        <title>Museum Theatre</title>
    </head>
    <body>
        <h1 align="center">MUSEUM THEATRE</h1>
        <p>
            The Museum Theatre, located within Chennai’s Egmore Government Museum complex, is a remarkable example of 19th-century Indo-Saracenic architecture. 
            Built in 1896, the theater boasts a distinctive circular structure with ornate detailing, combining Gothic, Roman, and Indian design elements. 
            Its interiors feature intricate woodwork and an expansive dome, creating excellent acoustics for performances. 
            Initially intended as a space for cultural events and social gatherings, the theater continues to host plays, concerts, and exhibitions, making it a cherished venue for the arts. 
            Surrounded by the museum’s historic artifacts, it stands as a cultural landmark blending Chennai’s history and artistic heritage.
        </p>

            
    </body>
</html>
```

#### SCB.html
```
<html>
    <head>
        <title>Santhome Cathedral Basilica</title>
    </head>
    <body>
        <h1 align="center">SANTHOME CATHEDRAL BASILICA</h1>
        <p>
            Santhome Cathedral Basilica in Chennai is a historic Catholic church built over the tomb of Saint Thomas the Apostle, one of Jesus Christ’s twelve disciples. 
            Originally constructed by Portuguese explorers in the 16th century, it was later rebuilt in Neo-Gothic style by the British in 1896. With its stunning white façade, soaring spires, and stained-glass windows, the basilica is a prominent religious site for pilgrims and tourists alike. 
            It houses a revered relic of Saint Thomas, making it one of only three churches in the world built over an apostle’s tomb, symbolizing Chennai’s rich Christian heritage and colonial history.
        </p>

            
    </body>
</html>
```

#### TLM.html
```
<html>
    <head>
        <title>Thousand Lights Mosque</title>
    </head>
    <body>
        <h1 align="center">THOUSAND LIGHTS MOSQUE</h1>
        <p>
            The Thousand Lights Mosque in Chennai is one of India’s largest and most historic mosques, renowned for its unique multi-domed architecture and serene atmosphere. 
            Built in the early 19th century by the Wallajah family, this mosque is named after the tradition of illuminating its large prayer hall with a thousand oil lamps. 
            The mosque features a distinctive pale green façade, towering minarets, and intricately designed arches. 
            It serves as an important religious center for Chennai's Shia Muslim community, hosting prayers, gatherings, and Muharram processions. 
            A symbol of religious harmony and heritage, it is a cherished landmark in Chennai’s cultural landscape.
        </p>

            
    </body>
</html>
```


## OUTPUT

#### map.html
![image](https://github.com/user-attachments/assets/82f090b1-e0dd-420a-aa64-07a6cdd25490)

#### KT.html
![image](https://github.com/user-attachments/assets/5164ad0c-49af-455f-8b26-7164b0b26fa2)

#### RB.html
![image](https://github.com/user-attachments/assets/74e8de17-1e96-4c82-8cbc-2632e1f6ecca)

#### MT.html
![image](https://github.com/user-attachments/assets/57b5de0d-63dd-44cf-9478-3eade20cf5ee)

#### SCB.html
![image](https://github.com/user-attachments/assets/eea3f275-89cc-4b2f-8d1e-e4e02fe5ba5c)

#### TLM.html
![image](https://github.com/user-attachments/assets/1d99f003-8563-457e-98e6-f2664617977e)

## RESULT
The program for implementing image maps using HTML is executed successfully.
