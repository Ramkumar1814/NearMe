# Ex04 Places Around Me
## Date: 10-10-2024

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
        <title>MY CITY</title>
    </head>
    <body bgcolor="lilblue">
        <h1 align="center">
            <font color="black"><b>CHIDAMBARAM</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>B.NIHITHA RANI (212223040131)</b></font>
        </h3>
        <center>
            <img src="cd.png" usemap="#MYCITY" height="910" width="1800">
            <map name="MYCITY">
                <area shape="rect" coords="820,495,960,470" href="hotel.html" title="AKSHAYA HOTEL">
                <area shape="circle" coords="1100,630,21" href="resort.html" title="KRISH GARDEN FARM RESORTS">
                <area shape="circle" coords="1250,619,21" href="university.html" title="ANNAMALAI UNIVERSITY">
                <area shape="rect" coords="800,480,850,460" href="mobiles.html" title="POORVIKA MOBILES">
                <area shape="rect" coords="820,150,825,155" href="mahal.html" title="SRI KRISHNA GRAND MAHAL">
            </map>
        </center>
        <title align="center">CHIDAMBARAM</title> 
        <title align="center">B.NIHITHA RANI (212223040131)</title>
    </body>
</html> 


hotel.html
<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="violet">
        <h1 align="center">
            <font color="lilblue">AKSHAYA HOTEL</font>
        </h1>
        <hr size="3" color="pink">
        <p align="justify">
            <font face="Georgia" size="5">
                This hotel is the most famous vegetarian hotel in CHIDAMBARAM.
                The hotel is large and spacious.
                It has a varieties of food.
                The food tastes so good and yummy.
            </font>
        </p>
    </body>
</html>

resort.html
<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="violet">KRISH GARDEN FARM RESORTS</font>
        </h1>
        <hr size="3" color="pink">
        <p align="justify">
            <font face="Georgia" size="5">
                This resort is the most famous in CHIDAMBARAM.
                It has a very spacious arrangement of rooms.
                The service is so good.
            </font>
        </p>
    </body>
</html>

mahal.html
<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="lilblue">
        <h1 align="center">
            <font color="white">SRI KRISHNA GRAND MAHAL</font>
        </h1>
        <hr size="3" color="pink">
        <p align="justify">
            <font face="Georgia" size="5">
                A very good mahal for marriage arrangements.
                There we can have birthday parties,engagement,and so on.
                Quite decent and huge mahal.
            </font>
        </p>
    </body>
</html>


university.html
<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
            <font color="red">ANNAMALAI UNIVERSITY</font>
        </h1>
        <hr size="3" color="pink">
        <p align="justify">
            <font face="Georgia" size="5">
                It is one of the oldest universities.
                It is famous for agriculture and medical.
                It is well known for its distinct education facility.
            </font>
        </p>
    </body>
</html>


mobiles.html
<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="red">
        <h1 align="center">
            <font color="yellow">POORVIKA MOBILES</font>
        </h1>
        <hr size="3" color="pink">
        <p align="justify">
            <font face="Georgia" size="5">
                The biggest showroom for mobiles in CHIDAMBARAM.
                Located near bus stand.
                There are many offers going on it.
            </font>
        </p>
    </body>
</html>


```

## OUTPUT
![alt text](map.png)
![alt text](akshayahotel.png)
![alt text](resorts.png)
![alt text](mahal.png)
![alt text](annamalai.png)
![alt text](poorvikamobiles.png)

## RESULT
The program for implementing image maps using HTML is executed successfully.
