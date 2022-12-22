# 30DayMapChallenge :world_map:

**My submissions to the 2022 [#30DayMapChallenge](https://www.achim-tack.org/30daymapchallenge).**

I've been meaning to develop my spatial data visualization skills and what better way to finally take action than to participate in the [#30DayMapChallenge](https://www.achim-tack.org/30daymapchallenge) created by the phenomenal geographer, [Topi Tjukanov](https://tjukanov.org/)?! The idea is to publish a map every day of November aligned with a specified theme. In addition to the themes prescribed by Topi, many of my maps will be related to three themes I am passionate about: environment :evergreen_tree:, wildlife :sloth:, and energy :bulb:. My good friend and colleague correctly referred to this amalgamation of themes as chaotic, but maybe I'll find some way to tie them all together...I also have the ambitious goal of learning and applying a variety of mapping tools throughout the challenge, from QGIS to R. Let's see how it goes!

At some point in the near future, I plan on updating this repo with my code and workflows for each map so that folks can reproduce and improve upon them.

A map a day keeps the doctor away...

**Tools used:**

| Tool  | Map count| 
| ------|----------| 
| QGIS  |    21    | 
| Python|    4     | 
| R     |          | 
| B3D   |    1     | 
| GEE   |    1     | 

Day 1: Points 🟣

Are you an introvert like me and would rather sip coffee with cats than humans? Well then, a cat cafe might be perfect for you. Cat cafes [originated in Taiwan in 1998](https://catcafesd.com/about/#:~:text=One%20of%20the%20Japanese%20tourists,has%20over%20150%20cat%20cafes) and have since become popular across the globe, especially in Japan, which has over 150 cat cafes with over 30 of them located in Tokyo. This map shows the abundance of cat cafes in Tokyo City 🗼 😸!

![Day 1 Final](https://user-images.githubusercontent.com/92735518/199236089-add59eff-6ec5-44ad-b716-a037c9c3cda4.jpeg)

Day 2: Lines 〰️

While making my day 1 map, I learned about Japan's abundant river network and was inspired to represent the country by its rivers. It's not surprising, looking at this map, to learn that [hydropower accounts for almost half of Japan’s overall renewable electricity generation](https://www.hydropower.org/publications/2022-hydropower-status-report). The country pledged to achieve net-zero emissions by 2050 and hydropower has a major role to play in fulfilling this commitment.

![Japan rivers](https://user-images.githubusercontent.com/92735518/199490273-5f4c9829-1179-409f-b461-9118565ccdaa.jpeg)

Day 3 - Polygons 🟪

Total # of meow meows rescued by animal shelters in each U.S. state (contiguous) in 2021 

This was my first time using #Plotly with #Python and it had a bit of a learning curve, so this map isn't as detailed as I'd like it to be, but I need to time box myself throughout the challenge! After completing this map, I realized Hawaii and Alaska are missing so this only applies to the contiguous states...

![Day 3 map](https://user-images.githubusercontent.com/92735518/199975778-6c178f84-d943-4a3a-81f1-1180bfe471d0.png)

Day 4 - Green 🟩

This map is meant to accompany a recent [Guardian article](https://bit.ly/3WtwOmy) written about forest loss in the DRC due to unsustainable harvesting of biomass for cooking.

Large-scale transitions to #cleancooking are needed to protect people and the planet.

Originally, I had loss portrayed as red, but red-green color blind folks wouldn't be able to see it, so I went with purple :). I'm trying to learn about accessibility as I make maps.

![Day 4 map](https://user-images.githubusercontent.com/92735518/199975486-5a231442-51c5-4e6b-b41e-27e247aa217e.jpeg)

Day 5 - Ukraine 🇺🇦

Ukraine is heavily dependent on nuclear energy, which powers nearly half of its electricity supply. In March, Russian armed forces took control of the Zaporizhzhia plant.

This animated map shows daily new conflict events between February 24th and October 21st, in relation to nuclear power plant locations (minus the decommissioned Chernobyl plant). Data for this map comes from: ACLED.

![](https://github.com/aliciaoberholzer/30DayMapChallenge/blob/main/Day5Map.gif)

Day 6 - Networks 🕸️

Nepal has ambitious climate targets and aims to achieve net-zero by 2050. The country has plans to leverage its immense hydropower potential to meet its goals and energy sovereignty.

Here is Nepal's existing electricity transmission network:

P.S. Can you spot the cross-border transmission line between Nepal & India?! This line is crucial for power trade between the two countries.

![Day 6 map](https://user-images.githubusercontent.com/92735518/200190342-b6895278-8e9a-4c14-91c7-9b960721a2a8.jpeg)

Day 7 - Raster 📷

I've barely worked with rasters, so I took this as an opportunity to learn more about the power of NASA's Black Marble. Here's a GIF of nighttime lights in Fort Myers, Florida 2 days after hurricane Ian made landfall vs. 7 days after, when the majority of power was restored. Ian was the deadliest hurricane to hit Florida since 1935. It was fascinating to learn about how the [Nighttime Blue/Yellow Composite can make detecting power outages easier](https://www.earthdata.nasa.gov/learn/articles/black-marble-blue-yellow-composite). I also picked two days with very little cloud coverage over Fort Myers to make the comparison of nighttime lights.

![Day 7 map](https://github.com/aliciaoberholzer/30DayMapChallenge/blob/main/Day7map.gif)

Day 8 - OpenStreetMap 🗺️

My friend & colleague, Anobha Gurung, requested a momo-themed map for Nepal so here it is! The custom momo icons were brought to life by my sister, Céline Oberholzer, who is an incredible artist. You can check out more of her work [here](https://instagram.com/celineslines/). Please note that there are plenty of restaurants in Nepal that don't contain "momo" in their name but serve momos. This only shows the results of a query for restaurant names that contain "momo".

![Day8map](https://user-images.githubusercontent.com/92735518/201444227-bac2e83b-64e5-4c4d-ab2d-5851f2cbd04e.png)

Day 9 - Space 👾

I was really tight on time for this one, so had to keep it simple! Here's an alien-themed map of U.S. UFO sightings since 1969:

UFO alien cutie drawn by Céline Oberholzer...you can check out her art work [here](https://instagram.com/celineslines/).

![Day 9 Map](https://user-images.githubusercontent.com/92735518/201444373-79e50915-26c1-498a-9b82-033b990ac432.png)

Day 10 - Bad Map ❌

Unlike most maps I've seen today, unfortunately my bad map wasn't intentionally made for today, but a mistake I made while working on an energy modeling research project 🙃.

Nepal feat. a whole missing province (among other map atrocities).

![FhOfnPdXEBcpVTp](https://user-images.githubusercontent.com/92735518/201444444-e7814cc8-40c1-45f6-84e2-d28755c1b699.png)

Day 11 - Red 🔴

I'm barely scraping by this challenge so I had to keep it simple again.

0 out of 61 countries being analyzed by the Climate Action Tracker have climate policies and/or commitments compatible with meeting the Paris Agreement 1.5°c temperature limit 😪.

The data being used was last updated in November, 2022. You can find it [here](https://climateactiontracker.org/countries/) and learn more about the methodology behind the rating.

![Day 11 Map](https://user-images.githubusercontent.com/92735518/201444539-246ff8e4-82f1-412f-bb8d-4ce7ddb16e31.jpg)

Day 12 - Scale :balance_scale:	

Did you know? Pangolins are the only mammal covered head to toe by scales!

I took today's theme as an opportunity to do a play on words and spotlight one of my favorite creatures, #Pangolins, which unfortunately also happen to be the world's most trafficked mammal.

Learn more about Pangolins and how you can help save them [here](https://wildaid.org/three-ways-you-can-help-us-protect-pangolins/)

P.S. Pangolin cutie drawn by Céline Oberholzer. You can checkout her artwork [here](https://www.instagram.com/celineslines/)

![Day 12 Map](https://user-images.githubusercontent.com/92735518/202027204-ae4d04c8-97fe-441c-8aa7-031d6dce1081.jpg)

Day 13 - 5 minute map ⏱️

Street network of Chicago in honor of growing up near the incredibly city. However, I sure don't miss Chicago traffic...

![Chicago](https://user-images.githubusercontent.com/92735518/202027420-8341fb12-c347-4b52-8a29-a82083c8a588.png)

Day 14 - Hexagon & Day 15 - Food & Drink :doughnut:

I was running low on time and running out of mapping energy so I combined Day 14 & Day 15. 

One of the first things I learned about when I moved to the U.S. was the Dunkin' + Starbucks craze! Are you a Dunkin' or Starbucks fan (I am neither 😆)?

![Day 15 map](https://user-images.githubusercontent.com/92735518/202028748-5083d143-5fc7-4255-9bb5-44e643e9c070.jpg)

Day 16 - Minimalist

I was born near Zurich, Switzerland!

My original plan to make a pretty map of the Zurich city center using #inkscape for the first time didn't go according to plan, so here is my "I'm too tired to keep mapping" version...

![Day 16 Map](https://user-images.githubusercontent.com/92735518/204320271-09b0469c-ac72-4fc8-bd94-9fe89a7f4bd5.jpg)

Day 17 - Map without a computer

I am crazy about climbing, specifically bouldering.

Here’s a picture of the map in the New River Gorge (West Virginia) bouldering guidebook, my favorite climbing spot in the world!

![1668702516930](https://user-images.githubusercontent.com/92735518/204320957-d6c82393-0b4a-441d-adaf-d08313dce6bc.jpg)

Day 18 - Blue

I made my first interactive #Plotly map with #Python. It's not as polished as I'd like it to be but I learned a ton making it!

You can check it out [here](https://aliciaoberholzer.github.io/2022-Police-Shootings/).

This map was inspired by the work that the The Washington Post has been doing to increase transparency about police brutality, learn more [here](https://lnkd.in/gyeKs3yT). 

![police](https://user-images.githubusercontent.com/92735518/204321391-d3e3a5e4-5c62-4285-b434-8e051df76341.png)

Day 19 - Globe 🌍

Running a day behind because getting acquainted with #blender & halfway through a 20-minute tutorial took me more than a whole day, so here is a halfway done globe 🥲.

I always underestimate the learning curve associated with applying new tools!

![Day19](https://user-images.githubusercontent.com/92735518/204322855-26cda262-649c-4d5e-828b-7cf0d3bab79b.png)

Day 20 - my favorite...

My favorite...animal is a sloth!

Sloths are extremely vulnerable to deforestation & the pygymy three-toed sloth in particular is critically endangered. Learn more about how cool sloths are [here](https://lnkd.in/gNgFJPR3)

The sloth graphic was brought to life by Céline Oberholzer, checkout her artwork [here](https://lnkd.in/gmtkCPCw)

![Day 20 Map](https://user-images.githubusercontent.com/92735518/204323009-11382d2e-6ee3-4feb-8ab6-78b7ecfca27e.jpg)

Day 21 - Kontur Population Dataset

This map was inspired by my time living in WV with health issues.

I had to go to the ER once and it took over a 30-minute drive to get there, which got me interested in emergency health service accessibility in rural America.

I'd really like to improve upon this map by layering socioeconomic data, as well as using driving distances / times instead of nearest hub distance from centroids of the 400-meter hexagons (which is what I did here). I'd be grateful for any constructive feedback!

![Day 21 Map](https://user-images.githubusercontent.com/92735518/204323083-b397dd05-6780-48f3-90a5-687751ef7aa2.jpg)

Day 22 - Null

This map was inspired by a recent [article](https://lnkd.in/grsTUjPU) written by the United Nations about how countries' efforts to tackle climate change are not enough to limit global temperature rise to 1.5 degrees celsius by the end of the decade.

![Day 22 Map](https://user-images.githubusercontent.com/92735518/204323153-697a57dd-2dbe-4a3d-a367-9a8bf62f55e2.jpg)

Day 23 - Movement

A timelapse version of my day 4 map about forest cover loss in the Democratic Republic of the Congo . I realize now that I should have replaced the basemap to make the loss standout more 😪 (lesson learned).

![](https://github.com/aliciaoberholzer/30DayMapChallenge/blob/main/Day%2023%20GIF.gif)

Day 24 - Fantasy

My fantasy map didn't go according to plan so I present to you...my last resort.

I'm not proud of this.

![Slothfinal2](https://user-images.githubusercontent.com/92735518/205762963-e253370e-ca30-40ae-b822-2606150588c1.png)

Day 25 - 2 colors 

My first bivariate choropleth map is based upon an analysis on gun law strength & gun violence rates in the U.S. conducted by Everytown Research & Policy. 

Let me know what you think - I am always open to constructive feedback.

![Day 25 Map](https://user-images.githubusercontent.com/92735518/205763062-7b5a96a9-fe12-456b-94e1-81220719ebf3.jpg)

Day 26 - Islands :desert_island:

I made a Google Earth Engine app that explores Puerto Rico night light intensity following Hurricane Maria in 2017 - it took ~11 months to restore power to all households who lost it:

[Check out the app here](https://lnkd.in/gRAvfVEY)!

This app was inspired by the [work](https://lnkd.in/gFQeQnti) NASA - National Aeronautics and Space Administration did to track power outages for disaster recovery in Puerto Rico following Hurricane Maria using its Black Marble product suite.

I welcome any feedback on the app and will also share the code in my GitHub soon! Learning JavaScript was not the plan, but there are so many free Google Earth Engine resources available via NASA - National Aeronautics and Space Administration's Applied Remote Sensing Training Program, so it was really approachable.

There were a couple things I couldn't figure out, such as getting the labels to appear on top of the selected night light layer 🥲 sometimes done is better than perfect...

<img width="1440" alt="Screen Shot 2022-12-19 at 8 51 19 PM" src="https://user-images.githubusercontent.com/92735518/208570443-b36768dc-f973-43f7-b704-1d33765b053d.png">


