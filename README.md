# Supply Chain Analysis

An exploratory data analysis project on the supply chain of a Fashion and Beauty startup (makeup products), covering product performance, shipping, cost, and quality metrics to identify areas for improving supply chain efficiency.

## What is Supply Chain Analysis?

Supply chain analysis evaluates every stage of a supply chain from acquiring raw materials from suppliers to delivering the final product to customers to identify where the process can be improved, shortened, or made more cost-effective.

## Dataset

The dataset is based on the supply chain of makeup products and includes features such as:
- Product Type, SKU, Price, Availability
- Number of Products Sold, Revenue Generated
- Customer Demographics
- Stock Levels, Lead Times, Order Quantities
- Shipping Carriers, Shipping Costs, Transportation Modes
- Manufacturing Costs, Defect Rates

## Analysis Covered

- **Price vs Revenue** — relationship between product price and revenue generated, by product type
- **Sales by Product Type** — revenue share across skincare, haircare, and cosmetics
- **Revenue by Shipping Carrier** — comparing carriers on total revenue generated
- **Lead Time & Manufacturing Costs** — average values by product type
- **SKU-level trends** — revenue, stock levels, and order quantities per SKU
- **Shipping Costs by Carrier**
- **Cost Distribution by Transportation Mode**
- **Defect Rate Analysis** — by product type and by transportation mode

## Key Insights

- Skincare products generate the most revenue (45%), followed by haircare (29.5%) and cosmetics (25.5%)
- Carrier B generates the most revenue but is also the most expensive of the three carriers
- The company spends the most on Road and Rail transportation
- Haircare products have the highest defect rate among product types
- Road transportation has the highest defect rate, while Air transportation has the lowest

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn

## Dataset File
`supply_chain_data.csv` — supply chain records for a makeup products business.
