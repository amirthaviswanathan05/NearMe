# Ex04 Places Around Me
## Date: 17.04.2024

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
<title>My city</title>
</head>
<body>
<h1 align="center">
<font color="blue"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="lightpink"><b>Amirtha Varshini V(212223040014)</b></font>
</h3>
<centre>
<h4 align="center">
<img src="vellore googlemap.png" usemap="MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="home.html title="MyHomeTown">
<area shape="circle" coords="570,230,45" herf="temple.html" title="Shri Murugam Temple">
<area shape="circle" coords="640,200,30" herf="college.html" title="VIT">
<area shape="circle" coords="1120,360,25" herf="fort.html" title="Vellore Fort">
<area shape="rect" coords="950,120,1100,140" herf="thetre.html" title="PVR cinemas">

</h4>
</map>
</centre>
</body>
</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Vellore - My home town</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Vellore (English: VAY-loor), also natively spelt as Velur,[note 1] is a sprawling city and the administrative headquarters 
of Vellore district in the Indian state of Tamil Nadu. It is located on the banks of the Palar River in the northeastern part of Tamil Nadu 
and is separated into four zones that are further subdivided into 60 wards, covering an area of 87.915 km2 and housing 
a population of 423,425 as reported by the 2001 census.
</font>
</p>
</body>
</html>

thetre.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="blue"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>PVR cinemas - Entertainment Centre</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Movie theater in Vellore, Tamil Nadu
Address: silk mill, 33/5,14th east cross road, Katpadi Main Rd, near Damro showroom, Gandhi Nagar, Vellore, Tamil Nadu 632006
</font>
</p>
</body>
</html>

fort.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="blue"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Vellore Fort - Tourist Spot</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Vellore Fort is a large 16th-century fort situated in heart of the Vellore city, 
in the state of Tamil Nadu, India built by the Emperors of Vijayanagara. 
The fort was at one time the imperial capital of the Aravidu Dynasty of the Vijayanagara Empire.
</font>
</p>
</body>
</html>

college.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="grey">
<h1 align="center">
<font color="black"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="black"><b>VIT - Educational University</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Vellore Institute of Technology is a private deemed university located 
in Katpadi in Vellore, Tamil Nadu, India. The institution offers 66 Undergraduate, 
58 Postgraduate, 15 Integrated, 2 Research and 2 M.Tech Industrial Programmes
</font>
</p>
</body>
</html>

temple.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lightgreen">
<h1 align="center">
<font color="blue"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Shri Murugan Temple - Devotional Centre</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Vellore Arulmigu Ratnagiri murugan temple is a temple dedicated to the god Murugan, 
in Thirumanikundram, Vellore, India. It was constructed around the 14th century, 
and was mentioned by the 14th century poet Arunagirinathar.
</font>
</p>
</body>
</html>
```


## OUTPUT

![WhatsApp Image 2024-04-17 at 21 47 56_1ef113b5](https://github.com/amirthaviswanathan05/NearMe/assets/149035397/9f42ce6c-04d9-4051-8b11-4d6e0360edba)

![WhatsApp Image 2024-04-17 at 21 41 15_7cd8eba1](https://github.com/amirthaviswanathan05/NearMe/assets/149035397/18ab25ba-a709-4955-9e56-46cea8512b57)

![WhatsApp Image 2024-04-17 at 21 41 15_8b242679](https://github.com/amirthaviswanathan05/NearMe/assets/149035397/e9b5a463-a896-4140-8269-8361523e5209)

![WhatsApp Image 2024-04-17 at 21 41 13_c8f8492f](https://github.com/amirthaviswanathan05/NearMe/assets/149035397/5e2f24b1-af12-4ac6-85ea-5942952428eb)

![WhatsApp Image 2024-04-17 at 21 41 12_09e621a0](https://github.com/amirthaviswanathan05/NearMe/assets/149035397/63d164a3-fbbe-4ada-b1b2-eb7b88ca8c87)


## RESULT
The program for implementing image maps using HTML is executed successfully.
