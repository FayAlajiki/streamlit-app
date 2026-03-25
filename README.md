**Sales Funnel Analyzer Project**

<img width="700" height="365" alt="image" src="https://github.com/user-attachments/assets/6f7803c4-085c-4714-bf5b-581ad1f95632" />


**Executive Summary**

This project analyzes the sales funnel performance of Olist, a Brazilian e-commerce platform that connects small and medium-sized businesses with customers. The goal was to understand how leads move from acquisition to conversion, how quickly deals close, and how order fulfillment performs after purchase.

Using Python and Jupyter Notebook, I cleaned and analyzed multiple Olist datasets to evaluate conversion rates, marketing channel performance, delivery timelines, customer behavior, and retention patterns. The result was an interactive dashboard that surfaces operational and commercial insights for stakeholders.

The analysis showed that the overall MQL-to-closed-deal conversion rate was 10.4%, with paid search, organic search, and direct traffic emerging as the strongest acquisition channels. It also revealed fulfillment and retention gaps, including long deal closure cycles and no observed repeat customers in the dataset.

Next steps include improving post-purchase retention strategies, optimizing logistics partnerships, and doubling down on the most efficient acquisition channels.

**Business Problem**

In e-commerce, strong top-of-funnel acquisition does not automatically translate into sustainable business performance. Teams need visibility into how efficiently leads convert, how long it takes to close deals, how customers behave after purchase, and where friction exists across the fulfillment journey.

For this project, I wanted to answer key business questions such as:

- How effectively are Marketing Qualified Leads converting into closed deals?
- Which marketing channels are driving the strongest conversion performance?
- How long does it take to close deals?
- What customer or behavioral patterns are associated with higher conversion?
- How efficient is the order fulfillment process from purchase to delivery?
- Are customers returning to make repeat purchases?

**Methodology**

I used Python to import, clean, transform, and analyze the Olist datasets. The workflow included:

- Importing multiple datasets related to leads, orders, products, and closed deals
- Correcting data types and standardizing date fields
- Removing duplicates and handling missing values
- Merging relevant datasets for funnel and order analysis
- Calculating conversion, delivery, and retention metrics
- Building visualizations to communicate findings clearly

The project combined exploratory analysis in Jupyter Notebook with dashboard development, while VS Code was used for application setup and development.

**Skills**

Python: data cleaning, exploratory analysis, metric calculation, transformation  
Jupyter Notebook: analysis workflow, validation, exploration  
Data Analysis: funnel analysis, customer behavior analysis, time-based performance analysis  
Data Preparation: missing value handling, deduplication, data type correction, dataset merging  
Tools: VS Code, Kaggle API

**Results & Business Recommendation**

**Key Results**

- Achieved an overall MQL-to-closed-deal conversion rate of 10.4%
- Identified paid search as the top-performing marketing channel, followed by organic search and direct traffic
- Found an average deal closure time of 48.5 days
- Observed that the cat lead behavior profile had the highest conversion rate
- Measured an average of 8 days for orders to be delivered after shipment
- Found no repeat customers in the dataset, highlighting a possible retention concern

**Business Recommendation**

The results suggest that Olist should continue investing in high-performing acquisition channels such as paid search, organic search, and direct traffic, as these channels appear to generate the strongest conversion outcomes.

At the same time, the business should address post-conversion friction by improving logistics efficiency and reducing fulfillment delays. Since repeat purchasing was not observed in the dataset, retention should become a priority area. This could involve customer feedback collection, post-purchase engagement campaigns, and targeted offers to encourage second purchases.

From a stakeholder perspective, this project highlights three major action areas:

- Marketing teams should scale the channels with the strongest conversion performance
- Operations and logistics teams should improve order speed and fulfillment consistency
- Customer success and growth teams should build retention strategies to improve repeat purchase behavior

**Next Steps**

- Investigate why no repeat customers were observed and validate whether this is a dataset limitation or a true retention issue
- Segment customers further by behavior, channel, or product category to identify high-value profiles
- Analyze delayed orders in more detail to isolate operational bottlenecks
- Explore landing page combinations and campaign paths that contribute most to conversions
- Add more interactivity to the dashboard for stakeholder filtering and drill-down analysis

**Project Outcome**

This project strengthened my skills in Python-based data analysis, data cleaning, business metric evaluation, and dashboard storytelling. It also demonstrated how data can be used to uncover opportunities across acquisition, conversion, fulfillment, and retention in an e-commerce environment.
