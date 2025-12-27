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

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Clickable Map</title>
</head>
<body>
  <h2>Interactive Map</h2>
  <img src="map.png" usemap="#image-map" alt="Map">

  <map name="image-map">
    <area target="_blank" alt="vallioor" title="vallioor" href="vallioor.html" coords="893,214,1020,305" shape="rect">
    <area target="_blank" alt="kesavaneri" title="kesavaneri" href="kesavaneri.html" coords="376,163,636,341" shape="rect">
    <area target="_blank" alt="nallangkulam" title="nallangkulam" 
          href="nallangkulam.html" coords="1057,155,1267,293,1248,16,1427,45" shape="poly">
    <area target="_blank" alt="kizhavaneri" title="kizhavaneri" href="kizhavaneri.html" coords="1154,558,1390,662" shape="rect">
  </map>
</body>
</html>

vallioor.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vallioor</title>
  <style>
    body {margin:0; font-family:Arial, sans-serif; color:#fff; 
          background:linear-gradient(135deg,#0078d7,#00b4d8);}
    header {padding:1.5rem; text-align:center; background:rgba(0,0,0,0.3);}
    main {padding:2rem; max-width:700px; margin:auto; background:rgba(255,255,255,0.1); border-radius:10px;}
    h1 {font-size:2rem; margin:0 0 .5rem;}
    p {line-height:1.6;}
    a {display:inline-block; margin-top:1rem; padding:.6rem 1rem; 
       background:#ffdd57; color:#333; text-decoration:none; font-weight:bold; border-radius:5px;}
    a:hover {background:#ffd633;}
  </style>
</head>
<body>
  <header>
    <h1>Vallioor</h1>
    <p>The Commercial Hub of Tirunelveli District</p>
  </header>
  <main>
    <p>
      Vallioor is a lively town in Tamil Nadu.<br>
      It is famous for its bustling markets and sacred temples.<br>
      The Sri Subramaniya Swamy Temple is a major attraction.<br>
      Its location on key highways makes it an important trade hub.<br>
      Travelers often stop here on the way to Kanyakumari or Tirunelveli.
    </p>
    <a href="index.html">⬅ Back to Map</a>
  </main>
</body>
</html>

kesavaneri.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kesavaneri</title>
  <style>
    body {margin:0; font-family:Georgia,serif; color:#333; 
          background:linear-gradient(135deg,#ffecd2,#fcb69f);}
    header {padding:1.5rem; text-align:center; color:#5a2a00; background:rgba(255,255,255,0.4);}
    main {padding:2rem; max-width:700px; margin:auto; background:rgba(255,255,255,0.6); border-radius:10px;}
    h1 {margin-bottom:.5rem;}
    a {display:inline-block; margin-top:1rem; padding:.6rem 1rem; 
       background:#5a2a00; color:#fff; text-decoration:none; border-radius:5px;}
    a:hover {background:#7a3d00;}
  </style>
</head>
<body>
  <header>
    <h1>Kesavaneri</h1>
    <p>A Glimpse of Rural Tamil Nadu</p>
  </header>
  <main>
    <p>
      Kesavaneri is a calm village surrounded by green fields.<br>
      Agriculture is the main livelihood of its residents.<br>
      The village reflects Tamil Nadu’s traditional rural culture.<br>
      Friendly locals welcome visitors warmly.<br>
      Its peaceful setting makes it perfect for a quiet retreat.
    </p>
    <a href="index.html">⬅ Back to Map</a>
  </main>
</body>
</html>

kizhavaneri.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kizhavaneri</title>
  <style>
    body {margin:0; font-family:'Segoe UI',sans-serif; color:#fff; 
          background:linear-gradient(135deg,#a18cd1,#fbc2eb);}
    header {padding:1.5rem; text-align:center; background:rgba(0,0,0,0.3);}
    main {padding:2rem; max-width:700px; margin:auto; background:rgba(255,255,255,0.1); border-radius:10px;}
    h1 {margin-bottom:.5rem;}
    a {display:inline-block; margin-top:1rem; padding:.6rem 1rem; 
       background:#ffd54f; color:#333; text-decoration:none; border-radius:5px;}
    a:hover {background:#ffca28;}
  </style>
</head>
<body>
  <header>
    <h1>Kizhavaneri</h1>
    <p>A Village Rich in Heritage</p>
  </header>
  <main>
    <p>
      Kizhavaneri is a heritage-rich village near Vallioor.<br>
      It is famous for its historic temples and festivals.<br>
      Local crafts and traditions thrive here.<br>
      The community is known for its warmth and hospitality.<br>
      Its rural scenery attracts many visitors seeking culture.
    </p>
    <a href="index.html">⬅ Back to Map</a>
  </main>
</body>
</html>

nallangkulam.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nallangkulam</title>
  <style>
    body {margin:0; font-family:Verdana,sans-serif; color:#fff; 
          background:linear-gradient(135deg,#43cea2,#185a9d);}
    header {padding:1.5rem; text-align:center; background:rgba(0,0,0,0.3);}
    main {padding:2rem; max-width:700px; margin:auto; background:rgba(255,255,255,0.1); border-radius:10px;}
    h1 {margin-bottom:.5rem;}
    a {display:inline-block; margin-top:1rem; padding:.6rem 1rem; 
       background:#ffdd57; color:#333; text-decoration:none; border-radius:5px;}
    a:hover {background:#ffd633;}
  </style>
</head>
<body>
  <header>
    <h1>Nallangkulam</h1>
    <p>The Land of Calm Waters</p>
  </header>
  <main>
    <p>
      Nallangkulam means “good pond” in Tamil.<br>
      The village is known for its serene water bodies.<br>
      It offers beautiful spots for nature photography.<br>
      Birdwatchers often visit for its rich wildlife.<br>
      The quiet surroundings provide a relaxing escape.
    </p>
    <a href="index.html">⬅ Back to Map</a>
  </main>
</body>
</html>

## OUTPUT


<img width="1905" height="951" alt="499815697-6607e7cd-375e-4dfa-b55c-bf536775cdf3" src="https://github.com/user-attachments/assets/b65fc101-b33d-4dee-bf65-e2b49c8aef65" />





## RESULT
The program for implementing image maps using HTML is executed successfully.
