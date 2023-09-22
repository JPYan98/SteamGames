# Steam Games Sentiment Analysis

This project aims to scrape video game data from Steam, apply sentiment analysis to the reviews to gauge the general sentiment (positive or negative), and visualize the data for better understanding. 

The game analyzed is Plant vs. Zombies, but it can be changed to any other game easily. This repository contains the source code, datasets, and visualization outputs of this project.

## Objectives:

Acquire data about video games on Steam, including prices and reviews.
Conduct sentiment analysis on the reviews using only the text to categorize them as positive or negative.

Extract relevant data from Steam, such as:

The most popular games at the moment.

Tags and genres of the most popular games

Basic text mining to identify popular words.

Generation of Pandas CSV datasets from scraping results

Plotting and data visualization to represent the findings

## Libraries Used:

requests: To fetch web pages from the internet.

lxml: To filter information in HTML files using the XPATH language.

nltk: For applying Natural Language Processing techniques for sentiment analysis.

pandas: To manage datasets in CSV and other formats.

matplotlib: For data visualization.

numpy: a mathematical library to assist in plotting.



# Steam Video Games Popularity Analysis - 2023
This part aims to scrape and analyze the most popular video games listed on Steam, focusing on their tags and genres. By doing so, we gain insights into the current trends and preferences of the gaming community.

## Overview
We'll first scrape the top-selling games on Steam, then delve deeper into each game's page to extract tags and genres. Once this data is gathered, we'll save it into a CSV dataset for easy analysis. The final output provides us with a visual representation of the most popular tags and genres for 2023, using bar plots and bubble charts.

## How It Works

### Data Collection

Fetching Top Sellers: We send a request to the top sellers page on Steam. From this page, we extract the names and URLs of the games.

Deep Dive into Each Game: For every game URL, we request its webpage to scrape its associated tags and genres.


### Data Processing

Cleaning Data: Tags and genres are stripped of unnecessary whitespace and characters.

Storing Data: All the information (game name, game URL, tags, and genres) is stored in a structured format.


### Data Analysis

From Raw to CSV: Using the pandas library, we save our structured data into a CSV file named Steam_Most_Popular_Games_2023.csv.

Counting Tags and Genres: We read our CSV file to count the occurrences of each tag and genre across the top-selling games.

Visualization: The most popular tags and genres are plotted using matplotlib. Two types of plots are generated:

Bar plots: Showcasing the top 20 tags and genres.

Bubble charts: Representing all tags and genres with bubble size indicating their popularity.


## Results

The outcome will give us two visual plots:

### Bar Plots:
Provides a clear indication of the 20 most popular tags and genres.

### Bubble Charts:
Displays all tags and genres. The most popular ones have the largest bubble size.

These visual representations give game developers, marketers, and enthusiasts an understanding of current gaming trends, enabling them to make data-driven decisions.

# Note: Scraping may be illegal!

Extracting information from websites through bots is usually frowned upon on some websites; it can violate intellectual rights, privacy, and information access regulations. Therefore, it is very important before scraping to always verify that the website allows it. Each company has its own rules.
