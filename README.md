# IS107 Laboratory-Work1- Introduction to Business Intelligence & PowerBI

# PART 1: Launching Power BI & Loading Data

## Step 1: Open Power BI Desktop
 #### This screenshot shows the Power BI Desktop startup screen after launching the application, ready for data import and analysis.

<img width="1920" height="649" alt="image" src="https://github.com/user-attachments/assets/808ce3d9-fd5c-407c-baf9-c1ccd7bf2067" />

## Step 2: Load the Dataset 
#### This screenshot shows the process of importing the CSV dataset into Power BI Desktop, where the file Week1_Basic_Sales_Data.csv is selected and loaded for analysis.

<img width="1920" height="1030" alt="image" src="https://github.com/user-attachments/assets/af83531b-c13a-4dd7-bd09-f3b98122a597" />

## Step 3: Verify Data in Data View
#### This screenshot shows the dataset loaded in Power BI's Data View, where all columns are visible and data types for each column can be verified and adjusted if needed.
<img width="1919" height="1030" alt="image" src="https://github.com/user-attachments/assets/6adc308e-93f7-4046-8363-fbe022822556" />

○ Are all columns visible? Yes, all columns are visible. 

○ Is “Date” formatted as Date? Yes, it was formatted as a date but in a long date format . 

○ Is “Sales” formatted as a Decimal Number? No, it was formatted as whole number

# PART 2: Exploring the Interface 

## Report View 
#### This screenshot shows Power BI's Report View, where users can create and arrange visuals like charts and graphs on the canvas.

<img width="1920" height="1036" alt="image" src="https://github.com/user-attachments/assets/074eb112-a10e-4b93-8a73-98a897974b6d" />

## Data View 
#### This screenshot shows Power BI's Data View, which allows users to see and inspect the raw dataset, including all rows and columns.

<img width="1919" height="1030" alt="image" src="https://github.com/user-attachments/assets/6adc308e-93f7-4046-8363-fbe022822556" />

## Model View 
#### This screenshot shows Power BI's Model View, where relationships between tables can be created and managed for proper data modeling.

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/1251904d-b822-4cb0-a2d7-4eaf940cc914" />

# PART 3: Creating Auto-Generated Visuals 

## Step 1: Quick Visualization 
#### This screenshot shows the automatic chart created when the Sales field is dragged onto the canvas, giving a quick summary of total sales.

<img width="506" height="480" alt="Screenshot 2026-02-19 080436" src="https://github.com/user-attachments/assets/a23030c3-edb2-4338-882c-0fdfb5840a6b" />

Question: 

● What type of chart was created?
 A clustered column chart was created.

● What does it show? 
It shows the sum of sales on the y-axis, summarizing over all total sales.



## Step 2: Create a Sales by Region Chart 
#### This screenshot shows a Clustered Column Chart displaying total sales per region, helping to compare regional performance visually.

<img width="564" height="480" alt="Screenshot 2026-02-19 080520" src="https://github.com/user-attachments/assets/0d9d7891-9d31-45c7-ba50-61c3a3656016" />

#### Question: 
● Which region has the highest sales? The west region has the highest sales.


## Step 3: Sales by Category
#### This screenshot shows a Pie Chart representing sales distribution across different product categories, highlighting the dominant categories.

<img width="805" height="360" alt="Screenshot 2026-02-19 080546" src="https://github.com/user-attachments/assets/eb4b4ffb-dbae-457e-81df-af60b7b1dce4" />

#### Question: 

● Which category dominates? The electronics category dominates the whole pie chart.

● Is the distribution balanced? No, distribution is not balanced.


## Step 4: Sales Over Time

#### This screenshot shows a Line Chart illustrating the trend of sales over time, making it easy to identify growth or decline patterns.

<img width="647" height="508" alt="Screenshot 2026-02-19 080603" src="https://github.com/user-attachments/assets/69bcd0bf-8029-4c8d-aa53-90293276dbc7" />

#### Question: 
● Is there growth? No, because the sales are decreasing in 2025.

● Any noticeable trend? Yes, there is a clear downward trend.

PART 4: Basic Data Insight Interpretation

#### Question: 

● Which region contributes most revenue? The west region contributes most revenue. 

● Which product category performs best? The electronics perform best. 

● Are sales consistent across dates? No. Sales are not consistent as  they drop sharply from   2024 to 2025, showing a significant decline.

● What business recommendation can you suggest? Investigate the drop, boost high-performing categories, and improve lower-performing regions.

## LABORATORY QUESTIONS 

### Part A – Technical Questions
1. What are the five columns in the dataset?
	Date, Product,Category, Region, and Sales

2. What data type is assigned to the “Sales” column? 
	The data type that was assigned to the “Sales” column is the decimal number.

3. Which Power BI view allows you to see raw data?  
	The table view allows me to see raw data.
	
4.What chart type is best for showing trends over time? 
	The best chart type for showing trends over time is the line chart.
	
5. What aggregation is automatically applied to Sales? 
	The aggregation that was automatically applied to Sales is sum.

### Part B – Analytical Questions 

6. Which region has the highest total sales?
 West has the highest total sales.
 
7. Which category has the lowest performance? 
	Office supplies have the lowest performance.
	
8. Are sales increasing, decreasing, or stable? 
	Sales are decreasing.
	
9. If you were a manager, which region would you prioritize? 
       If I were a manager I would prioritize the north  region since it has the lowest sales. Focusing there would help improve the overall sales.
	   
10. Provide one actionable recommendation based on the data. 
      Launch a targeted marketing campaign like promotions or discounts  in the North region to boost its lower sales and improve overall revenue.

# ENHANCEMENT SECTION 

## Task 1: Add a Card Visualization 

<img width="605" height="524" alt="Screenshot 2026-02-19 080656" src="https://github.com/user-attachments/assets/db849747-8864-4f0e-a1de-aad308c42f8a" />

#### Question: 
● What is the total sales amount? The total sales is 220,000.

## Task 2: Add Slicer 
<img width="756" height="592" alt="Screenshot 2026-02-19 080747" src="https://github.com/user-attachments/assets/b5954d62-cbf7-447a-bb15-f92349f69027" />

#### Question: 
● What happens to other visuals when you click a region? 
	The visuals change when I click a specific region, it is like filtering regions.
	
● Why is filtering important in BI? 
	To filter out the different sales visualizations of regions.

## Task 3: Sort Sales

<img width="740" height="605" alt="Screenshot 2026-02-19 080711" src="https://github.com/user-attachments/assets/059dc81f-fa35-45bd-a95d-b148a5619f5c" />

## Task 4: Identify Outliers 

● Which region is significantly higher or lower? 
	West is the significantly higher region while the North region is the lowest

● What might explain that difference? 
	The west region highest sum of sales and the north region has the lowest.


	
#### Question: 
● Does sorting improve readability? Yes sorting improve readability

● Why? Because it sort the sales from highest to lowest





# _________________________________________________________________________________________________________________________________________


# Insight Summary

After loading the sales data and creating the visualizations in Power BI, I have identified the following five key insights:

Electronics is our "Powerhouse" Category: When I created the Pie Chart, it was clear that Electronics dominates the sales. It isn't a balanced split at all; people are buying tech products way more than Furniture or Office Supplies. This shows where the company is making most of its money.

The West is Winning, the North is Struggling: By looking at the Clustered Column Chart, the West region stands out as the top performer. On the flip side, the North region has the lowest sales. This tells me that our current marketing or sales team is much more successful in the West than in the North.

Alarming Downward Trend for 2025: The Line Chart was the most surprising visual. Even though total sales look okay on the Card visual with 220,000, the trend shows a sharp drop moving into 2025. This means that while we did well in the past, something is going wrong lately and sales are decreasing.

Office Supplies Need Help: Out of all the categories, Office Supplies performed the worst. Since the distribution isn't balanced, the business is "top-heavy," meaning if Electronics sales ever fail, the whole company will be in trouble because Office Supplies aren't selling enough to back them up.

Interactive Filtering Changes the Story: Using the Slicer tool showed me that the data is very different depending on the region. For example, the "Total Sales" card changes completely when you filter by region. This proves that a single "Total" number doesn't tell the whole story—you have to look at the specific regions to see who is actually contributing to that 220,000.

My Final Recommendation
Based on the data, I suggest the company investigate why sales are dropping in 2025 immediately. While they should keep supporting the West, they need to launch a special promotion or discount campaign in the North to try and bring those low numbers up to match the rest of the regions.










