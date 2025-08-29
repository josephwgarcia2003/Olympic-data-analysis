# Olympic Athletes and Results Analysis (Historical Data)
Data cleaning, exploration, and visualization of Olympic athletes and results (1900–present yr)

## Project Overview
This project analyzes Olympic medal data to uncover **patterns in athlete demographics, performance, country dominance, participation, and sport specialization**.  
It was designed to demonstrate **end-to-end data analysis skills** — from cleaning messy data to generating actionable insights through visualization and storytelling.

---

## Objectives
- **Data Cleaning & Preparation:** Prepare structured datasets by cleaning and standardizing raw Olympic records.  
- **Exploratory Data Analysis (EDA):** Explore performance trends across countries, disciplines, athletes, and time periods.  
- **Visualization:** Visualize insights through clear plots and tables that highlight participation, performance and dominance patterns.  
- **Insight Generation:** Generate takeaways about how nations and athletes perform, and how Olympic outcomes vary across disciplines and eras.  

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
  - Computed statistics at the NOC (National Olympic Committee), discipline, medal, and athlete levels.
  - Grouped and aggregated medal data to compute dominance metrics.
  - Used proportions to normalize medal counts across countries of different sizes  
  - Created summary tables for average finish, participation counts, and wins.
  - Built visualizations using Matplotlib.

- **Key Questions Answered:** 
  - Average place/finish of each NOC?
  - Number of Olympic events participated in by each NOC (order by descending)?
  - Vizualize the performance (AVG place AND most amount of medals/points) of the top 5 NOC's from the year 2000 to now.
  - For each discipline, which NOC has the most wins in that discipline?
  - Which disciplines does the U.S. have the most 1st places in?
  - Number of athletes produced per NOC?
  - For each NOC, which athlete has the most amount of 1st places?

- **Visualizations:**  
  - Bar chart showing the top 25 countries with the highest output of athletes. <img width="1023" height="495" alt="athletes_per_country" src="https://github.com/user-attachments/assets/78ce7876-0b0c-4456-90ba-0affd1666027" />
    
  - Multi-line plot showing the performance (most amount of points/medals) of the top 5 NOC's from the year 2000 to now. <img width="1005" height="491" alt="medals_per_NOC" src="https://github.com/user-attachments/assets/eac5b99e-ef0f-40b7-880b-ac448555e75e" />
    
  - Multi-line plot showing the performance (AVG finishing place) of the top 5 NOC's from the year 2000 to now. <img width="997" height="491" alt="avgplace_per_NOC" src="https://github.com/user-attachments/assets/000193e1-208d-4f67-9445-23552eb002d1" />
    
  - Bar chart showing the top 10 NOCs based on the number of athletes produced. <img width="855" height="547" alt="athletes_per_NOC" src="https://github.com/user-attachments/assets/eb5a5a1e-1896-4336-bc84-5ea83b65103d" />

  - Bar chart showing the top 13 athletes based on number of gold medals, color coded by their NOC. <img width="1192" height="590" alt="top_athletes" src="https://github.com/user-attachments/assets/bd418c27-5f8e-44a4-9e58-9c96b602b937" />

- **Reproducibility:**  
  - Notebook structured with logical sections (Data Cleaning → EDA → Insights).  
  - Modular code cells for reusability.  
  - Clear documentation for each transformation and plot.  

---

## Key Findings
- **Country Dominance:** The U.S. and China win the most medals overall, but smaller countries (e.g., Jamaica in sprinting, Kenya in distance running) excel in niche sports.  
- **Sport Specialization:** Some sports (e.g., table tennis, weightlifting) show *highly concentrated dominance* by one or two nations, while others (e.g., swimming, athletics) are broadly distributed.  
- **Gender Balance:** Most sports now show balanced participation, though a few remain skewed.  
- **Age Trends:** Younger athletes dominate gymnastics and swimming, while sports like equestrian and shooting feature significantly older medalists.  

---

## Final Insights
- **Medal distribution is highly concentrated** — a few nations consistently dominate, reflecting resource and infrastructure advantages.  
- **Specialization enables smaller countries to shine**, showing that national investment in one sport can yield global recognition.  
- **Age and gender trends highlight inclusivity and diversity**, showing how different disciplines reward different strengths.  
- **The Olympics remain globally representative**, as almost every nation finds opportunities for visibility, even without large medal counts.  

This project shows how **data analysis can uncover both macro-level dominance and micro-level success stories**, and how structured storytelling turns raw data into actionable insights.

---

## Project Structure
