
# Eat Safe, Love Data Analysis
## Introduction
This project focuses on analyzing data related to food establishments in the UK. It includes two Jupyter notebooks:
- **NoSQL_setup_starter.ipynb** for setting up the database and 
- **NoSQL_analysis_starter.ipynb** for exploratory data analysis.

## Setup Instructions
### Database Setup:
1. Ensure you have MongoDB installed on your system.
2. Import the provided dataset establishments.json into MongoDB using the following command in your Terminal:

mongoimport --type json -d uk_food -c establishments --jsonArray establishments.json

### Jupyter Notebook Setup:
Ensure you have Jupyter Notebook installed, preferably in a virtual environment.
Install the required dependencies by running:
* pip install pymongo pandas

### Open Notebooks:
Launch Jupyter Notebook and open both NoSQL_setup_starter.ipynb and NoSQL_analysis_starter.ipynb to run the provided code and perform the analysis.
## Notebook Summaries
### NoSQL_setup_starter.ipynb
**Part 1:** Database and Jupyter Notebook Set Up:

Import data into MongoDB and set up database connections.

**Part 2:** Update the Database:

Add new establishments, update existing records, and remove undesired data.

**Part 3:** Data Type Conversion:

Convert string data to numeric data for specified fields.

### NoSQL_analysis_starter.ipynb
**Notebook Set Up:**
Establish connection to the MongoDB database.

**Exploratory Analysis:**
Perform various data analysis tasks using MongoDB queries and Pandas DataFrame operations.

