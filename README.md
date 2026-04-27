# 📊 Meta Ads Performance Dashboard

## 📌 Project Overview

"This is a Meta Ad Performance Dashboard that tracks the effectiveness of ad campaigns across 
key KPIs such as impressions, clicks, engagements, conversions, and budget. It 
provides a complete funnel view—from awareness to engagement to purchases—along with 
demographic, geographic, and time-based insights." 
---

## 🎯 Problem Statement

Step 2: Walk Through the Funnel Metrics 
"At the top of the funnel, the ads generated 216K impressions and 25.4K clicks, giving a 
very high CTR of 11.76%. This is well above the industry average, which tells me the ad 
creatives and targeting were very effective in attracting attention. 
The engagement rate is also strong at 13.56%, showing users are interacting with the content. 
However, when we move down the funnel, only 1.3K purchases were made, giving a 
conversion rate of 5.21% from clicks and a purchase rate of 0.61% from impressions. 
This indicates a big drop in efficiency from engagement to purchase." 
Key takeaway you highlight to interviewer: “The ads are good at generating awareness and 
engagement, but the purchase funnel is leaking heavily—likely due to landing page experience, 
audience mismatch, or weak offers.” 

Step 3: Break Down by Audience 
"Looking at demographics, females (43%) engage more than males (22%), and the 18–30 age 
group drives the majority of interactions. This shows the core audience is young 
females. 
From a geographic perspective, India and Brazil are the biggest engagement markets, while 
Germany and the UK likely represent higher-value audiences with stronger 
purchasing power. So, campaigns should be tailored differently for high-volume vs. high
value regions." 

Step 4: Time & Seasonality 
"The dashboard shows consistent weekly engagement, but hourly trends peak in the 
afternoon and evening hours. This suggests that ads should be scheduled and budget
weighted towards those times to maximize ROI. 
The calendar highlights certain days (19th–21st, 25th–27th) with spikes in engagement, 
which could be linked to promotions or campaign launches. This indicates that event-based 
campaigns drive higher performance." 

Step 5: Ad Type Performance 
_"When we compare formats, Video ads perform best, with the highest CTR, conversion 
rate, and engagement rate. Stories ads also perform strongly, while images and carousels lag 
slightly in conversion efficiency. 
This suggests that the budget should be shifted more towards video and story ads, as they 
generate the best return per dollar spent."_ 

Step 6: Wrap Up with Insights & Recommendations 
"In summary: 
• Strong awareness & engagement, but low purchase efficiency → optimize landing 
pages, retargeting, and offers. 
• Target audience = young females, 18–30, in India & Brazil → refine campaigns 
accordingly. 
• Best formats = Video and Stories → increase spend here. 
• Best times = afternoons & evenings → schedule ads accordingly. 
• Geography → volume from India/Brazil, value from Germany/UK → segment 
strategies. 
If I were leading this project, I’d focus on conversion optimization and retargeting strategies 
to capture the users who engage but don’t purchase."_

Marketing teams often struggle to evaluate campaign effectiveness across multiple dimensions such as audience demographics, engagement, and conversion performance.

This project aims to:

* Analyze ad performance across campaigns
* Identify high-performing audience segments
* Compare effectiveness of different ad types
* Provide actionable insights to improve ROI

---

## 📊 Key Metrics Tracked

* Impressions
* Clicks
* Engagements 
* Click-Through Rate (CTR)
* Engagement Rate
* Conversion Rate
* Purchases
* Purchases Rate
*  Total Budget 
* Avg. Budget per 
Campaign


---

## 📈 Dashboard Features

### 🔹 Performance Overview

* KPI cards showing overall campaign performance
* Budget vs performance tracking

### 🔹 Audience Insights

* Impressions by Gender
* Impressions by Age Group

### 🔹 Geographic Analysis

* Country-wise distribution of impressions using map visualization

### 🔹 Time-Based Trends

* Weekly impressions trend
* Hourly engagement patterns

### 🔹 Campaign Filtering

* Dynamic filters for:

  * Campaign Name
  * Platform (Facebook / Instagram)
  * Target Interests

### 🔹 Ad Type Analysis

* Performance comparison of:

  * Video Ads
  * Image Ads
  * Carousel Ads
  * Stories

---

## 🛠 Tools & Technologies Used

* Power BI
* DAX (Data Analysis Expressions)
* Excel / CSV (Data Source)

---

## 🧮 Sample DAX Measures

```DAX
CTR = DIVIDE([Clicks], [Impressions], 0)

Conversion Rate = (Purchases ÷ Clicks) × 100)

Engagement Rate =(Engagements ÷ Impressions) × 100 
```

---

## 💡 Key Insights

* CTR improved from **10.1% to 11.7%**, indicating better ad targeting
* Video ads showed the **highest engagement rate (~13.7%)**
* Majority of impressions came from the **20–30 age group**
* Female audience contributed a significant share of total impressions
* Peak activity observed during specific hourly intervals, useful for ad scheduling

---[

## 📷 Dashboard Preview

Demo. Page 1 - ![Alt text](https://github.com/ANALYST-AHTESHAM/Meta-Ads-Performance-Dashboard/blob/main/Meta%20Ad%20Performance%20Dashboard_page-0002.png)

Demo. Page 2 - ![Alt text](https://github.com/ANALYST-AHTESHAM/Meta-Ads-Performance-Dashboard/blob/main/Meta%20Ad%20Performance%20Dashboard_page-0001.png)
---

## 📂 Repository Structure

```
marketing-analytics-powerbi-dashboard/
││
├── dashboard pdf/
│   └── meta_ad_performance.pdf
├── dashboard/
│   └── meta_ad_performance.pbix
│
├── data/
│   ├── raw_data.csv
│   
│
├── images/
│   ├── overview.png
│   ├── demographics.png
│   ├── trends.png ....etc

│
├── Report/
│   └── Business Requirements Document (BRD) 

---

## 🚀 Business Impact

This dashboard enables data-driven decision-making by:

* Identifying high-performing campaigns and ad formats
* Improving targeting strategies
* Optimizing budget allocation
* Enhancing overall marketing ROI

---

## 🔮 Future Improvements

* Integrate real-time data sources
* Add predictive analytics for campaign performance
* Enhance segmentation with advanced filters
* Include A/B testing analysis

---

## 🙌 Acknowledgements

This project is a self-developed case study for learning and demonstrating data analytics and visualization skills using Power BI.

---

## 📬 Contact 
LinkedIn:- www.linkedin.com/in/analyst-ahtesham
Email:- khanahtesham887@gmail.com
# Meta-Ads-Performance-Dashboard
