# ITI-Graduation-Project
## Data Analysis Track intake 43 
### Ecommerce Behavior
E-commerce refers to the buying and selling of goods or services through electronic means, primarily over the internet. It has revolutionized the way people conduct business by enabling consumers to shop from anywhere and at any time, and businesses to reach a global audience. E-commerce platforms provide various features such as online storefronts, shopping carts, payment gateways, and order management systems, among others. The industry has seen tremendous growth in recent years, driven by advancements in technology, increasing consumer demand for convenience and flexibility.

**Overview**

This file contains behavior data for two months (October and November 2019) from a medium cosmetics online store hosted by REES46 niche-specific personalization engine Platform. Each row in the file represents an event. All events are related to products and users. Each event is like many_to-many relation between products and users. A session can have multiple purchase events if it's a single order.
File structure
Property

**Description**

*event_time* 

- Time when event happened at (in UTC).

*event_type*

- view- a user viewed a product
- cart - a user added a product to shopping cart
- remove_from_cart- a user removed a product from shopping cart
- purchase - a user purchased a product

*product_id*

- ID of a product

*category_id*

- Product's category ID
Property.

*category_code*

- Product's category taxonomy (code name) if it was possible to make it. Usually present for meaningful categories and skipped for different kinds of accessories.

*brand*

- Downcased string of brand name.

*price*

- Float price of a product. Present.

*user_id*

- Permanent user ID.

*user_session*

- Temporary user's session ID. Same for each user's session. Is changed every time user come back to online store from a long pause.

**Business Requirements**

You can support the business in various ways including and not limited to :
1. the marketing department need your help to identify the following :
a. which products to feature in the next advertising campaigns and promotions?
b. Which brands are customers most loyal to?
c. Who is the most valuable customers based on their purchase history.
d. Are there any price trends for a particular product over time?
2. Define a KPI that measures customer loyalty from the data.
3. Design a sample recommendation engine using association analysis, and what metrics would you use to evaluate its performance?
Deliverable Layout
You are expected to deliver your key insights and recommendation in the form of a presentation that covers the following aspects – when applicable -:

• Business challenge: Introduce why this is analysis important and what kind of problem we are trying to solve
• Analysis Scope: Define analysis base, inclusion and exclusion criteria, time frame and data included.
• Analysis and Insights: Present any interesting insights, patterns, behaviors, visualizations extracted from data.
• Recommendations: Suggest actions the business can take to improve decisions making process.
modeling : the model you used and evaluation of this model and any preprocessing/ feature engineering you used
