# Movies-Automobile-Analysis
Dataset Overview:

The dataset comprises information about various movies, including details like budget, revenue, release date, genres, popularity, and more.
The objective of this analysis is to unravel interesting trends, correlations, and facts hidden within the data.
Key Steps in the Notebook:

Importing Libraries: I begin by importing essential Python libraries, such as NumPy, Pandas, Seaborn, and Matplotlib, which are crucial for data manipulation and visualization.

Loading the Dataset: The movies dataset is loaded into the notebook using Pandas. I also identify and drop unnecessary columns, optimizing our dataset for analysis.

Data Cleaning: I clean the dataset by removing duplicate rows and eliminating entries with missing or zero values, ensuring the quality of our data.

Data Transformation: I convert data types, such as the release date, budget, and revenue, to more suitable formats for analysis. Additionally, I also flatten JSON columns for ease of interpretation.

Exploratory Data Analysis (EDA): This is the heart of our analysis, where I delve into the dataset to discover intriguing patterns and relationships:

I identified the five most expensive movies and compared them with the cheapest movie in terms of budget, revenue, and viewer ratings.

I uncovered the top five most profitable movies and compared the highest and lowest profits, shedding light on the diverse outcomes of different movie approaches.

I identified the ten most popular movies based on their popularity scores.

I showcased movies that have received ratings above 7, providing insights into viewer preferences.

I analyzed the frequency of movies in each genre, generating a bar plot to visualize genre popularity.

Three Data Visualizations with Stories:

Yearly Movie Release Trend: I presented a line plot that demonstrates the trend in yearly movie releases. This visualization highlights a gradual increase in movie production from the 1980s to 2010, followed by a decline, possibly due to factors like the COVID-19 pandemic.

Revenue vs. Budget: A scatter plot illustrates the relationship between movie budget and revenue. While most movies show a positive correlation, some outliers indicate that high budget doesn't guarantee high revenue, emphasizing the unpredictability of the film industry.

Average Rating Distribution: I depict a histogram showcasing the distribution of average ratings. Most movies fall within the 6-7 rating range, indicating that the majority of films are perceived as average by viewers.

In this notebook, I aimed to provide a comprehensive exploration of the movies dataset, offering a glimpse into the intriguing world of cinema through the lens of data analysis.
