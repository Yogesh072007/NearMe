# Ex04 Places Around Me
## Date:29\10\2025

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
## Imagemap.html:
```python
<html>
    <head>
        <title> Imagemap</title>
        <style>
            h1,h2{
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            }
            .center{
                  text-align: center;
            }
        </style>
    </head>
    <body>
        <div style="text-align: center;">
        <h1> Explore My Neighbourhood</h1>
        <h2> Please click any of the pictures in the middle to know more about it</h2>
        
        <map>
            <div style="text-align: center;">
           
            <img src="mapp.png"  usemap="#Mapnew" class="center" >
            </div>
            <Map name="Mapnew">
                <area shape="rect" coords="575,306,756,381" href="garden.html">
                <area shape="rect" coords="205,328,448,425" href="n4 beach.html">
                <area shape="rect" coords="89,661,254,738" href="railway.html">
                <area shape="rect" coords="535,680,713,758" href="museum.html">
        </map>
    </div>
   
    </body>
</html>
```
## Garden.html:
```python
<html>
   <head>
       <title> Botanical garden</title>
       
   </head>
   <body>
       <h1 style="text-align: center;"> Madhavaram Botanical park</h1>
       <h2 style="text-align: center;"><a href="https://maps.app.goo.gl/xA4YgPFntDKrL1VK7" title="Botanical park"> Click here for Directions</a></h2>
       <div style="text-align: center;">
       <img src="Garden.png" width="30%" height="30%" >
       <h2> Madhavaram Botanical Garden is the largest botanical garden in the city. The garden also has a small bridge has been built to attract birds from where visitors will get a view of the lake. The garden will have nearly 400 species of plants including about 200 ornamental plants. </h2>
   
      </div>
      
   </body>
</html>
```
## museum.html:
```python
<html>
    <head>
        <title> rail Museum</title>
        <style>
            h1,h2,h3{
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            }
        </style>
    </head>
    <body>
        <h1 style="text-align: center;"> Chennai Rail Museum</h1>
        <h2 style="text-align: center;"> <a href="https://maps.app.goo.gl/RypGvDXRX2XdL6Kp6" title="Rail museum"> Click here for Directions</a></h2>
        
        <div style="text-align: center;">
        <img src="museum.png" width="30%" height="30%">
    </div>
        <h2> The 6.5-acre (2.6 ha) museum has two galleries, a number of 19th-century outdoor heritage exhibits, a toy train that takes visitors around the perimeter, and a playground. Its collection includes indoor and outdoor exhibits. The indoor galleries contain photographs detailing the early years of the ICF and Indian Railways. The museum also houses working scale models of trains, and rare colonial-period artifacts. This will be the location of new exhibits for the museum's second decade</h2>
        <h2>The museum's outdoor exhibits include 41 train models. An 1895 model of a Fowler steam ploughing engine (manufactured by John Fowler) and 1860s double-deck coaches are on display. Models include Coach of Inspection car RA 30 (manufactured by Metropolitan Carriage and Finance), Crane Hercules (used for emergency relief) and luxury coaches</h2>
    </body>
    </html>
```
## n4 beach.html:
```python
    <html>
   <head>
       <title> N4- Beach</title>
       <style>
           h1,h2,div{
               font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
           }
       </style>
   </head>
   <body>
       <h1 style="text-align: center;"> N4 beach </h1>
       <h2 style="text-align: center;"> <a href="https://maps.app.goo.gl/oeyCXGVZYedn8PgMA" title="N4 beach"> Click here for Directions</a></h2>
       <div style="text-align: center;">
       <img src="n4 beach.png" alt=" Image not found" class="Image">
       <h1>
          N4 Beach is a lesser-known yet vibrant beach located in the northern part of Chennai, India, in the Kasimedu fishing harbor area. It is primarily a working beach associated with the fishing community, offering visitors a glimpse of the daily lives of fishermen and the hustle and bustle of a traditional coastal market.
   </h1>
</div>
   </body>
   </html>
```
   ## Railway.html:
```python
   <html>
    <head>
        <title> Perambur Railway Station</title>
        <style>
            h1,h2{
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            }
        </style>
        
    </head>
    <body>
        <h1 style="text-align: center;">Perambur Railway Station </h1>
        <h2 style="text-align: center;"><a  href="https://maps.app.goo.gl/d5cRpxZYWwnCeu2VA"  title="Perambur_Railway_Station"> Click here for Directions</a></h2>

        <div style="text-align: center;">

        <img src="Railway.png" Width="30%" height="30%" >
    </div>
        <h2> Perambur railway station is the second oldest railway station in the city after Royapuram railway station.</h2>  
        <h2> The station was built in the 1860s to cater to employees at Southern Railway's locomotive, carriage, wagon, and coach-building workshops. The lines at the station were electrified on 29 November 1979, with the electrification of the Chennai Central–Tiruvallur section</h2>
        <nav></nav>
     </body>
</html>
```


## OUTPUT
## imagemap:

![alt text](<Screenshot 2025-11-03 132413.png>)

## Garden:

![alt text](<Screenshot 2025-11-03 133143.png>)

## N4 beach:

![alt text](<Screenshot 2025-11-03 133128.png>)

## Rail museum:

![alt text](<Screenshot 2025-11-03 133206.png>)

## railway:

![alt text](<Screenshot 2025-11-03 133154.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
