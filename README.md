# Dashboard Analysis Movie at Netflix
The 'netflix_data' schema has each table having a 'show_id' column that acts as a foreign key, connecting each table with the 'netflix_titles' table. However, there are a few potential issues that may be worth noting. Firstly, the 'mediumtext' and 'text' data types for 'show_id' may be redundant for unique identification and could be replaced with more efficient data types such as 'int' or 'varchar'. Secondly, the 'date_added' column in the 'netflix_titles' table is a 'text' data type, which may complicate date operations. Converting it to a date data type would facilitate time-based analysis. Finally, there is no information about whether there are missing or inconsistent values in the data, which could affect the quality of the analysis.

![Screenshot 2024-02-25 200540](https://github.com/roniantoniius/Dashboard-Analysis-Data-Movie-at-Netflix--PowerBI/assets/121453378/803fce04-0153-4054-a608-26f9741a9a31)

In this project, I have leveraged the netflix_data database schema to create a comprehensive visualization using PowerBI, as depicted in the attached figure.
![Screenshot 2024-02-25 200555](https://github.com/roniantoniius/Dashboard-Analysis-Data-Movie-at-Netflix--PowerBI/assets/121453378/75d2005f-be1f-48ec-9929-2e175c1fda57)

The business understanding phase involved identifying key metrics and trends that are critical to analyzing Netflix's content strategy, including the volume and diversity of shows/movies added over time, popular genres, and global availability.

In the data understanding phase, I carefully examined each column in the schema to gain insights into the type and quality of data available. This helped me identify patterns, anomalies and potential relationships between different data elements.

During data preparation, I cleaned and transformed the raw data to make it suitable for analysis. I ensured consistency in format, addressed missing values, and created calculated fields to gain additional insights.

The last step is data visualization where we use PowerBI to create interactive visualizations that offer insights at once. We have a line graph showing the trend of added shows by date; a bar graph distinguishing between Movies & TV Shows; a horizontal bar graph displaying the top 10 genres; and a world map highlighting the countries where these shows are available. 

![Screenshot 2024-02-25 200308](https://github.com/roniantoniius/Dashboard-Analysis-Data-Movie-at-Netflix--PowerBI/assets/121453378/2baeb389-a637-41ff-9959-d5d0e5c8ab22)

On the second page of the PowerBI visualization, I added more details about each title available on Netflix. I also have an "Overview" panel that presents specific information about a particular title, in this case "Christmas with a Prince". This panel includes the release year, rating, and countries where the movie or TV show is available. In addition, there is also a brief synopsis and additional information such as genre, director, and cast. The interactive map allows users to easily see the global distribution of the content. As such, this visualization provides a deeper understanding of each title, allowing users to explore and understand the data in a more intuitive and in-depth way.
![Screenshot 2024-02-25 200524](https://github.com/roniantoniius/Dashboard-Analysis-Data-Movie-at-Netflix--PowerBI/assets/121453378/4c9c5288-f008-4a0d-a53b-0beee373943a)
