# YouTube Data Analysis in Kenya

## 📝 Project Description
This project, titled "Data Analysis youtube_videos_EDA Project," is a comprehensive analysis of Kenyan YouTube channels using the YouTube API and Python. 

The analysis focuses on a range of metrics, including subscriber trends, video content, and audience engagement. The goal is to provide insights into channel performance and content effectiveness.

----
## 🛠️ Tools, Frameworks, and Technologies
The project utilizes the following technologies for data extraction, manipulation, and visualization:


> - Python: The primary programming language used for the project.

> - YouTube API v3: Used to access and extract data from YouTube channels and videos.

> - Google API Python Client: The library for interacting with the YouTube API.

> - Pandas: Essential for data manipulation and analysis, particularly for structuring data into DataFrames.

> - Matplotlib and Seaborn: Libraries for creating data visualizations, such as charts and graphs, to illustrate key trends.

> - NLTK and Wordcloud: Employed for text analysis on video titles and comments to identify popular themes and keywords.

---


##  Project  Methodology 

The analysis is structured into a series of steps to ensure a complete and systematic approach:

1. API Key Generation: The process begins with generating a YouTube API key from the Google Developers Console.

2. Prerequisites: A virtual environment is set up and all required Python packages are installed using conda and pip.

3. Data Extraction: Functions are used to fetch channel statistics (subscribers, views, video count) and video-specific details (title, views, likes, comments, publication date) for selected channels.

4. Data Loading: The extracted data is loaded into a pandas DataFrame for efficient data cleaning and analysis.

5. Data Cleaning & Type Conversion: Relevant columns like Views, Subscribers, and Likes are converted from objects to integers to enable numerical analysis.

6. Analysis and Visualization: The data is analyzed to identify top-performing videos and channels. Visualizations are created to showcase subscriber growth, view counts, and video engagement.

7. Text Analysis: Keywords from video titles are analyzed to identify common trends and popular topics. Word clouds are generated to visually represent the most frequently used words.

8. Sentiment Analysis: Basic sentiment analysis is performed on video comments to gauge audience reaction and sentiment.

## 📈 Analysis & Key Insights
The project provides valuable insights into video performance, audience preferences, and potential areas for strategic focus. 

The top videos serve as performance benchmarks, helping creators understand which content resonates most with their audience. 

The analysis of publication dates can also reveal performance trends over time, indicating if a channel's popularity is growing or if older content continues to perform well.

