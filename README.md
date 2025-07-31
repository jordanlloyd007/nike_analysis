# Nike - Discriptive Analysis - sample data from Kaggle
#### Jordan Lloyd - Junior Data Analyst - Atlanta GA 
## Project objective 
Nike as a company has always been a staple in my casual attire for as long as I can remember. As a life long fan it was only right to start my data analysis portfolio with an analysis of a token favorite brand of mine, Nike. Sorced from Kaggle.com of course. This Nike dataset was extracted from the dataset Adidas.nike.csv then analyzed for its KPIs and unanswered questions. I developed a dynamic comprehensive workbook in Excel, Creating multiple tables, dashboards, and pivot tables to analyze the data. 
## Dataset used
- https://www.kaggle.com/datasets/kaushiksuresh147/adidas-vs-nike

## Questions? (KPIs)
- What is the duration of time bwtween the first viewed product and the last viewed product?
- from this data sample, What are the top 3 most viewed products today?
- What products are customer favorites? limit to 5
- Create a dynamic dashboard that summarizes the data in one view
- What are the driving factors behind the discounted products?
- Create a dynamic dashboard summarizing the discounted products

## Analysis - Aggrigate, Data Wrangling, EDA and Data Mining
- Checked for anomalies using box and whiskers charts
- Created a new worksheet titled "f.nike.discriptive"
  
<img width="787" height="484" alt="Screenshot 2025-07-31 at 5 59 17 AM" src="https://github.com/user-attachments/assets/332d4c04-b8f9-4a5a-92d0-ae0c8c32f0ca" />

- This worksheet contains a statistical summary of Nike data. Also discounted product metrics
- Discovered the length of time the sample was taken - 15 mins
- Discovered the average review count was 8
- Created 2 new worksheets "c.nike.unbias"/Average +, and "d.nike.bias"/Below Average
- These two new worksheets would allow me the comfort to explore the deeper qualities of these two groups
- Created a new worksheet titled "e.nike.discount" 
- This worksheet contains a table of all records from the "b.nike.views" that contain a discount percent

- Preformed conditional formating on worksheets b. - e. using color scaling to get a quick feel for category variations
- Created a pivots table and charts in a new worksheet titled "g.nike.input" to answer the question of my analysis
- This worksheet will serve as input for dynamic dashboards and reports I plan to create in this analysis 
- "g.nike.input" includes all KPIs and valuble information collected for this analysis
- Create category boxes for "g.nike.input" worksheet including KPI's extracted from the "f.nike.discriptive"

<img width="954" height="507" alt="Screenshot 2025-07-31 at 7 23 17 AM" src="https://github.com/user-attachments/assets/d8e0a98d-997b-4839-bde2-9c713f1069fb" />

- Created a dynamic sales dashboard "g.nike.sale.dash" to display the data summary and KPIs 
- Created a dynamic discount dashboard "h.nike.discount.dashboard" to display a discount summary along with KPIs

## Sales Dashboard
<img width="1003" height="430" alt="Screenshot 2025-07-31 at 6 00 07 AM" src="https://github.com/user-attachments/assets/303d093b-fd72-4811-9964-96980b101877" />


## Discount Dashboard
<img width="692" height="455" alt="Screenshot 2025-07-31 at 6 02 56 AM" src="https://github.com/user-attachments/assets/fe6e2311-b58b-4f93-8a89-67ccac4142c7" />

- 71 % of Nikes discount products fall below the average review count of 8.
- The percentage breakdown of the rate_group ( 0 - 2.9, 3 - 3.9, 4 - 5) for the discount products chosen is near equal to the percentage breakdown of all products
- This implies that the chosen discounted products were not selected because of there rate but were chosen with the intention to ampify review counts to increase the marketing credibility   
  
- only 35 % of Nikes products are discounted
- 34 % of Nike product views are associated with discounted products
- This implies that the marketing is 97 % effective

- There appears to be a correlation between the discounted product percent and the total product view percentage
- the choice to select 35 % of Nikes products could have been done purposely by marketing to match the view percentage 

## Most viewed - Pivot Report
<img width="614" height="508" alt="Screenshot 2025-07-31 at 6 04 20 AM" src="https://github.com/user-attachments/assets/cd908362-9f46-4403-b25e-f784fcbe6e75" />

## Customer Favorite - Pivot Report + Tree Map
<img width="571" height="527" alt="Screenshot 2025-07-31 at 6 05 15 AM" src="https://github.com/user-attachments/assets/d37935d8-a764-4ec6-9a48-d23caeb24d1a" />

## Excel Worksheet Index
<img width="756" height="426" alt="Screenshot 2025-07-31 at 7 45 27 AM" src="https://github.com/user-attachments/assets/c1d248f8-e817-4104-b90b-de1e02e8d757" />

## Conclusion
- Every 15 minutes Nike products are reciving between 1 and 2 views.
- With a view count almost equal to the highest rated products, Nikes lowest rated products are receiving nearly equal attention

<img width="258" height="216" alt="Screenshot 2025-07-31 at 4 37 29 PM" src="https://github.com/user-attachments/assets/e112b56f-6044-48d2-b1a9-d2175ee9b11d" />
    
- Customers are equally intersted in all that nike has to offer			
- Discounts are targeted at products  with a review count below average. Not the rate.

<img width="379" height="88" alt="Screenshot 2025-07-31 at 4 41 56 PM" src="https://github.com/user-attachments/assets/dcd307b1-2d68-42e3-82f3-6989a22fbff5" />


- Nike customers fall into two categories, spenders $100 + and spenders under $100
  
<img width="775" height="147" alt="Screenshot 2025-07-31 at 4 46 01 PM" src="https://github.com/user-attachments/assets/7946189e-0791-4380-a341-d2105071eac8" />

- Shoes prices >=100 make up 49 % of the view_count including 62% of the product reviews
- Shoes prices >=51 make up 43 % of the view_ count including 
- majority of nike products are $100 +. These products receive 50 % of the views and make up over 60% of the reviews
- Products $50 + make up 40% of nikes inventory, receiving 40 % of the views and 30% of the review count







