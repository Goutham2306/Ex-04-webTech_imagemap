# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
## Step 1
Create a new django project and app.
## Step 2:
Add a new imagemap html file in templates and neede images in static folder and define it in settings.

## Step 3:
Type ur image map code in the html with coordinates and target file to redirect on click.

## Step 4:
Define your components pages and create content in such a way that it gives information about place which is being clicked.

## Step 5:
Include pictures and contents for your subpages and map them using urls and views.

# Code:
```
Developed by: Kandukuri Goutham
Ref no:23008975
```
## MAP.HTML:
```
map.html:
<!DOCTYPE html>
<html>
    <head>
        <title>Tirupathi Image Map</title>
    </head>
    <body>
       
        <img src = "C:\Users\admin\Pictures\Screenshots\tirupathi.png" height="750" width="1800" align="center" usemap="#imgmap">
        <map name="imgmap">
           <area target="" alt="Sree Venkateswara swami temple" title="Sree Venkateswara swami temple" href="temple.html" coords="413,514,389,462,399,406,425,387,449,370,482,367,529,372,565,416,565,476,528,523,470,540" shape="poly">
           <area target="" alt="Seshachalam Forest" title="Seshachalam Forest" href="forest.html" coords="611,709,545,745,492,797,669,773,498,805,562,882,622,888,664,872,695,862,707,836,718,802,715,755,686,711,647,709,624,716" shape="poly">
           <area target="" alt="SV Zoological Park" title="SV Zoological Park" href="zoo.html" coords="1025,286,1020,304,1000,315,992,341,1008,357,1039,374,1065,374,1085,370,1119,349,1126,312,1093,289,1054,286" shape="poly">
           <area target="" alt="Kalyani Dam" title="Kalyani Dam" href="dam.html" coords="1056,157,1021,170,1012,207,1016,229,1026,251,1041,256,1065,260,1088,255,1108,251,1109,224,1106,198,1106,185,1087,162" shape="poly">
           <area target="" alt="ISCKON Temple" title="ISCKON Temple" href="isckon.html" coords="811,192,839,190,881,188,898,171,899,128,873,107,829,104,806,109,790,120,775,135,774,157,780,177,793,185" shape="poly">
        </map>
    </body>
    </html>
```
# Temple.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>TIRUMALA</title>
    </head>
    <body>
        <h1 align='center'>SRI VENKATESWARA SWAMY TEMPLE</h1>
        <img src ="C:\Users\admin\Documents\tirumala.jpg"  height="500" width="700" align="center" >
        <p>
       Tirumala is a spiritual town in Tirupati district of the Indian state of Andhra Pradesh. It is one of the suburbs of the Tirupati urban agglomeration. The town is a part of Tirupati Urban Development Authority and located in Tirupati (urban) mandal of Tirupati revenue division. It is a hill town where Tirumala Venkateshvara Temple is located, a popular shrine of Vishnu. The town is strictly vegetarian.
          In ancient literature, Tirupati is mentioned as Adi Varaha Kshetra. The Puranas associate the site with Varaha, one of the Dashavatara of Vishnu. In the Varaha Purana, Venkatadri is believed to be a part of Mount Meru, which was brought on to the earth from Vishnu's abode Vaikuntham by his mount Garuda. The seven peaks represent the seven heads of Adishesha.
      
        </p>
    </body>

</html>
```
# Forest.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>SESHACHALAM FOREST</title>
    </head>
    <body>
        <h1 align='center'>SESHACHALAM FOREST</h1>
        <img src ="C:\Users\admin\Pictures\sesha.jpg" align="center" height="500" width="700"  >
        <p>
      Seshachalam Hills are hilly ranges part of the Eastern Ghats in southern Andhra Pradesh state, in southeastern India. The Seshachalam hill ranges are predominantly present in Annamayya and Tirupati Districts of the Rayalaseema region in Andhra Pradesh, India.

      Tirupati, a major Hindu pilgrimage town is located in the hills. The hills contain seven peaks namely, Anjanadri, Garudadri, Narayanadri, Neeladri, Seshadri, Venkatadri and Vrishabhadri, the highest at about 600 m (2,000 ft) above sea level. The seven peaks are said to represent the seven hoods of Shesha, the king of the serpents in Hindu mythology. The Srivenkateshwara National Park is also located in these ranges. The famous Natural Arch, Tirumala Hills is also a part of Seshachalam Hills, which dates back to the period in between Middle and Upper Proterozoic Eon.

The Seshachalam hill ranges running to North West to South East, over to a length about 80 km and width ranged from 32 to 40 km in the two Rayalaseema region districts, Tirupati and Kadapa. These ranges have typical gorges and gaps due to faulting and stream erosion resulting in to discontinuous ranges. The altitude of Seshachalam hill ranges varies from 168 to 1187 m above MSL. The highest hill peak is Tellaralla penta (1187 m) and most of the other hill peaks are above 900 m MSL.
     </p>
    </body>

</html>
```
# Zoo.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>SV ZOO PARK</title>
    </head>
    <body>
        <h1 align='center'>SRI VENKATESWARA ZOOLOGICAL PARK</h1>
        <img src ="C:\Users\admin\Documents\zoo.webp"  height="500" width="700" align="center" >
        <p>
      Sri Venkateswara Zoological Park is located in Tirupati, Andhra Pradesh, India.It was established on 29 September 1987,[1] and covers an area of 5,532 acres (22.39 square kilometres). it is the largest zoological park in Asia.
      The zoo had an exceptionally heavy leopard called 'Balaji', which weighed 139–143 kg (306–315 lb) against the normal weight of 70 kg (150 lb) of its class. Balaji was captured at the age of 12 in 1996, when he weighed 108–113 kg (238–249 lb). The leopard ate 4 kg (8.8 lb) of beef daily, the same as the other leopards in the zoo. The park's management was said to be in touch with the Guinness Book of World Records authorities seeking its entry in the records as the biggest leopard.Due to an illness and old age, it died at the age of 27 on 11 June 2013.
        </p>
    </body>

</html>
```
# Dam.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>KALYANI DAM</title>
    </head>
    <body>
        <h1 align='center'>KALYANI DAM</h1>
        <img src ="C:\Users\admin\Pictures\dam.jpg" align="center" height="500" width="700"  >
        <p>
      The Kalyani Dam is a gravity dam constructed across the Swarnamukhi river at Tirupati city and located in Tirupati District of Andhra Pradesh, India. This dam is one of the major sources of water supply for Tirupati city and its catchment areas. Once filled, the dam can cater to the water needs of Tirupati for at least two years.The dam was constructed in the year 1977.

        The dam was constructed across Swarnamukhi River with 25 million cubic meters storage capacity between hills which are part of Seshachalam Hill ranges.Catchment area: 48.56 km2 (18.75 sq mi).Location of dam: Tirupati, Tirupati District, Andhra Pradesh.
Full Reservoir Level: 274.31 metres (900 ft) msl
        </p>
    </body>

</html>
```
# Isckon.html:
```
<!DOCTYPE html>
<html>
    <head>
        <title>ISKCON TEMPLE</title>
    </head>
    <body>
        <h1 align='center'>ISKCON TEMPLE</h1>
        <img src ="C:\Users\admin\Pictures\ISKON.jpg" align="center" height="500" width="700"  >
        <p>
      ISKCON (International Society for Krishna Consciousness) Krishna Temples are located all over the world. Although, in almost every important city of India, there is an ISKCON Temple, ISKCON Temple in Tirupati is especially popular. Its architecture and location makes it is even more attractive to the devotees.

The idea for this temple germinated in the year of 1974 – 1975, when his holy Srila Prabhupada visited Tirumala- Tirupati on the request of Andhra Pradesh Government. Impressed with the spiritual atmosphere of the place and after seeing thousands of devotees visiting every day, he saw this Tirupathi as an ideal place to promote the teachings of Bhagwat-Gita and Lord Krishna while in turn creating an environment of amity throughout the world.

It in the year of 1982, this idea started taking a physical form while in 1983; a small Brahmachari ashram was established. Located at the foot of Tirumala Hills, in 1984, a small temple was inaugurated with the installation of the idols of Lord Krishna and Goddess Radha. In 2005, this temple was opened to everyone.

        </p>
    </body>

</html>
```
# Output:
## Map:
![WhatsApp Image 2023-11-21 at 17 07 24_ee629cdf](https://github.com/Goutham2306/Ex-04-webTech_imagemap/assets/138971154/5d0586fe-92cd-46d5-84dd-4f71a8f3c0b5)
# VENKATESWARA SWAMI TEMPLE:
![WhatsApp Image 2023-11-21 at 17 14 45_42b9243c](https://github.com/Goutham2306/Ex-04-webTech_imagemap/assets/138971154/1683e5fc-5efb-45e5-bc01-a832da6c498d)
# FOREST:
![WhatsApp Image 2023-11-21 at 17 34 22_8ac93608](https://github.com/Goutham2306/Ex-04-webTech_imagemap/assets/138971154/fc200d45-a515-4c1a-9865-99049a4bf6c8)
# SV ZOO PARK:
![WhatsApp Image 2023-11-21 at 17 40 32_4b6a14db](https://github.com/Goutham2306/Ex-04-webTech_imagemap/assets/138971154/8e75ddc6-0dbe-43e3-87fd-312af4be50f7)
# KALYANI DAM:
![WhatsApp Image 2023-11-21 at 17 19 30_eb3ea777](https://github.com/Goutham2306/Ex-04-webTech_imagemap/assets/138971154/2fb12cff-6432-4435-99de-4209ad1a4290)
# ISCKON:
![WhatsApp Image 2023-11-21 at 17 26 44_97b5580a](https://github.com/Goutham2306/Ex-04-webTech_imagemap/assets/138971154/7ff46f1d-5367-4bee-a41d-612a49d283e6)

# Result:
The program for implementing image map is executed successfully.
