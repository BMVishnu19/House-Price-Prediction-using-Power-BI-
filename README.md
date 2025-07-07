# House-Price-Prediction-using-Power-BI-
This project presents a comprehensive Power BI dashboard designed to analyze key factors influencing residential property prices across various regions in India. 
Leveraging interactive visualizations, the dashboard provides deep insights into market trends, price drivers, location-based value, and the impact of amenities.
The primary goal of this dashboard is to assist potential homebuyers, real estate agents, and investors in making informed decisions by offering a data-driven perspective on the Indian real estate market.The Kaggle Dataset serves as the data source for the dashboard.

## Dashboard Features & Key Insights

The dashboard is structured across five interactive pages, each focusing on a different aspect of house price analysis:
### 1. Indian House Prices Dashboard (Overview)
* **Purpose:** Provides a high-level executive summary of the market.
* **Visualizations & Insights:**
    * **Bar Chart: Top 5 Regions by Average Property Price:** Identifies the most expensive geographical areas based on average property prices (e.g., Jubilee, Lavasa, Tudoo, Madakul, Wadi). Visually represents the price disparity among these top regions.
    * **Card Visuals: Max Price, Min Price, Average Price, Avg Price per Area:** Displays crucial summary statistics like maximum (₹4.00K - likely Crores), minimum (₹20.0 - likely Lacs), average property prices (₹124.62 - likely Lacs), and the overall average price per square foot (₹0.08) across the entire dataset. Provides a quick snapshot of the market's range and central tendencies.

### 2. Key Locations Analysis
* **Purpose:** Dives deeper into the geographical distribution of property pricing.
* **Visualizations & Insights:**
    * **Map Visual: Average Price and Text City by Latitude and Longitude:** Visualizes regions with high-value or low-value properties on an interactive map of India. This allows for intuitive spatial analysis and identification of geographical hotspots and regional price differences.
    * **Table Visual (Detailed Location Data):** Provides detailed tabular data for precise price values, areas, and other attributes for specific cities/locations, complementing the map's visual overview.
   * **Slicer: No. of Bedrooms:** Allows dynamic filtering by the number of bedrooms to see how prices and their distribution on the map change for different property sizes in various locations.

### 3. Key Amenities Analysis
* **Purpose:** Explores the role and impact of various amenities on property characteristics.
* **Visualizations & Insights:**
      * **Ribbon Chart: Amenity Presence Ranking by City:** Shows how different amenity types rank in terms of presence or impact across various cities. It identifies the most common or prevalent amenities and reveals city-specific amenity trends.
      * **Card Visuals: Count of Amenity Type, Average Amenities per Property:** Displays summary counts, indicating the variety of amenities (e.g., 12 distinct types) and the average number of amenities a property typically offers (e.g., 2.51K, likely indicating 2.51 amenities per property). This suggests the level of development or luxury in the market.
    * **Table Visual (Sum of Has Amenity with conditional formatting):** (Not fully visible in provided screenshots, but implied by analysis). Provides a detailed table listing each amenity type and the total count of properties possessing that amenity, often with visual highlighting for higher/lower counts. This allows for quick identification of prevalent or rare amenities.

### 4. Price Drivers and Correlations Analysis
* **Purpose:** Uses advanced analytics to uncover the primary factors influencing property prices and their relationships.
* **Visualizations & Insights:**
   * * **Decomposition Tree Visual (Likely Top-Right, not fully visible but common pairing with Key Influencers):** (Implied by analysis). Offers an interactive, hierarchical breakdown of a key metric (e.g., Average Price) by various dimensions, allowing for flexible drill-down to understand the contribution of different factors to the overall price.
   * * **Scatter Plot: Property Price vs. Area by No. of Bedroom:** Visualizes the relationship between `Area` (X-axis) and `Price` (Y-axis), with `City` determining the color of points and `No. of Bedrooms` determining the size of points.
        * **Correlation:** A visible positive trend suggests that larger areas generally correlate with higher prices.
        * **Outliers:** Helps spot unusually expensive or inexpensive properties for their size or bedroom count.
        * **City & Bedroom Impact:** Different colored clusters and varying bubble sizes help compare price-area relationships across cities and for different bedroom configurations.

### 5. Value & Price Efficiency Analysis
* **Purpose:** Focuses on the crucial "Price per Square Foot" metric to assess property value.
* **Visualizations & Insights:**
    * **KPI Card: Overall Average Price per Square Foot:** Provides the single, overall average value for money metric (e.g., ₹0.08 per Area) for quick reference and as a market benchmark.
    * **Bar Chart: Avg. Price per Sq. Ft. by City:** Compares the average price per square foot across different cities (e.g., Bengaluru, Chennai, Delhi, Hyderabad, Kolkata, Mumbai). This identifies which cities offer better or worse "value for money" based on cost per unit area.
    * **Bar Chart: Avg. Price per Sq. Ft. by No. of Bedrooms:** Analyzes how the average price per square foot varies depending on the number of bedrooms. It reveals if larger or smaller properties offer better price efficiency.
    * **Bar Chart: Avg. Price per Sq. Ft. by Amenity Type:** Understands which amenity types are associated with higher or lower price efficiency. It helps to identify value-adding amenities that command a premium per square foot.
    * **Scatter Plot: Price per Sq. Ft. vs. Area:** Visualizes the relationship between a property's total `Area` (X-axis) and its `Avg Price per Area` (Y-axis). This plot often shows if larger properties offer a lower price per square foot (economies of scale) and helps identify outliers in value for specific sizes.

