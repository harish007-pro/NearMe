# Ex04 Places Around Me
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
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="Royal Blue"><b>P A L L A V A R A M </b></font>
</h1>
<h2 align="center">
<font color="Midnight"><b>RAJAGOPAL 23002920</b></font>
</h2>
<center>
<img src="map.png" usemap="#MyCity" heigth="650" width="1450">
<map name="MyCity">
<area shape="rect" coords="950,100,650,300" href="home.html" title="My Home Town">
<area shape="circle" coords="450,250,65" href="temple.html" title="Temple">
<area shape="circle" coords="1150,50,65" href="airport.html" title="Airport">
<area shape="circle" coords="1100,350,65" href="college.html" title="College">
<area shape="circle" coords="900,500,50+/*" href="chromepet.html" title="Chromepet">
</map>
</center>
</body>
<html>


airport.html

<html>
<head>
<title> Airport </title>
</head>
<body bgcolor="ICE BLUE">
<h1 align="center">
<font color="night teal"><b>My Home Town</b></font>
</h1>
<h1 align="center">
<font color="teal"><b>Chennai airport </b> </font>
</h1>
<hr size ="3" color="red">
<p align="justify">
<font face="comic Sans MS" size="5">
chennai International Airport (IATA: MAA, ICAO: VOMM) is an international airport serving the city of Chennai, the capital of Tamil Nadu, India and its metropolitan area. It is located in Tirusulam, around 20 km (12 mi) southwest of the city centre. The airport is the 5th busiest airport in India, and 3rd by international traffic. It was also 49th busiest airport in Asia in 2018 making it one of the four major airports in India under the top 50 list of 2018. In financial year 2022-23, the airport handled over 18 million passengers.
The airport is served by the airport metro station of the Chennai Metro and the Tirusulam railway station of the Chennai Suburban Railway system. To cope with the passenger traffic, two new terminals, including one satellite terminal, are under construction to handle 40 million passengers per year. Once completed, it will be India's first airport to have a satellite terminal. The new satellite terminal will be connected through a four way underground walkalator for passenger movement across different terminals.Still, the Tirusulam airport complex is expected to reach saturation by 2035, with a peak capacity of 40 million passengers, and a proposal for a new greenfield airport in Parandur has been approved. Once the new airport is commissioned, both airports will be functional.
The older domestic and international blocks 2 and 3 were named after former Chief Ministers of Tamil Nadu K. Kamaraj and C. N. Annadurai, respectively. It was the first airport in India to have international and domestic terminals located adjacent to each other. It was designed by Creative Group, an India-based architecture firm. The airport serves as the southern regional headquarters of the Airports Authority of India (AAI) for South India comprising the states of Tamil Nadu, Andhra Pradesh, Kerala, and the union territories of Puducherry and Lakshadweep. In total, the airport consists of four terminals (Terminals 1-4), where Terminals 1 and 4 are used for domestic arrivals and departures and Terminal 2 for international arrivals and departures. The older Terminal 3 on Terminal 2's western side will be demolished to extend Terminal 2.
</p>
</body>
</html>


chromepet.html

<html>
<head>
<title> near area </title>
</head>
<body bgcolor="ice blue">
<h1 align="center">
<font color="night shade"><b>My Home Town</b></font>
</h1>
<h1 align="center">
<font color="teal"><b>Chromepet</b> </font>
</h1>
<hr size ="3" color="red">
<p align="justify">
<font face="comic Sans MS" size="5">
Chromepet is a neighbourhood of Tambaram located in the Chennai Metropolitan Area, around 22 km from the Chennai Central Railway Station and 4 km south of the Chennai International Airport on the Grand Southern Trunk (GST road). Formerly a part of Pallavaram Municipality,it is now governed by the Tambaram City Municipal Corporation.Neighbouring areas include Thirumudivakkam, Tambaram, and Pallavaram. The 200-feet road connects Chromepet with Thoraipakkam.
The neighbourhood is home to the Madras Institute of Technology, whose alumni include former president of India A. P. J. Abdul Kalam and Tamil writer Sujatha. The neighbourhood is served by the Chromepet railway station of the Chennai Suburban Railway Network and is a residential locality. Chromepet votes for the Sriperumbudur parliamentary constituency in the Indian national elections.

</p>
</body>
</html>


college.html

<html>
<head>
<title> college </title>
</head>
<body bgcolor="ice blue">
<h1 align="center">
<font color="Night shade"><b>My Home Town</b></font>
</h1>
<h1 align="center">
<font color="teal"><b>Vels university </b> </font>
</h1>
<hr size ="3" color="red">
<p align="justify">
<font face="comic Sans MS" size="5">
Vels Institute of Science, Technology & Advanced Studies (VISTAS) is an institute of higher education located in Pallavaram, Chennai, Tamil Nadu, India. It was established in 1992 and granted Deemed University status in 2008 by University Grants Commission under section 3 of UGC Act 1956.Vels Institute of Science, Technology & Advanced Studies was ranked 43 in India by the National Institutional Ranking Framework (NIRF) pharmacy ranking in 2020.

<h2>Campus:</h2>

Campus is located in the heart of the city in Pallavaram with about 29.13 acres. It is the only university campus which has its main campus within the city.

</p>
</body>
</html>

home.html

<html>
<head>
<title> Pallavaram </title>
</head>
<body bgcolor="ICE BLUE">
<h1 align="center">
<font color="night shade"><b>My Home Town </b></font>
</h1>
<h1 align="center">
<font color="teal"><b>Pallavaram </b> </font>
</h1>
<hr size ="3" color="red">
<p align="justify">
<font face="comic Sans MS" size="5">
Pallavaram (originally Pallava Puram) is a neighborhood in the city of Tambaram, situated within the Chennai Metropolitan Area, Tamil Nadu, India.Pallavaram is considered to be one of the oldest inhabited places in South India. A major archaeological find was made in the year 1863 when the British archaeologist Robert Bruce Foote discovered a stone implement from the Paleolithic Age inside a ballast pit. Since then, a number of Stone Age artifacts have been uncovered. Most of these artifacts are currently lodged in the Egmore museum.
</p>
</body>
</html>


temple.html

<html>
<head>
<title> temple </title>
</head>
<body bgcolor="Ice Blue">
<h1 align="center">
<font color="Night shade"><b>My Home Town</b></font>
</h1>
<h1 align="center">
<font color="teal"><b>Thiruneermalai temple
</b> </font>
</h1>
<hr size ="3" color="red">
<p align="justify">
<font face="comic Sans MS" size="5">
The Thiruneermalai temple complex consists of two temples, the Ranganatha Temple and the Thiruneermalai Neervanna Perumal Temple. Both are Hindu temples in Thiruneermalai, a populated place in Kovur, a town in Chengalpattu district, Tamil Nadu, India.There are two temples, one at the top of the hill and other in the foothills. In all, the temple occupies an area of 15 acres (6.1 ha), with the lower shrine covering 3 acres (1.2 ha). The presiding deity of the temple in the foothills is Neervana Perumal in standing posture. Ranganatha is the presiding deity uphill and the shrine, vimana above the sanctum is called Ranga Vimana. There are images of Trivikrama and Narasimha around the first precinct. The temple tank is called the Kshira Pushkarini and it is believed to feed the waters of Vaikuntha, and the Ocean of Milk. The Karunya Pushkarini is the second tank, which is believed to have formed from the weeping of Narasimha, who was moved by the divine prayers of Prahlada. There are two other tanks called Svarna Pushkarini and Siddha Pushkarini.

</p>
</body>
</html>







```


## OUTPUT
![image](https://github.com/user-attachments/assets/d5202c34-06f6-4305-b8e2-fb2358da3dc1)
![image](https://github.com/user-attachments/assets/9ee68cba-415e-413f-8fe4-c3405be83863)
![image](https://github.com/user-attachments/assets/6f87f864-f9c2-4a0b-b947-5c2fe7289ca9)
![image](https://github.com/user-attachments/assets/fda81f74-6503-4645-880c-01855c171849)
![image](https://github.com/user-attachments/assets/cdf2f8b4-2ed5-4e8e-b998-41d9b984bbcb)
![image](https://github.com/user-attachments/assets/a45a0cb9-8d37-4e07-81a3-7ba922b1ffa5)


## RESULT
The program for implementing image maps using HTML is executed successfully.
