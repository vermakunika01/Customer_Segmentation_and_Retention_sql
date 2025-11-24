# Customer Segmentation & Retention Analysis
Company ABC is an e-commerce retailer specializing in catering to customers across multiple countries and product lines (Bikes, Accessories, and Clothing). The leadership team wanted to understand which customer segments drive the most value, how their engagement behaviours differ, and where opportunities exist to expand business and improve retention.

## Expected Outcome 
Strengthen customer retention and drive sustainable revenue growth by analyzing high-value (VIP) customer behaviour and uncovering opportunities to expand engagement across segments and product lines.

## Key Insights and Takeaways
**_Refer to the attached Summary Report for detailed insights and actionable recommendations_**
- **Value is concentrated but fragile:** A small group of customers contribute the majority of revenue, yet their engagement depth remains shallow, posing a risk for long-term revenue stability.
- **Category diversification is key:** Overreliance on a single high-ticket category (Bikes) limits repeat purchases and cross-sell potential.
- **Retention ROI is highest in early lifecycle:** Targeting Big Spenders within their first 60–90 days post-purchase can yield faster gains than broad-based acquisition efforts.
- **Data-driven loyalty design:** Combining behavioural metrics (frequency, recency) with transaction data can create smarter segmentation for future marketing interventions.

## Data Structure
The data is distributed across 3 tables in the 'data'  folder: 
- Customers: cutsomer details including the country they belong to and the date of their account creation (PK = customer_key)
- Products: product details like the category, subcategory, and price points (PK = product_key)
- Sales: transaction-related details with (PK = order_key + product_key, FK1 = product_key, FK2 = customer_key)

## Problem-Solving Approach
Data from customers, products, and orders tables was cleaned and analysed using **PostgreSQL (CTEs, window functions, segmentation logic)** to:
- Segment customers into four groups based on lifespan and engagement.
- Identify key behavioural (order frequency, contribution to revenue) and product-level differences across segments.
- Evaluate of retention patterns.

## Key Skills Demonstrated
- Translating raw transaction data into actionable business insights.
- Applying segmentation and churn analysis for strategic decision-making.
- Balancing analytical rigor with executive-level storytelling.

## Author & Contact 
Kunika Verma

Aspiring Business Intelligence and Data Analyst

📧 Email: vermakunika01@gmail.com

🔗 [LinkedIn](https://www.linkedin.com/in/kunikaverma/)
  
