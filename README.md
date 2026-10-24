# Sugar Cosmetics Instagram Performance Analytics

## Business Problem
Sugar Cosmetics' marketing team wants to know which Instagram content drives the most engagement, so it can decide what to post, when to post, and which formats and hashtags to prioritize.

## Dataset
- 50,000 records, 14 columns
- Period: 19 Apr 2024 to 19 Apr 2025
- No missing values or duplicate rows
- Key fields: Post Date, Post Type (Reel, Story, Video, Image), Impressions, Reach, Likes, Comments, Shares, Saves, Profile Visits, Follows

## Tools Used
- **Python (Pandas):** data validation
- **Power BI (DAX):** calculated measures, analysis and interactive dashboard

## Approach
1. Validated the data in Python: checked dates, category spellings, numeric fields, zero values and duplicates
2. Created DAX measures and columns: Total Engagement, Engagement Rate, Month-Year, Day of Week
3. Built 10 visualizations and combined them into one interactive Power BI dashboard with slicers
4. Interpreted the results and prepared business recommendations

## KPI Definitions
- **Total Engagement** = Likes + Comments + Shares + Saves
- **Engagement Rate** = Total Engagement / Reach x 100
- **Profile Visit Rate** = Profile Visits / Reach x 100

## Analysis Covered
- KPI overview (posts, likes, comments, reach, engagement rate)
- Monthly posting trend
- Top 10 posts by likes and by engagement rate
- Post type comparison (average likes, comments, saves)
- Day-of-week analysis
- Engagement funnel (Impressions > Reach > Likes > Comments > Shares > Saves)
- Hashtag analysis
- Interactive dashboard with slicers and filters

## Key Findings
- Average engagement rate across records: 18.54%
- Reels had the highest average engagement rate (18.61%), but the differences between Reel, Story, Video and Image were very small
- No single format is an overwhelming winner, so recommendations should be tested further before shifting the content mix

## Dashboard Preview

### Final Dashboard
![Final Dashboard](Final%20Dashboard.png)

### Hashtag Analysis
![Hashtag Analysis](Hashtag%20Analysis.png)

### Top 10 Posts by Engagement Rate
![Top 10 Posts by Engagement Rate](TOP%2010%20Posts%20BY%20Engagement%20Rate.png)

## Files
- `Sugar_Cosmetics_Instagram_Analytics_v2.pbix` : Power BI report
- `Final Dashboard.png`, `Hashtag Analysis.png`, `TOP 10 Posts BY Engagement Rate.png` : dashboard screenshots
