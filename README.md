# Ex04 Places Around Me
## Date: 16/04/2024

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin:0;

        }
    </style>
</head>
    <script>
        function coordinate(event){
            let x = event.clientX;
            let y = event.clientY;
            document.getElementById("text1").value = x;
            document.getElementById("text2").value = y;
        }
    </script>
<body>
    <img src="Screenshot 2024-04-12 090033.png" width="1000" height="500"
    usemap="#MapNew" onmousemove="coordinate(event)">
    <map name="#MapNew">
        <area shape="rect" coords="414,157,448,183" href="www.saveetha.ac.in" alt="" title="Saveetha Engineering College">
        <area shape="rect" coords="517,154,550,183" href="www.simatsengineering.com" alt="" title="Saveetha School of Engineering College">
        <area shape="rect" coords="580,232,615,260" href="www.scop.in" alt="" title="Saveetha College Of Pharmacy">
        <area shape="rect" coords="555,315,589,337" href="www.smc.in" alt="" title="Saveetha Medical College">
        <area shape="rect" coords="0,276,317,20" href="www.scad.in" alt="" title="Saveetha College Of Architecture">
   
    </map>
    <br>
    <br>
    X-Coordinate:
    <X-Coordinate><input type="text" name="" id="text1"></X-Coordinate>
    <br><br>
    Y-Coordinate
    <Y-Coordinate><input type="text" id="text2"></Y-Coordinate>
</body>
</html>
```




## OUTPUT:

![Screenshot 2024-04-16 094242](https://github.com/Mohammed-Saajid/NearMe/assets/141727149/fd679986-b0c0-4393-bc33-a0d287e8f4a7)






## RESULT
The program for implementing image maps using HTML is executed successfully.
