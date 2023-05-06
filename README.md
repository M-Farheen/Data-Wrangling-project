
# FIFA Data Cleaning Project

![world cup](https://github.com/M-Farheen/FIFA_DATA_CLEANING_CHALLENGE-1/blob/main/Images.jpg)


This project is a part of data cleaning challenge held in a data community aimed at cleaning the FIFA dataset, which contains information on the ratings and attributes of football players from the video game FIFA. The dataset is quite large, containing over 18,000 rows and 100 columns, and as such, it requires extensive cleaning to make it suitable for analysis.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Conclusion](#conclusion)

## Introduction

The FIFA dataset is a valuable resource for anyone interested in football or video games. It contains a wealth of information on the ratings and attributes of football players from the FIFA video game, including their age, position, nationality, and various other statistics.

However, before this dataset can be used for analysis or visualization, it needs to be cleaned. The dataset contains missing values, inconsistencies, and other errors that need to be addressed. In this project, we will go through the process of cleaning the dataset and making it suitable for analysis.

## Dataset

The FIFA dataset contains over 18,000 rows and 100 columns, and it can be found on Kaggle. The data is provided in a CSV file, and it contains information on the ratings and attributes of football players from the FIFA video game.

The columns in the dataset include the following:

- ID: A unique identifier for each player
- Name: The name of the player
- Age: The age of the player
- Nationality: The nationality of the player
- Overall: The overall rating of the player
- Potential: The potential rating of the player
- Club: The club that the player belongs to
- Value: The value of the player in Euros
- Wage: The weekly wage of the player in Euros
- Preferred Foot: The preferred foot of the player (left or right)
- International Reputation: The international reputation of the player (on a scale of 1 to 5)
- Weak Foot: The weak foot rating of the player (on a scale of 1 to 5)
- Skill Moves: The skill moves rating of the player (on a scale of 1 to 5)
- Position: The position of the player on the field
- Jersey Number: The jersey number of the player
- Joined: The date that the player joined their current club
- Contract Valid Until: The date that the player's contract with their current club expires
- Height: The height of the player in centimeters
- Weight: The weight of the player in pounds
- Crossing: The crossing attribute of the player (on a scale of 1 to 100)
- Finishing: The finishing attribute of the player (on a scale of 1 to 100)
- HeadingAccuracy: The heading accuracy attribute of the player (on a scale of 1 to 100)
- ShortPassing: The short passing attribute of the player (on a scale of 1 to 100)
- Volleys: The volleys attribute of the player (on a scale of 1 to 100)
- Dribbling: The dribbling attribute of the player (on a scale of 1 to 100)
- Curve: The curve attribute of the player (on a scale of 1 to 100)
- FKAccuracy: The free kick accuracy attribute of the player (on a scale of 1 to 100)
- LongPassing: The long passing attribute of the player (on a scale of 1 to 100)
- BallControl: The ball control attribute of the player (on a scale of 1 to 100)
- Acceleration: The acceleration attribute of the player (on a scale of 1 to 100)
- SprintSpeed: The sprint speed attribute of the player (on a scale of 1 to 100)
- Agility: The agility attribute of the player (on a scale of 1 to 100)
- Reactions: The reactions attribute of the player (on a scale of 1 to 100)
- Balance: The balance attribute of the player (on a scale of 1 to 100)
- ShotPower: The shot power attribute of the player (on a scale of 1 to 100)
- Jumping: The jumping attribute of the player (on a scale of 1 to 100)
- Stamina: The stamina attribute of the player (on a scale of 1 to 100)
- Strength: The strength attribute of the player (on a scale of 1 to 100)
- LongShots: The long shots attribute of the player (on a scale of 1 to 100)
- Aggression: The aggression attribute of the player (on a scale of 1 to 100)
- Interceptions: The interceptions attribute of the player (on a scale of 1 to 100)
- Positioning: The positioning attribute of the player (on a scale of 1 to 100)
- Vision: The vision attribute of the player (on a scale of 1 to 100)
- Penalties: The penalties attribute of the player (on a scale of 1 to 100)
- Composure: The composure attribute of the player (on a scale of 1 to 100)
- Marking: The marking attribute of the player (on a scale of 1 to 100)
- StandingTackle: The standing tackle attribute of the player (on a scale of 1 to 100)
- SlidingTackle: The sliding tackle attribute of the player (on a scale of 1 to 100)
- GKDiving: The goalkeeper diving attribute of the player (on a scale of 1 to 100)
- GKHandling: The goalkeeper handling attribute of the player (on a scale of 1 to 100)
- GKKicking: The goalkeeper kicking attribute of the player (on a scale of 1 to 100)
- GKPositioning: The goalkeeper positioning attribute of the player (on a scale of 1 to 100)
- GKReflexes: The goalkeeper reflexes attribute of the player (on a scale of 1 to 100)

## Data Cleaning

Before we can start analyzing the dataset, we need to clean it up. This includes addressing missing values, handling inconsistencies, and removing any irrelevant or redundant columns.

In this project, we will perform the following cleaning steps:

1. Handling missing values: We will identify any missing values in the dataset and decide how to handle them. We may choose to drop rows or fill in missing values using various methods such as imputation or interpolation.

2. Addressing inconsistencies: We will check for any inconsistencies in the data, such as inconsistent spelling or formatting of player names or club names. We will also address any inconsistencies in the data types of columns.

3. Removing irrelevant or redundant columns: We will identify any columns that are not relevant to our analysis or that contain redundant information. We will remove these columns to simplify the dataset and reduce noise.

4. Standardizing units: We will standardize the units used in the dataset to ensure consistency and facilitate comparisons.

## Exploratory Data Analysis

Once the dataset has been cleaned, we can start exploring it. In this project, we will perform exploratory data analysis (EDA) to gain insights into the data and identify any patterns or trends.

Our EDA will include the following:

1. Descriptive statistics
: We will calculate various summary statistics such as mean, median, and standard deviation to describe the distribution of the data.

2. Visualizations: We will create various visualizations such as histograms, box plots, and scatter plots to explore the relationships between variables and identify any outliers or anomalies.

3. Correlation analysis: We will calculate correlation coefficients to identify any relationships between variables and determine which attributes are most important in determining a player's overall rating.

4. Clustering analysis: We will use clustering algorithms such as k-means clustering to group similar players together based on their attributes.

## Conclusion

In this project, we will perform data cleaning and exploratory data analysis on the FIFA 19 player dataset. We will use various statistical and machine learning techniques to gain insights into the data and identify any patterns or trends.
