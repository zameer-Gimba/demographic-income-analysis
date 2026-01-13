# Demographic Income Analysis

## Overview
This project explores demographic factors associated with income levels using a structured census-style dataset. The focus is on analyzing patterns in education, work hours, race, and geographic location.

## Dataset
The dataset is not included in this repository.  
A placeholder folder exists at `data/raw/` for the original dataset if available.  

> The dataset is extracted from the 1994 U.S. Census database, often called the "Adult Income Census" dataset. It contains anonymized demographic and employment information (like age, education, work class, capital gains/losses, native country) for individuals to predict if their annual income exceeds $50,000. Curated by Barry Becker and Ronny Kohavi from the UCI Machine Learning Repository, it is widely used for data pre-processing and machine learning practice.

## Questions Answered
- Race distribution
- Average age of men
- Percentage with Bachelor's degrees
- Percentage of people with advanced education earning >50K
- Percentage of people without advanced education earning >50K
- Minimum hours worked per week
- Percentage of minimum-hour workers earning >50K
- Country with the highest percentage of >50K earners
- Most popular occupation for those earning >50K in India

## Tools
- Python
- Pandas

## Usage
Place the dataset in `data/raw/` as `adult_data.csv` and run:

```bash
python src/analysis.py
