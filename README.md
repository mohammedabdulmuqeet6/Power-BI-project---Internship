# Power-BI-project---Internship
# Power BI Twitter Engagement Analysis

## Project Overview
This project aims to analyze Twitter engagement metrics using Power BI. The focus is on visualizing various aspects of tweet interactions, impressions, and engagement rates over specific time frames and conditions.

## Tasks

### 1. Average Engagement Rate & Total Impressions
- **Visual Type**: Line Chart
- **Description**: Display the average engagement rate and total impressions for tweets posted between **01-01-2020** and **30-06-2020**.
- **Filters**:
  - Impressions must be greater than or equal to **100**.
  - Likes must be **0**.
  - Only display between **3 PM to 5 PM IST**.

### 2. Proportion of Total Clicks
- **Visual Type**: Pie Chart
- **Description**: Represent the proportion of total clicks (URL clicks, user profile clicks, and hashtag clicks) for tweets with more than **500** impressions.
- **Drill-Down**: View specific types of clicks for each tweet.

### 3. Tweets with Highest Engagement Rates
- **Visual Type**: Bar Chart
- **Description**: Display tweets in the top **10%** of engagement rates.
- **Filters**:
  - Must have received more than **50** likes.
  - Only include tweets posted on **weekdays**.
  - Only display between **1 PM to 4 PM**.
  - Word count must be below **30**.

### 4. Interaction Types by Tweet Category
- **Visual Type**: Clustered Bar Chart
- **Description**: Break down the sum of URL clicks, user profile clicks, and hashtag clicks by tweet category (tweets with media, links, hashtags).
- **Filters**:
  - Include only tweets with at least one interaction type.
  - Only display between **3 PM to 6 PM**.
  - Tweet date must be even, and word count below **40**.

### 5. Top 10 Tweets by Retweets and Likes
- **Visual Type**: Bar Chart
- **Description**: Identify the top **10** tweets based on the sum of retweets and likes.
- **Filters**:
  - Exclude tweets posted on **weekends**.
  - Show the user profile that posted each tweet.
  - Only display between **3 PM to 6 PM**.
  - Impressions must be even, tweet date odd, and word count below **30**.

### 6. Media Engagements vs. Media Views
- **Visual Type**: Scatter Chart
- **Description**: Analyze the relationship between media engagements and media views for tweets that received more than **10** replies.
- **Highlight**: Tweets with an engagement rate above **5%**.
- **Filters**:
  - Only display between **12 PM to 6 PM**.
  - Tweet date must be odd, and word count below **50**.

### 7. Replies, Retweets, and Likes Comparison
- **Visual Type**: Bar Chart
- **Description**: Compare the number of replies, retweets, and likes for tweets with media engagements greater than the median value.
- **Filters**:
  - Tweets must be posted between **June and August 2020**.
  - Only display between **3 PM to 6 PM**.
  - Tweet date must be odd, media views even, and word count below **50**.

### 8. Media Views and Engagements by Day of the Week
- **Visual Type**: Dual-Axis Chart
- **Description**: Show the number of media views and media engagements by the day of the week for the last quarter.
- **Highlight**: Days with significant spikes in media interactions.
- **Filters**:
  - Only display between **3 PM to 6 PM**.
  - Impressions must be even, tweet date odd, and word count below **30**.

### 9. Engagement Rate Comparison (App Opens vs. Non-App Opens)
- **Visual Type**: Bar Chart
- **Description**: Compare engagement rates for tweets with app opens versus those without.
- **Filters**:
  - Only include tweets posted between **9 AM and 5 PM** on weekdays.
  - Only display between **12 PM to 6 PM**.
  - Impressions must be even, tweet date odd, and word count below **40**.

### 10. Monthly Engagement Rate Trend
- **Visual Type**: Line Chart
- **Description**: Show the trend of the average engagement rate over each month of the year.
- **Highlight**: Separate lines for tweets with media content and those without.
- **Filters**:
  - Only display between **3 PM to 6 PM**.
  - Engagement must be even, tweet date odd.

## Getting Started
1. Clone this repository to your local machine.
2. Open the Power BI file and ensure your data is properly connected.
3. Refresh the data to load the latest metrics.

## Dependencies
- Power BI Desktop
- Data source with the required tweet metrics.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
