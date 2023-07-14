+++
title = "Food Tracker"
date = 2020-03-10T12:00:00-05:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags: ["machine-learning", "deep-learning"]`
tags = ["web development", "javascript", "react"]

# Project summary to display on homepage.
summary = "A simple food tracking application focused on visualization."

# Optional image to display on homepage.
image_preview = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use source code highlighting?
highlight = true
+++

While I was following the University of Helsinki's [Full Stack Open](https://fullstackopen.com/en/) course, I decided one of the projects I should work on would be a food tracker. I have loosely used Fitbit's food tracking functionality since I am a Fitbit user. However, I intended the focus of the tracker to be visualizing various metrics / breakdowns of a user's diet. I settled on using [Nutritionix](https://www.nutritionix.com/business/api) for the nutrition lookup and [d3.js](https://www.d3js.org) for the visualization framework.

The application has basic functionality for logging in, logging an entry based either on entered information or UPC lookup (no barcode scanning), and charting the breakdown of calories by meal and macros.

[Frontend](https://github.com/mythWizard/foodtracker-frontend)

[Backend](https://github.com/mythWizard/foodtracker)

This project was inevitably abandoned. At the time, I was a tad frustrated with Fitbit's food tracking. So I thought I would engineer a solution I was happy with. I ended up discovering [Cronometer](https://cronometer.com), which I still use today.