---
title: "Fusing Map Information with a Probabilistic Sensor Model for Indoor Localization Using RF Beacons"
collection: publications
excerpt: 'Novel sensor fusion models for location classification that counter traditional approaches of mapping RSSI to distance.  Further contributes new techniques for extending particle filter approach to leverage map information. '
permalink: /publication/2018-09-24-fusing-map-information
date: 2018-9-24
venue: 'International Conference on Indoor Positioning and Indoor Navigation (IPIN)'
citation: 'Patel, M., Girgensohn, A. & and Biehl, J.T. &quot;Fusing Map Information with a Probabilistic Sensor Model for Indoor Localization Using RF Beacons,&quot; <i>International Conference on Indoor Positioning and Indoor Navigation (IPIN)</i>, Nantes, 2018, pp. 1-8.'

---
Accurate localization is a fundamental requirement for a variety of applications, ranging from industrial robot operations to location-powered applications on mobile devices. A key technical challenge in achieving this goal is providing a clean and reliable estimation of location from a variety of low-cost, uncalibrated sensors. Many current techniques rely on Particle Filter (PF) based algorithms. They have proven successful at effectively fusing various sensors inputs to create meaningful location predictions. In this paper we build upon this large corpus of work. Like prior work, our technique fuses Received Signal Strength Indicator (RSSI) measurements from Bluetooth Low Energy (BLE) beacons with map information. A key contribution of our work is a new sensor model for BLE beacons that does not require the mapping from RSSI to distance. We further contribute a novel method of utilizing map information during the initialization of the system and during the resampling phase when new particles are generated. Using our proposed sensor model and map prior information the performance of the overall localization is improved by 1.20 m on comparing the 75th percentile of the cumulative distribution with traditional localization techniques.

DOI: [10.1109/IPIN.2018.8533758](https://doi.org/10.1109/IPIN.2018.8533758)
