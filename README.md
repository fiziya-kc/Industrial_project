# Industrial_project
T20 World Cup Cricket Data Preprocessing
This project focuses on preprocessing T20 World Cup cricket data, including match results, batting summaries, bowling summaries, and player information. The goal is to prepare the data for further analysis and insights.

Overview
The preprocessing steps include:

Processing match results data to create a summary dataframe and a match ID dictionary for linking with other tables.
Processing batting summary data and performing transformations such as categorizing 'out' and 'not out', and removing special symbols.
Connecting the match results and batting summary tables using the match ID dictionary.
Processing bowling summary data and linking it to the match results.
Processing player information data.

File Structure
t20_JSON_FILES/: Contains JSON files for match results, batting summaries, bowling summaries, and player information.
t20_CSV_FILES/: Contains CSV files for processed data.
README.md: This file providing an overview of the project.

Usage
To use this project, follow these steps:
Ensure you have the necessary libraries installed (Pandas).
Run the Python script preprocess_data.py to preprocess the JSON files.
Check the t20_CSV_FILES/ directory for the processed CSV files.

Dependencies
Pandas
JSON

Author
[Fiziya Kausaar Chuhe]
