### ✨Recommendation Systems✨

### Breif Intro :

Recommendation Systems taking a new revolutionary step in e-commerce, It is evident that
Amazon stated that these systems boost revenue by 35% from the product recommendation in the past. In
this, we explored the models that can improve revenue by promoting upselling and cross-selling through
product recommendations throughout the customer journey.

Three models have been explored to provide personalized recommendations for a customer and

to foster customer loyalty aiding long-term relationships and higher conversion rates.
#### Data Provided for the Analysis:
- Data Provided : Online_Sales, Customer, Discount_Coupon, Tax_amount, Marketing Spend
- Initial Data consists of 1468 customers, 1145 products transactional details
- At higher level, data has info on customerID, Gender, Location, transactionID, transaction Date, productID,
productCategory, Product_Price, Quantity, CouponStatus, CouponCode, Discount
- We have considered 1338 customers’ transactional data containing 1110 products from 20 categories with 46 coupons
available for a few of them.

#### Model Methodology

_**Data Preprocessing**_

- Data Integration
- Standardize data types
- Null value analysis
- Handled Duplicates Transaction IDs
- Feature Generation
- Distribution Analysis
- Correlation

_**Customer-Product Matrix**_

- CustomerID, ProductSKU, user interest
- User Interest = 0.45*purchase+0.2*quantity+
0.35*recency
- Sparse Matrix
- Calculated Sparsity >90%

_**DataModeling**_
- Collaborative Filtering
1. User-Based: KNN
2. Product-Based: KNN
High Sparsity – TurncatedSVD
- Content-Based
1. Product feature Dataset
2. Cosine similarity matrix – fetch top 5 products by sorting on similarity scores

![image](https://github.com/user-attachments/assets/e390aa3d-1096-4521-9bc4-05cdc0320d89)

### 📝 Insights

- _Consistent Sales Outperform Marketing Spend_ –Despite variations in sales performance throughout the year, our analysis reveals that sales consistently exceed marketing spend, indicating a positive return on investment.
- _Factors Influencing Sales Performance_: Our analysis identified several key factors contributing to fluctuations in sales, including variations in the average selling price of products, changes in product quantity sold, and fluctuations in the number of orders placed.
- A significant portion of our sales come from coupon usage, as revealed. We can further refine our coupon strategy

### 🚀 Strategies

- _Product Bundling and Cross-Selling_: Create bundled offers combining complementary products within the top categories to encourage upselling and increase the average order value. Implement cross-selling strategies by recommending related products at checkout to maximize sales opportunities.
- Offer strategic discounts or promotions on slower-moving products within categories to stimulate demand and clear inventory.
- Promote the least happening products across the regions where they do less with new campaigns and offers.
- Implement loyalty programs or reward incentives to incentivize repeat purchases with Subscription offers and foster long-term customer relationships.

With these insights, we can adjust our marketing strategies to ensure a more consistent and effective approach to driving sales and maximizing returns.
