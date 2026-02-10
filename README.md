## Sales Performance Analysis

### Project Overview
This project provides a comprehensive analysis of a US company's sales data from **2017**. The objective is to identify key revenue and profit drivers across products, sales channels, and regions to inform pricing, promotions, and expansion strategy.

### Tech Stack
- **Data Analysis:** Python (Pandas, NumPy)
- **Data Visualization:** Matplotlib, Seaborn
- **Business Intelligence:** Power BI (Interactive Dashboards)
- **Workflow:** Jupyter Notebook for ETL and EDA

### Dataset Details
The analysis uses a relational dataset consisting of:
- **Sales Orders:** Transactional data (quantities, prices, channels)
- **Products:** 30+ product types
- **State Regions:** Geography (States, Cities, Counties)
- **Customers:** 100+ corporate clients

### Data Processing (ETL)
Steps performed using Python:
1. **Cleaning:** Handle missing values and standardize date formats
2. **Merging:** Consolidated multiple CSVs into a master dataset (`sales.csv`)
3. **Feature Engineering:**
	- Calculated **Total Cost**, and **Profit**
	- Derived **Profit Margin %**, **Return ober Investmant (ROI) %**, **Cost to Profit Ratio**, **Average Orders per Customer**, and **% of Total Revenue per State**


	- Extracted **Order Month** and **Year** for trend analysis

### Key Insights & Findings
- **Dominant Channel:** The **Wholesale** channel contributes **~54%** of total business volume 
- **Peak Performance:** **May** is the highest-grossing month (~$26.35M) 
- **Geographical Leaders:**
  - **Region:** West leads overall 
  - **State:** California leads in sales volume 
- **Product Performance:**
  - **Top 3 Products:** Product 25, Product 26, Product 13 
  - **Underperformers:** Product 28, Product 10 (candidates for replacement or re-marketing) 
- **Top Customers:** **Aibox Company** — top revenue (~$3.5M) and orders (139) 

### Dashboard Visualization
1. **Navigation Page**
	 <img width="1310" height="741" alt="Nav" src="https://github.com/user-attachments/assets/97e3da74-80a1-4e96-b94b-643ee9fb97b6" />

2. **Overview** — Overview KPIs (Total Revenue, Total Profit, Sales Trends, Profit Margin, Return over Investment (ROI), etc.)
	 <img width="1306" height="737" alt="Overview" src="https://github.com/user-attachments/assets/7eabbe6a-2fd5-4de1-ab12-2d911110720a" />
	
3. **Product** — Top products, Cost to Profit Ratio, Total Units Sold, Total Orders
	 <img width="1310" height="740" alt="Products" src="https://github.com/user-attachments/assets/47b00212-9e5f-4e82-a0d9-e927c4b4d6fa" />

4. **Customers** — Top Customers, Total Customers, Total Units Sold, Total Orders, Average Orders per Customer
	 <img width="1305" height="737" alt="Customers" src="https://github.com/user-attachments/assets/4a6c2167-96c8-4bce-83bb-3016f88dadb1" />

	
5. **Geographics** — Geographic performance, % of Total Revenue, Number of States, Total Orders, Total Revenue
	 <img width="1418" height="796" alt="Geographics" src="https://github.com/user-attachments/assets/73db8552-ed57-47c6-bfc7-630c3d3dfa5c" />


### Recommendations
- Seasonal Promotions: Launch recovery campaigns in April and amplify January offers to smooth revenue swings.
- SKU Optimization: Double down on top products 26 & 25 and re-evaluate pricing or phase out low‑margin SKUs.
- Channel Expansion: Incentivize Export partnerships for high margins and introduce volume deals in Wholesale.
- Regional Investment: Replicate California’s success in other regions and boost marketing in the Northeast & Midwest.
- Margin Monitoring: Flag orders below 80 % margin and analyse cost drivers to uplift underperforming segments.



### File Structure
```
├── Data/                       # Raw Xlsx file
├── Images/                     # Screenshots for README
├── Sales.ipynb                 # Notebook (Data Cleaning & EDA)
├── Sales.pbix                  # Power BI Dashboard file
├── sales.csv                   # Final cleaned master dataset
└── README.md                   # Project documentation
```

## 👤 Author
**Loay Ayman**
- **LinkedIn:** https://linkedin.com/in/loayayman
- **Portfolio:** https://loayayman.vercel.app/








