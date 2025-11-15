# Movie Industry ROI Analysis

## Overview
This project analyzes 7,669 films spanning 1980-2020 to identify which movie characteristics generate the highest return on investment (ROI). By examining genre, rating, and critical reception, this analysis reveals patterns about film profitability. The key finding: Family films achieve 10.14x average ROI (1,014% return), outperforming all other genres and representing a 252% advantage over the industry average of 2.87x.

## Business Question
Film studios invest millions in production budgets without reliable profitability frameworks which results in unpredictable ROI and significant financial losses. Due to lack of reliable profitablity frameworks, the film industry lacks guidance on which film characteristic (genre, rating catergory, and score) generate the highest ROI. Which movies achieve the highest ROI? What factors predict profitability in the film industry?

## Methodology
- Adjusted all revenues to 2023 dollars using CPI data to ensure fair comparison across decades
- Calculated ROI as: (Revenue - Budget) / Budget × 100%
- Excluded movies with missing budget or revenue data (data quality validation)
- Analyzed patterns by genre, year, and budget tier

## Key Findings
1. Family Films Deliver 252% Higher ROI Than Industry Average
2. Critical Score Is the Strongest ROI Predictor (384% Performance Gap)
3. G-Rated Films Outperform R-Rated by 48%
4. Horror Flims Presents High-ROI on Low-Budget (4.22x ROI on 60-75% lower budget than some other genres)

## Skills Demonstrated
- **Excel:** Advanced formulas, pivot tables, charts, data validation, XLOOKUP
- **Financial Analysis:** ROI calculations, inflation adjustment using CPI
- **Data Cleaning:** Identified and excluded incomplete records

## Tools Used
- Microsoft Excel
- CPI data for inflation adjustment

## Results & Recommendations
Films in the Family genre achieve 10.14x average ROI compared to the 2.87x industry average, outperforming all other genres. This 252% performance advantage reflects the genres family-freindly appeal, ranging from children to grandparents. Films rated 8.0+ average 5.52x ROI versus poorly-rated films (1.0-4.0) at 1.14x ROI—a 384% performance gap. Flim qualityappears to be a significantly stronger profitability predictor than production budget size. G-rated films achieve 3.55x ROI compared to R-rated at 2.40x ROI. Horror films achieve 4.22x ROI on 60-75% lower production budgets than action/drama films ($10M typical horror budget vs. $150M action budget). 

To optimize profitability, film studios should prioritize family-friendly, high-quality content with broad audience appeal over high-budget productions.

## Next Steps
1. Include international box office data

---

## Project Files & Visualizations

### 📊 Excel Workbook
**[Download Complete Analysis: movie_industry_roi_project.xlsx](movie_industry_roi_project.xlsx)**

### 📈 Key Charts

#### Average ROI by Movie Genre
![Genre ROI](screenshots/Average%20ROI%20by%20Movie%20Genre%20Chart.PNG)

#### ROI by MPAA Rating Category
![Rating ROI](screenshots/Profitability%20by%20Movie%20Rating%20Chart.PNG)

#### ROI vs. IMDb Score Range
![Score ROI](screenshots/Average%20ROI%20vs.%20Score%20Chart.PNG)


