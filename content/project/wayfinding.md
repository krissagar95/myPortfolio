+++
# Date this page was created.
# date = "2016-04-27"

# Project title.
title = "Smart 101"

# Project summary to display on homepage.
summary = "A product that alerts the owner and the nearest fire-station if fire breaks out and also cuts home electricity"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "media/tesla.png"

# Optional image to display on project detail page (relative to `static/img/` folder).
# image = "tesla.png"

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

  
