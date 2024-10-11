# Pricing Strategy Analysis for Google Ads

## Objective
The goal of this project is to analyze ad exchange performance data and create an optimized pricing strategy for a partner using Google Ad Manager. The task focuses on developing pricing rules, setting price splits, and identifying strategies for maintaining competitive pricing while maximizing revenue generation.

This project is based on the following test task and questions provided by the client:

## Task Requirements:
- Create some visualizations using the provided data. Ideally, one or two dashboards to understand what's going on.
- How should we set pricing rules for this partner – any split you prefer and why?
- What should be the pricing setup per each split and why?
- Should we use a target CPM, a hard floor, or both for pricing?

## Data Provided

- Ad Exchange performance data, including impressions and revenue per hour.
- Average eCPM (effective cost per thousand impressions) values by country.

## Steps Taken

1. Data Exploration and Visualization (Question 0)
Created two key dashboards for better understanding of the ad performance:

- Time-based Dashboard: Displays impressions and revenue trends across various hours of the day, identifying peak and off-peak times.
- Country-based Dashboard: Highlights average eCPM by country to identify premium, mid-tier, and low-tier markets.
These visualizations help identify optimal pricing opportunities and guide the strategic decision-making process.

2. Pricing Rule Recommendations (Question 1)
Developed a dual-split pricing strategy based on time of day and country to optimize revenue.

## Time-based Split:

- Peak hours (14:00–16:00): Suggested higher pricing due to high impressions and revenue during these hours.
- Off-peak hours (6:00–8:00): Lower pricing recommended to stimulate demand and fill ad inventory during low-traffic periods.

## Country-based Split:

- Premium Markets (Switzerland, Singapore, UAE): Higher pricing recommended due to their elevated eCPM values.
- Mid-tier Markets (US, Belgium, Denmark): Maintained average pricing as these regions show steady demand and eCPM values.
- Low-tier Markets (Ireland, France, Australia): Lower prices suggested to attract more advertisers and monetize impressions in less competitive markets.

## 3. Pricing Setup per Split (Question 2)

- Time-based Pricing:
Peak Hours (14:00–16:00): Increase CPM by 20-30% to take advantage of the highest demand. For example, countries like Switzerland could see CPM increases above £0.65.
Off-Peak Hours (6:00–8:00): Reduce CPM by 15-20% to attract more ads during low-demand periods. For example, France’s CPM could drop from £0.16 to £0.13–£0.14.

- Country-based Pricing:
Premium Markets (e.g., Switzerland): Suggested CPMs of £0.65 or higher.
Mid-tier Markets (e.g., US): Maintain CPM at around £0.21.
Low-tier Markets (e.g., Ireland, France, Australia): Keep CPMs around £0.16, with potential reductions during off-peak times.

## 4. Use of Target CPM and Hard Floors (Question 3)
Recommended a combination of both target CPMs and hard floors:
Premium Markets: Use a hard floor (e.g., £0.65 for Switzerland) to ensure valuable impressions are not undersold.
Mid-tier and Low-tier Markets: Use a target CPM approach to allow for flexible pricing based on market demand and conditions.

## Insights and Recommendations (Additional Insights)

- Opportunities in High-eCPM Markets: Switzerland, Singapore, and UAE have high eCPM values but lower impressions. Increasing ad volume in these regions could significantly boost revenue.
- Off-Peak Hours: Impressions and revenue are lower between 6:00 and 8:00. Introducing further price reductions or special deals during these hours could increase demand.
- US Market Potential: The US has a moderate eCPM (£0.21) but accounts for 90% of total impressions and revenue. Slight CPM increases during peak hours could further capitalize on this high volume.

## Tools Used

- Data Analysis: Python (Pandas, Matplotlib)
- Visualization: Dashboards created using Excel/Power BI for performance overview visualizations.

# Conclusion

The proposed pricing strategy incorporates both time-based and country-based insights to optimize revenue generation. By setting higher prices during peak hours and in premium markets, and offering competitive pricing in off-peak periods and low-tier markets, the ad exchange partner can maximize ad sales and enhance their monetization strategy.

## Files
- Assignment: Pricing Strategy Report: A detailed report answering the test questions related to pricing strategies and rules.
- Dashboard: Ads Exchange Performance Overview: A visual representation of key metrics like impressions, revenue, and eCPM performance.
