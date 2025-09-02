# Data-Analytics-Projects
All the projects described in this folder is from various reference websites to gain the practice on various data analytics practices as capstone as well as self paced.

**Drug Safety Data Analysis**

## Project Overview

A pharmaceutical company, GlobalXYZ, has completed a randomized controlled drug trial. To promote transparency, the dataset has been provided to our organization, which focuses on drug safety. The dataset contains demographic data, vital signs, and records of five adverse effects. Our primary goal is to analyze adverse reactions and answer key questions about the drug's safety profile.

## Dataset

The modified dataset (`drug_safety.csv`) includes:
- `sex`: Gender of the individual
- `age`: Age of the individual
- `week`: Week of drug testing
- `trx`: Treatment group (`Drug`) or control group (`Placebo`)
- `wbc`: White blood cell count
- `rbc`: Red blood cell count
- `adverse_effects`: Presence of at least one adverse effect (`Yes`/`No`)
- `num_effects`: Number of adverse effects experienced

## Questions Answered

1. **Are adverse reactions significantly different between Drug and Placebo groups?**
   - Compared the proportion of individuals with adverse effects in each group using a two-sided z-test.

2. **Are the number of adverse effects (`num_effects`) and treatment group (`trx`) independent?**
   - Used a chi-square test of independence to check if the number of adverse effects is related to the treatment group.

3. **Is there a difference in age distribution between Drug and Placebo groups?**
   - Visualized age distributions and performed a Mann-Whitney U test to compare ages between groups.


## References

- Dataset source: [Hbiostat](https://hbiostat.org/data/) courtesy of Vanderbilt University Department of Biostatistics.

## Files
- `drug_safety.csv`: Dataset
- `notebook.ipynb`: Main analysis script

**PROJECT - II**
**Netflix 1990s Movie Analysis**

## Project Overview

This project explores Netflix's movie catalog, focusing on films released in the 1990s. As a production company specializing in nostalgic styles, we aim to understand trends and characteristics of 1990s movies available on Netflix using exploratory data analysis.

## Dataset

The analysis uses `netflix_data.csv`, which contains:
- `show_id`: Unique identifier for each show
- `type`: Movie or TV Show
- `title`: Name of the show
- `director`: Director's name
- `cast`: Main cast
- `country`: Country of origin
- `date_added`: Date added to Netflix
- `release_year`: Year of release
- `duration`: Duration in minutes
- `description`: Brief summary
- `genre`: Genre of the show

## Questions Answered

1. **What is the distribution of movie durations for Netflix movies released in the 1990s?**
   - Visualized the duration of 1990s movies to understand typical lengths.

2. **What is the most common duration for 1990s movies?**
   - Identified the mode (most frequent value) of movie durations.

3. **How many short action movies (less than 90 minutes) were released in the 1990s?**
   - Filtered for action movies and counted those with durations under 90 minutes.


## Files

-netflix_data: Raw Dataset
-netflix_1990s_summary: Explored Data
-netflix_movies.ipynb: Main analysis script
