
# LAPD Crime Data Analysis

![LAPD Crime Data Analysis Banner](https://images.jems.com/wp-content/uploads/2023/03/LAPD-Officers-Killed.jpg)

## Overview

This project provides an in-depth analysis of crime data in the City of Los Angeles from 2020 onwards, using data sourced from the LAPD API. The main objective is to identify patterns, trends, and insights that could be valuable for various stakeholders, including law enforcement, tourism agencies, and the general public.

## Table of Contents

- [Dataset Description](#dataset-description)
- [ELT Process](#elt-process)
- [Data Analysis Highlights](#data-analysis-highlights)
- [Conclusions](#conclusions)
- [Learnings](#learnings)
- [Technologies & Libraries](#technologies--libraries)
- [Contributors](#contributors)

## Dataset Description

The dataset used for this analysis is fetched from the LAPD API, reflecting incidents of crime in the City of Los Angeles dating back to 2020. This dataset is stored in a MongoDB collection for efficient querying and analysis.

## ELT Process

1. **DB Setup:** Initialization of the MongoDB database and collection for storing crime data.
2. **Extract:** Retrieval of data from the LAPD API in batches.
3. **Load:** Storing the fetched data in MongoDB.
4. **Transform:** Applying necessary transformations for data consistency and integrity.

## Data Analysis Highlights

- Identification of the most common types of crimes reported.
- Analysis of the top 15 weapons used in crimes.
- Breakdown of crime incidents based on the descent and gender of victims.
- Time-based analysis of crime occurrences.
- Geographical heatmap visualizing crime concentration across the city.

## Conclusions

The analysis provides insights into crime patterns in Los Angeles, highlighting potential hotspots, frequent crime timings, and common crime characteristics. These findings can assist stakeholders in decision-making, safety measures, and resource allocation.

## Learnings

The project offered valuable experience in data extraction, storage, and analysis, particularly with tools like MongoDB and Jupyter Notebook. It also emphasized the importance of data-driven decision-making in urban environments.

## Technologies & Libraries

- **Database:** MongoDB
- **Analysis & Visualization:** Python, Jupyter Notebook, Pandas, Matplotlib, Seaborn
- **Data Retrieval:** LAPD API, Python's `requests` library

## Contributors

- Bahram Khanlarov
