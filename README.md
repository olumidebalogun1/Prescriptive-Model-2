# **Clustering Cities Using the K-Means Model**

## **Introduction**
Clustering cities using the **K-Means model** is a powerful **prescriptive analytics technique** that uncovers natural groupings based on factors like **consumer behavior and purchasing power**. I developed and deployed my **second Python-based prescriptive model** to reveal these hidden patterns, enabling businesses to **tailor regional strategies, optimize distribution, and design impactful interventions**. This data-driven approach transforms broad planning into **targeted, localized action**, boosting both **efficiency and strategic precision**.


## **Why This Clustering Model & Project Matters**

**1. Uncovers Hidden Sales Patterns Across Cities**:

-  Clustering reveals natural groupings of cities based on performance, helping spot trends that spreadsheets often hide. 

**2. Enables Targeted Regional Strategies**:

- Instead of blanket campaigns, each cluster gets a custom playbook—what works in Cluster 1 may flop in Cluster 2. 

**3. Optimizes Product Distribution**:

- Knowing which cities behave similarly lets you fine-tune inventory and logistics, cutting down on stockouts or overstock. 

**4. Increases ROI on Marketing & Sales Efforts**:

- Tailored campaigns to specific clusters = better conversion rates and reduced marketing waste.
  
**5. Data-Driven Segmentation, Not Guesswork**:

- You're not just assuming which cities are top or low performers—the algorithm backs it with hard data. 

**6. Bridges Sales with Operations**:

- Aligns sales strategy with backend processes like supply chain and warehousing—driving operational efficiency. 



## **Files**
-	 [Dataset](https://github.com/olumidebalogun1/Prescriptive-Model-2/blob/main/1.%20Monthly%20Sales%20Dataset.ipynb): The dataset used for this analysis is fictional (synthetically generated) but designed to reflect realistic sales data.

-	[Load and Clean_data](https://github.com/olumidebalogun1/Prescriptive-Model-2/blob/main/2.%20Load%20and%20Clean.ipynb): This is the code I used to extract and clean the data before loading it into the model.

- [Code](https://github.com/olumidebalogun1/Prescriptive-Model-2/blob/main/3.%20Prescriptive%20Model%202%20-%20Clustering%20Using%20the%20KMeans.ipynb): The full code covers everything from loading and cleaning the dataset to training the model.



## **I. Key Business Question**

### **How can we group cities based on sales performance to uncover patterns for better sales strategy**?


## **II. Project Overview**

### **1. Business Challenge**:
The organization operates in multiple cities but lacks a strategic understanding of how sales performance varies across them. This makes it difficult to prioritize resource allocation, tailor regional sales strategies, and identify underperforming or high-potential markets.

### **2. Project Goal**:
To segment cities into distinct clusters based on Total Sales and Units Purchased using K-Means clustering. These clusters will help the business identify city-level patterns, optimize marketing and sales strategies, and guide regional decision-making.

## **III. Approach**:
**1. Data Cleaning**: 

- Clean and standardize the dataset to remove errors, ensure consistency, and establish a reliable foundation for accurate analysis.

**2. Feature Expansion**:

- Enrich the dataset by adding supplementary columns that provide additional context and enhance the depth of analysis.

**3. Data Preparation**:

- Aggregate total sales and units purchased by city.

**4. Modeling**: 

- Apply K-Means clustering (with 3 clusters) using these two metrics to categorize cities with similar sales behavior.

**5. Visualization**: 

- Use a scatter plot colored by cluster to visually distinguish groups, and add a table for detailed inspection.

**6. Interpretation**:

- Each cluster represents a group of cities with similar sales dynamics.

- Insights can inform which cities are high performers, moderate markets, or low performers, allowing targeted strategy formulation for each group.



## **Visualizing City Clusters Using the K-Means Model**
![Clustering Cities Using the KMeans Model](https://github.com/user-attachments/assets/ba9e814b-1c3d-437d-8c42-ff834719653e)



## **Key Insights and Strategic Recommendations**
### **Cluster 0 – High Sales & High Volume Cities**

**Interpretation**:

- Cities in this cluster show strong performance in both revenue and unit sales.

- Indicates high demand, strong customer base, and effective local execution.

**Strategic Recommendations**:

- Double down on success: Increase inventory levels, staffing, and marketing budget.

- Introduce loyalty programs to retain high-value customers.

- Launch premium products or upsell/cross-sell strategies, these cities are more likely to adopt.

- Consider using these cities as benchmarks or pilots for new product launches.

### **Cluster 1 – Moderate Sales & Moderate Volume Cities**

**Interpretation**:

- These cities perform reasonably well but have room for growth.

- Represents stable markets with potential to be moved into the high-performing cluster.
  

**Strategic Recommendations**:

- Localized promotions to drive awareness and increase repeat purchases.

- Sales training or incentive programs to boost performance.

- Monitor customer behavior and competitor activityt.


### **Cluster 2 – Low Sales & Low Volume Cities**

**Interpretation**:

- Underperforming regions with low revenue and low units sold.

- Could indicate market saturation, low demand, or ineffective sales presence.


**Strategic Recommendations**:

- Cost-efficiency measures: Evaluate whether continued investment is justified.

- Reassess market potential: Are these markets viable with a different strategy?

- If potential exists, relaunch campaigns or rebrand offerings. If not, consider consolidation or focusing efforts elsewhere.


 
