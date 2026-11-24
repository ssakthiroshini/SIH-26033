# Smart India Hackathon Workshop
# Date:24/11/2026
## Reference Number:26018138
## Name:Sakthiroshini.s

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
FarmBridge AI – An Intelligent Farm-to-Consumer Marketplace

FarmBridge AI is a smart agricultural marketplace that works on a Harvest-to-Order model. Instead of farmers harvesting crops first and searching for buyers later, our platform collects expected customer demand in advance and helps farmers plan their sales accordingly.
Detailed explanation of the proposed solution
Our platform introduces five major features:

1. Pre-Harvest Demand Booking
- Farmers upload details about their crops, expected harvest date and estimated quantity.
- Consumers, hotels, supermarkets and restaurants can place advance orders.
- AI compares expected demand with available crop supply.
- Farmers receive an estimate of how much produce they can sell before harvesting.
2. Smart Group Buying
- Consumers in the same locality can combine their vegetable and fruit orders.
- The platform combines multiple small orders into one bulk order.
- This reduces transportation costs and makes direct delivery more affordable.
- Farmers can sell larger quantities without depending on multiple intermediaries.
3. AI-Based Fair Price Advisor
- The system compares local market prices, previous sales, demand and transportation expenses.
- It suggests a suitable selling price to farmers.
- Consumers can view the farmer's price, delivery cost and platform charge separately.
- This creates transparency in the pricing system.
4. Shared Logistics Network
- Farmers and FPOs can register available transport vehicles.
- The system groups nearby deliveries into common routes.
- AI suggests efficient delivery routes to reduce fuel costs and delays.
- Small farmers can share transportation instead of arranging separate vehicles.
5. Digital Crop Identity
- Every order receives a unique QR code.
- Buyers can scan it to view the farmer or FPO, harvest date, crop details and journey information.
- This increases trust and helps consumers understand where their food comes from.
  
How it addresses the problem:
Existing problem	                            FarmBridge AI solution
-Too many intermediaries                    -Direct farmer-to-buyer transactions
-Uncertain demand	                          -AI-based demand prediction
-Low bargaining power	                      -Fair price recommendations
-High transportation cost	                  -Shared delivery system
-Food wastage	                              -Pre-harvest demand booking
-Lack of transparency	                      -QR-based crop identity

Innovation and uniqueness of the solution:
The main innovation is the combination of Pre-Harvest Booking + AI Demand Prediction + Community Group Buying.
Unlike a normal online vegetable shopping application, FarmBridge AI starts coordinating demand even before harvesting.
For example:
Suppose five farmers expect to harvest 500 kg of tomatoes. Nearby hotels, supermarkets and households collectively place advance orders for 400 kg.
The platform identifies the demand, reserves the required quantity and helps the farmers arrange transportation. This reduces the risk of unsold produce.
Another unique feature is the Farmer Opportunity Score. It analyses demand, nearby buyer availability, expected selling price and delivery cost to suggest the most beneficial selling opportunity.
## Technical Approach
Technologies to be used
Technology                 	Purpose
Python	                    Backend programming
Django / FastAPI	          Server-side development
HTML, CSS, JavaScript	      User interface
React	                      Interactive frontend
MySQL / PostgreSQL	        Database management
Machine Learning	          Demand and price prediction
Google Maps API	            Route optimization
QR Code                   	Product traceability
Cloud hosting	              Platform deployment
AI and Machine Learning models
We propose three intelligent modules:

A. Demand Forecasting Model
- Uses previous sales, seasonal trends, weather information and customer orders.
- Predicts the expected demand for different crops.
- Helps farmers plan harvesting and selling quantities.
B. Price Recommendation Model
- Analyses historical market prices, current demand and transportation expenses.
- Suggests a reasonable selling price.
- Helps farmers avoid selling their products at unnecessarily low prices.
C. Route Optimization Model
- Uses delivery locations, order quantities and vehicle capacity.
- Groups nearby orders together.
- Calculates efficient delivery routes to reduce time and fuel consumption.

<img width="409" height="645" alt="{2E93BE8B-84E7-4521-A8B1-3AE7D2FB4C00}" src="https://github.com/user-attachments/assets/deb79494-422c-4777-9acd-4d7e139f078c" />


Implementation methodology
1. Collect farmer, crop, buyer and market-price information.
2. Develop separate registration and login facilities for farmers, consumers and bulk buyers.
3. Create a digital marketplace to display available crops.
4. Integrate machine learning models for demand forecasting and price suggestions.
5. Implement group ordering and shared transportation.
6. Integrate map services for route optimization.
7. Test the system with a small group of farmers and consumers before expanding.
For the initial prototype, we can use sample agricultural data and simulated orders. Later, real market and weather data can be integrated.

## Feasibility and Viability
Analysis of the feasibility of the idea:
FarmBridge AI is technically and economically feasible because it uses existing technologies such as mobile applications, machine learning, cloud databases and digital payment systems.
- Technical feasibility: Python, Django, machine learning and map APIs can support the complete platform.
- Economic feasibility: The system does not require farmers to purchase expensive equipment. They can access it through smartphones or FPO assistance.
- Operational feasibility: FPOs can act as local collection and coordination centres.
- Scalability: The platform can initially support selected crops in one region and gradually expand to other districts and states.
Potential challenges and risks
Challenges	                                                    Strategies to overcome them
Farmers may have limited digital knowledge                    	Simple regional-language interface and FPO assistance
Incorrect demand predictions	                                  Regularly update models with actual sales data
Produce quality differences	                                    Standardized grading and quality verification
Delivery delays	                                                Backup transport partners and route updates
Low farmer participation	                                      Awareness campaigns and easy registration
Internet connectivity issues	                                  Lightweight application and offline data entry

Long-term viability:
The platform can generate revenue through a small transparent service fee on completed transactions, optional logistics coordination charges and subscriptions for bulk buyers.
Farmers will not need to pay high registration fees. FPO partnerships can help maintain affordable access.
The system can gradually expand to include dairy products, grains, fruits and other agricultural commodities.

## Impact and Benefits
Potential impact on the target audience
For farmers
- Direct access to consumers and bulk buyers.
- Better control over selling prices.
- Reduced dependence on traditional intermediaries.
- Better planning of harvesting and sales.
- Increased market opportunities for small farmers.
For consumers
- Access to fresher agricultural products.
- Transparent product and delivery pricing.
- Affordable prices through group buying.
- Information about the source of agricultural products.
For FPOs and bulk buyers
- Easier collection of produce from multiple farmers.
- Better supply planning.
- Reduced procurement time and transportation expenses.
- Direct access to verified agricultural suppliers.

  Social, economic and environmental benefits
Category                                     Expected benefit
Economic	                        Better farmer income opportunities and reduced unnecessary costs
Social	                          Stronger relationships between farmers and consumers
Environmental	                    Reduced food wastage and unnecessary transportation
Agricultural	                    Demand-based harvesting and improved market planning
Digital	                          Increased adoption of digital services in rural areas

Expected measurable outcomes
We will evaluate the prototype using the following performance indicators:
1. Increase in the farmer's share of the final selling price.
2. Reduction in delivery cost per kilogram.
3. Percentage of advance orders successfully fulfilled.
4. Reduction in unsold agricultural produce.
5. Number of farmers and buyers actively using the platform.

## Research and References
Research findings
1. Reserve Bank of India – Agriculture Supply Chain Survey (2025)
   The RBI study found that farmers' share in consumer prices ranged from 40% to 67% across selected crops. It also highlighted the importance of better storage,          transportation and supply-chain infrastructure.
 Relevance: Supports our idea of direct selling and shared logistics. 
 Reserve Bank of India


2. RBI – Price Dynamics and Value Chain of Fruits in India (2024)
  The research estimated farmers' share in consumer prices at approximately 31% for bananas, 35% for grapes and 43% for mangoes.
Relevance: Shows why improving the fruit supply chain and reducing unnecessary costs are important. 
Reserve Bank of India


3. Government of India – Future Farming in India: AI Playbook (2025)
  The report discusses AI-powered smart marketplaces, price forecasting, buyer matching and agricultural traceability.
Relevance: Supports our proposed AI demand prediction, price recommendation and digital marketplace features. 
Principal Scientific Adviser


4. Ministry of Agriculture – e-NAM
  The National Agriculture Market (e-NAM) provides a digital platform for agricultural trading and connects farmers with buyers.
Relevance: FarmBridge AI can complement existing digital agricultural markets by introducing pre-harvest demand booking and community-based order consolidation. 
Avantis CDN Production Storage

Reference links
1. RBI – Agriculture Supply Chain Survey (2025)
2. RBI – Price Dynamics and Value Chain of Fruits
3. Future Farming in India – AI Playbook
4. Government of India – Digital Agricultural Platforms
