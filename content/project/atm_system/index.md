---
title: Automated Teller Machine System
summary: An interactive Automated Teller Machine system that enables the user to create and interact with different types of accounts.
tags:
- Java
- Coursework
- Group Project
date: "2019-04-02T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Mirza Babic on Unsplash.
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
Automated Teller Machine System was a group project from Software Design (CSC 207) in Winter 2019. The program implements the Model-View-Controller design pattern and interacts with users by displaying options on a GUI for users to select.

Every user can log on to the system using a username and password. They are able to view and interact with their accounts.

When a user requests the creation of a new account, they can choose their new account's type from a variety of debt accounts and asset accounts, such as a credit cards account or a savings account. All account creation requests will be sent to the bank manager, and the bank manager can choose to accept or decline the account creation request. 

After an account has been created, the user of the account is then able to view account balance, transfer money into or out of the account, view and request to undo the most recent transaction, as well as deposit by cheque or cash into the account and withdrawing cash from the account. 

The bank manager also logs on to the system using a username and password. The bank manager handles all account-related requests and restocks cash for the machine when any denomination runs low. 