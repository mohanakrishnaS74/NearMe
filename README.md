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
map.html
```
<html lang="en">
<head>
    <title>My City</title>
</head>
<body>
    <h1 allign="center">
        <font color="red"><b>Gingee</b></font>
    </h1>
    <h3 allign="'center">
        <font color="'blue"><b>Bhagyalalkshmi E (23016303)</b></font>
    </h3>
    <center>
        <img src="map.png" usemap="#MyCity" height="610" width="1450">
        <map name="MyCity">
            <area shape="circle" coords="'583,305,109" href="home.html" title="My Home Town">
            <area shape="circle" coords="'212,116,71" href="temple.html" title="Temple">
        </map>
    </center>
    
</body>
</html>
```
home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p>A home is a special place that provides us with safety, comfort, and a sense of belonging.
         It's more than just a structure made of bricks and beams; it is filled with memories, emotions, and warmth shared with loved ones. 
         My home, in a peaceful neighborhood, is the place where I can truly be myself without judgment, and where the daily stresses of the world seem to lessen because of the love and security found within its walls.
My house is a cozy, two-story building that is well-lit and airy due to its large windows. 
The exterior is a soft cream color with a lovely front garden where my mother grows various flowers and a few fruit trees. 
The interior is simply designed but comfortable, with a spacious living room where the family gathers to watch movies or chat, and a kitchen that is often filled with the delicious smells of home cooking. 
My favorite part, however, is the large terrace, where I enjoy spending my evenings reading books or simply lying down to count the stars on a clear night. It is the perfect haven, a sanctuary that nurtures my growth and preserves our family's shared experiences. I love my home more than any other place in the world because it is where my heart is, a safe place where I always feel loved and valued.</p>
</body>
</html>
```
template.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p>
        A temple is a sacred space designed to foster a connection between the human and the divine, serving as a center for spiritual activities, community gatherings, and the preservation of culture and tradition. 
        These architectural marvels are found across various religions and regions, each with unique styles but a common purpose of providing a sanctuary for peace and reflection.
    </p>
</body>
</html>
```

## OUTPUT
<img width="1038" height="488" alt="Screenshot 2025-12-28 162753" src="https://github.com/user-attachments/assets/07c0cdd2-8dfe-48c6-bd14-2505c4fcc198" />
<img width="1037" height="480" alt="Screenshot 2025-12-28 162805" src="https://github.com/user-attachments/assets/ebe7100e-9592-441b-8e89-e899cea054a6" />
<img width="1034" height="488" alt="Screenshot 2025-12-28 162822" src="https://github.com/user-attachments/assets/b2e272e4-6bb7-4697-8974-8fb2b6b900db" />







## RESULT
The program for implementing image maps using HTML is executed successfully.
