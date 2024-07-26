# NoSQL Project: UK Food Hygiene Ratings Analysis

This project analyzes food hygiene ratings data from the UK Food Standards Agency to assist journalists and food critics from the magazine "Eat Safe, Love" in identifying establishments for future articles.

## Project Overview

### Part 1: Database and Jupyter Notebook Setup

- Set up the database and Jupyter Notebook environment.
- Loaded initial dataset of UK food hygiene ratings.

### Part 2: Update the Database

- Added a new halal restaurant, "Penang Flavours," in Greenwich to the database.
- Removed all establishments within the Dover Local Authority from the database.

### Part 3: Exploratory Analysis

The analysis addressed specific questions to guide "Eat Safe, Love" in their investigations:

1. **Hygiene Score Analysis**:
   - Identified establishments with a hygiene score of 20.
2. **Rating Value Analysis in London**:
   - Found establishments in London with a RatingValue of 4 or higher.
3. **Proximity Analysis to "Penang Flavours"**:
   - Listed the top 5 establishments with a RatingValue of 5, sorted by the lowest hygiene score, near "Penang Flavours."
4. **Local Authority Analysis**:
   - Counted the number of establishments in each Local Authority with a hygiene score of 0 and sorted the results from highest to lowest, highlighting the top ten areas.

## Files

- **NoSQL_setup.ipynb**: Contains the database setup, data update processes, and the exploratory analysis.

## Tools

- MongoDB
- Python
- Jupyter Notebook
- Pandas
- PyMongo

## Installation

To run the project, install the necessary Python libraries:

```bash
pip install pymongo pandas
