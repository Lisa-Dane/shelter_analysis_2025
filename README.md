**Animal Shelter Analysis with MongoDB**

**Project Description**

Analysis of Austin animal shelter intake data (2013-2025) using MongoDB for big data processing. Focuses on seasonal patterns in cat intakes.

**Files**

- shelter_analysis.ipynb - Complete analysis notebook
- shelter_intakes_data.csv - Raw dataset (173K+ rows)
- README.md - This file

Note: config.yaml is NOT included (contains database credentials). Create your own using the template below.

**Quick Start**

- Install: pip install -r requirements.txt
- Create config.yaml (see template below)
- Run: jupyter notebook shelter_analysis.ipynb
- config.yaml Template 

**Create a file called config.yaml with:**
  
    mongodb:
      uri: "your_mongodb_connection_string_here"
      database: "animal_shelter"
      collection: "cat_intakes"
    
Get a free MongoDB Atlas connection string at: https://www.mongodb.com/cloud/atlas
