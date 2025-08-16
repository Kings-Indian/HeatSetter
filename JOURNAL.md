---
title: "Put Me Down"
author: "Tanishq Goyal"
description: "A Vertical Heatpress for Threaded Inserts"
created_at: "2025-15-25"
---

# Project Overview
**Total Time Spent: 7.5 hours**

My goal was to create a vertical heat press machine with the goal of inserting threaded inserts. It shouldf also have a fixed easily swappale bottom position and a machism that makes the weighrt more ballanced.

---

## Day 1: Initial Design and Framework
**Date: 7/15/24**  
**Time spent: 3h**

### Initial Skeleton Design
Fiorst I started with the overall skelaton 
<img width="953" height="879" alt="image" src="https://github.com/user-attachments/assets/86ae2e04-e6fb-47ae-befb-bbfa2f6afb06" />

These were based off some cheap extrusions. I then added a linear slide due to the need for a Z axis up and down moevment.

I created the board based around 200x170, based off my setup and the extrusion size. 
<img width="856" height="760" alt="image" src="https://github.com/user-attachments/assets/013311c9-fe91-4eff-953e-f0738767a624" />

### Material Selection
I decided to use a silicone sodlering mat since any 23d printed material would melt to the touch of a soldering iron. Ill cut https://www.amazon.com/MMOBIEL-Anti-Static-Non-Slip-Magnetic-Soldering/dp/B08XVZTF3P/ref=sr_1_1?crid=1JMLOY7PWC4LR&dib=eyJ2IjoiMSJ9.Yhwh1rp77hbMeAsrrAorLH0v_E1ULy9BThg3rhZRBFP_pb3Z9hyY52_HPXKwxJ1i-pImXmmvpaA2F2JavRQsxIbW1_neKWaq4lW5i71j8q4fdzY4JGnqqfdVBJWokIm16DKXINtAzh8D6HYDGidZvat7cFX5rRuU0Aiina6bn4Km29L_vEMfY6ruBTu-q6em4JrojB-Xb1wNnUVI5_VKw4c2Z5jq97cOGMZff_UhIiwX-dOgRTBVEppcf_nkWpZiWtcoIbbRQ2H-2B3imw8KswXPkrdOexCQf2yvvmXMoDU.u5mhVmEduHV_95o3bpwfod_V4AIwyp_Cx1-UzIwAe3s&dib_tag=se&keywords=Ceramic%2BSoldering%2BMat&qid=1752715560&refinements=p_85%3A2470955011&rnid=2470954011&rps=1&sprefix=ceramic%2Bsoldering%2Bmat%2Caps%2C147&sr=8-1&th=1 to the size needed

### Product Links
These are the product links of the following:
- **2020 Extrusions**: https://www.amazon.com/Aluminum-Extrusion-European-Standard-Anodized/dp/B0D52KNHB5/ref=sr_1_2?crid=37LMN9DTRE4ZP&dib=eyJ2IjoiMSJ9.2QyJGbhVR5Ytxj6-OEb62EKSPZmCHvUECXsAoWW_FjCrQeudZbmpWuZpDyFmw5mfBQjHOTixOfi1c3tI6cu1drMm5HJwHBW7LCyy93nUQvrGVeiNS-_InPIrC3YJGZbbUEAq0eJEGtbyhMIPXu0VKDtwBuEzWUN70J94zWXzssdPh-TNKREiv78MEjBtfEJu_NZfpHLhP7SYoZGElsaFmOaNNsjvpIzi3lRUeokKLC8.wHHPsg4jtTAFuexoeSSF7b3S-38xde_tWHyx9VeKp94&dib_tag=se&keywords=2020%2Bextrusion&qid=1752716025&refinements=p_85%3A2470955011&rnid=2470954011&rps=1&sprefix=2020%2Bextr%2Caps%2C146&sr=8-2&th=1
- **Linear Rail**: https://www.amazon.com/BEVDICNC-Bearing-Carriage-Printers-Upgrades/dp/B0BZ45L9J4/ref=sr_1_59?crid=1BMTFP59Q44PF&dib=eyJ2IjoiMSJ9.X_zD2kWF_W0D3Gqatax35SYZjUIehiZ9LjFaUIsb73cWU5c-d5dZmZV1ey6f-76R2ia4sR0cnxOfl81Chw1cEuMoxtikAHfoJgqqf2EpYg2SY_kG-Jlh_PgFB8BY92jwKVQzH-CUtUukHepdvfrN3VEoRDJihcsnXijEtJAflGg.CGyB3N1cohrq9L9QHV6qnuXg4wKGk8zntZfkyPSv3LM&dib_tag=se&keywords=200%2Bmm%2Blinear%2Brail&qid=1752630984&refinements=p_85%3A2470955011&rnid=2470954011&rps=1&sprefix=200%2Bmm%2Blinear%2Brai%2Caps%2C106&sr=8-59&xpid=IwdVSMXZiO04Y&th=1

<img width="923" height="909" alt="image" src="https://github.com/user-attachments/assets/761d3215-d41a-4f9e-b5d3-1d0ff382855d" />

---

## Day 2: Toolhead Design and Implementation
**Date: 17/17/24**  


### Toolhead Requirements
For the toolheasd, there two reuirements:
1. It musrt fit a range (defined by "soldering-tightness") soldering irons
2. It must be easily adjustable on the X axis

### Grip Design
<img width="1703" height="991" alt="image" src="https://github.com/user-attachments/assets/bee1627f-df61-404c-a206-577d2c88fca9" />
(this is for grip)

<img width="1335" height="1179" alt="image" src="https://github.com/user-attachments/assets/1b849c06-b80a-4c07-89b0-62e9e560e546" />
(this is based on my sister's soldering iron)
for the fit of more soldering irons (even though Im opretty sure most of them are this size by looking online )

### Adjustable Tightness Mechanism
the tighness can be done by adding these

<img width="210" height="41" alt="image" src="https://github.com/user-attachments/assets/d447dba3-bdfc-4634-ac56-cf7ddf4e3fbc" />
<img width="1332" height="776" alt="image" src="https://github.com/user-attachments/assets/6a46b2db-46d4-4909-9966-1139bc908034" />
<img width="1730" height="1083" alt="image" src="https://github.com/user-attachments/assets/def07d46-71f9-41ee-8aa2-bed3f8ecec97" />

<img width="1672" height="789" alt="image" src="https://github.com/user-attachments/assets/1bb514dd-9b2f-4f83-8bea-9c76c27d5bf2" /> for screw, and the toolheads done :D 

<img width="1737" height="820" alt="image" src="https://github.com/user-attachments/assets/eeb2ee94-6578-457f-a743-7d08d2ee823f" />

### Custom T-Nut Design
Since T nuts tend to rotate and unfasten them selved I decided to make an elongated T nut that would stay in its orientation

<img width="1123" height="498" alt="image" src="https://github.com/user-attachments/assets/10e7d534-4dcc-4f32-8370-241e88a06c9e" />

<img width="1967" height="1144" alt="image" src="https://github.com/user-attachments/assets/45d7baad-d0a8-48ef-aadb-6da94acb19e5" />
**Time Spent: 3 hours**

---

**Time Spent: 1h**

### Counterbalance System Design
Now, for the system that makes it "lgihter" and creates a hard stop.

<img width="716" height="1201" alt="image" src="https://github.com/user-attachments/assets/f490aa82-0406-43c0-b1a0-5f5fd0c9a4fa" />

### Spring Force Calculations
According to https://www.wellste.com/2020-aluminum-extrusion/, The weight of 2020 extrusion is 0.65kg/m. 

Linear mass = 0.65 kg/m  
Length = 200 mm = 0.2 m  
Weight = 0.65kg/m×0.2m=0.13kg  
W=Carriage Weight+Extrusion Weight=0.12kg+0.13kg=0.25kg  
W=0.25kg×9.81m/s²=2.45N  
F=k*change in x=2.45N  
Ill asssume theres no reason to go beyong 10 mm, so  

k=2.45N/0.01m=245N/m

### Spring Selection
I realized I cant really use this on amazon, so Ill just get a set and see which one fits best 😭 https://www.amazon.com/Sorting-Extension-Compression-Galvanized-Mechanical/dp/B0D6GXV687/ref=sr_1_4?crid=3MR9MA55ROSVI&dib=eyJ2IjoiMSJ9.2ILUb2wM6TB2baRpbg61sZsK1BbH-sg69QZt1INDBkU69KAh013eWQ--Tu9TWu95G3DSlWhcsJ41yX1LUZBpmV-b488gt4IQNKI0fi3Rv5Id5McQ_16F-rUFlt6wEjKrnScA8knj0R5V6BcCOj9SUU-t49rfK1jkUFOQIqCTJoSogN5cb0YYzgj-2hr7_h_0YhSrPHo9XdpRZxVZwqKOC99lxYdajbvLuuLmcB8Tt3U.4K9BquBh7X5EGDUUQiMHj9aivTtFlrA7U-Z_Sojkug4&dib_tag=se&keywords=extension+spring&qid=1752783680&refinements=p_85%3A2470955011&rnid=2470954011&rps=1&sprefix=extension+spring%2Caps%2C151&sr=8-4 this set seems good 

### Hardware Selection
fOR THE SCREW HOLDING IT, Ill use https://www.amazon.com/Thumbscrews-Universal-Mounting-Hardware-Clamping/dp/B0CNQX6PQR/ref=sr_1_1?crid=1AY2GZ498RNPO&dib=eyJ2IjoiMSJ9.hoDa7lHvCPRCzo_sY4w96dLiE-ru0D_wzqKmmB3Vy22F2zoVXxLRwtk2LHVW1TXfnx5tvYAw1HYoq18BumN1dRtY8ANW8O-cwjk74QNU6Pr03G2orM_3Li-v9oUkzX69VApUnWqZI8wWKnn6l1DfMCMTLVneSW-1kvhrAV-YTLN3TfaqJKBdbugXdWEEQboed8IpriYvKHqdl3jM5FoZtjqfxU0yQx0NnCzQZRTzE1M.HCl2yFVp4F_S1DkUwEI2fvHh2r48vEPNNsoE_qNEzns&dib_tag=se&keywords=m4+screw+knob&qid=1752784480&refinements=p_85%3A2470955011&rnid=2470954011&rps=1&sprefix=m4+screw+knob%2Caps%2C125&sr=8-1

for the T Nut, ill use https://www.amazon.com/FOCMKEAS-European-Standard-Aluminum-Extrusion/dp/B0CJ8623TH/ref=sr_1_2?crid=3EX8KOQQGWTBX&dib=eyJ2IjoiMSJ9.WHG5fH2j2KI6TtlpBMpfU3PWglxHyVlq9eZ3KoRdTzZR69yp4PU70GRGT1yFbIW6BwVdyiZN5OBUBjxXM7WhsZZ9nJyRfJOObjx_Wrab1uIRGQK9_yNbOxiTVa1Y1zTzupExTTkzEbcd9dsUjIDAgx5uoQzDEdSMkCsEMnneGlIOhFywKlerFS6-dq_kfV2IKlXCMX4z7BpERqaLqP4ibKb3AQP0BfqXDaNzFO2_Tgk.zvp81yb2t25nhfuYXCyNfrpLsmhNwKRjHMVuu3AKXEs&dib_tag=se&keywords=M4%2BT%2BNUT&qid=1752785108&refinements=p_85%3A2470955011&rnid=2470954011&rps=1&sprefix=m4%2Bt%2Bnut%2Caps%2C131&sr=8-2&th=1. This may actually replace the 3d pritned nut based on tested performance. 
(The nuts are for 4040 extrusion so I cant. Found this in the futuire (I got so hapyy b4 :( )) For this, I think I shoukld use a normal T nut. I can make the other side attached to this screw)

<img width="638" height="357" alt="image" src="https://github.com/user-attachments/assets/87921ac0-96d3-4508-83a2-6f75da58bc64" />
<img width="844" height="764" alt="image" src="https://github.com/user-attachments/assets/a3c2660c-0e36-446f-9d8b-fe6024d0fcfa" />

### Bottom Limit Design
for the bottom limit, Ill use a printed bracket as such

<img width="1157" height="949" alt="image" src="https://github.com/user-attachments/assets/9892f876-ef81-4a8e-938a-460364516f1d" />
<img width="1066" height="557" alt="image" src="https://github.com/user-attachments/assets/12abeb48-15ef-4168-9a1b-43203f42ea11" />
this is the final design, if it ends up being too thin which I doubt due to the spring Ill just reprint a thicker one.

### Final Functional Assembly
<img width="1112" height="861" alt="image" src="https://github.com/user-attachments/assets/6d27761e-3020-4e28-a303-868d9d3c7c37" />
This is the final everything as far as functional goes.
Time spent: 3 hours
---
\

### Endcap Design
Now, my only concern is polishing it. The only non polished things I see are these 2 sides.

<img width="1060" height="779" alt="image" src="https://github.com/user-attachments/assets/b1196d86-2da1-4545-a3c0-d66f264bc6f7" />
This is the endcap design

<img width="578" height="670" alt="image" src="https://github.com/user-attachments/assets/9d8b4694-cd5e-4f5b-9c04-7ebda5c2d9ba" />
Side Endcap:

<img width="1069" height="758" alt="image" src="https://github.com/user-attachments/assets/953fdddc-aaf4-4162-a5ee-f837c6ec51db" />

<img width="1103" height="977" alt="image" src="https://github.com/user-attachments/assets/011e7c71-a317-4bdd-8fd5-06ce2c5aacd6" />

^Top Endcap ^
Time spent: 0.5h
<img width="1181" height="1133" alt="image" src="https://github.com/user-attachments/assets/4905477a-52ef-4539-98d3-043e2bb6702e" />
Final design!

8/1/25

turns out I caznt drill after trying for 5 hours with barely a dent (was using a normal drill and drillbit instead of a drill pressdown thing since i dont have one), 3d printing this thing 

<img width="1166" height="783" alt="image" src="https://github.com/user-attachments/assets/8a466718-4e53-484f-b256-ec8dbc8abaf3" />
<img width="684" height="614" alt="image" src="https://github.com/user-attachments/assets/37d596cf-59b5-4c84-aea3-8a056f0ae5e3" />

time spent: 1h

8/2/25

YAYY itd early morning and it printed PERFECTLY
<img width="181" height="168" alt="image" src="https://github.com/user-attachments/assets/d4fc48f4-cea2-45c6-af4d-005492d006ef" />
took im an hour to install and it was perfect
<img width="430" height="529" alt="image" src="https://github.com/user-attachments/assets/e715abe6-0a51-4270-86f1-6679e7532820" />
Time Spent: 1h



