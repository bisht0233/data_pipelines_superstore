-------------------------------------------------------------- data_pipelines_superstore------------------------------------------------------------------------------------
I built this project to turn the messy, flat Superstore CSV into a structured database ready for real analysis. Instead of just working with the original file, I wrote an ETL pipeline to clean the data and load it into a SQL database using a Star Schema.

-Why I did this
When you download a big dataset, it’s usually hard to work with. It has duplicates, missing info, and it’s all in one massive file. I wanted to build a little system that cleans that up automatically so it’s actually useful for finding answers later.

-How it works
Cleaning things up: I wrote a Python script that goes through the file, fixes missing gaps, and deletes duplicate entries so the data is accurate.

Organizing the data: Instead of keeping everything in one giant file, I split the information into smaller, logical groups (like separating customer info from product info). This makes it way easier to look up specific details without getting lost in the spreadsheet.

The "System": I set up a small, automated process (an ETL pipeline) that takes the file and processes it step-by-step, logging what it does along the way so I know if anything goes wrong.

Tools used
python(pandas,logging)
library-sqlite3

auther by
sanjay singh bisht

credit to kaggle community
website link:https://www.kaggle.com/datasets/bravehart101/sample-supermarket-dataset




