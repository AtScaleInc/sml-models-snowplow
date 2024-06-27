# Snowplow Digital Analytics Model

Over two million sites and applications use Snowplow to generate and model first-party customer data from across their digital interfaces, capture descriptive customer journeys, and build actionable first-party behavioral profiles. Snowplow empowers organizations to create a scalable, first-party data foundation so marketing and data teams can effectively analyze and tackle Customer 360 use cases, such as customer acquisition, engagement, segmentation, and retention.

In leveraging out-of-the-box data models to aggregate journeys across the web and mobile, Snowplow deterministically identifies a single view of the customer in Snowflake for analytics purposes. Compared to more traditional tools like Google Analytics, Snowplow Digital Analytics offers a scalable solution to collect deeper behavioral insights into customer journeys within the Data Cloud. Toggle through turnkey visualizations powered by first-party data to better understand behavioral trends with website/app engagement, customer retention, campaign performance, demographics, and other insightful user metrics. With new and improved insights into your customer base, companies can take necessary action in their marketing, product, and business strategy to drive innovation and maintain competitive advantages.

With Snowplow, organizations like Strava, Burberry, and Autotrader acquire, engage, and retain customers in a scalable manner while retaining an industry-leading data governance posture with full GDPR and CCPA compliance.

## Demonstrated Model Features
1. Multi-fact model
2. Calculated Columns
3. Time-relative calculations

## Supported Data Platforms
1. Snowflake

## Data Model Overview

![SnowPlow](images/snowplow-model.png)

## Data Loading Instructions

### Snowflake
The Snowplow data for the Snowplow model is free in the Snowflake Marketplace. To get access to the tutorial data in the Snowflake Marketplace:

1. **Go to the Snowflake Marketplace:** In the Snowflake console, click "Data Products" and click the "Marketplace" link.

![Snowflake Marketplace Page](images/Snowflake-Marketplace-Page.png)

2. **Find the "Snowplow" data product:** In the search bar, type in "Snowplow" and select the "Snowplow Digital Analytics" data product.

![Snowflake Marketplace Search - Snowplow](images/Snowflake-Marketplace-Search-Snowplow.png)

3. **Connect to the Snowplow Digital Analytics Data Product:** On the screen's right side, click on the "Get" button.

![Snowflake Marketplace Snowplow Page](images/Snowflake-Marketplace-Snowplow-Page.png)

4. **Name Your Database:** Click on the down arrow on the "Options" accordion control, and enter `SNOWPLOW_DIGITAL_ANALYTICS` (note that it needs to be capitalized as shown) in the "Database" field and assign the proper access role. Click the "Get" button.

![Snowflake Marketplace Get](images/Snowflake-Marketplace-Get-Snowplow.png)

