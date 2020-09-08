---
title: Autocomplete Engine
summary: An autocomplete engine that suggests strings or melodies based on a few letters or intervals.
tags:
- Python
- Coursework
- Individual Project
date: "2018-11-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Benjamin Dada on Unsplash. <br> Google and the Google logo are registered trademarks of Google LLC, used with permission.
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
Autocomplete Engine was a course project from Introduction to Computer Science (CSC 148) in Fall 2018. The program suggests strings or melodies based on a few letters (for strings) or intervals (for melodies).

The letter/sentence autocompleter reads from a formatted txt or csv file and stores the information in a prefix tree implementation. The engine then takes a string from the client and returns all suggestions based on the string along with the number of occurrences of each suggestion in the file.

The melody autocompleter reads from a formatted csv file and stores the information in a prefix tree implementation. The engine then takes a list intervals and plays all melodies based on the input list.