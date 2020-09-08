---
title: Database Design for Vacation Rental Application
summary: A database design in SQL for a vacation rental application, written in Data Definition Language.
tags:
- SQL
- Coursework
- Individual Project
date: "2019-12-04T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Wiktor Karkocha on Unsplash.
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
The database design was a course project from Introduction to Databases (CSC 343) in Fall 2019. It is a back-end database for a vacation rental application in SQL's Data Definition Language. The database aims to avoid as much redundancy as possible while effectively represents the data and enforces the constraints below. 

Guests rent properties that each have a single host. Renting is only by the week, and can be for any number of weeks. Each property can have a different price, and its price can be the same for all weeks,
but it can also be different.

For all properties, a week is defined to start on a Saturday. Each property has its own number of bedrooms, number of bathrooms, capacity, and address. The capacity of the property is at
least the number of bedrooms.

Every property also includes one or more luxuries from this list: hot tub, sauna, laundry service, daily cleaning, daily breakfast delivery, and concierge service. The price for a week is all-inclusive and there are no extra charges.

Some properties are considered to be city properties and some are considered to be on the water. It is possible that a property is both a city property and a water property.

City properties have a walkability score (0 to 100) and the closest transit (either bus, LRT, subway, or none). Water properties have a water type (either beach, lake, or pool), and may or may not provide lifeguards. A water property can have multiple water types. 

In each rental, one guest is the renter and has responsibility for paying and taking care of the property. They must be at least 18 years old on the first day of the rental. The renter can have 0 or more other guests registered to use the property with them. These guests are registered for the whole
rental.

The number of guests in each rental (including the renter) must not exceed the property's sleeping capacity. Every guest has a name, address, and date of birth recorded, and the renter additionally has to provide a credit card number.

Guests can optionally rate the property with 0 to 5 stars. Hosts can also be rated on the same star system, but only the renter can rate the host. All guests may also leave a comment, but only if they have rated the property.

