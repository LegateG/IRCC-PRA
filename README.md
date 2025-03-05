# IRCC-PRA
![PRA Dashboard](/assets/img/cover.jpg)
Permanent Residency Admissions dashboard based on IRCC data

[See it here👆🏻](https://app.powerbi.com/view?r=eyJrIjoiZGFkNmNhOGMtNWI0Zi00MzJmLTliY2MtMWU3ZWNjNzdlNDAwIiwidCI6IjdjMDFkZWNlLTcwNzUtNGM3OC04MWE0LWMyMGEyODYxMzlkZSIsImMiOjF9)

I've used Power BI to visualize IRCC's open data on Express Entry and Permanent Residency admissions. Color scheme ensures accessibility.

My goal was to make a compelling and user-friendly product from raw data that delivers key insights.

Some key highlights from the analysis:
1. Seasonality: From 2015 to 2025, excluding 2020 and 2022, permanent resident admissions have typically exhibited a cyclical pattern, characterized by an upward trend in the first half of the year and a subsequent downward trend beginning in July. This seasonality is more significant in "Business" category, hitting its peak at July 2024.
2. The Express Entry pool's 701-1200 CRS score range is trending upward, signaling increased competition📈. This highlights the significance of tracking and interpreting these trends to inform immigration strategies.
3. Ontario accounts for the majority of candidates, followed by British Columbia and Alberta (Quebec is not included in federal Express Entry data)
4. Categorical Express Entry draws show clear score differentials: Healthcare🩺 consistently ranks lowest, followed by French🥐, then STEM🔬. Especially Healthcare and French have a serious score advantage over general draws in 2024. This data highlights strategic opportunities for candidates within these targeted streams.

Power BI skills gained from this project: 
1. Data acquisition, integration, feature engineering (Pulling data directly from online sources and transforming in Power Query, rather than in Excel)
2. Data modeling (Combining different data tables to work with each other, enabling slice & dice)
3. New Power BI features like swapping charts via bookmarks, integrating images via URLs, and creating boxplot charts (Not a native feature)

The report/dashboard includes four pages:
1. Total Admissions: Key figures like peak admission periods (February 2023!), total admissions to date, and the leading category (Worker Program 👷). A donut chart breaks down the categories, and a target gauge provides a quick performance overview.
2. Countries of Citizenship: A map highlights admission trends over the years, with a historical line graph to show changes. See the percentage of total admissions by country and the top 10 countries. 🌍
3. PR Admissions by Category: A bar chart shows admissions by category over time. A trend line tracks the median lowest CRS score, revealing score increases or decreases. Plus, a cumulative distribution chart shows candidate scores in the Express Entry pool. 
4. Score comparison: Healthcare and French categories versus general. Each boxplot chart shows the score advantage of the respective category over the general draws.

What's ahead of us?

The upcoming removal of LMIA-based job offer points 's expected to lead to a lower downward shift in the overall distribution of scores in the future.
