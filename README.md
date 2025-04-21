# Ex04 Places Around Me
# Date:21.04.2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html

<html>
    <head> 
        <title>My City</title> 
        </head> 
        <body> 
        <h1 align="center"> 
        <font color="red"><b>TIRUCHENGODE</b></font> 
        </h1> 
        <h3 align="center"> 
        <font color="blue"><b>V.SHRIYHA - 212224230267</b></font> 
        </h3> 
        <center> 
        <img src="Screenshot 2025-04-15 112809.png" usemap="#MyCity" height="610" width="1450"> 
        <map name="MyCity">  
            <area target="_blank" alt="ARTHANAREESHWARAR HILL TEMPLE" title=" ARTHANAREESHWARAR HILL TEMPLE " href="L1.html" coords="205,330,259,369" shape="rect">
            <area target="_blank" alt="HOTEL RADHA PRASAD" title="HOTEL RADHA PRASAD" href="L2.html" coords="505,225,545,255" shape="rect">
            <area target="_blank" alt="SANKARI FORT" title="SANKARI FORT" href="L3.html" coords="530,385,580,430" shape="rect">
            <area target="_blank" alt="MALAR ARASAN CINEMAS" title="MALAR ARASAN CINEMAS" href="L4.html" coords="505,465,535,485" shape="rect">
        </map>
        </center> 
        </body> 
</html>

```
```
L1.html

<html>
    <head>
        <title> ARTHANAREESHWARAR HILL TEMPLE</title>
    </head>
    <body bgcolor="white">
        <h1 align="center">
        <font color="black"><b> ARTHANAREESHWARAR HILL TEMPLE</b></font>
        </h1>
        <h3 align="center">
        <font color="maroon"><b> FAMOUS SHIVA TEMPLE</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        
            <center> <img src="Tiruchengode_sivan_hill_temple.jpeg" usemap="#image-map" width="50%" height="50%"></center>

        <font face="Century Schoolbook" size="5">
            <center>The Ardhanareeswarar Temple in Tiruchengode is a significant Shiva temple known for its unique deity, a single image of Shiva and Parvati combined in one form, representing the unity of masculine and feminine aspects. 
                It is located on a hill and is considered one of the oldest temples in the region, mentioned in the Tamil work Silapathikaram. The presiding deity is depicted as half-male and half-female, vertically to represent Shiva and Parvati worshipped as one form. 
                It is considered one of the oldest temples in this region. Tiruchegode is the olden Poondurainadu in Kongunadu.
            </center>
        </font>
        </p>
    </body>
</html>
```
```
L2.html

<html>
    <head>
        <title> HOTEL RADHA PRASAD</title>
    </head>
    <body bgcolor="white">
        <h1 align="center">
        <font color="black"><b> HOTEL RADHA PRASAD</b></font>
        </h1>
        <h3 align="center">
        <font color="maroon"><b>WORTH OF VISITING</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        
            <center> <img src="5696b1c8cdba11ebb10e0242ac110002.avif" usemap="#image-map" width="50%" height="50%"></center>

        <font face="Century Schoolbook" size="5">
            <center>We would like to introduce ourselves as the only three star cadre Hotel in Thiruchengode.
                Hotel Radha Prasad a symbol of luxury, quality service and comfort is situated in the prime location of Tiruchengode savored by blessings of Lord Arthanareeswarar.
                The place is renowned for its educational institutions and various industries. 
                The hotel offerswide range of exclusively designed suites, a perfect blend of southern services with best of western amenities that adds credentials to the standard of the hotel.
            </center>
        </font>
        </p>
    </body>
</html>
```
```
L3.html

<html>
    <head>
        <title> SANKARI FORT</title>
    </head>
    <body bgcolor="white">
        <h1 align="center">
        <font color="black"><b> SANKARI FORT</b></font>
        </h1>
        <h3 align="center">
        <font color="maroon"><b> OLDEST ANCIENT FORT</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        
            <center> <img src="download.jpeg" usemap="#image-map" width="50%" height="50%"></center>

        <font face="Century Schoolbook" size="5">
            <center>Sankagiri Fort is a historical fort maintained by the Archaeological Survey of India. 
                It is located 22 km from the city of Erode and 38 km from Salem. 
                Sankari or Sankagiri is the town located around this place. 
                The fort is 707 meters (2319.6 feet) high and covers an area of 558.58 acres.
                Sangagiri Fort was built in 15th century Vijayanagar empire. 
                It has 14 fort walls built on and around a hill and the last phase these walls were built by the British.
            </center>
        </font>
        </p>
    </body>
</html>
```
```
L4.html

<html>
    <head>
        <title> MALAR ARASAN CINEMAS</title>
    </head>
    <body bgcolor="white">
        <h1 align="center">
        <font color="black"><b> MALAR ARASAN CINEMAS</b></font>
        </h1>
        <h3 align="center">
        <font color="maroon"><b>MULTIPLEX THEATRE</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        
            <center> <img src="images.jpeg" usemap="#image-map" width="50%" height="50%"></center>

        <font face="Century Schoolbook" size="5">
            <center>3D movies, Live performances, Arcade games, Restaurant, Stadium seating, and Onsite services.
                Malar Arasan Theatre in Tiruchengode was renovated and reopened by Vettri Theatres on August 11, 2023. 
                The renovated theatre includes 4K RGB Laser and Dolby Atmos, and bookings are available on platforms like Paytm and TicketNew. 
                The theatre is open daily from 10:00 AM to 10:30 PM. 
            </center>
        </font>
        </p>
    </body>
</html>
```
# OUTPUT
![alt text](<Screenshot 2025-04-21 164236.png>)
![alt text](<Screenshot 2025-04-21 164253.png>)
![alt text](<Screenshot 2025-04-21 164307.png>)
![alt text](<Screenshot 2025-04-21 164321.png>)
![alt text](<Screenshot 2025-04-21 164335.png>)

# RESULT
The program for implementing image maps using HTML is executed successfully.
