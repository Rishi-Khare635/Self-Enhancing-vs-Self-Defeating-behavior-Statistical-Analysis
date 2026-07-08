# Self-Enhancing-vs-Self-Defeating-behavior-Statistical-Analysis

A statistical analysis investigating whether the association between 
self-defeating and self-enhancing humor differs significantly between 
younger and older respondents.

## Research Question
Does the association between self-defeating and self-enhancing humor 
differ significantly between younger (under 23) and older (23 or above) 
university students?

## Dataset
- **Source:** Open Psychometrics (openpsychometrics.org)
- **Instrument:** Humor Styles Questionnaire (HSQ)
- **Original Authors:** Martin, Puhlik-Doris, Larsen, Gray & Weir (2003)
- **Original sample:** 1,071 respondents, 39 variables
- **Working sample:** 989 respondents after cleaning
- **Link:** https://openpsychometrics.org/_rawdata/

## Key Findings
- Both age groups show a statistically significant **positive** association 
  between self-defeating and self-enhancing humor — contradicting the 
  original hypothesis
- Under 23: r = 0.2641, p < 0.001
- 23 or above: r = 0.1362, p = 0.0024
- Fisher's Z test confirmed the difference between groups is statistically 
  significant (Z = 2.0922, p = 0.0364)

## Project Structure
data/
data.csv              — original raw file
clean_humor_data.csv  — processed data
notebooks/
01_cleaning.ipynb     — data cleaning and score recalculation
02_eda.ipynb          — exploratory data analysis and visualizations
03_analysis.ipynb     — formal statistical testing
report/
full written report (PDF)

## Tools Used
- Python
- pandas — data cleaning and manipulation
- matplotlib — data visualization
- scipy — statistical testing
- numpy — numerical operations

## How to Run
Open notebooks in order: 01 → 02 → 03

## Note on Data Cleaning
The dataset's pre-computed humor style scores could not be exactly 
reproduced from raw items using standard scoring methods. All four 
scale scores were recalculated from scratch using the original codebook 
formulas. This is documented in 01_cleaning.ipynb.

## Author
Rishi Khare
