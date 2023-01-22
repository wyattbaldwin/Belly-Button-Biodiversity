# Belly Button Biodiversity

## Overview
This project utilizes Plotly.js, a JavaScript data visualization library, to create an interactive data visualization for the web. The visualization allows users to explore the types of bacteria that colonize the belly button of volunteers.

## Aim
The goal of this project is to create an interactive webpage that allows readers to parse Belly Button Biodiversity data.

## Results
Using JavaScript and HTML, data was retrieved from an external JSON file. Methods such as map() and filter() were used to iterate through objects and arrays to retrieve necessary data. An interactive webpage was created that allows the reader to parse the data by selecting an individual’s ID from the dropdown menu.

For each ID, the following were created:

A panel displaying demographic information such as ID, ethnicity, gender, age, location, bbtype and wfreq.
A horizontal bar chart displaying the top 10 bacterial species (OTUs).
A bubble chart displaying Bacteria cultures per sample.
A gauge chart displaying the weekly washing frequency's value (wfreq).
HTML and Bootstrap were used to customize the webpage by:

Adding an image to the jumbotron.
Adding a background color to the webpage.
Using a custom font with contrast for the colors.
Adding user instructions at the top of the page.
When the dashboard is first opened in a browser, ID 940’s data is displayed in the dashboard and the three charts display data related to ID 940.

## Outcomes vs. Goals
The interactive dashboard was built successfully and allows for exploration of the Belly Button Biodiversity data in a visually appealing and dynamic way. However, making the webpage mobile responsive would be an interesting next step.