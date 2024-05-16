[# Ex04 Places Around Me

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
<font color="green"><b>TUTICORIN</b><font>
</h1>
<h2 align="center">
<font color="red"><b> VARSHA A(212223220121)</b><font>
</h2>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="home.html" title="My Home Town">
<area shape="circle" coords="570,230,45" href="temple.html" title="Rajapandi Nagar kovil">
<area shape="circle" coords="640,200,30" href="beach.html" title="Muthu Nagar Beach">
<area shape="circle" coords="1120,360,25" href="park.html" title="Eco park">
<area shape="circle" coords="950,120,1100,140" href="bridge.html" title="GOLDEN WEIGH BRIDGE">
</map>
</center>
</body>
</html>


home.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>TUTICORIN</b><font>
</h1>
<h2 align="center">
<font color="blue"><b> Tuticorin - My Home Town</b><font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5" color="green">
Thoothukudi is traditionally known for pearl fishing and shipping activities, production of salt and other related business. This is a port city in the southern region of Tamilnadu. This is a natural port, from this place freedom fighter V.O. Chidambaranar operated the Swadeshi shipping company during the British rule.</font>
</p>
</body>
</html>


beach.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="purple"><b>TUTICORIN</b></font>
</h1>
<h2 align="center">
<font color="violet"><b> Muthu Nagar Beach - A beach love paradise</b><font>
</h2>
<hr size="3" color="purple">
<p align="justify">
<font face="Georgia" size="5" color="brown">
Muthu Nagar Beach gels seamlessly with the landscape of the locale. Situated 5 km south of the town, the refurbished beach park attracts great tourist interest. It is an ideal location for families to spend quality time together. There is a skating rink, a basketball court and a volleyball court in this park. The beach itself is adorned with tents so that the people who come to visit are safe from extreme sunlight and rain. The park also hosts an artificial fountain and a gallery for visitors to enjoy. The beach access ramp is designed to be helpful for differently abled people. The walls of the park are covered with amazing paintings. </font>
</p>
</body>
</html>


bridge.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="sky blue">
<h1 align="center">
<font color="blue"><b>TUTICORIN</b></font>
</h1>
<h2 align="center">
<font color="orange"><b> GOLDEN WEIGH BRIDGE</b><font>
</h2>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="5" color="yellow">
Golden Weigh Bridge is a reputable in Tuticorin Harbour, Thoothukudi that provides a reliable, accurate, and secure method of weighing bulk materials.
Golden Weigh Bridge in Tuticorin, Thoothukudi is known to satisfactorily cater to the demands of its customer base. The business came into existence in 2011 and has, since then, been a known name in its field. It stands located at Bye Pass Road, Tuticorin HO-628001.The business strives to make for a positive experience through its offerings.
</p>
</body>
</html>


temple.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="green"><b>TUTICORIN</b></font>
</h1>
<h2 align="center">
<font color="red"><b> Rajapandi Nagar kovil - Devotional Centre</b><font>
</h2>
<hr size="3" color="green">
<p align="justify">
<font face="Georgia" size="5" color="blue">
Rajapandi Nagar is a small Village/hamlet in Thoothukkudi Block in Tuticorin District of Tamil Nadu State, India. It comes under Korampallam Panchayath. It is located 7 KM towards west from District head quarters Thoothukudi. 5 KM from Thoothukudi Rural. 621 KM from State capital Chennai. It is one of the few temples in India which has various forms and avatars of both Lord Vishnu and Lord Shiva together.</font>
</p>
</body>
</html>


park.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="gray">
<h1 align="center">
<font color="blue"><b>TUTICORIN</b></font>
</h1>
<h2 align="center">
<font color="orange"><b>Eco park - Environmental friendly</b><font>
</h2>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="5" color="yellow">
Eco park is one of the prime attraction in thoothukudi. Eco park is situated in nearly one kilometer away from Roche park on south beach road. In the long years thoothukudi Eco park had faced several setbacks, was finally launched in 10, December 2018. Eco park inaugurated by thoothukudi collector Mr. Sandeep Nanduri, I.A.S and Tamil Nadu information and publicity minister Kadambur Mr. C. Raju, M.L.A. Eco park was constructed at a cost of Rs. 1.39 crore. The V.O.C port trust contributed Rs. 79 lacks
and thoothukudi corporation gives Rs. 60 lacks. Nowadays ECO Park is one of the famous tourism spot in thoothukudi. It very attracts thoothukudi peoples and children.</font>
</p>
</body>
</html>

~~~

## OUTPUT

![Ex 3 beach](https://github.com/04Varsha/NearMe/assets/149035374/059f020e-4a77-4d4a-b82b-d3a1ac51222d)

![Ex 3 Bridge](https://github.com/04Varsha/NearMe/assets/149035374/cf3b0ec1-d91c-4030-b959-15319ef85440)

![Ex 3 temple](https://github.com/04Varsha/NearMe/assets/149035374/8337f465-7897-4906-a49f-79a4f54b6c3d)

![Ex 3 park](https://github.com/04Varsha/NearMe/assets/149035374/01609f32-bfa9-4658-a2eb-4de14b6e6809)


## RESULT
The program for implementing image maps using HTML is executed successfully.
](https://github.com/swethasurendar/ORM/blob/main/README.md)
