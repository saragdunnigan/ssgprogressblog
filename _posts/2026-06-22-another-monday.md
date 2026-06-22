##STELLA

Today went really well. I think I have an idea of the approach we can use to determine and quantify flares. Despite what I said for Friday I think we actually should use AltaiPony as well as STELLA. What I have determined is that STELLA is good for determining the probability that something is a flare, and it is really good at it. The AltaiPony is good at quantifying the flare, duration, start stop time, etc. So I think a route we would take is running them through STELLA to see which flares are valid and then using AltaiPony to get the data from those flares, it automatically makes tables with all that data. 
Today with AltaiPony I took a flaring star and compared our LC to its flare detection shown below:
<img width="1200" height="500" alt="TIC 272076451 SEC 15 RSFlares" src="https://github.com/user-attachments/assets/21d16872-70f5-46b6-a16b-3aca7a5b5862" />

<img width="848" height="400" alt="TIC 272076451 SEC 15 RS" src="https://github.com/user-attachments/assets/c2912fb0-a9c9-411d-8dd1-97f30db73688" />


Then with STELLA I finally got it to work, took a while to get around a windows issue of accessing the models. So I was only able to get the demos up. Shown below (one flare probability is one model the other is an avg of all 100 models):![Uploading TIC 272076451 SEC 15 RSFlares.png…]()

<img width="844" height="387" alt="Stella test" src="https://github.com/user-attachments/assets/5deebc23-0b43-4f04-8b7a-51c8aa535146" />
<img width="2560" height="1327" alt="stella test flares" src="https://github.com/user-attachments/assets/3496c675-9549-425e-ac28-2960037170de" />

<img width="2560" height="1327" alt="stella flare avg" src="https://github.com/user-attachments/assets/9969181b-06ee-4a8c-af8d-b77b5e7f7b07" />


Here is my list of next steps:
-get STELLA to work on our catalog of stars and compare it to the "standard" star I picked out for AltaiPony comparison
- figure out how to get the data from the AltaiPony table in python into a usable spreadsheet for analysis and how that should be organized
- this step is going to take a while but potentially trying to integrate the two into one usable code block for example AltaiPony will only add data to the spreadsheet for flares with probability above 95%. something of that nature
