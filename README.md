<p align="center">
  <img width="250" height="250" src="https://github.com/a-pradono/national_park_indonesia/blob/main/images/header.jpg">
</p>
<p align="center">
Photo by <a href="https://unsplash.com/@rizknas?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Rizknas</a> on <a href="https://unsplash.com/photos/brown-mountain-beside-body-of-water-during-daytime-tqvF1JXzOxs?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
</p>


## Table of Contents

- [I. Introduction](#i-introduction)
- [II. Data and Methodology](#ii-data-and-methodology)
- [III. Results](#iii-results)
- [IV. Conclusions](#iv-conclusions)

## I. Introduction
Indonesia is an archipelago located in Southeast Asia, home to more than 50 national parks spread across thousands of islands. Each park offers its own unique experiences, including tropical rainforests, active volcanoes, and rich marine ecosystems. However, many people are familiar with only a few of them. Therefore, the purpose of this project was to examine how these national parks are geographically spread throughout the country.

## II. Data and Methodology
In this project, the data is obtained from [Wikipedia](https://en.wikipedia.org/wiki/List_of_national_parks_of_Indonesia) website, specifically from the listing of national parks in Indonesia. To ensure accuracy, the information has been validated from several references, making the dataset reliable for further analysis.

<p align="center">
  <img width="400" height="200" src="https://github.com/a-pradono/national_park_indonesia/blob/main/images/workflow.png">
</p>

The workflow above demonstrates how to achieve the objective of this project. First, web scraping has been used to retrieve information on 57 national parks in Indonesia. After data cleaning and preprocessing, geocoding with Nominatim was applied to automatically determine the province or region for each national park based on its latitude and longitude coordinates. This step enriched the dataset with administrative locations, enabling spatial analysis and data visualization.

## III. Results
The first figure below shows that Sumatra has the highest amount of national parks compared to other islands, while Maluku has the fewest. 

<p align="center">
  <img width="700" height="400" src="https://github.com/a-pradono/national_park_indonesia/blob/main/images/plot01.png">
</p>

In terms of proportions, Sumatra (22.8%) and Java (21.1%) hold the largest shares of national parks, followed by Sulawesi and Bali and Nusa Tenggara (15.8% each), Kalimantan (14%), Papua (7%), and Maluku (3.5%).

<p align="center">
  <img width="500" height="500" src="https://github.com/a-pradono/national_park_indonesia/blob/main/images/plot02.png">
</p>

To make the data easier to explore, an interactive visualization was developed to enhance clarity and improve user's ability to filter national parks by island.

<p align="center">
  <img width="700" height="600" src="https://github.com/a-pradono/national_park_indonesia/blob/main/images/plot03.gif">
</p>

## IV. Conclusions
The objective of this project was to explore the distribution of national parks in Indonesia through web scraping and data analysis. These are the conclusions drawn from this project:
  * Web scraping, data preprocessing, and geocoding improves automate and simplify the workflow in building a comprehensive national park dataset.
  * The results highlight clear geographic patterns, demonstrating how data science and geospatial analysis can be used to understand the distribution of national parks across Indonesia.
