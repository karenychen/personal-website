---
title: Temperature and Humidity Control System
summary: A control system that manages the real-time operation of a remotely connected air conditioner (AC) by reading the temperature and humidity sensor data, which are deployed in the environment.
tags:
- C
- Coursework
- Individual Project
date: "2019-12-05T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Wesley Tingey on Unsplash.
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
Temperature and Humidity Control System was a course project from Software Tools and Systems Programming in Fall 2019. The program is an implementation of parts of the functionality of a sample Internet of Things (IoT) software system. The system manages the real-time operation of a remotely connected air conditioner (AC) by reading the temperature and humidity sensor data deployed in the environment.

The system consists of 2 parts:

- Gateway Controller
- Humidity and Temperature Sensors

The gateway controller is mainly responsible for reading temperature and humidity sensors and adjusting the AC system accordingly. It establishes a TCP socket communication with each sensor and is able to multiplex between different connections. 

The humidity and temperature sensors simulate a real sensor's behaviour that reads the environment and reports the changes at a pre-defined frequency. They create and maintain a TCP socket communication with the gateway controller, and a new connection is made for each message sent to the gateway controller. 
