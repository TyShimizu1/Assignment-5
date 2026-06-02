Assignment 5
=========
# Team Members:
- Nigel Alston
- 
- 
# Expected Data Structures
Placeholder text.
# Initial Code Examination
Placeholder text.
# Detailed Code Examination

The code file that I chose to do a detailed examination on was the sqldata.py file.
The purpose of the code in this file to my understanding is to record and manage the code   using an sqlite-backed storage layer. It has a central class, called CoverageData, that stores the public API and stores the data produced on a successful test run. It contains multiple different functions that each  play key roles in data collection and readability, with one function called dumps that even serializes data to a byte string, and another function called loads that restores this data, and finally another separate function called update that combines these data files. The file even has if statements that handle code that is present in other databases. There are a lot of auxiliary helper functions that complete tasks like managing files, mapping file paths, and preventing random character collisions. There is a function called purge whose purpose is to delete coverage files to clean up the code and to save space. Many of the functions in this file also have locks on them, which handle thread safety and help avoid concurrency problems during coverage collection. This code file provides great efficiency and flexibility for the coverage.py folder as a whole.


# Summary
Placeholder text.
