---
title: "Zephyr Storm Probe"
date: 2026-06-12
layout: "full-width"
summary: "Information Regarding Serge's Zephyr Mobile Deployment Probe"
draft: false
tags: ["Probes"]
---

### Zephyr is our newest creation from the Serge team, the name being one of our old team name ideas.

### Goal of Zephyr

Zephyr aimed to fix all of the issues that came from the first probe built by our team. The extremely flaky structure, data not saving properly, the poor engineering leading to things constantly breaking. While we held the WSMP close in our hearts, the flaws were extremely apparent all the time. When WMSP sadly had its last deployment, it was clear that we could make something many times better.

Zephyr does exactly that. The first main difference is the extremely different build compared to the first. Instead of using 3D prints and PVC pipe, it is made entirely of metal, and mostly iron steel. The bottom of the probe consists of a 3/8 thick steel plating, and bars of stainless steel to insulate the electronics. The heavy weighting from the plate keeps the center of mass low, and the design makes it easier to pick up than you would think. Instead of embedding the computer in the middle, it's accessible through a metal junction box mounted on the outside. This solves one of our BIGGEST issues from the WMSP, no longer needing to remove an entire section of the probe to access our electronics!

### Zephyr's Setup

Sensor wise, we brought over the BME280 and the SGP30 from the WMSP probe, along with introducing the SEN 15901 weather station. This additional sensor will allow us to collect wind speed, wind direction, and precipitation rates of storms. These environmental variables are extremely valuable and are used extensively in cataloguing storms. We hope to contribute as much as possible with this new sensor.

Under the hood, the program has been redone from the ground up. There were many issues with the software for the WMSP. Issues included needing a manual connection to a monitor/mouse to start the probe, not getting information live, having no indication if it was successfully running, data being wiped if the pi ended incorrectly, and much more. The new one blows the old one out of the water, fixing all of these issues and then some. The new probe can connect to our PC's and start running all by the click of a single command. It also now sends the live data to a server to be backed up during the chase, just in case another piece of rebar decides to choose the probe as its home. It now also saves all the data as an extremely readable database, allowing for easier extracting of information. All of this while being a lot faster and more reliable on the raspberry pi in the probe.

### Zephyr's Data View

Our goal is to make all the data from the probe as accessible as possible. We want the data that we collect to be used for everything it possibly can be. Ranging from integration with the National Weather Service's forecasting models, to the data being used in an aspiring middle schooler's weather project. We strive hard for our creations to bring a positive influence into the world, and we hope that this probe can do so.

The live data feed from Zephyr will be visible to all of you on a website. At the time that you're reading this, the website has not been fully completed yet (our apologies!) This page will be updated with the link when the live data feed can be viewed.

Zephyr is still a work in progress, with the team constantly figuring out innovative ways to expand on what it can currently do. One thing is for certain, it is a massive upgrade from the previous project that was done by our team, and we are so proud to have been able to make it.