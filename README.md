# Reddit Posts Analysis on Gaming Preferences

## Project Description

This project involves web scraping Reddit posts related to gaming preferences using Python's PRAW library. Data from 11 Reddit posts was extracted, including post titles, authors, scores, and comments, and saved to a CSV file for analysis. A Tableau dashboard was then created to visualize insights from the data, focusing on topics like single-player vs. multiplayer gaming.

## Data Extraction

The data was extracted from specific Reddit URLs using Python and the PRAW library. Key fields retrieved include:
- **Title** of the post
- **Author** of the post
- **Score** of the post (upvotes)
- **Number of comments**
- **Comments** text

The collected data is stored in `reddit_data.csv`, making it easy to analyze and visualize.

## Dashboard Overview

The Tableau dashboard created for this project provides insights into the Reddit posts. Here are some of the main components:

1. **Word Cloud** - Visualizes frequently occurring words from the post comments, highlighting popular terms like "games," "play," "multiplayer," and "single," reflecting discussions on different gaming modes and experiences.

2. **Score by Title of the Post** - A bar chart showing the scores (upvotes) for each post. Posts favoring single-player games over multiplayer tend to have higher engagement, indicating a strong preference among commenters for single-player experiences.

### Dashboard
![Dashboard Image](Images\Reddit_posts_Analysis_Dashboard.png)