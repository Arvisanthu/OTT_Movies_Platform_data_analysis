### **1. Project Objectives**

* Perform **exploratory analysis** of movies across streaming platforms:

  * Netflix
  * Amazon Prime
  * Hulu
  * Disney+
* Answer key questions:

  * Where are the best movies found?
  * Which directors, years, and genres have the highest-rated movies?
  * How do genres and ratings vary across platforms?

---

### **2. Methods**

* **Data Understanding & Cleaning**

  * Load dataset (`MoviesOnStreamingPlatforms_updated.csv`).
  * Handle missing values and duplicates.
  * Transform “Genres” into dummy variables for analysis.
* **Exploratory Data Analysis (EDA)**

  * Visualizations using **Matplotlib, Seaborn, and Plotly**.
  * Check movie distribution across platforms.
  * Identify top genres, directors, and years.
  * Compare IMDb ratings and Rotten Tomatoes scores.

---

### **3. Dataset**

* Source: Public dataset from [GitHub repository](https://github.com/rajeevratan84/datascienceforbusiness/blob/master/MoviesOnStreamingPlatforms_updated.csv).
* Content:

  * Movies available on **Netflix, Prime, Hulu, and Disney+**.
  * Features include: Title, Year, Age rating, IMDb rating, Rotten Tomatoes rating, Genres, Directors, Runtime, and Platform availability.

---

### **4. Results**

* **Distribution of Movies:**

  * Amazon Prime has the **largest movie catalog**, followed by Netflix, Hulu, and Disney+.
* **Top-Rated Movies:**

  * Best movies (by IMDb) are spread across platforms, but some platforms have more consistently high-rated titles.
* **Yearly Trends:**

  * Certain years had significantly higher numbers of top-rated movies.
* **Directors:**

  * Some directors consistently appear in top-rated lists.
* **Genres:**

  * Drama, Comedy, and Action are the most common.
  * Some genres score higher on IMDb and Rotten Tomatoes.

---

### **5. Insights**

* **Amazon Prime leads in quantity** but not always in quality—Netflix and Disney+ often host higher-rated movies.
* **Genre diversity matters**: platforms with broader coverage (e.g., Netflix, Prime) attract varied audiences.
* **High ratings correlate with certain genres and directors**, suggesting content strategy opportunities for platforms.
* **Disney+ specializes more in family-oriented and high-rating niche genres**, while Hulu has a smaller but unique collection.

---

*Visualisation:*

<img width="1242" height="525" alt="newplot" src="https://github.com/user-attachments/assets/d5d45380-e4b9-4388-bef7-77d93c72bccb" />
The chart shows that the Rotten Tomatoes and Age columns have the highest missing values, while other columns like Directors, Language, Runtime, IMDb, Country, and Genres have relatively few missing entries.


<img width="1242" height="525" alt="newplot (2)" src="https://github.com/user-attachments/assets/6bf15a5a-cd63-482c-a9eb-42757b06af7b" />
The chart shows that Prime Video dominates with 71.1% of movies, followed by Netflix (20.5%), while Hulu (5.2%) and Disney+ (3.24%) have comparatively smaller shares.


<img width="1242" height="525" alt="newplot (1)" src="https://github.com/user-attachments/assets/4e66d779-f348-40a0-aba0-9eba1d46fc90" />
The chart shows that Prime Video has the highest number of IMDb 8.5+ movies (80), followed by Netflix (16), while Hulu (4) and Disney+ (2) have very few.


<img width="1000" height="1300" alt="newplot (3)" src="https://github.com/user-attachments/assets/2b11a5f0-12eb-45c0-9a40-6fec0661d3df" />
The visualization highlights the top 10 highest-rated IMDb movies across Netflix, Hulu, Prime Video, and Disney+, showing that all platforms feature critically acclaimed titles, with ratings ranging between 8.6 and 9.3.


<img width="1242" height="525" alt="newplot (4)" src="https://github.com/user-attachments/assets/13c53245-6734-4ac7-bb46-8e8fb0d562d9" />
The chart shows that movie production has steadily increased over the decades, with a sharp surge after 2000 and peaking around 2017–2018 with over 1,400 movies released.


<img width="1242" height="525" alt="newplot (5)" src="https://github.com/user-attachments/assets/2d624242-8256-4f26-adc6-205c0c555a95" />
The chart shows that the best-rated movies each year have generally improved over time, with IMDb ratings rising from around 6–7 in the early 1900s to consistently above 8.5–9 after 2000.


<img width="1242" height="525" alt="newplot (6)" src="https://github.com/user-attachments/assets/02869769-45a8-4ed4-bf9b-29c0cdc110bb" />
The chart shows that movie runtimes gradually increased from around 60–80 minutes in the early 1900s to about 90–100 minutes after 1960, remaining fairly stable in recent decades.


<img width="1242" height="525" alt="newplot (7)" src="https://github.com/user-attachments/assets/6918bbf8-5d04-4264-8854-0851fae10b70" />
The chart highlights the top 10 directors with the highest average IMDb ratings, with Miguel Gaudêncio, Fen Tian, and Danny Wu leading at around 9.2–9.3 ratings.


<img width="1242" height="525" alt="newplot (8)" src="https://github.com/user-attachments/assets/fe8ea23b-2484-4133-979a-be545d1b8911" />
The bar chart displays the top 10 movie genres with the highest movie counts, with Drama, Documentary, and Comedy leading the list. The color gradient indicates count intensity, with red representing the highest values.


<img width="1242" height="525" alt="newplot (9)" src="https://github.com/user-attachments/assets/8b68442c-63ea-4e8b-89f2-bd6bebd3f3e2" />
The bar chart shows that Documentary has the highest average IMDb rating, while Horror and Horror,Thriller genres have the lowest. Most other genres cluster around a 6.0 average rating.
