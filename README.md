Using aggregated data, Produced forecasts for four different metrics for the next 12 months. Accurately calculated the national aggregates for the metrics—if using non-count metrics, I have calculated weighted averages.



## Data Dictionary

|Column|Logical|Description|
|---|---|---|
|month_date_yyyy_mm|	Month Date|	Monthly date in a YYYYMM format.|
|county_name|	County Name|	The of the county.|
|active_listing_count	|Active Listing Count|	The count of active listings within the specified geography during the specified month. The active listing count tracks the number of for sale properties on the market, excluding pending listings where a pending status is available. This is a snapshot measure of how many active listings can be expected on any given day of the specified month.|
|average_listing_price|	Avg Listing Price|	The average listing price within the specified geography during the specified month.|
|median_listing_price_per_square_foot|	Median List Price Per Sqft|	The median listing price per square foot within the specified geography during te specified month.|
|median_listing_price	|Median Listing Price|	The median listing price within the specified geography during the specified month.|
|median_square_feet	|Median Listing Sqft	|The median listing square feet within the specified geography during the specified month.|
|new_listing_count	|New Listing |	The count of new listings added to the market within the specified geography. The new listing count represents a typical week’s worth of new listings in a given month. The new listing count can be multiplied by the number of weeks in a month to produce a monthly new listing count.|
|pending_listing_count|	Pending Listing Count	|The count of pending listings within the specified geography during the specified month, if a pending definition is available for that geography. This is a snapshot measure of how many pending listings can be expected on any given day of the specified month.|
|total_listing_count|	Total Listing Count	|The total of both active listings and pending listings within the specified geography during the specified month. This is a snapshot measure of how many total listings can be expected on any given day of the specified month.|
