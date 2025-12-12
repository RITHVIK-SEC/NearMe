# Ex04 Places Around Me
## Date: 8-12.2025
## NAME:RITHVIK S
## REF NO. : 25007067

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
~~~

map.html
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>CHENNAI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>RITHVIK.S (25007067)</b></font>
</h3>static
<img src="abc.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="" title="" href="railway station.html" coords="725,400,815,494" shape="rect">
    <area target="" alt="" title="" href="beach.html" coords="1033,745,37" shape="circle">
    <area target="" alt="" title="" href="port.html" coords="1243,81,1178,79,1246,81,1247,116,1212,144,1178,123,1177,82,1219,59,1243,81" shape="poly">
    <area target="" alt="" title="" href="museum.html" coords="1045,324,1195,406" shape="rect">
    <area target="" alt="" title="" href="home.html" coords="886,337,85" shape="circle">
</map>
</body>
</html>

home.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>CHENNAI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>CHENNAI - my home town</b></font>
</h3>
<p align="justify">
<font size="3" color="red">
</font>
<font face="Georgia" size="5">
Chennai, India's capital of Tamil Nadu, is a major South Indian hub for culture, 
economy, and education, known for its strong automobile industry
(dubbed the "Detroit of India"), vibrant IT sector, rich traditions in music  (Carnatic) and dance (Bharatanatyam), historic temples, and famous landmarks like 
Marina Beach. Formerly Madras, it's one of India's oldest cities, home to India's first 
city corporation (after London) and a significant cultural center for the Tamil film 
industry (Kollywood)
</p>
</body>
</html>

beach.html

<html>
<head>
<title>BEACH</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>CHENNAI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>CHENNAI - beach</b></font>
</h3>
<p align="justify">
<font size="3" color="red">
</font>
<font face="Georgia" size="5">
Marina Beach, or simply the Marina, is a natural urban beach in Chennai, Tamil Nadu,
India, along the Bay of Bengal. The beach runs from near Fort St. George in the north
to Foreshore Estate in the south, a distance of 6.0 km (3.7 mi),[1] making it the second 
longest urban beach in the world, after Cox's Bazar Beach.[citation needed][2][3][4]
It is a prominent landmark in Chennai.    
</p>
</body>
</html>

museum.html

<html>
<head>
<title>MUSEUM</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>CHENNAI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>CHENNAI - museum</b></font>
</h3>
<p align="justify">
<font size="3" color="red">
</font>
<font face="Georgia" size="5">
Fort St. George (or historically, White Town)[1] is a fortress at the coastal city of Chennai,
India. Founded in 1639, it was the first English (later British) fortress in India.[2] The
construction of the fort provided the impetus for further settlements and trading activity,
in what was originally an uninhabited land.[3] Thus, it is a feasible contention to say that
the city (named Madras since before the arrival of the Europeans until July 1996) evolved 
around the fortress.[4] The fort currently houses the Tamil Nadu legislative assembly and 
other official buildings.

</p>
</body>
</html>

port.html

<html>
<head>
<title>PORT</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>CHENNAI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>CHENNAI - harbour</b></font>
</h3>
<p align="justify">
<font size="3" color="red">
</font>
<font face="Georgia" size="5">
Chennai Port, formerly Madras Port, is India's third oldest and largest artificial port on the
East Coast, a major hub for containers, cars, and general cargo, serving as a vital gateway
for South India with facilities including cruise terminals and strong rail links, managing
diverse cargo like petroleum, fertilizers, and automobiles
</p>
</body>
</html>

railway station.html

<html>
<head>
<title>RAILWAY STATION</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>CHENNAI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>CHENNAI - railway station</b></font>
</h3>
<p align="justify">
<font size="3" color="red">
</font>
<font face="Georgia" size="5">
Chennai Egmore (formerly: Madras Egmore, also known as Chennai Elumbur)(station code: MS[1]),
is an NSG–1 category Indian railway station in Chennai railway division of Southern Railway
zone.[2] Situated in the neighbourhood of Egmore, it is one of the four intercity railway
terminals in the city; the other three are Dr. M.G.R. Chennai Central, Tambaram railway station
and Chennai Beach railway station. The station was built in 1906–1908 as the terminus of the
South Indian Railway Company
</p>
</body>
</html>

~~~

## OUTPUT
![alt text](<Screenshot 2025-12-11 112606.png>)
![alt text](<Screenshot 2025-12-11 112740.png>)
![alt text](<Screenshot 2025-12-11 112838.png>)
![alt text](<Screenshot 2025-12-11 112929.png>)
![alt text](<Screenshot 2025-12-11 113027.png>)
![alt text](<Screenshot 2025-12-11 113115.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
