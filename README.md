# Rotten Tomatoes TV Shows Analysis

A comprehensive web scraping and data analysis project that extracts TV show information from Rotten Tomatoes and performs exploratory data analysis.

## Overview

This project scrapes TV show data from Rotten Tomatoes including show names, ratings, scores, genres, networks, and other metadata, then performs detailed analysis to uncover insights about the entertainment industry.

## Features

- **Web Scraping**: Automated extraction of TV show data from Rotten Tomatoes
- **Data Processing**: Handles missing data, URL formatting, and data validation
- **Comprehensive Analysis**: 
  - Network distribution and performance
  - Genre popularity and ratings
  - Language distribution analysis
  - Critics vs audience score comparisons
  - Rating system analysis (TV-MA, TV-PG, etc.)
- **Visualizations**: Multiple charts and graphs showing key insights
- **Data Export**: Saves results to CSV format

## Requirements

```
pandas
requests
beautifulsoup4
matplotlib
seaborn
plotly
lxml
time
re
numpy
```

## Installation

1. Clone this repository
2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter notebook: `Rotten Tomatoes Analysis - Copy.ipynb`
2. Run all cells to execute the scraping and analysis
3. The script will:
   - Scrape TV show data from Rotten Tomatoes
   - Process and clean the data
   - Generate visualizations and insights
   - Export data to `TV_Shows.csv`

## Key Insights Discovered

- **Content Rating**: 76.3% of TV shows are rated TV-MA (mature content)
- **Language Distribution**: 90.2% of shows are in English variants
- **Genre Performance**: Anime and documentaries receive highest ratings from critics and audiences
- **Network Analysis**: Netflix leads in content volume with diverse genre distribution
- **International Content**: Shows in international languages score higher on average

## Data Structure

The scraped dataset contains 11 columns:
- Show Name
- Latest Episode Date
- Critics Score (%)
- Audience Score (%)
- Cover Image URL
- Synopsis
- Network
- Genre(s)
- Content Rating
- Language
- Release Date

## Project Structure

```
├── Rotten Tomatoes Analysis - Copy.ipynb  # Main analysis notebook
├── TV_Shows.csv                          # Generated dataset
├── README.md                             # Project documentation
└── requirements.txt                      # Python dependencies
```

## Ethical Considerations

This project is for educational purposes. 
