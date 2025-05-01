# User-Feedback-Recipes  
### An Excel Data Analysis Project Exploring Recipe Review and User Feedback Trends

---

## Summary  
This project explores whether a user's reputation score correlates with how they rate recipes on a public dataset. The analysis focuses on thumbs up/down ratings, star ratings, and user feedback, using Excel to clean, structure, and visualize the data.

---

## Dataset  
- **Recipe Reviews and User Feedback Dataset**  
- **Source:** UCI Machine Learning Repository – Recipe Reviews  
- **Citation:**  
  Amir Ali, Stanisław Matuszewski, Jacek Czupyt, Usman Ahmad. (2023). *Textual Taste Buds: A Profound Exploration of Emotion Identification in Food Recipes through BERT and AttBiRNN Models.* *International Journal of Novel Research and Development*, Volume 8. ISSN: 2456-4184.

---

## Project Goals  
- Examine the relationship between user reputation score and recipe rating behavior.  
- Test whether higher reputation users are more critical or consistent in their ratings.  
- Evaluate the effectiveness of a user reputation system for feedback platforms.  

---

## Methods  
**Tools Used:** Excel  
- Cleaned and structured the dataset in **Excel**.  
- Isolated key variables: user reputation, thumbs up, thumbs down, and star rating.  
- Calculated descriptive statistics (mean, standard deviation, range, min, max).  
- Created a pivot table to understand the distribution of user reputation scores (range: 0–520).  
- Ran correlation analyses and visualized results with scatterplots.  

---

## Key Findings  

**Correlations with User Reputation:**  
- **Thumbs Up:** *r = 0.057* → almost no correlation  
- **Thumbs Down:** *r = 0.023* → almost no correlation  
- **Star Ratings:** *r = 0.016* → almost no correlation  

**Top vs. Bottom-Rated Recipes:**  
- **Top-rated (Recipe #16):** *r = 0.03* → almost no correlation  
- **Lowest-rated (Recipe #21):** *r = -0.04* → almost no correlation  
- **Highest review count (Recipe #3):** *r = -0.10* → almost no correlation  

> *Note: The top 100 recipes were not ranked in descending order of average star rating.*

---

## Next Steps  
- Explore whether high-reputation users consistently rate more critically or generously.  
- Consider review volume thresholds to assess stability in correlations.  
- Expand to tools like **Python**, **R**, or **SQL** for deeper data exploration.  

---

## Tools Used  
- **Excel** (data cleaning, pivot tables, descriptive statistics, scatterplots)  

---

## View the Full Analysis Workbook  
[Click here to view the Excel file (XLSX)](https://github.com/Ashley-Goldstein/User-Feedback-Recipes/blob/main/Project%20-%20Recipe%20Reviews%20and%20User%20Feedback%20Dataset%203.xlsm)

---

