# Ex04 Places Around Me
## Date: 

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
### map
```
<html>
    <head>
        <title>Places in Thiruvananthapuram</title>
        <h1 align="center">Thiruvananthapuram</h1>
        <h1 align="center">Created by:Prajin S(212223230151)</h1>
    </head>
    <body bgcolor="silver"> 
        <img src="tvc.png" usemap="#image-map">
        <map name="image-map">
            <area target="" alt="Padmanabha Swamy Temple" title="Padmanabha Swamy Temple" href="swa.html" coords="1003,491,1198,535" shape="rect">
            <area target="" alt="Thiruvananathapuram International Airport" title="Thiruvananathapuram International Airport" href="air.html" coords="646,560,853,617" shape="rect">
            <area target="" alt="Thiruvananthapuram Zoological Park" title="Thiruvananthapuram Zoological Park" href="zoo.html" coords="1153,81,1405,151" shape="rect">
            <area target="" alt="Veli Beach" title="Veli Beach" href="veli.html" coords="29,116,258,181" shape="rect">
            <area target="" alt="Attukal Bhagavathy Temple" title="Attukal Bhagavathy Temple" href="bha.html" coords="1188,686,37" shape="circle">
        </map>
    </body>
</html>
```

### temple
```
    <head>
        <title>Padmanabhaswamy</title>
    </head>
    <body bgcolor="Mistyrose">
        <h1 align="center">Anantha Padmanabhaswamy Temple</h1>
        <h2 align="center">East Fort,Thiruvananthapuram</h2>
        <hr size="3" color="MediumVioletRed">
        <img align="right" src="pds.jpg">
        <br><br>
        <p><h3>The Padmanabhaswamy Temple is a Hindu temple, dedicated to Vishnu, in Thiruvananthapuram, the capital of the state of Kerala, India. It is one of the 108 Divya Desams, the sacred abodes of Vishnu in the Sri Vaishnava tradition. It is widely considered as the world's richest Hindu temple.The temple is built in an intricate fusion of the Kerala style and the Dravidian style of architecture, featuring high walls, and a 16th-century gopuram.</h3></p>
    </body>
</html>
```

### AIRPORT
```
<html>
    <head>
        <title>Airport</title>
    </head>
    <body bgcolor="LightSkyBlue">
        <h1 align="center">Thiruvananthapuram International Airport</h1>
        <h2 align="center">Eanchakkal,Thiruvananthapuram</h2>
        <hr size="3" color="LightSteelBlue">
        <img align="right" src="air.jpg" height="600" width="900">
        <br><br>
        <p><h3>Thiruvananthapuram International Airport (IATA: TRV), is an international airport that serves Thiruvananthapuram, the capital city of Kerala, India. Established in 1932, it is the first airport in the state of Kerala and the fifth international airport of India, officially declared in 1991.It is the operating base of Air India, Air India Express, IndiGo and SpiceJet.</h3></p>
    </body>
</html>
```

### KOCHUVELI
```
<html>
    <head>
        <title>Veli</title>
    </head>
    <body bgcolor="Navajowhite">
        <h1 align="center">Veli Lake Tourist Village</h1>
        <h2 align="center">Veli,Thiruvananthapuram</h2>
        <hr size="5" color="Powderblue">
        <img align="right" src="veli.jpg" height="600" width="900">
        <br><br>
        <p><h3>The Veli Tourist Village which lies where the Veli Lake meets the Arabian Sea provides for unique boating and picnicking opportunities. Visitors can hire pedal boats or paddleboats as per their convenience. One can also roam the gardens and have a nice picnic or choose to employ the boats for the entire duration of the trip.</h3></p>
    </body>
</html>
```

### BIOLOGICAL PARK
```
    <head>
        <title>Zoological Park</title>
    </head>
    <body bgcolor="aquamarine">
        <h1 align="center">Thiruvananathapuram Zoological Park and Napier Museum</h1>
        <h2 align="center">Palayam,Thiruvananthapuram</h2>
        <hr size="3" color="cornflowerblue">
        <img align="right" src="zoo.jpg" height="600" width="900">
        <br><br>
        <p><h3>Thiruvananthapuram Zoo is one of the oldest zoos in India. It occupies 55 acres (22 ha) of woodland, lakes, and lawns.It is home to 82 species from around the world.Similarly the Museum and Botanical Gardens are also one of the oldest of their kind in the country. Swathi Thirunal Rama Varma (1816-1846), the ruler of Travancore during 1830-1846, was the visionary behind the establishment of the Thiruvananthapuram Museum and Zoo.</h3></p>
    </body>
</html>
```

### ATTUKAL
```
<html>
    <head>
        <title>Attukal</title>
    </head>
    <body bgcolor="Crimson">
        <h1 align="center">Attukal Bhagavathy Temple</h1>
        <h2 align="center">Attukal,Manacaud,Thiruvananthapuram</h2>
        <hr size="3" color="Darkgoldenrod">
        <img align="right" src="att.jpg" height="700" width="600">
        <br><br>
        <p><h3>The Attukal Bhagavathy Temple is a Hindu religious shrine at Attukal in Kerala, India. Goddess Bhadrakali (Kannaki), mounted over 'vethala', is the main deity in this temple.The Goddess Kannaki (Bhadrakali) is the main deity in this temple. Attukal Pongala is the main. Attukal Pongala Mahotsavam is a 10 days festival which falls on February-March every year .</h3></p>
    </body>
</html>
```


## OUTPUT
![alt text](<tvm/tvc/static/Screenshot 2024-03-25 180553.png>)
![alt text](<tvm/tvc/static/Screenshot 2024-03-25 180458.png>)
![alt text](<tvm/tvc/static/Screenshot 2024-03-25 180519.png>)
![alt text](<tvm/tvc/static/Screenshot 2024-03-25 180508.png>)
![alt text](<tvm/tvc/static/Screenshot 2024-03-25 180530.png>)
![alt text](<tvm/tvc/static/Screenshot 2024-03-25 180540.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
