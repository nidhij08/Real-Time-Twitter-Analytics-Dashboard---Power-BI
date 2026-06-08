# Twitter Analytics Dashboard

## Project Overview

This project is a Twitter Analytics Dashboard developed using Power BI. The dashboard analyzes tweet performance and user engagement through multiple interactive visualizations. Various filtering conditions, calculated measures, and time-based visibility rules have been implemented to provide meaningful insights into tweet interactions and engagement patterns.

## Objectives

The main objective of this project is to analyze Twitter data and understand how different tweet characteristics influence user engagement. The dashboard helps identify trends, compare performance metrics, and discover high-performing content.

---

## Tasks Implemented

### 1. Tweet Interaction Breakdown by Category

* Created a clustered bar chart showing:

  * URL Clicks
  * User Profile Clicks
  * Hashtag Clicks
* Grouped by tweet categories:

  * Tweets with Media
  * Tweets with Links
  * Tweets with Hashtags
* Applied filters:

  * At least one interaction must exist
  * Tweet date must be an even number
  * Tweet word count greater than 40
* Visibility condition:

  * Displayed only between 3 PM IST and 5 PM IST

### 2. Engagement Rate Comparison

* Compared engagement rates between:

  * Tweets with App Opens
  * Tweets without App Opens
* Applied filters:

  * Weekday tweets only
  * Posted between 9 AM and 5 PM
  * Impressions must be even numbers
  * Tweet date must be odd
  * Character count greater than 30
  * Excluded tweets containing the letter 'D'
* Visibility condition:

  * Active only between 7 AM–11 AM IST and 12 PM–6 PM IST

### 3. Media Interaction by Day of Week

* Created a dual-axis chart showing:

  * Media Views
  * Media Engagements
* Analyzed interactions by weekday for the last quarter
* Highlighted spikes in engagement
* Applied filters:

  * Even tweet impressions
  * Odd tweet dates
  * Character count above 30
  * Excluded tweets containing the letter 'H'
* Visibility condition:

  * Active only between 7 AM–11 AM IST and 3 PM–5 PM IST

### 4. Replies, Retweets, and Likes Comparison

* Created a bar chart comparing:

  * Replies
  * Retweets
  * Likes
* Applied date filter:

  * Tweets posted between June and August 2020
* Used SUM aggregation for all engagement metrics

### 5. Monthly Engagement Rate Trend

* Created a line chart showing:

  * Average Engagement Rate by Month
* Compared:

  * Tweets with Media
  * Tweets without Media
* Used:

  * Month as time dimension
  * Average Engagement Rate as metric

### 6. Top 10 Tweets by Engagement

* Identified top-performing tweets using:

  * Retweets + Likes
* Displayed associated user profiles
* Applied filters:

  * Weekdays only
  * Even impressions
  * Odd tweet dates
  * Word count less than 30
* Visibility condition:

  * Displayed only between 3 PM IST and 5 PM IST

---

## Tools and Technologies

* Power BI
* DAX Measures
* Data Transformation
* Data Modeling
* Interactive Dashboard Design

## Key Features

* Interactive visualizations
* Dynamic filtering
* Time-based visibility conditions
* Advanced DAX calculations
* Data-driven insights
* User engagement analysis

## Learning Outcomes

Through this project, I gained practical experience in:

* Data cleaning and preparation
* Power BI dashboard development
* DAX calculations
* Conditional filtering
* Time-based visualization logic
* Data analysis and reporting
* Interactive dashboard design

## Conclusion

This dashboard provides a comprehensive analysis of tweet performance and engagement metrics. By applying advanced filtering conditions and dynamic visualizations, the project helps identify trends, compare engagement behaviors, and evaluate the effectiveness of different tweet categories.
