# Unlocking Insights from Consumer Complaints Using Text Analytics

## Problem Statement

### What is the dataset?  
The **Consumer Financial Protection Bureau (CFPB)** collects and publishes consumer complaints about financial products and services in the U.S. These complaints are sent to companies for response. The public database allows users to:  
- Explore trends in complaints.  
- View individual cases.  
- Analyze data for research or business purposes.  

### Why text analytics?  
Text analysis allows us to:  
- Uncover hidden trends in consumer experiences.  
- Detect sentiment to gauge satisfaction or frustration.  
- Identify emerging issues not captured in predefined categories.  
- Support companies in improving products, services, and compliance.  

### Business relevance  
- Prioritize addressing complaints based on severity.  
- Identify emerging issues not captured in existing categories.  
- Focus on the most frustrated users first.  
- Enable data-driven improvements in products, services, and compliance processes.

## Focus of Analysis

This analysis will focus specifically on **credit reporting complaints** (around 80% of all complaints) and will examine data from the three companies with the highest number of cases:  
- **TransUnion Intermediate Holdings, Inc.**  
- **Experian Information Solutions, Inc.**  
- **Equifax, Inc.**

## Sentiment Analysis

- The **Loughran-McDonald Master Dictionary** is used to classify sentiments.  
- Created by Tim Loughran and Bill McDonald, finance professors at the University of Notre Dame.  
- Designed for financial texts, avoiding the misinterpretations common in general-purpose sentiment tools.  
- For this analysis, words are grouped into three categories:  
  - **Slightly Negative**: values between 0 and the threshold (mean – standard deviation).  
  - **Negative**: values below the threshold.  
  - **Undetected**: words not associated with negative sentiment (including neutral/positive).  

## Key Insights

- TransUnion shows a proportionally higher number of negative comments (~14.31%), though differences across companies are relatively small.  
- Most reviews fall into the **slightly negative** category. Words such as *fraudulent*, *dispute*, or *violation* carry stronger connotations and are classified as **negative**.  
- Companies should focus on these strongly negative terms to better understand the root causes of customer dissatisfaction.  
  


