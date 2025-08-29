# Olympic-data-analysis
Data cleaning, exploration, and visualization of Olympic athletes and results (1900–present)
# Olympic Athletes and Results Analysis (Historical Data)

## Project Overview
This project analyzes Olympic medal data to uncover **patterns in athlete demographics, country dominance, and sport specialization**.  
It was designed to demonstrate **end-to-end data analysis skills** — from cleaning messy data to generating actionable insights through visualization and storytelling.

---

## Objectives
- **Data Cleaning & Preparation:** Handle missing values, parse dates, extract structured fields (e.g., birth year, birthplace).  
- **Exploratory Data Analysis (EDA):** Compare medal distributions across countries, sports, and gender.  
- **Visualization:** Communicate findings with professional plots and tables.  
- **Insight Generation:** Translate patterns into **clear takeaways and real-world implications**.  

---

## Process
- **Data Cleaning & Preparation (pandas):**  
  - Merged and cleaned two messy Olympic datasets.
  - Dropped columns that were not useful.
  - Standardized column formats and types.
  - Handled duplicates and missing values.
  - Parsed and aggregated date, height, and weight columns.
  - Converted inconsistent birth date formats into numeric years.  
  - Extracted birthplace information from unstructured text using regex.  
  - Standardized categorical fields (e.g., NOC codes, gender).  

- **Exploratory Data Analysis (EDA):**  
  - Computed statistics at the NOC, discipline, medal, and athlete levels.
  - Grouped and aggregated medal data to compute dominance metrics.
  - Used proportions to normalize medal counts across countries of different sizes  
  - Created summary tables for average finish, participation counts, and wins.
  - Built visualizations using Matplotlib.

- **Key Questions Answered:** 
  - Average place/finish of each NOC?
  - Number of events participated in by NOC (the count of each NOC)?
  - Illustrate the performance (AVG place AND Most amount of points) of the top 5 NOC's from the year 2000 to now.
  - Per discipline, which NOC has the most wins in it?
  - Which disciplines does the U.S. have the most 1st places in?
  - Number of athletes produced per NOC
  - For each NOC, which athlete has the most amount of 1st places?

- **Visualizations:**  
  - Bar chart showing the top 25 countries with the highest athlete output.
    
  - Multi-line plot showing the performance (most amount of points/medals) of the top 5 NOC's from the year 2000 to now.
    
  - Multi-line plot showing the performance (AVG finishing place) of the top 5 NOC's from the year 2000 to now.
    
  - Bar chart showing the number of athletes produced by the top 10 NOCs.
 
  - Bar chart showing the performance (# of wins) of the top 13 athletes, color coded by their NOC.

- **Reproducibility:**  
  - Notebook structured with logical sections (Data Cleaning → EDA → Insights).  
  - Modular code cells for reusability.  
  - Clear documentation for each transformation and plot.  

---

## 📊 Key Findings
- **Country Dominance:** The U.S. and China win the most medals overall, but smaller countries (e.g., Jamaica in sprinting, Kenya in distance running) excel in niche sports.  
- **Sport Specialization:** Some sports (e.g., table tennis, weightlifting) show *highly concentrated dominance* by one or two nations, while others (e.g., swimming, athletics) are broadly distributed.  
- **Gender Balance:** Most sports now show balanced participation, though a few remain skewed.  
- **Age Trends:** Younger athletes dominate gymnastics and swimming, while sports like equestrian and shooting feature significantly older medalists.  

---

## 🏁 Final Insights
- **Medal distribution is highly concentrated** — a few nations consistently dominate, reflecting resource and infrastructure advantages.  
- **Specialization enables smaller countries to shine**, showing that national investment in one sport can yield global recognition.  
- **Age and gender trends highlight inclusivity and diversity**, showing how different disciplines reward different strengths.  
- **The Olympics remain globally representative**, as almost every nation finds opportunities for visibility, even without large medal counts.  

This project shows how **data analysis can uncover both macro-level dominance and micro-level success stories**, and how structured storytelling turns raw data into actionable insights.

---

## 📂 Project Structure
