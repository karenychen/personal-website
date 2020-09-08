---
title: Elevator Simulation
summary: A system that simulates moving algorithms of elevators with different arrival algorithms of passengers.
tags:
- Python
- Coursework
- Individual Project
date: "2018-10-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Russ Ward on Unsplash
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
Elevator Simulation was a course project from Introduction to Computer Science (CSC 148) in Fall 2018. The program simulates elevators' movement in pygame given the number of elevators and floors along with one of the moving and arrival algorithms below.

There are three moving algorithms in the simulation: 

- Random Moving Algorithm: An algorithm that picks a random direction for each elevator.
- Pushy Passenger Algorithm: An algorithm that preferences the first passenger on each elevator.
- Short-Sighted Algorithm: An algorithm that preferences passengers with the closest possible destination.

There are two arrival generators in the simulation:

- Random Arrival Generator: An algorithm that generates a fixed number of passengers on random floors.
- File Arrival Generator: An algorithm that generates arrivals from reading a csv file