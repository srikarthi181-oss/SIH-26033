# Smart India Hackathon Workshop
# Date:25/11/26
## Reference Number:26002519
## Name:P.Srikarthikeyan

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
1. Detailed explanation of the proposed solution
FarmDirect is a mobile and web marketplace that connects farmers directly with nearby households, college hostels, and restaurants. Farmers set their own prices and list the produce they expect to harvest. A Farmer Producer Organisation (FPO) can help farmers create listings and use its collection centre to coordinate local orders.
1. Farmers list produce. Each listing shows the crop, available quantity, harvest date, price per kilogram, and available pickup or delivery slots.
2. Buyers place preorders. Buyers choose the quantity they need and select pickup or delivery. Before ordering, they see how much goes to the farmer and how much covers packing, collection, and delivery.
3. The collection centre groups orders. Staff verify the weight and quality of the produce, pack orders, and group them by pickup point or delivery route.
4. Buyers receive their orders. Buyers confirm receipt or report missing or damaged items. Farmers can track order status and payments from their dashboard.
2. How it addresses the problem
- Improves farmers’ earnings. Farmers set their selling price and reach buyers directly. Confirmed orders give farmers an estimate of how much produce they can sell before sending it to the collection centre.
- Reduces costs for buyers. Direct sales can reduce markups from repeated resale. Grouping nearby orders spreads delivery costs across several buyers, and pickup gives buyers a lower-cost option.
- Makes prices transparent. Buyers can see the farmer’s share and each service charge before ordering. Farmers can see how much they are due for each completed sale.
- Helps reduce unsold produce. Preorders give the collection centre a clearer estimate of demand, so it can plan how much produce to collect and pack.
Illustrative example. If a farmer receives ₹20 for one kilogram of tomatoes and the buyer pays ₹45 through the existing route, FarmDirect could pay the farmer ₹28 and charge the buyer ₹38, including ₹10 for packing, collection, delivery, and platform operations. The farmer would earn ₹8 more per kilogram, and the buyer would pay ₹7 less. A pilot would test these figures using actual operating costs.
3. Innovation and uniqueness of the solution
FarmDirect combines harvest-based preorders, shared local delivery, and a visible farmer share in one workflow.
Feature	What makes it useful
Preorders tied to harvest dates	Farmers see confirmed demand before sending produce for collection, and buyers know when it will be available.
Shared pickup and delivery	A hostel’s bulk order and several household orders can be grouped at the same collection centre, making smaller orders easier to serve.
Visible farmer share	Every order shows the amount the farmer receives alongside the actual service charges.
FPO-assisted access	An FPO operator can manage listings and orders for farmers who have limited internet access or need help using the app.

## Technical Approach
Technical Approach
1. Technologies to be used
- Frontend: HTML, CSS, JavaScript, and Bootstrap will provide a mobile-friendly interface for farmers, buyers, and collection-centre staff.
- Backend: Python and Django will manage user accounts, produce listings, stock, orders, and pricing.
- Database: SQLite will store user profiles, produce availability, order details, and price breakdowns for the prototype.
- Hardware: Users can access FarmDirect through a web browser on a smartphone or laptop with an internet connection.
2. Methodology and process for implementation
1. Create three dashboards. Farmers list produce, buyers place preorders, and collection-centre staff manage packing and distribution. Staff can also create listings on behalf of farmers.
2. Manage stock and pricing. Buyers select the quantity and a pickup or delivery slot. Before confirming, they see the farmer’s share and any packing or delivery charges. The system reserves stock when an order is confirmed to prevent overselling.
3. Group and fulfil orders. Staff group confirmed orders by pickup point or delivery route and time slot. They check the weight and quality, pack the produce, and update the order status when the buyer receives it.
4. Demonstrate the working prototype. Two farmers list tomatoes, and three buyers preorder for the same pickup slot. The collection centre prepares a single batch. After pickup, the prototype shows the buyer’s total cost and the farmer’s earnings using simulated payments.
## Feasibility and Viability
Feasibility and Viability
1. Analysis of the feasibility of the idea
FarmDirect can be tested with one Farmer Producer Organisation (FPO), one college hostel, and a nearby residential community. Farmers and buyers can access the web app from a smartphone or laptop. The pilot can use an existing FPO collection centre to weigh and pack produce and manage scheduled pickups, keeping setup costs low.

FarmDirect is financially viable if farmers earn more per kilogram, buyers pay less, and service fees cover operating costs. The pilot will compare the farmer’s net earnings and the buyer’s total price with local market transactions for the same crop, quality, and week. It will also track the cost of collection, packing, and delivery per order.
2. Potential challenges and risks
1. Some farmers may have limited internet access or need help using the app.
2. Weather or crop damage may leave farmers with too little produce to fulfil confirmed orders.
3. Delivering small orders to different locations may cost more than the delivery fees collected.
4. Fresh produce can spoil or get damaged during packing and transport.
3. Strategies for overcoming these challenges
1. Provide FPO support. Collection-centre staff can create listings and manage orders on behalf of farmers.
2. Verify available stock. Farmers confirm the quantity before the collection centre starts preparing orders. If there is a shortage, buyers can accept a replacement or receive a refund.
3. Group nearby orders. Deliver orders together by location and time slot, and offer collection-centre pickup as a lower-cost option.
4. Check quality before dispatch. Collect produce based on confirmed preorders, inspect it before packing, and let buyers report damaged or missing items through the app.
## Impact and Benefits
Impact and Benefits
1. Potential impact on the target audience
- Farmers can set their own prices and sell directly to nearby buyers. Preorders help them estimate demand before bringing produce to the collection centre.
- Consumers can buy fresh local produce and see how much of the price goes to the farmer. Shared delivery and pickup options can help lower the total cost.
- College hostels and restaurants can place bulk orders in advance and choose pickup or delivery slots that fit their schedules.
- Farmer Producer Organisations (FPOs) can help small farmers reach more buyers by managing listings, checking produce quality, and coordinating orders.
2. Benefits of the solution
- Economic benefits. Direct sales can reduce markups from repeated resale, allowing farmers to earn more per kilogram and consumers to pay less when packing and delivery costs are kept low.
- Social benefits. FPO-assisted listings can help farmers with limited internet access sell online. Clear price breakdowns show buyers how their purchase supports local farmers.
- Environmental benefits. Collecting produce against confirmed orders can reduce waste from unsold stock. Grouping nearby deliveries can reduce the number of trips needed.
The pilot will measure farmers’ net earnings per kilogram, consumers’ total price per kilogram, unsold produce, and the number of delivery trips to see whether these benefits are achieved.

## Research and References
Research and References
1. RBI Working Paper — Vegetables Inflation in India (2024). The study estimated that farmers received about 33% of the final consumer price for tomatoes, 36% for onions, and 37% for potatoes. This finding supports FarmDirect’s decision to show the farmer’s share and service charges separately at checkout. Read the RBI working paper. rbi.org.in
2. Uzhavar Sandhai — Tamil Nadu Farmers’ Markets. This state initiative lets farmers sell fruits and vegetables directly to consumers. It provides a local example for FarmDirect’s proposed model of direct sales and scheduled pickup. View the Tamil Nadu government initiative. agrimark.tn.gov.in
3. Ministry of Agriculture and Farmers Welfare — Farmer Producer Organisations (FPOs). The Government of India’s FPO scheme aims to improve market access for small and marginal farmers. In FarmDirect, a local FPO would help farmers list produce, combine orders, and coordinate collection. Read the Ministry’s Rajya Sabha response. ru508
4. AGMARKNET — Daily Wholesale Market Prices. The dataset provides daily minimum, maximum, and modal wholesale prices across mandis. FarmDirect can use it as a wholesale benchmark and collect local farmer and retail prices separately to assess whether the pilot improves farmer earnings and lowers buyer costs. Access the AGMARKNET dataset. Open Government Data (OGD) Platform India

    
