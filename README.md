# Jose Moncada - Belly Button Biodiversity Dashboard

## Project Overview

This project provides an interactive dashboard to explore the **Belly Button Biodiversity** dataset, which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (Operational Taxonomic Units or OTUs) were present in more than 70% of people, while the rest were relatively rare.

The goal of this dashboard is to allow users to interactively explore the data and see various visualizations such as a bar chart, bubble chart, and metadata information based on the sample selected.

## Features

- **Bar Chart:** Displays the top 10 OTUs found in a selected sample.
- **Bubble Chart:** Shows the distribution of OTUs in a selected sample, with marker size and color representing the sample values and OTU IDs.
- **Metadata:** Displays demographic information (age, gender, ethnicity, etc.) of an individual based on the sample selected.
- **Dynamic Interaction:** Updates all charts and metadata when a new sample is selected from the dropdown menu.

## Deployment

The app is live and can be accessed through GitHub Pages:  
[Live App - Belly Button Biodiversity Dashboard](https://josemoncada91.github.io/belly-button-challenge/)

## Getting Started

### Prerequisites
To run the project locally, you'll need:
- A modern web browser (e.g., Chrome, Firefox, Safari).
- Internet access to fetch the dataset.

### Clone the Repository
Clone the repository to your local machine:
```bash
git clone https://github.com/JoseMoncada91/belly-button-challenge.git
cd belly-button-challenge

Technologies Used
HTML: For the structure of the webpage.
CSS: For styling the layout and charts.
JavaScript: For interactivity, data processing, and visualization.
D3.js: To load and manipulate the dataset and create interactive charts.
Plotly.js: For creating the bar chart and bubble chart.
GitHub Pages: For deploying the project online.

How the App Works
D3.js is used to load the samples.json file from a URL and process the data.
Bar Chart: Displays the top 10 OTUs based on sample values.
Bubble Chart: Visualizes the full OTU distribution in each sample.
Metadata: Displays the individual's demographic information (age, ethnicity, gender, etc.).
Interactive Dashboard: The visualizations update when a new sample is selected from the dropdown.
