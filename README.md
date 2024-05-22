# NBA Player Statistics Scraper and Analysis

This repository contains tools for scraping and analyzing NBA player statistics. The project leverages Python, Jupyter Notebooks, and various libraries to gather, process, and analyze NBA data.

## Table of Contents

- [Project Overview](#project-overview)
- [Directory Structure](#directory-structure)
- [Installation](#installation)
- [Usage](#usage)
  - [Scraping Data](#scraping-data)
  - [Analyzing Data](#analyzing-data)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project consists of several Jupyter Notebooks that perform the following tasks:
1. **Scraping NBA Statistics**: Extracts player statistics from various sources.
2. **Cleaning and Processing Data**: Prepares the scraped data for analysis.
3. **Analyzing Player Performance**: Provides insights and visualizations based on the cleaned data.

## Directory Structure

├── 01_nba_stats_scraping.ipynb # Notebook for scraping NBA statistics
├── 02_nba_stats_scraping.ipynb # Continuation of the scraping process
├── 03_nba_analysis.ipynb # Notebook for analyzing NBA player statistics

├── nba_player_stats.csv # CSV file containing scraped NBA player statistics

├── pyproject.toml # Project configuration file

├── poetry.lock # Dependency lock file

└── README.md # Project documentation


## Installation

To set up this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/nba-stats-scraper.git
   cd nba-stats-scraper

2. **Install Dependencies**:
    ```bash
    poetry install

## Usage

1. **Open the Jupyter Notebooks**:

    ```bash
    poetry run jupyter notebook

2. **Run the scraping notebooks**:

Open 01_nba_stats_scraping.ipynb and 02_nba_stats_scraping.ipynb to run the scraping scripts. These notebooks will gather the data and save it to nba_player_stats.csv.

### Analyzing Data

1. **Open the analysis notebook**:

Open 03_nba_analysis.ipynb in Jupyter to run the data analysis scripts. This notebook includes various analyses and visualizations of the player statistics.


