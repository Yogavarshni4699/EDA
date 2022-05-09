# EDA-Exploratory Data Analysis

Exploratory Data Analysis in Python using pandas

A notebook that carries out Exploratory Data Analysis on web scraped data of NBA player stats. The CSV files uploaded are the files used. 

1.Web scraping data using pandas
URL: https://www.basketball-reference.com/leagues/NBA_2021_per_game.html
![image](https://user-images.githubusercontent.com/91062811/167402690-cfcf1180-85a7-4f79-bdaa-296a428d1854.png)

![image](https://user-images.githubusercontent.com/91062811/167402735-9cca9276-eca0-4e52-9bb6-65738d302cc5.png)

2.Data cleaning
Steps involved in data cleaning of this analysis:

•	Check for Data frame contents
•	Check for missing values
•	Replace missing values with 0
•	Remove unwanted columns
•	Write to CSV file 

3.Exploratory Data Analysis

•	Read data from csv file
•	Display the data frame

Answering the following question for Analysis:

Which player scored the most Points (PTS) Per Game? 
Further question, what team is the player from?
Which position is the player playing as?
How many games did the player played in the season?
Which player scored more than 20 Points (PTS) Per Game?
Which player had the highest 3-Point Field Goals Per Game (3P) ?
Which player had the highest Assists Per Game (AST) ?
Which player scored the highest (PTS) in the Los Angeles Lakers?

4.Data Visualization
Showing some analysis by making plots
Here I generated few visuals for analysis. Also, I have compared some with Pandas built-in visualization to seaborn built-in visualization for better graphs.

1.Histograms
•	pandas built-in visualization
![image](https://user-images.githubusercontent.com/91062811/167400806-9ce96ae4-71f7-4829-a348-5145d79544f8.png)

Visualization for Positions by points
•	Seaborn built-in visualization
![image](https://user-images.githubusercontent.com/91062811/167400886-771ebe45-aff1-46ab-a7a1-aa6f2a0be72b.png)

  
  
2.Box Plot

•	Pandas built-in visualization 

![image](https://user-images.githubusercontent.com/91062811/167402847-16da915a-6ed6-4eec-9857-6876c59fd4c6.png)


 
•	Seaborn built-in visualization

![image](https://user-images.githubusercontent.com/91062811/167402889-bf983546-762b-43d6-844c-c284efd0df67.png)



Stripplot:

![image](https://user-images.githubusercontent.com/91062811/167402921-d8c18ee8-40b8-4d63-942a-ab4fa418430d.png)
 

3. Heat map 

•	Heat map by Computing the correlation matrix 

![image](https://user-images.githubusercontent.com/91062811/167403091-4cc087b9-5b73-4644-805b-7fe062e19f92.png)




•	Heat Map by Masking the upper triangle

![image](https://user-images.githubusercontent.com/91062811/167403135-c5dfe3aa-92ea-4206-bee3-0965a4c8262b.png)




4. Scatter plot grid 


Scatter plot by computing the number data type for 6  columns

![image](https://user-images.githubusercontent.com/91062811/167403198-7aa0e1fc-3df8-4a5f-9556-62ced07917d9.png)

•	Scatter plot grid by computing the number data type for all  columns

![image](https://user-images.githubusercontent.com/91062811/167403236-ef415856-b97b-4610-b77b-4aa46a7be2f8.png)
 









