# Clash of Titans: State of Play vs Xbox Games Showcase

## 1. Introduction
This project aims to analyze the engagement and sentiment of the public regarding the State of Play and Xbox Games Showcase events. The analysis includes data distribution, main topics discussed, and engagement patterns over time.

## 2. Objective and Scope
- Analyze user engagement (likes, comments, and reposts) related to the events.
- Evaluate the sentiments expressed in the comments (positive, negative, neutral).
- Identify the main topics and keywords discussed.
- Examine the temporal distribution of comments and engagement.

## 3. Data Description
### Data Types
- **Name:** User's name
- **Username:** User's handle on the platform
- **Comments:** Comments made by users
- **Likes:** Number of likes received
- **Replies:** Number of replies received
- **Shares:** Number of shares
- **Location:** User's location
- **Verified:** Whether the user is verified
- **Blue Verified:** Whether the user is blue-verified
- **Date:** Date of the comment
- **Hour:** Hour of the comment
- **Sentiment:** Sentiment of the comment (positive, negative, neutral)
- **Emotion:** Emotion expressed in the comment
- **Most Common Keyword:** Most common keyword in the comment

### Data Sources
- **Twitter:** TWCommentExport Extension
- **Reddit:** PRAW library
- **YouTube:** WEBHARVY app
- **Facebook:** ESUIT Extension
- **Instagram:** ESUIT Extension

### Data Quantity
A total of 3456 comments were collected.

## 4. Tools and Languages
- **Languages and Libraries:**
  - Python (Pandas, NLTK, tex2emotion, tqdm, collections)
- **Tools:**
  - VS Code
  - Tableau
  - Excel

## 5. Methodology
### Engagement Analysis
- Summed the values of likes, comments, and reposts to create a total score per comment.
- Compared the total scores between the events.

### Temporal Analysis
- Used the dates (month, day, and hour) of each event to identify:
  - Most commented hours
  - Most commented times of the day
  - Most commented days
  - Most commented topics per day using keywords

## 6. Key Insights and Conclusions
Here are the top 10 most interesting insights selected:

1. **Engagement Speed:**
   - Xbox's content achieved higher engagement in a shorter period compared to Sony.

2. **Popularity:**
   - Xbox's event appears to have been more popular or more effectively promoted, resulting in significantly higher views in a shorter time.

3. **Astrobot's Impact:**
   - Astrobot consistently drove high engagement across multiple days, indicating strong interest and discussion among users.

4. **Event-driven Engagement:**
   - PlayStation's comment spikes coincided with specific events or game announcements, suggesting that major releases or updates significantly influence engagement levels.

5. **Variability in Xbox Engagement:**
   - Xbox showed varying levels of engagement after the initial event day, indicating that sustained interest might depend more on ongoing updates or diverse game releases rather than single events.

6. **Division of Opinions at State of Play:**
   - State of Play showed a significant division of opinions, with almost equal proportions of positive (52%) and negative (46%) comments, indicating strong influence on gamers' sentiments.

7. **Positive Reception of Xbox Games Showcase:**
   - Xbox Games Showcase received a significantly higher percentage of positive comments (77%) compared to negative comments (21%), suggesting a more favorable reception.

8. **Platform Comparison:**
   - YouTube and Reddit emerge as the most active platforms for gaming discussions, indicating their importance for audience engagement in this context.

9. **Disproportionate Engagement:**
   - Verified users, who make up only 13% of the user base, receive 72% of the engagement. This highlights a significant skew in user interaction and engagement toward verified accounts.

10. **Time of Day Engagement:**
    - The high number of comments in the morning and at night suggests that gamers have more free time during these periods, indicating peak times for engagement.

## 7. How to Reproduce the Analysis
### Data Extraction
- **Twitter:** TWCommentExport Extension
- **Reddit:** PRAW library
- **YouTube:** WEBHARVY app
- **Facebook:** ESUIT Extension
- **Instagram:** ESUIT Extension

### Data Manipulation
- **Languages and Libraries:**
  - Python (Pandas, NLTK, tex2emotion, tqdm, collections)

### Installation Instructions
1. Install the necessary libraries:
   ```bash
   pip install pandas nltk tex2emotion tqdm collections
   ```

2. Run the data extraction scripts for each platform.

3. Run the data preprocessing and analysis notebooks/scripts.

### Execution Steps
1. Load the datasets.
2. Preprocess the data (cleaning, filtering, etc.).
3. Perform sentiment analysis using NLTK and tex2emotion.
4. Analyze engagement metrics.
5. Create visualizations in Tableau.
6. Summarize the findings.

## 8. Contact Information
For any questions or comments, please contact:
- **Phone:** +258 855673021
- **Email:** sheltonelias992@gmail.com
