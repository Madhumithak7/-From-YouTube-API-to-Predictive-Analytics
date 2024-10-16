# -From-YouTube-API-to-Predictive-Analytics
"From YouTube API to Predictive Analytics: Comprehensive Data Analytics and Predictive Modeling for Video Performance Optimization"


This project explores a comprehensive approach to enhancing video performance through advanced data analytics and machine learning techniques. After Scrapping the data from the Youtube Channel "VJ Sidhu Vlogs" and Created a CSV file for futhur analysis. By integrating Exploratory Data Analysis (EDA), sentiment analysis, and a suite of predictive models—including Random Forests, Gradient Boosting, and Neural Networks this uncover key drivers of video engagement. The project includes rigorous hyperparameter tuning, cross-validation, and feature importance assessment to optimize model performance and extract actionable insights. These integrated efforts provide a robust framework for understanding and optimizing video content strategies, ultimately aiming to increase viewer engagement and success.

## Objectives:
1) Initialize the YouTube Client: Set up the YouTube Data API client to interact with YouTube data.
2) Fetch Channel Statistics: Retrieve general statistics about the YouTube channel, such as the number of subscribers, total views, and total videos.
3) Get Video Details: Extract detailed information about each video in the channel's upload playlist, including video statistics and metadata.
4) Data Preprocessing: Clean and transform the data to make it suitable for analysis. This includes converting data types, handling missing values, and creating new features.
5) Exploratory Data Analysis (EDA): Visualize and analyze the data to discover patterns and insights about the channel's performance and audience engagement.
6) Sentimental Analysis: Analyze viewer comments using natural language processing to gauge sentiment and correlate these findings with video performance metrics.
7) Predictive Analysis: Employ machine learning models
8) Random Forests: Implement with hyperparameter tuning and randomized search to identify optimal settings.
9) Gradient Boosting: Optimize model parameters using cross-validation and randomized search to enhance predictions.
10) Neural Networks (TensorFlow Keras): Explore deep learning models for capturing complex nonlinear patterns.
11) Model Optimization and Evaluation: Utilize hyperparameter tuning, cross-validation, and feature importance analysis to improve model robustness and interpretation. Perform extensive evaluation, including residual analysis, to ensure predictive accuracy across models.

## Tools and Libraries
1) Python & TensorFlow Keras: Core programming and deep learning framework.
2) Google API Client: To interact with YouTube Data API.
3) Pandas: For data manipulation and sentimental analysis.
4) Matplotlib & Seaborn: For data visualization.
5) Scikit-learn: Machine learning models, tuning, and validation.
6) WordCloud: To create word cloud visualizations.
7) NLTK: For natural language processing tasks like removing stop words.

## Data Preprocessing
1) Convert columns to appropriate data types (e.g., numeric, datetime).
2) Handle missing or inconsistent data.
3) Create new features, such as the day of the week a video was published and the duration of videos in seconds.

## Exploratory Data Analysis (EDA)
1) Best and Worst Performing Videos: Identify the videos with the highest and lowest view counts.
2) View Distribution: Visualize the distribution of views across different videos.
3) Engagement Metrics: Analyze the relationship between views, likes, and comments.
4) Word Cloud: Generate a word cloud to visualize the most common words in video titles.
5) Upload Day Analysis: Determine the distribution of video uploads by day of the week.
6) Trend Analysis between view counts over time period.
7) Correlation analysis between like counts,comment counts and View counts.

##Predictive and Sentimental Analysis
1) Sentiment Analysis: Applied natural language processing to viewer comments, correlating positive sentiment with higher engagement levels.
2) Predictive Modeling with Machine Learning: Implemented Random Forests, Gradient Boosting, and Neural Networks.
3) hyperparameter tuning and cross-validation: To optimize performance
4) Conducted feature importance analysis: To understand key predictors driving model predictions, leveraging Randomized Search for parameter exploration and tuning.

## Outcomes
1) The Best performing video is Vijay Antony Sir Food Delivery | Vj Siddhu Vlogs | #shorts (6,000K views)
2) The least views video is Best Crackers testing video which got around 320k views
3) While analysing view across different videos it shows a right skew, indicating a few videos have significantly higher view counts than most.
4) Analysing relationship among likes and comments, it reveals a right skew, suggesting a small number of videos have much higher viewership than most.It suggests a strategic reason behind it (viral content).
5) Analyzing video titles with a word cloud reveals prominent the keywords that can guide content strategy for appealing as suggestion for the users. The word cloud suggests content focuses on food, parties, and celebrities.
6) The videos are most likely to be uploaded on wednesday, Monday and Friday of the week.
7) The line graph shows an upward trend in view counts over time. The y-axis shows view count, labeled from 1 million to 6 million. The x-axis shows the published date, ranging from July 2023 to May 2024. The view count clearly increases over time.
8) It suggests that there may be an inverse relationship between view count/like count and comment count, and a positive relationship between view count and like count.
9) Random Forests: The model achieved a Mean Squared Error (MSE) of 504,706,782,356.27 and an R² Score of 0.71
10) Gradient Boosting: Delivered enhanced predictive accuracy with a Cross-validated MSE of 462,024,080,625.75 and an R² Score of 0.78.
11) Neural Networks: Explored complex data interactions using TensorFlow Keras, capturing nonlinear patterns.

## Recommendations
1) Engagement Insights: Identified features that most significantly influence video performance, notably likeCount with the highest model importance, guiding content strategy to emphasize these elements.
2) Strategic Recommendations: Encouraged strategic focus on engagement metrics and key upload days to maximize visibility and viewer interaction. Suggested content optimization around highlighted themes and times of increased viewer activity for continued growth and engagement enhancement.
3) Performance Monitoring: Recommended ongoing performance assessment and incorporation of emerging data trends to ensure sustained relevancy and viewer-centric content strategies

