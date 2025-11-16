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
```
map.html

<!doctype html>
<html>
  <head>
    <title>MY CITY</title>
  </head>
  <body>
    <h1 align="center">
      <font color="red"><b>HOSUR</b></font>
    </h1>

    <h3 align="center">
      <font color="blue"><b>SUBIKSHA K (212224040332)</b></font>
    </h3>

    <center>
      <!-- map.png displayed at 1050x610 (must remain this size for coords to match) -->
      <img src="map.png" usemap="#MYCITY" height="610" width="1050" alt="Hosur map">

      <map name="MYCITY">
        <area shape="rect" coords="470,290,520,335" href="home.html" title="MY HOME TOWN">
        <area shape="circle" coords="237,159,32" href="sipcot.html" title="SIPCOT">
        <area shape="circle" coords="380,257,34" href="hotel.html" title="HOTEL HILLS">
        <area shape="circle" coords="599,237,34" href="temple1.html" title="SRI SUYAMBU TEMPLE">
        <area shape="circle" coords="757,354,36" href="temple2.html" title="MAA PRATYANGIRA KALIKA ALAYAM">
      </map>
    </center>
  </body>
</html>

home.html

<html>
    <head>
        <title> My home town </title>
    </head>
    <body bgcolor="grey">
        <h1 align="center">
            <font color="white"><b>HOSUR</b></font>
        </h1>
        <h3 align="center">
            <font color="white"><b>HOTEL HILLS</b></font>
        </h3>
        <hr size="3" color="black">
        <p align="justify">
            <font face="georgia" size="5" color="white">
               Hotel Hills in Hosur is a modern, 3-star business hotel known for its spacious, clean rooms and a range of amenities designed for both business and leisure travelers. Located near the Bangalore-Chennai highway in the SIPCOT industrial complex, it offers a convenient and quiet place to stay.
               75 well-appointed rooms, including Superior and Executive King/Twin options and Junior Suites, all featuring modern design, rain showers, and amenities like flat-screen TVs and mini-bars.
               An on-site restaurant (Copper Bowl) and a coffee shop offering a variety of cuisines, including Indian, Chinese, and Western dishes, with buffet options available for breakfast, lunch, and dinner.
               An outdoor swimming pool, a well-equipped 24-hour fitness center, a large convention center with multiple event spaces, and a garden area.
               24-hour front desk, room service, free Wi-Fi, laundry service, shuttle service, and ample on-site parking including valet options.
               Guests often describe the hotel as having a posh feeling with a modern yet cozy ambiance and helpful, friendly staff.


            </font>

        </p>
        </body>
</html>

hotel.html

<html>
    <head>
        <title> My home town </title>
    </head>
    <body bgcolor="grey">
        <h1 align="center">
            <font color="white"><b>HOSUR</b></font>
        </h1>
        <h3 align="center">
            <font color="white"><b>HOTEL HILLS</b></font>
        </h3>
        <hr size="3" color="black">
        <p align="justify">
            <font face="georgia" size="5" color="white">
               Hotel Hills in Hosur is a modern, 3-star business hotel known for its spacious, clean rooms and a range of amenities designed for both business and leisure travelers. Located near the Bangalore-Chennai highway in the SIPCOT industrial complex, it offers a convenient and quiet place to stay.
               75 well-appointed rooms, including Superior and Executive King/Twin options and Junior Suites, all featuring modern design, rain showers, and amenities like flat-screen TVs and mini-bars.
               An on-site restaurant (Copper Bowl) and a coffee shop offering a variety of cuisines, including Indian, Chinese, and Western dishes, with buffet options available for breakfast, lunch, and dinner.
               An outdoor swimming pool, a well-equipped 24-hour fitness center, a large convention center with multiple event spaces, and a garden area.
               24-hour front desk, room service, free Wi-Fi, laundry service, shuttle service, and ample on-site parking including valet options.
               Guests often describe the hotel as having a posh feeling with a modern yet cozy ambiance and helpful, friendly staff.


            </font>

        </p>
        </body>
</html>

temple1.html

<html>
    <head>
        <title> My home town </title>
    </head>
    <body bgcolor="lavender">
        <h1 align="center">
            <font color="purple"><b>HOSUR</b></font>
        </h1>
        <h3 align="center">
            <font color="purple"><b>SRI SUYAMBU TEMPLE</b></font>
        </h3>
        <hr size="3" color="purple">
        <p align="justify">
            <font face="georgia" size="5" color="pink">
               Hosur is home to several temples with "Suyambu" (self-manifested) deities, including the Sri Suyambu Kottai Mariyamman Temple, the Hosur Sri Suyambu 18m Padi Karuppasamy Temple, and the Suyambu Arthanareeswarar Kugai Kovil.
               This is an ancient and highly regarded temple in Hosur dedicated to the powerful Goddess Mariyamman.
               The deity is considered very powerful, and devotees believe that prayers offered here are always answered. Many people visit the temple regularly and report a strong sense of peace and positive energy.
               The temple is known for its positive and divine vibrations. It attracts heavy crowds during festivals and on Tuesdays and Fridays.
               It is located in Ram Nagar, SBM Colony, Anthivadi, Hosur.

            </font>
        </p>
        </body>
</html>

temple2.html

<html>
    <head>
        <title> My home town </title>
    </head>
    <body bgcolor="turquoise">
        <h1 align="center">
            <font color="white"><b>HOSUR</b></font>
        </h1>
        <h3 align="center">
            <font color="white"><b>MAA PRATYANGIRA KALIKA ALAYAM</b></font>
        </h3>
        <hr size="3" color="green">
        <p align="justify">
            <font face="georgia" size="5" color="white">
               The Maa Pratyangira Kalika temple in Hosur is a spiritual site dedicated to the Goddess Pratyangira Devi, known for its powerful energy and intricate architecture.
               It features the world's largest statue of Pratyangira Devi on its main gopuram and is based on Shakti and Tantric traditions.
               The temple is believed to offer protection against negative energies and evil spirits, and devotees often leave offerings of chilies and lemons for this purpose.
               The main deity is Maa Pratyangira Devi, and the temple also houses other deities like Sarabeshwara and Lord Narimha.
               The temple is known for its potent spiritual energy and is visited by people seeking to ward off negative energies, the evil eye, or mental health issues.
               The temple showcases intricate architectural and artistic work.


            </font>
        </p>
        </body>
</html>

sipcot.html

<html>
    <head>
        <title> My home town </title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="white"><b>HOSUR</b></font>
        </h1>
        <h3 align="center">
            <font color="white"><b>SIPCOT</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="georgia" size="5" color="white">
                The SIPCOT Industrial Park in Hosur is a major industrial hub developed by the State Industries Promotion Corporation of Tamil Nadu (SIPCOT) to promote large and medium scale industries in the region.
                It is strategically located near the Tamil Nadu-Karnataka border, approximately 40 km from Bangalore, offering excellent connectivity via National Highway 44 (NH-44).
                The park hosts a wide range of industries, including manufacturing, engineering, automotive, pharmaceuticals, watches and jewellery, and export-oriented units.
                Prominent companies operating within or near the SIPCOT complex include TVS Motors, Ashok Leyland, Titan Company, Caterpillar, and Tenneco Automotive.
                SIPCOT provides essential infrastructure, such as roads, water supply (including a new Tertiary Treatment and Reverse Osmosis (TTRO) plant), and power. 
                It also features a dedicated SIPCOT Industrial Innovation Centre (SIIC) to foster technology-driven startups and R&D activities.

            </font>
        </p>
        </body>
</html>

```
## OUTPUT
![alt text](<bakkiya/Screenshot 2025-11-16 204011.png>)
![alt text](<bakkiya/Screenshot 2025-11-16 210516.png>)
![alt text](<bakkiya/Screenshot 2025-11-16 210603.png>)
![alt text](<bakkiya/Screenshot 2025-11-16 210611.png>)
![alt text](<bakkiya/Screenshot 2025-11-16 210619.png>)
![alt text](<bakkiya/Screenshot 2025-11-16 210627.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
