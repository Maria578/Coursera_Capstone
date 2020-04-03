# Coursera_Capstone
This is a repository for Applied Data Science Capstone project

Part 1 - Segmenting and Clustering Neighborhoods in Toronto

Description from Coursera: 
In this assignment, you will be required to explore, segment, and cluster the neighborhoods in the city of Toronto. However, unlike New York, the neighborhood data is not readily available on the internet. What is interesting about the field of data science is that each project can be challenging in its unique way, so you need to learn to be agile and refine the skill to learn new libraries and tools quickly depending on the project.
For the Toronto neighborhood data, a Wikipedia page exists that has all the information we need to explore and cluster the neighborhoods in Toronto. You will be required to scrape the Wikipedia page and wrangle the data, clean it, and then read it into a pandas dataframe so that it is in a structured format like the New York dataset.
Once the data is in a structured format, you can replicate the analysis that we did to the New York City dataset to explore and cluster the neighborhoods in the city of Toronto.

Part 2 - Final Project: Where to go when you want to eat some pizza?

Goal - to define a place where Pizza restaurants show the highest density.
The Four Square API was used to get venues in the cities. 
CategoryID was set to show only Pizza places. This request was repeated for the both studied cities. 
Next, to get an indicator of the density of Pizza Places, I calculated a centroid of the venues to get the mean longitude and latitude values. Then the mean of the Euclidean distance was calculated from each venue to the mean coordinates. This indicator was used for evaluation.
