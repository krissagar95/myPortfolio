+++
# Date this page was created.
# date = "2016-04-27"

# Project title.
title = "Data Driven Extraction for Challenging Situations for Autonomous Vehicles"

# Project summary to display on homepage.
summary = "Using vehicle sensor data to predict the behaviour of vehicles when they face challenging situations to train autonomous vehicles and to set standards to deploy them in future."

# Optional image to display on homepage (relative to `static/img/` folder).
# image = "static/img/tesla.jpg"

# Optional image to display on project detail page (relative to `static/img/` folder).
# image = "tesla.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Masters"]

# Optional external URL for project (replaces project detail page).
# external_link = ""

# Does the project detail page use math formatting?
# math = false

+++
Autonomous vehicles or Self-Driven Vehicles (SDVs) are becoming increasingly common in Singapore and for a wide variety of applications – from first-and-last-mile commutes to logistics. The areas of deployment are similarly diverse, ranging from docks to housing estates and highways. This variance in operating environments necessitates careful validation and analysis of SDVs in contextual situations before deployment.
To support the Land Transport Authority's (LTA) development of test requirements and standards to deploy AVs in Singapore, NTU led the Centre of Excellence for Testing & Research of AVs – NTU (CETRAN). While CETRAN does not directly develop new technologies for AVs, it generates fundamental research on how these systems should operate, develop testing requirements, and establish an international standard for AVs. 
CETRAN houses an expert research team formed by NTU that performs testing in a computer-simulated environment representative of Singapore's traffic conditions, to complement the tests being performed in the test circuit. In order to create realistic tests which correspond as closely as possible with traffic situations occurring on Singapore roads, 15000 km of driving data has been collected and analyzed over a course of 2 years (including video and vehicle dynamics), and 20000 labelled situations have been identified in conjunction with CETRAN.

I was provided a subset of the total driving data containing video recorded using front and back cameras, as well as vehicle dynamic data from the Controller Area Network bus (CANbus) containing various signals, such as GPS location, velocity, orientation, yaw rate, etc. Additionally, I had access to event labels which have been manually annotated by a trained team of dedicated labelers. The goal my research was to train machine learning algorithms to automatically extract two specific situations from the collected data. The resulting algorithm was validated in comparison with the manually annotated labels. The resulting work was of great value to CETRAN, allowing them to scale up the data analysis over a much larger database.
