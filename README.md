# Ex04 Places Around Me
## Date:22.10.2024

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

Developed by :RAMKUMAR.S
Register Number :212223220085
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            background-color: aqua;
        }
        
    </style>
</head>
<body>
    <img src="d2.png" alt="" height = "530" usemap = "#MapNew" onmousemove = "coordinate(event)">
    <map name="MapNew">
        <area shape="RECT" coords="234,189,267,244" href="https://www.booking.com/hotel/in/hyatt-regency-chennai.html" alt="hyatt">
        <area shape="RECT" coords="366,311,389,280" href="https://www.kauveryhospital.com/" alt="kauvery hospital">
        <area shape="rect" coords="223,231,267,340" href="https://www.kunmotorrad.in/" alt="bmw">
        <area shape="rect" coords="50,240,76,250" href="https://www.booking.com/hotel/in/grt-grand-chennai-chennai.html" alt="grt">
        <area shape="rect" coords="197,468,220,498" href="https://www.agscinemas.com/" alt="ags">
    </map><br>
    
    
   
</body>
</html>
```

## OUTPUT

![Screenshot 2024-04-16 225804](https://github.com/gowshik145/NearMe/assets/155086127/c99928af-9c0d-4516-ae02-07e6662520f9)
![Screenshot 2024-04-16 230010](https://github.com/gowshik145/NearMe/assets/155086127/3996a70c-5496-43be-8fe8-4ba486c84687)
![Screenshot 2024-04-16 230119](https://github.com/gowshik145/NearMe/assets/155086127/a36d43fa-580f-4157-a3f4-c39bc4a85b52)
![Screenshot 2024-04-16 230220](https://github.com/gowshik145/NearMe/assets/155086127/a7d7ad3f-1083-44e4-8066-fa08bf9edeb0)
![Screenshot 2024-04-16 231253](https://github.com/gowshik145/NearMe/assets/155086127/8be72dbf-6fcd-458f-b52a-e3a29d1f7e4c)
![Screenshot 2024-04-16 230952](https://github.com/gowshik145/NearMe/assets/155086127/38c8a9ac-0563-466e-b8d2-751c5c7891b5)









## RESULT
The program for implementing image maps using HTML is executed successfully.
