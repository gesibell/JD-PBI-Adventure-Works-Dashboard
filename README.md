# 📊 Project  
Adventure Works Sales Dashboard (2021 – 2023) using Microsoft Power BI

---

## 📈 Project Features  

- Built using **Microsoft Power BI**  
- Comprehensive multi-year sales performance and profitability analysis  
- Clean, executive-ready UI design with modern visual hierarchy  
- Enables data-driven decision-making for executive and sales teams  

### Key Performance Indicators (KPIs)  
- **Gross Revenue:** $24.91M  
- **Total Orders:** 25K  
- **Total Units Sold:** 84K  
- **Total Cost:** $14.46M  
- **Gross Profit:** $10.46M  
- **Average Order Value (AOV):** $990.09  

### Interactive Filtering System  
- Year-based slicers for **2021, 2022, and 2023**  
- Dynamic visual filtering across all charts on selection  
- Seamless drill-down capability across product categories and regions  

### Dashboard Design  
- Modern green-and-neutral color scheme designed for corporate reporting  
- High-density information architecture displaying top metrics without clutter  
- Card-based layout separating financial, geographic, and product data  

### Revenue & Profit Trend Analysis  
- Time-series tracking comparing **Total Revenue**, **Total Profit**, and **Prior Year Revenue (Revenue PY)**  
- Highlights strong historical growth trajectory from 2021 through 2023  

### Category & Geographic Breakdown  
- **Revenue by Category:** Donut breakdown highlighting Bikes (~$23.64M / 94.89%), Accessories, and Clothing  
- **Revenue by Country:** Top market performance tracking led by United States ($7.9M) and Australia ($7.4M), followed by United Kingdom, Germany, France, and Canada  

### Product Insights & Rankings  
- **Most Ordered Product:** Water Bottle - 30 oz. (3,983 total orders)  
- **Top Product Revenue Driver:** Mountain-200 Black, 46 ($1.24M in revenue)  
- **Detailed Product Performance Table:** Itemized breakdown of Units Sold, Revenue, Profit, Profit Margin %, and Avg. Order Value  

### Key Insight  
While Accessories generate the highest volume of individual orders (e.g., Water Bottles), the **Bikes category generates 94.89% of overall revenue**, driven heavily by top-tier models like the Mountain-200. North America and Australia represent the primary revenue strongholds.

---

![Adventure Works Sales Dashboard](https://github.com/gesibell/JD-PBI-Adventure-Works-Dashboard/blob/eb539eb1b7b17f76d3fce23593d574675ec70452/Dashboard%20Preview.png)

---

## 🛠️ Technical Implementation & Architecture

### **Data Transformation & ETL (Power Query / M Language)**
- Extracted and cleaned raw relational sales data using **Power Query**
- Handled missing values, standardized text formats, and optimized data types for query speed
- Unpivoted and merged tables to establish a optimized reporting structure

### **Data Modeling & Schema**
- Designed a **Star Schema** data model (Fact Tables linked to Dimension Tables)
- Established active 1-to-Many relationships across Products, Customers, Territories, and Sales tables
- Created a custom **Date Table** for seamless time intelligence reporting

### **Advanced Business Logic & Calculations (DAX)**
- Written optimized **DAX measures** for dynamic reporting (e.g., Gross Profit Margin %, Average Order Value)
- Implemented **Time Intelligence functions** (`SAMEPERIODLASTYEAR`, `DATEADD`) to evaluate Year-over-Year (YoY) performance
- Used dynamic calculation contexts (`CALCULATE`, `FILTER`, `DIVIDE`) to prevent runtime errors and optimize report responsiveness

> [!NOTE]  
> Created with ❤️ using Microsoft Power BI by **gesibell** <br/>
> As I continue to develop my data analytics skills, I welcome any feedback or suggestions for improvement.
