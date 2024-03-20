# MLB Stolen Base Analysis
A look into the relationship between MLB players max recorded sprint speed and stolen bases accumulated throughout the 2023 season.

In this statistical analysis, I grabbed data from the 2023 MLB season from baseballsavant.mlb.com with an interest in stolen bases and sprint speed. I first downloaded a csv of the data directly from the website and imported it in python. Using the pandas library, I manipulated the data to get it in a workable format. Finally, I plotted the data with pyplot and added a linear regression line to explore the relationship.

Based on this linear regression, we can see a positive relationship between a player's top sprint speed and their total number of stolen bases. I found an R value of 0.6 and a P value of approximately 0, showing there is in fact a positive correlation between sprint speed and stolen bases

![image](https://github.com/dschondo/mlb_sb_analysis/assets/97190481/754d1c69-2572-43cd-92c2-3586b31a975c)

