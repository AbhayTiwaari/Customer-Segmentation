# Customer-Segmentation
RFM Analysis Across 2,213 Rows

## Business Problem 

In a quiet neighborhood, NeighborMart faced a critical challenge: leveraging rich customer data for targeted marketing required segmenting customers to discern high-value from low-engagement patrons. 

## Solution
categorize customers into four segments based on buying habits, enabling tailored strategies for each group..

## Step 

Implementing RFM methodology will empower NeighborMart to efficiently segment customers into four categories, yielding actionable insights for optimized targeted marketing strategies aimed at maximizing both customer value and engagement.

Methodology for RFM analysis at NeighborMart
For this project, we will be using Microsoft Excel for cleaning, analysis, and Visualization.

#### 1. *Data Cleaning*: 
Clean the dataset by filling in missing values, correcting wrongly spelled values, and removing duplicates.

#### 2. *Data Transformation*: 
Create new columns based on existing columns, Calculate the customer's age based on their year of birth; create a new column for the total number of children; Calculate the total monetary value spent by each customer; and the frequency (number of purchases) for each customer.

#### 3. *Feature Selection*: 
Identify and select the relevant features (columns) from the dataset that will be used for customer segmentation.

#### 4. *Percentrank*: 
Create a new column for Percentrank for Monetary Value, Frequency, and Recency to normalize these metrics.

#### 5. *Create RFM Score*: 
Calculate an RFM score based on the Percentrank values, summing the three columns created in the previous step, and create a new column for Percentrank.inc for the RFM score to segment customers based on their combined RFM values.

#### 6. *Customer Segment*: 
Create a new column called “Customer Segment” and segment customers based on the RFM score using VLOOKUP. Update segment names as follows:
— Top customers
— Loyal customers
— At risk
— Immediate Attention

#### 7. *Pivot Chart for Customer Segments*: 
Create a pivot chart displaying the count of customers in each segment (Top customers, Loyal customers, At-risk, and immediate attention).

#### 8. *Visualize and Analyze*: 
Create visualizations that explain each segment and add key performance indicators (KPIs). Include demographic values (average age, income, number of children, marital status) for the top customers and the “Immediate Attention” segment to understand customer profiles better.

This methodology will enable NeighborMart to effectively segment customers into four categories and gain valuable insights for targeted marketing strategies to maximize customer value and engagement

## Insight 

Analysis of 2,213 customers revealed distribution across segments: 19% top customers, 26% loyal customers, 33% at-risk/need attention, and 21% immediate attention; top customers averaged 21 purchases with $1303 spending per purchase, last purchase 21 days ago, while at-risk and immediate attention customers averaged 7 purchases with $196 spending per purchase, last purchase 56 days ago.

## Recommended 

*Top Customers*: Exclusive offers, Personalized recommendations, Priority support, Loyalty program.
*At Risk/Immediate Attention*: Re-engagement campaign, Feedback request, Customer service outreach, Win-back offers.
