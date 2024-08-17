# Netflix-Project
# Netflix Data Analysis Dashboard - Tableau

This repository contains the Tableau workbook and data files for a comprehensive analysis of Netflix's content catalog. The project showcases my ability to transform raw data into actionable insights through visually engaging dashboards. The project aims to provide detailed insights into the content trends on Netflix, helping stakeholders make data-driven decisions.

## Key Features:

### 1. **Area Chart: Growth of Movies and TV Shows Over Time**
   - This area chart tracks the increase in the number of movies and TV shows added to Netflix from 2008 to 2021. The visual highlights the rapid content expansion starting around 2015, showcasing Netflix's strategy to scale up its library.
 

   ! ![Area chart for Total movies and tv shows by years](https://github.com/user-attachments/assets/ee82073c-0fd6-47dc-92b1-283e08f8a849)

### 2. **Map Visualization: Global Distribution of Content**
   - This map visualization displays the geographical distribution of Netflix content, highlighting key regions with high content volumes. It provides insights into where Netflix's content is most prolific, with the USA standing out as a significant contributor.
  
   ![Map chart for total movies and tv shows](https://github.com/user-attachments/assets/17140a3d-8e2c-4168-a30e-e8bcaf57b932)


### 3. **Top 10 Genres:**
   - This bar chart ranks the most popular genres on Netflix, helping stakeholders understand content trends. The visualization shows which genres are dominating the platform, with ‘Drama’ and ‘Documentaries’ being the top contenders.
  
   ![Bar chart for Top 10 genre](https://github.com/user-attachments/assets/bbfe05dd-e18f-4d19-8b91-29ada64cc783)


### 4. **Ratings Distribution:**
   - Analyzes the spread of content ratings on Netflix, focusing on user preferences and content targeting. This chart helps in understanding the distribution of content based on ratings such as TV-MA, TV-14, PG-13, etc.
  
   ![Bar chart for Ratings](https://github.com/user-attachments/assets/994f83f1-62dd-4fe0-9c6f-d0971823bfbb)


### 5. **Content Distribution: Movies vs TV Shows**
   - A circle chart that compares the proportion of movies to TV shows in Netflix's catalog. This visualization highlights that movies constitute nearly 70% of the total content, reflecting Netflix’s emphasis on movie content.
  
   ![Circle chart for movies and tv shows distribution](https://github.com/user-attachments/assets/96371464-9af9-4924-993e-7308b77835fd)


### 6. **Dashboard Overview:**
   - The dashboard compiles all the visualizations into a cohesive view for easy analysis. It allows users to interact with the data and derive insights in a structured manner, with the ability to filter and explore different dimensions of the data.
  
   ![Netflix Dashboard](https://github.com/user-attachments/assets/7917444f-5b4a-47aa-9f03-32ebd19a6b56)


## Tools and Technologies:

- **Tableau:** For data visualization and dashboard creation.
- **CSV Files:** As a data source containing Netflix titles and attributes.
- **Data Preparation:** Involved cleaning and structuring the dataset to ensure accurate and meaningful visualizations.

## Insights and Achievements:

- **Content Growth:** Identified significant growth in Netflix's content catalog, particularly after 2015.
- **Genre Popularity:** 'Drama' and 'Documentaries' are the leading genres, reflecting audience interest.
- **Geographical Insights:** The USA leads in content production, with a diverse range of genres and titles.

## Stakeholders:

- **Content Strategists:** To leverage insights for content curation and acquisition.
- **Marketing Teams:** To design targeted campaigns based on content preferences.
- **Data Analysts:** As a template for similar data-driven projects.

## Step-by-Step Process:

1. **Data Importation:**
   - Imported Netflix's titles dataset in CSV format into Tableau.

2. **Data Cleaning:**
   - Removed null values from the dataset.
   - Ensured data accuracy by cross-verifying key fields like `Show Id`, `Type`, `Title`, `Director`, etc.

3. **Area Chart Creation:**
   - Created an area chart to visualize the growth of content over time.
   - Used `Date Added` for columns and `Show Id` for rows, setting it as a count distinct measure.
   - Filtered null values and customized colors to align with Netflix branding.

4. **Map Visualization:**
   - Developed a map chart to display the geographical distribution of Netflix content.
   - Double-clicked `Country` and adjusted the map to fill mode.
   - Added `Show Id` to the color marks to represent content count.

5. **Top 10 Genres:**
   - Constructed a bar chart to show the top 10 genres.
   - Used `Listed In` for rows and `Show Id` for columns with a count distinct measure.
   - Applied a top 10 filter to the chart and adjusted formatting for clarity.

6. **Ratings Distribution:**
   - Designed a bar chart to analyze the distribution of content ratings.
   - Added `Rating` to columns and `Show Id` to rows, using count distinct.
   - Customized the chart with Netflix’s red color scheme and adjusted grid lines.

7. **Content Distribution:**
   - Created a circle chart to compare the distribution of movies to TV shows.
   - Added `Type` to rows and `Show Id` to the size marks, using count distinct.
   - Used a packed bubble visualization and applied percentage calculations for clarity.

8. **Dashboard Assembly:**
   - Compiled all the charts into a single dashboard.
   - Set the background to black and organized charts to ensure clarity.
   - Added filters and formatted titles and text to match Netflix branding.

9. **Final Touches:**
   - Added a description section with key information like release year, rating, and genre.
   - Included the Netflix logo for brand consistency.
   - Adjusted the layout for optimal viewing, ensuring all elements were aligned and accessible.

## How to Use:
- Download the `.twb` file and open it in Tableau.
- Explore the various dashboards to gain insights into Netflix’s content.

