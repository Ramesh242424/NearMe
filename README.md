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


<!DOCTYPE html>
<html>
<head>
    <title>My City</title>
</head>
<body bgcolor="#fdfaf6" text="#2c2c2c">

    <h1 align="center">
        <font color="#4B0082" size="10" face="Georgia">CHENNAI</font>
    </h1>

    <h3 align="center">
        <font color="#800000" size="6" face="Trebuchet MS">RAMESH KRISHNAN S (212224220076)</font>
    </h3>

    <center>
        <img src="c:\Users\admin\Desktop\Screenshot 2025-05-07 134444.png" usemap="#MyCity" height="610" width="1450">
        <map name="MyCity">
            <area target="" alt="veeras" title="veeras" href="veeras.html" coords="542,86,669,164" shape="rect">
            <area target="" alt="idream theater" title="idream theater" href="idream.html" coords="648,285,771,351" shape="rect">
            <area target="" alt="appolo hospital" title="appolo hospital" href="rela.html" coords="1085,215,1297,291" shape="rect">
            <area target="" alt="PVR" title="PVR" href="pvr.html" coords="476,345,643,407" shape="rect">
            <area target="" alt="AGS" title="AGS" href="ags.html" coords="306,530,490,556" shape="rect">
        </map>
    </center>

</body>
</html>




<!DOCTYPE html>
<html>
<head>
    <title>CHENNAI CITY</title>
</head>
<body bgcolor="#fefcf9" text="#2c2c2c">

    <h1 align="center">
        <font size="10">CHENNAI</font>
    </h1>

    <h2 align="center">
        <font size="7">VEERAS</font>
    </h2>

    <hr size="5" width="80%" color="#003366">

    <p align="center">
        <font face="Georgia" size="6">
            VEERAS, founded in 1969, is a chain of retail stores in India. 
            It is the largest family owned business retail chain in India.[3][4] 
            It is the first store to introduce Aadi Thallupadi sale concept.

            VEERAS operates seven stores in Chennai, at royapuram.The company has mega stores in Madurai, Tirunelveli and Coimbatore. The company is growing rapidly and has 
            plans to open stores in Mumbai, New Delhi, and Bengaluru. 
        </font>
        <img src="https://lh3.googleusercontent.com/8vGv70jBrcwKSzKmtBJbfL8xuPvaCiG9725xU13wLTb9iUSRIH5TwyDZdwXWZ2qpWjO9PqS_VtUJcTa2h_JGm37pMjc=w360-rw" usemap="#MyCity" height="610" width="1450">
    </p>

    <hr size="3" width="60%" color="#800020">

</body>
</html>






<!DOCTYPE html>
<html>
<head>
    <title>CHENNAI CITY</title>
</head>
<body bgcolor="#fefcf9" text="#2c2c2c">

    <h1 align="center">
        <font size="10">CHENNAI</font>
    </h1>

    <h2 align="center">
        <font size="7">Idream Theatre</font>
    </h2>

    <hr size="5" width="80%" color="#003366">

    <p align="center">
        <font face="Georgia" size="6">
            CHENNAI, India – Christie®, a leader in creating and delivering the world’s best visual and audio experiences, 
            is proud to announce that Idream Theatres has become the first cinema in India to be equipped with Christie’s next-generation CP4325-RGB 
            RealLaser™ cinema projector.​Located in Chennai, idream Theatres is the most prominent cinema in the city’s royapuram district 
            with a single-screen auditorium featuring ergonomic cushion seats, three-way stage speakers and eye-catching interiors. 
            The massive auditorium has a capacity of 776 seats and is highly popular among students, working professionals and residents in and around Chrompet district.
        </font>
        <img src="https://assetscdn1.paytm.com/images/cinema/BG2%2520(1)-5396f2e0-2b9f-11ee-b34d-05fa8644d6a7%5B1%5D-aba8ca30-e7b4-11ef-b0cb-6f1a8f777f1f.jpg" usemap="#MyCity" height="610" width="1450">
    </p>

    <hr size="3" width="60%" color="#800020">

</body>
</html>





<!DOCTYPE html>
<html>
<head>
    <title>CHENNAI CITY</title>
</head>
<body bgcolor="#fefcf9" text="#2c2c2c">

    <h1 align="center">
        <font size="10">CHENNAI</font>
    </h1>

    <h2 align="center">
        <font size="7"> appolo hospital </font>
    </h2>

    <hr size="5" width="80%" color="#003366">

    <p align="center">
        <font face="Georgia" size="6">
            appolo hospital, an international medical facility, is a quaternary care hospital. 
            We have access to cutting-edge technology and experienced, caring medical professionals. We are dedicated to fostering 
            and responding to the needs of our patients along with compassion and care. Our hospital has a facility of over 4500 beds 
            inclusive of 130 critical care beds, 14 operating rooms, contemporary reference laboratories and radiology services. 
            appolo hospital is in a sprawling area of 36 acres of land located in royapuram, Chennai, India.
        </font>
        <img src="https://images.jdmagicbox.com/v2/comp/chennai/75/044p7010475/catalogue/apollo-hospitals-tondiarpet-chennai-multispeciality-hospitals-bg3ijbtypr.jpg" usemap="#MyCity" height="610" width="1450">
    </p>

    <hr size="3" width="60%" color="#800020">

</body>
</html>



<!DOCTYPE html>
<html>
<head>
    <title>CHENNAI CITY</title>
</head>
<body bgcolor="#fefcf9" text="#2c2c2c">

    <h1 align="center">
        <font size="10">CHENNAI</font>
    </h1>

    <h2 align="center">
        <font size="7">PVR</font>
    </h2>

    <hr size="5" width="80%" color="#003366">

    <p align="center">
        <font face="Georgia" size="6">
            PVR is a popular multiplex located in Pallavaram, Chennai.
            It was originally known as  before being acquired by PVR in 2018.
            The theatre is known for its comfortable seating and high-quality sound system.
            It offers a great movie experience along with popular snacks like popcorn and cold coffee.
            Movie tickets and showtimes are available on platforms like BookMyShow.
        </font>
        <img src="https://etimg.etb2bimg.com/photo/98506022.cms" usemap="#MyCity" height="610" width="1450">
    </p>

    <hr size="3" width="60%" color="#800020">

</body>
</html>

```

## OUTPUT
![image](https://github.com/user-attachments/assets/91c2f062-ea1a-4633-a697-ce87f8190247)


![Screenshot 2025-05-07 135725](https://github.com/user-attachments/assets/69332120-3d83-49bb-8b92-f5df7d1364dc)

![Screenshot 2025-05-07 135748](https://github.com/user-attachments/assets/96451e1b-b428-40bb-95c9-930664156191)


![Screenshot 2025-05-07 135808](https://github.com/user-attachments/assets/ad58d1e0-2d9a-4835-bf05-7a8161710fd7)


![Screenshot 2025-05-07 135825](https://github.com/user-attachments/assets/6f9c8e4f-3c6d-4e9a-8c4d-873441a43b63)



## RESULT
The program for implementing image maps using HTML is executed successfully.
