# Exploratory_Data_Analysis_with_Python

# Exploratory Data Analysis of Instagram Social Media Reach

# Project Overview

Instagram produces a wealth of data daily. Content creators keenly analyze engagement and reach to identify the types of posts that perform well. In this project, I delved into an Instagram dataset for exploratory analysis. The aim was to uncover patterns, trends, and relationships within the data, empowering better decision-making and the development of strategies for maximizing reach and engagement through content posting.

# Dataset and Data Source

The Instagram Data was collected from the Keggle and the dataset contains columns such as Impressions, From Home, From Hashtags, From Explore, From Other, Saves, Comments, Shares, Likes, Profile Visits, Follows, Caption, Hashtags


# Importing Python Libraries and Datasets

Here, I incorporated essential Python libraries, including Pandas, Matplotlib, and Seaborn. Additionally, I imported the dataset crucial for my exploratory analysis, laying the foundation for further examination and insights.

# Exploratory Data Analysis 

In this section, I conduct an initial exploratory analysis of the imported dataset, focusing on the following steps before delving into exploring the dataset columns:

1. Inspect the initial five rows of the data with `data.head()`.
2. Survey all the columns within the dataset using `data.columns`.
3. Examine column details through `data.info()`.
4. Assess descriptive statistics via `data.describe()`.
5. Verify the existence of any missing values using `data.isnull().sum()`.

Next, I delved into the columns containing information about reach. Specifically, I focused on the 'Impressions' column, which holds data about the reach of an Instagram post. I conducted the following exploratory analysis of the dataset:

1. Distribution of the Instagram account Impressions
2. Number of impressions on each post over time
3. Metrics like Likes, Saves, and Follows from each post over time
4. Distribution of reach from different sources such as From Home, From Hashtags, From Explore, From Other columns
5. Distribution of engagement sources such as Saves, Comments, Shares, Likes
6. Relationship between the number of profile visits and follows
7. Correlation between all the features

# Insights and Recommendations

1. Most Instagram posts had impressions between 0 and 9999.
2. Save and like metrics are higher than follow metrics, suggesting more people save and like content than follow. Recommend adding a call to action for follows.
3. The majority of interactions are from the Instagram homepage, not external sources like hashtags or explore.
4. Fewer comments and shares compared to likes and saves. Suggest adding a call to action in each post.
5. Profile visits are higher with fewer followers, indicating gained credibility over time.
6. Strong correlations exist between columns in the dataset.




