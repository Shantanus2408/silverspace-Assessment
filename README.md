# silverspace-Assessment
Twitter Data Querying System Overview
This repository contains a system designed to ingest and query Twitter data related to Britney Spears. The goal is to allow users to analyze tweets by searching for specific terms and gathering various insights based on tweet metrics.

Implementation Details
Environment: The system is implemented using Jupyter Notebook, allowing for interactive development and analysis.
Library Used: The primary library utilized is Pandas, which facilitates data manipulation and analysis.
Data Ingestion: The TSV dataset is loaded into a Pandas DataFrame within the Jupyter Notebook.
Problem Statement: After ingesting the data, I address the problem statement outlined in Part 2 by implementing functions that allow users to query the dataset for various insights, such as:
The number of tweets posted containing a specific term on each day.
The number of unique users who posted tweets containing the term.
The average number of likes for tweets containing the term.
The places (place IDs) from where the tweets originated.
The times of day when the tweets were posted.
The user who posted the most tweets containing the term.
