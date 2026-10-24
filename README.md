# Smart India Hackathon Workshop
# Date: 24.10.2026
## Reference Number: 26017697
## Name: Sangavi A.

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
FarmDirect AI is a digital agricultural marketplace that connects farmers and Farmer Producer Organizations (FPOs) directly with consumers, retailers, hotels, restaurants, and other bulk buyers. It aims to reduce unnecessary intermediaries, improve price transparency, and make agricultural produce more accessible.

The platform enables farmers to list their produce, specify available quantities and prices, and receive orders from multiple buyers. Buyers can compare produce listings and view an itemized estimate of product prices, logistics charges, and platform fees.

## How It Addresses the Problem

Traditional agricultural supply chains may involve several intermediaries, each adding costs between production and consumption. FarmDirect AI aims to shorten this chain by facilitating direct connections between farmers and buyers.

Transparent pricing helps farmers understand their potential earnings and buyers understand the total purchase cost. Demand forecasting can support better production planning, while logistics optimization can help reduce avoidable transport expenses and post-harvest losses.

## Technical Approach
The initial prototype uses HTML, CSS, and JavaScript to demonstrate the marketplace, product search, sample listings, basket calculations, demand estimation, and area-based delivery grouping.

The proposed production architecture includes a React frontend, Python FastAPI backend, PostgreSQL database, and a machine-learning module using historical demand data. A geospatial routing service will support road-distance calculations and delivery-route optimization.

Forecasting models will be evaluated using historical data and time-based validation. Route recommendations will consider delivery locations, vehicle capacity, time windows, and transport costs.

## Feasibility and Viability
The project can be developed incrementally, starting with a web-based marketplace and then adding backend services, data analytics, and logistics integrations.

Potential challenges include unreliable data, farmer adoption, changing market prices, produce spoilage, connectivity limitations, and delivery costs. These can be addressed through pilot testing, farmer and FPO partnerships, regional-language interfaces, verified listings, transparent fees, and continuous evaluation.

The business model may include a clearly disclosed transaction fee, optional logistics services, or subscriptions for institutional buyers. Fees should be designed so that they do not recreate the same affordability problem the platform aims to solve.

## Impact and Benefits
For farmers: Direct access to buyers, greater market visibility, and better-informed selling decisions.

For consumers: Transparent pricing, more purchasing options, and potentially lower total costs.

For bulk buyers: Easier sourcing, quantity-based purchasing, and coordinated deliveries.

For the environment: Potential reductions in unnecessary travel, food spoilage, and wasted resources.

These benefits will be validated through a pilot measuring farmer net earnings, consumer prices, fulfilment rates, delivery costs, and produce wastage.

## Research and References
Smart India Hackathon: https://www.sih.gov.in/

React documentation: https://react.dev/learn

FastAPI tutorial: https://fastapi.tiangolo.com/tutorial/

Scikit-learn time-series forecasting example: https://scikit-learn.org/stable/auto_examples/applications/plot_time_series_lagged_features.html
