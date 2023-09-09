## MARKETING ANALYSIS: WHO ARE THE SPROCKET'S CUSTOMERS?

# INTRODUCTION
I recently completed the KPMG virtual data analytics internship; it was an amazing experience learning from one of the world-class consulting firms. The internship is one of the biggest, free, virtual and educative internship programs that gives real-life experience, testing knowledge of skills such as Consultation, Data Analytics and Data Visualization. 
The KPMG virtual internship is made up of three tasks which are meant to examine your skills at different level. 

# PROBLEM STATEMENT 
Sprocket Central PTY Ltd is an organization that specializes in high quality bikes and cycling accessories sales and needs help with its customer and transactions data. The organization has a large dataset relating to its customers, but their team is unsure how to effectively analyze it to help optimize its marketing strategy. 
The organization provided KPMG with 3 datasets
1. Customer Demographic
2. Customer Addresses
3. Transaction data
4. New Customer List
# TOOLS USED – Excel, PowerPoint, Tableau

# SKILLS DEMONSTRATED – Data Cleaning, Data Exploration, Data Manipulation, Data Analysis, Visualization 

# FIRST TASK: DATA QUALITY ASSESSMENT
The first task in this exercise is to test my data exploration. Data exploration involves identifying data quality and its readiness for analysis. Data exploration is one of the most important phases of data analysis as it is the only way to ensure data integrity and also lay ground for sound data-driven decisions.
After data exploration, the task required that I draft an email to the client identifying the data quality issues and strategies to mitigate these issues. To serve as a guide and to aid the data exploration process, KPMG provided the Data Quality Framework Table.
After due data exploration, I identified all data quality issues and ways to mitigate them. Below is the email drafted to Sprocket Central Pty Ltd informing them of the issues identified in the dataset and how this will impact the analysis. 

# SECOND TASK: DATA INSIGHTS 
This task required that the three datasets (Customer demographic, customer address and transactions) should be utilized to recommend which of the company’s 1000 new customers should be targeted to drive the most value for the organization. 
The recommendation should however be shared using a PowerPoint in order to outline the approach used in building this recommendation. As agreed by Sprocket Company, the recommendation should be built on the following 3 phases - Data Exploration; Model Development and Interpretation.
Prepare a detailed approach for completing the analysis including activities – i.e. understanding the data distributions, feature engineering, data transformations, modelling, results interpretation and reporting. This detailed plan is to be presented to the client company in order to get a sign-off to signify their consent for working on their dataset. 
Also, the instruction provided is to ensure the PowerPoint presentation includes a detailed approach for our strategy behind each of the 3 phases including activities involved in each - i.e. understanding the data distributions, feature engineering, data transformations, modelling, results interpretation and reporting. This detailed plan needs to be presented to the client to get a sign-off.

# THIRD TASK: DATA VISUALIZATION AND PRESENTATION 
Before visualizing data, it is important to ensure proper steps are taken to ensure the integrity and quality of such data. The most important steps taken to ensure data integrity is Data cleaning. Data cleaning involves fixing, formatting or removing incorrect, incomplete, duplicate data within a dataset. A lot of the steps taken in cleaning the Sprocket company dataset have been carried out and explained in the first task, however to mention but a few, these steps include 
•	Removing blank cells and duplicates 
•	Fixing structural errors such as typos, incorrect capitalization, 
•	Filtering out unwanted outliers which appeared in columns such as the “DOB’ column etc 
•	Handling missing data – missing data were handled in two ways and one is to drop the observed missing values and second is to input missing values based on other observation. Example of the first option was adopted to drop blank cells in “Job Title” column while an example of the second option was adopted in filling out the “region” column (The regions are Victoria, New South Wales and Queensland) 

# Data Analysis
After taking the necessary steps to ensure the data integrity, the next step before visualizing such data is Data Analysis. Data Analysis involves transforming and interpreting data to discover insights, draw conclusions and support decision-making. The steps taken in the Data Analysis process include 
•	In the Customer Demographic dataset, I created a “Age” column which was calculated using the “DOB’ column and the formula (NOW () – DOB/365)
•	In the Transaction dataset, I created a “Profit” column using the “List Price” and “Standard Cost” columns and the formula (List Price – Standard Cost). 
•	Using the VLOOKUP function, I merged the Customer Demographic table and the Transaction table. 
•	Also in the Transaction dataset, I created a “Comparison Date” column which is the last day/ earliest day in the “Transaction Date” column 
•	I created a “Recency” column (how recent a customer bought a product) which was calculated using the Comparison column and the Transaction column (Comparison - Transaction).  
•	I created pivot tables explore trends and patterns in the data and also summarize the data to extract insights from the data. 

# Data Visualization
I created a dashboard to display my insights and communicate my analysis through visual. 
<img width="554" alt="My KPMG Virtual Internship Dashboard" src="https://github.com/mansuurah/KPMG-Virtual-Internship-Who-Are-Sprocket-Customers-/assets/136700743/a8542834-1bd0-4502-b25b-341f6b31807f">

# INSIGHTS 
Sprocket Central customers are spread across 3 states - NSW, QLD, VIC, in Australia. Notably, customers from NSW generated the highest profit, contributing approximately $400,000, and made 37,262 bike-related purchases. Also, among the three states, the chart reveals that NSW has the highest number of customers who own a car (385) as well as the highest number of customers who do not own a car (353). The number of customers that own a car in VIC is slightly higher than those that do not own a car while those of QLD is split quite evenly distributed. However, car ownership distribution in both states is considerably lower than NSW. 

Throughout the fiscal year 2017, customers between the age 45-54 generated the highest profit for the company to total of $221,080, which is followed closely by the 35-44 age group. Similarly, this 45-54 customers age group have purchased the highest number of bikes for all six brands and the highest number of bike accessories. Additionally, it is worth noting that the brand "Solex" was the most purchased brand among customers of all age groups, suggesting its popularity and market appeal.

This chart showcases the average order for each month. Notably, all months from January to December recorded at least 1000 orders, indicating consistent customer engagement throughout the year. October secured the highest number of orders, reaching 1,756. It was closely followed by August with 1,733 orders and July with 1,703 orders. 

# RECOMMENDATIONS 
1. The company should focus on NSW to drive sales and increase profits as it has the highest number of customers who made purchases and the highest number of customers who own and do not own cars. Targeted marketing campaigns should be developed based on customer behavior and preferences identified from the data. Separate campaigns can be created to promote bikes as a convenient alternative to car ownership. For car owners, emphasize the benefits of using bikes for certain trips to reduce maintenance and cost. For non-car owners, highlight the advantages of choosing bikes over cars due to lower maintenance and cost. Conducting further research can provide deeper insights into the factors influencing car ownership and cycling habits in each state.
2. Given the higher contribution of Mass customer segment to overall orders, allocate resources to effectively engage and retain customers from this segment through loyalty offers like VIP customer events. Tailor marketing messages and promotions to address their specific needs and preferences.
3. Implement strategies like exclusive benefits, dedicated customer services, event experiences to regularly monitor and analyze the response and engagement of the High Net worth and Affluent customer segments in order to influence the purchasing choice of these customer segments. 
4. Investigate the factors such as specific marketing campaigns, events, promotions, or external factors that may have influenced customer behavior that contributed to the high order volumes in peak order months and also factors that might have contributed to the lower order volume for improvement or potential challenges. Leverage these insights to replicate successful strategies to maximize order volumes across all months subsequently. 
5. For 18-24 age group who are tech-savvy generation and have low purchase of bike and its accessories, the company can create awareness campaigns highlighting the physical and mental health benefits of cycling, the latest trends, bike models, and accessories that align with their lifestyle and fashion sense through platforms like social media platforms and influencer marketing highlight 
