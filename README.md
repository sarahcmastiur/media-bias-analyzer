# media-bias-analyzer
The Media Bias Analyzer helps users identify media bias by comparing how major outlets report on the same news events.  By analyzing sentiment, tone, and framing, the tool reveals differences in how each outlet covers a topic. 


## File Directory Overview

    media-bias-analyzer/
    ├── data/      # Scraped JSON file
    │   └── Output_Guardian
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
