# media-bias-analyzer
Media Bias Analyzer is a data-driven dashboard that helps users detect bias across news articles from major outlets including The Guardian, The New York Times, and Fox News. By leveraging structured data pipelines, sentiment analysis, and interactive filtering, this tool offers transparency into how the media frames topics in politics, education, and the environment.

##  Features

- Bias Visualization: Compare tone and framing across media outlets by category and issue

- Sentiment & Emotion Tagging: Analyze polarity and emotional tone using VADER and TextBlob

- Real-Time Exploration: Search by topic, date, and sentiment to uncover hidden patterns

- Article Metadata Insights: Extract title, author, abstract, and publication date per outlet

- Structured + Unstructured Storage: Uses PostgreSQL and MongoDB for optimized access


## Tech Stack
Data Sources: New York Times API, Guardian API, NewsAPI

Languages: Python (Pandas, Requests)

Analysis: VADER, TextBlob, Zero-shot classification

Storage: PostgreSQL (structured), MongoDB (unstructured)

Dashboard: Streamlit



## File Directory Overview

    media-bias-analyzer/
    ├── data/      # Scraped JSON file
    │   └── Output_Guardian
    │   └── Output_NYT
    │   └── Output_NewsApi (Fox)
    ├── src/
    │   └── webscraping
    │   └── Final_Page1.ipynb  # streamlit page 1
    │   └── Final_Page2.ipynb  # streamlit page 2
    │   └── Final_Page3.ipynb  # streamlit page 3
    │   └── Final_Storing_database.ipynb  # mongodb database
    │   └── combining_json.ipynb          # news agency JSON consolidation
    │   └── sqltable_creation.ipynb       # sql database
    ├── README.Rmd             # This file


#### Note: This project is intended for educational use only. All data sourced via public APIs in compliance with their respective terms.
