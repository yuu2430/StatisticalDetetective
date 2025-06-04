# Statistical Detetective
***Game Link***- https://statisticaldetetective.streamlit.app/

## Game Overview

![image](https://github.com/user-attachments/assets/de122fe8-5286-4d23-8357-555a2ecdf954)

A data-driven mystery game where players analyze crime statistics to identify suspects.
Statistical Detective is an interactive web-based game that challenges players to solve crimes using data analysis skills. 
Players must examine crime statistics, interpret patterns, and make educated guesses about suspects' characteristics.

## Features
Three Difficulty Levels: Easy (3 attempts), Hard (2 attempts), Expert (1 attempt)
Dynamic Crime Generation: Randomly generated cases with unique characteristics
Data Analysis Tools: Players examine a dataset of recent crimes
Gradual Hint System: More hints are revealed after failed attempts
Score Tracking: Players earn points for each correctly solved case
Responsive Design: Works on desktop and mobile devices

## Technical Details
Built with Python using Streamlit for the web interface
Uses scikit-learn's KMeans for crime pattern detection
Pandas for data manipulation and analysis
Custom CSS styling for an immersive detective theme

## Game Mechanics
Crime Data Generation:
The game generates 10 random crime cases with:
Time of day (morning, afternoon, evening, night)
Location (4 possible areas)
Crime type (assault, burglary, kidnapping, etc.)
Suspect demographics (age, gender)
Weapons used
Crime scene evidence

## Pattern Detection
Uses KMeans clustering to identify high-risk zones
Generates dynamic hints based on crime patterns
Player Interaction:
Players analyze the crime data
Receive gradual hints based on performance
Make guesses about the suspect's location, age, and gender
Have limited attempts based on difficulty level

## Certificate
[Link](https://github.com/yuu2430/StatisticalDetetective/blob/main/open%20house%20participation.pdf)

