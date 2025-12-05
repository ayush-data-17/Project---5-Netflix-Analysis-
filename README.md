#  📺 Netfllix Analysis Using Python And Power BI 
<img width="1707" height="960" alt="c35e3e9b-7203-4f50-9425-c850336a2e7b-cover" src="https://github.com/user-attachments/assets/6cf16867-ac56-4c60-8576-ab7673ff8cb0" />

An in depth  **data anlaytics and visualization project** built by using **Python** and **Power BI** , amied at analyzing netflix content preference among movies and TV Shows, genres , age group and etc.

---
## 📘 Project Overview 
This project focus on understanding the key aspects of business netflix data by analyzing the data .
It helps to answer the following question :
- What is the distribution of content type (Movies v/s Tv Shows)?
- Which is the genre are most popular among netflix user for TV Shows and Movies?
- Which country are the major contributor to the netflix content?
- Which is the best time to release content on netflix?
- In which year did the netflix see the highest number of release?
- What are the most common viewers rating for netflix content?

---
## 📁 Dataset Details 

 - Source : "imtkaggleteam/netflix"
 - Rows : Over 8,000
 - Columns Name : show_id , title ,type ,cast,director , country , date_added , release_year , rating , duration , listed_in , description . 

---
## 🧹 Data Cleaning and Visualization
All the preprocessing and visual analysis were done in the python using **pandas , numpy , matplolib and seaborn**

### Steps Performed :
- Handelled the missing values by filling them using mean/mode in **Country and rating** column.
- Handelled the missing values by filling **Unknown** in **director and cast** column.
- Drop the **description** column because there is no use of it in the entire analyse.
- Done some feature engineering by adding new columns like **Month** , **Month_Name**, **Year** and **Age Group** .
- Converted the data type of **date_added** column to datetime data type .
- Generated summary satistics using **describe()** and **Correlation analysis**.

---

## 📊 Dashboards and Features 

<img width="1306" height="739" alt="Screenshot 2025-12-05 120115" src="https://github.com/user-attachments/assets/2163f0de-62ad-49df-8f01-231b39aa024b" />


**Features:**

**KPI'S:**
- Total Titles : 8802
- Total Movies : 6131
- Total Country : 751
- Total Directors : 4529

**Charts And Visuals:**
- Bar Chart : Number of shows by rating (adults and teens are more into netflix content) . 
- Bar Chart : Number of shows by genre (Drama and International TV Shows are most consumed) . 
- Filled Map : Total number of shows by country (USA , India and UK are the three most content providng nations) . 
- Doughnut Chart : Number of total shows by Movies v/s TV Shows .
- Column Chart : Content consumtion among age group . 

---

## 🔍 Key Insights – Netflix Content Analysis

🎬 **Diverse Content Mix**  
Netflix’s library is movie-heavy, with **over 69% of the content being Movies** and only **around 30% TV Shows**, showing a clear opportunity to grow long-format series content.

🌍 **Top Content Providers**  
The **USA, India, and the UK** dominate Netflix’s catalog, making them the strongest contributors to global content production.

📅 **Best Months for Release**  
**December, July, and September** are the most active months for content releases, indicating seasonal release strategies.

📈 **Peak Content Year**  
**2018 stands out** as the year with the **highest number of releases**, making it the most important production year in Netflix’s history.

👥 **Viewer Age Groups**  
Most content is targeted at **Teens and Adults**, highlighting Netflix’s strong focus on mature and young adult audiences.

🎭 **Content Specialization**  
**International TV Shows** lead the series category, while **Drama dominates Movies**, showing strong audience demand for emotional and story-driven content.


---

## 💼 Recommendation

Based on the analysis here are some recommendation for  company that can help them in the better decision making:

 **1.) Strengthn TV Shows Library :**
       With movies up 69% of catlog , increase high-quality TV Shows production can boast retntion rate and boinge watching behavior .

      
**2. ) Priotize High-Performing Country :**
       As USA , India and UK lead the market in most content providing nations in the world , so netflix should deepen investment and partnership in these key market .
       
**3. ) Expand Top Genre :**
       Increase invenstment in International TV Shows and Drama as they dominate viewers preference .
       
**4. ) Optimize Release Stratergy :**
       Major realease should be concented in the December , July and September to maximize visiblity and viewer engagement .
       
**5. ) Target Teens and Adults :**
       Focus content development on teen and adults aduience who consume the majority of the netflix content . 
       

---

## 🧰 Tools Used 

- **Python:** pandas, numpy, matplotlib, seaborn
- **Power BI:** For dashboard making , creating DAX problems and building report
- **EDA:** For doing bivaraite and univariate analysis on the dataset and creating some basic visualizations .

---

## 🔗 Connect With Me 

- **Author:** Ayush Lohat
- **Linkdin:** www.linkedin.com/in/ayush-lohat-463187381
- **GitHub:** https://github.com/ayush-data-17

---

✨ *Thank you for exploring this project! Your feedback and suggestion are always welcome .*

  



 
 
