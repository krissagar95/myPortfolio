+++
# Date this page was created.
# date = "2016-04-27"

# Project title.
title = "Density Based Traffic Control System"

# Project summary to display on homepage.
summary = "Use of Image Processing to determine the number of vechiles in each road at a jucntion to manage traffic."

# Optional image to display on homepage (relative to `static/img/` folder).
# image = "static/img/tesla.jpg"

# Optional image to display on project detail page (relative to `static/img/` folder).
# image = "tesla.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["UG"]

# Optional external URL for project (replaces project detail page).
# external_link = ""

# Does the project detail page use math formatting?
# math = false

+++
There are many ways in which fire can break out on your property. In most cases, we can mitigate the fire damage and avoid explosions if we do the following. Firstly, alerting the fire department and owner no matter where they are. Secondly, disconnecting power to the property before sprinklers start to prevent explosions. Keeping these scenarios in mind, we designed Smart 101, a GSM-based fire alarm module that alerts the fire station and owner using alert messages, no matter where they are.

It works on code developed over an atmega-320p microcontroller and monitors the data received from smoke and temperature sensors, calibrated according to the environment. The microcontroller serially relays the alert signal to a GSM Sim 900 module to send alert notifications to the registered numbers. In addition to this, the microcontroller also relays the control signal to a magnetic relay switch. It toggles the primary power connection to the house, thereby reducing the risk of an explosion.


Main Project:

As a day scholar, traveling to college on my bike was the daily norm. The stagnant junction traffic close to my campus inspired me to develop this project. The local road authority sets the timer for each road at a junction based on extensive study on the area's traffic behavior. But the trend of traffic varies according to time of the day. Failing to update the road timers regularly, based on the traffic trends, leads to jams. My team and I developed a foolproof system that utilizes techniques like image thresholding and morphological processing to determine the number of vehicles in a road's image to tackle this issue. 

The system houses a 360 camera mounted on top of the junction center to capture roads' real-time images. I built a tool on MATLAB to import the road images and process them as follows. My tool converts each road image into a binary image using grayscaling and double thresholding. The tool then subtracts a pre-loaded binary image of the road from the current binary image. Thus, we obtain an image whose total number of pixels denotes the vehicles on the road. This number is known as road density.

Consequently, we find the road density of the remaining roads. The tool then arranges the road labels in descending order of road densities. A microcontroller receives the road label sequence and assigns a more extended time slot according to the order of road labels. The system also detects ambulances to give way in case of emergencies.

Impressed by our project and its social relevance, the CENTRE FOR ENGINEERING RESEARCH AND DEVELOPMENT(CERD) funded the project.





    
  
