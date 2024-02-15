# sql_video_game_sales

This is a project using SQL and Tableau to show insights into Video Game Sales data, and then visualize it.
Dataset was created by Jason Holm from Kaggle: https://www.kaggle.com/datasets/holmjason2/videogamedata/data

I began by moving the dataset into a CSV file and uploading it into BigQuery. From here I viewed the schema and looked at a preview of the table.

<img src="Images/Schema.png?raw=true"/>
<img src="Images/Preview.png?raw=true"/>

Right away I noticed some of the reviews were null, but upon further review it seemed less than 10% of the total games had null values, so I left them as 
they were.

I made a list of questions for myself to try and answer. Below I include these questions and show the SQL queries I used to answer them.

### What are the top 10 best selling video games?
<img src="Images/top_10.png?raw=true"/>

### What are the top 10 best selling PC video games?
<img src="Images/top_10_pc.png?raw=true"/>

### Does Blizzard Entertainment have any games in the top 100 best selling list?
<img src="Images/blizzard_top_100.png?raw=true"/>

### What years had the best average critic score?
<img src="Images/critics_year.png?raw=true"/>

### What years with at least 20 games released had the best average critic score? Do the average user scores match this ranking?
<img src="Images/avg_critic_user.png?raw=true"/>

## I will be adding a link for my tableau of this data.
