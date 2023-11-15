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
![image](https://github.com/haseres1/Exploratory_Data_Analysis_with_Python/assets/139165499/a1c0baab-5263-49e3-8bd4-542a7899c235)

2. Number of impressions on each post over time
![image](https://github.com/haseres1/Exploratory_Data_Analysis_with_Python/assets/139165499/1814697f-86f9-4956-b4f4-a6e00a154bbe)

3. Metrics like Likes, Saves, and Follows from each post over time
 ![image](https://github.com/haseres1/Exploratory_Data_Analysis_with_Python/assets/139165499/6f1b767e-5f8b-4d31-94e1-50e5689775bc)

4. Distribution of reach from different sources such as From Home, From Hashtags, From Explore, From Other columns
 ![image](https://github.com/haseres1/Exploratory_Data_Analysis_with_Python/assets/139165499/f42dee28-8529-4e30-a14d-92f8e5473bc4)

5. Distribution of engagement sources such as Saves, Comments, Shares, Likes
![image](https://github.com/haseres1/Exploratory_Data_Analysis_with_Python/assets/139165499/32ddf29a-baa5-4b1e-a694-8bc68af3a71f)

6. Relationship between the number of profile visits and follows
![image](https://github.com/haseres1/Exploratory_Data_Analysis_with_Python/assets/139165499/29b6e78d-ce5b-4eb9-9cf7-ebd555b37cef)

7. Correlation between all the features
 ![image](https://github.com/haseres1/Exploratory_Data_Analysis_with_Python/assets/139165499/20e05955-a375-43b2-b7f8-aee934969778)


# Insights and Recommendations

1. Most Instagram posts had impressions between 0 and 9999.
2. Save and like metrics are higher than follow metrics, suggesting more people save and like content than follow. Recommend adding a call to action for follows.
3. The majority of interactions are from the Instagram homepage, not external sources like hashtags or explore.
4. Fewer comments and shares compared to likes and saves. Suggest adding a call to action in each post.
5. Profile visits are higher with fewer followers, indicating gained credibility over time.
6. Strong correlations exist between columns in the dataset.




