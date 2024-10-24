
# YouTube Data Analytics Project 📊🎥

## Overview
This project is a deep dive into **YouTube video analytics** using the **YouTube API** and **Natural Language Processing (NLP)** techniques. The focus is on understanding how different factors influence video performance in the **data science niche**. By analyzing video metadata, we aim to uncover trends that can guide content creators to optimize their strategies for better engagement.

## Project Goals 🎯
The main objectives of this project are:
- To collect and analyze YouTube video data using the **YouTube API**.
- To verify common assumptions about video performance:
  - Does the number of likes and comments impact video views?
  - How does video duration affect engagement?
  - What role do tags and title length play in attracting viewers?
- To explore trending topics using **NLP** techniques on video titles and comments.
- To engineer additional features for in-depth analysis like:
  - **Engagement ratios** (comments and likes per 1,000 views)
  - **Title length** analysis
  - **Tags** optimization

## Data Collection & Processing 📂
- Data is sourced from the **YouTube API** for the top 10-15 channels in the data science field.
- Preprocessing steps include:
  - Conversion of video duration to seconds.
  - Creating additional features such as day of the week from the published date.
  - Calculating engagement metrics like the comment and like ratios.

## Analysis Highlights 🔍
Key insights from the project:
- A strong positive correlation was found between **view count** and **like count**, suggesting that videos with more views tend to receive more likes.
- Video duration impacts engagement, with longer videos sometimes leading to higher interaction.
- Tags and title length play a crucial role in visibility, with videos having **optimized tags** and longer, descriptive titles performing better.
- NLP analysis of comments revealed frequently discussed topics, helping identify key areas of interest in the data science community.

## Visualization 📊
Several visualizations were created to illustrate trends, including:
- **Scatter plots** for engagement metrics (views vs. comments/likes).
- **Word clouds** for popular topics in comment sections.
- Analysis of video duration, title length, and tags distribution.

## Future Work 🔮
- Expanding the dataset to include smaller, emerging channels for a more diverse analysis.
- Running **sentiment analysis** on the comments to gauge viewer feedback and satisfaction.
- Exploring additional metadata such as **thumbnails**, **video descriptions**, and **upload timing**.
- Analyzing content types (tutorials, interviews, live streams) for their unique engagement patterns.

## Inspiration ❤️
This project was inspired by my passion for data analytics and the fantastic educational content by **Rishabh Mishra**. His videos motivated me to explore this domain and perform in-depth analytics on the data science community's viewing habits.

## How to Use 📥
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/YouTubeDataAnalytics.git
