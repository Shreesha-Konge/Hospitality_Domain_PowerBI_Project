# Hospitality_Domain_PowerBI_Project

* Project Description :
AtliQ Grands a luxury/business hotel chain,  is experiencing a decline in market share and revenue within the business and luxury categories of hotels. This decline is attributed to strategic moves made by competitors and ineffective decision-making within Atliq Grand’s management.The Managing Director of Atliq Grand aims to regain market share and revenue by implementing data-driven decisions.

  To facilitate data-informed decision-making, I developed an
end-to-end dashboard. Using Power BI, I analysed data to track revenue by
category, trends by key metrics, property performance, realization
percentage, and several other KPIs.This dashboard enabled the Revenue team to regain their
revenue and market share by 20% in the next month.
                                                                                    
* Atliq Grand owns multiple 5-star hotels primarily in cities like Bengaluru, Delhi, Mumbai, and Hyderabad, boasting a total of 7 properties:                
- Atliq Bay
- Atliq Blu
- Atliq City
- Atliq Exotica
- Atliq Grand
- Atliq Palace
- Atliq Season
                                                                                                                                                                         
* Data set:                                                                                                                             
The dataset comprises information on hotels, rooms, bookings, and dates across five CSV files. Here’s a concise explanation of each dataset:                                           
1) dim_date:                                                                                                                         
Contains information about dates in May, June, and July.                                           
Columns:date, mmm yy, week no, day_type                                                                                            
2) dim_hotels:                                                                
Provides details about hotels.                                                               
Columns: property_id, property_name, category, city                                                         
3) dim_rooms:                                                                 
Describes the types of rooms available in hotels.                                                     
Columns: room_id, room_class                                                 
4) fact_aggregated_bookings:                                                                                                     
Provides aggregated booking information.                                             
Columns:property_id, check_in_date, room_category, successful_bookings, capacity                                     
5) fact_bookings:                                                                               
Contains detailed booking information.                                                                  
Columns: booking_id, property_id, booking_date, check_in_date, check_out_date, no_guests, room_category, booking_platform, ratings_given, booking_status, revenue_generated, revenue_realized                                                                                                                             
* Business Outcomes :                                                                                        
1) Mumbai generates highest revenue and Delhi the least revenue during May to July . Company need to focus on increasing the revenue in Delhi.                            
2) The occupancy rate is higher during weekends across all cities, months and booking platforms. Leverage this insight to increase revenue generated during weekends.              
3) 82% of the bookings are checked out while 5% of booking don’t show up across all cities and booking platforms which means 87% of bookings generate revenue for AtliQ hotels. Identify and analyze the reasons for cancellations and try to reduce them.                                                                 
* Conclusion :                                                                                                                       
1) A revenue dashboard was built for AtliQ hotels depicting its various KPIs visually.                                                        
2) Relevant filters along with tooltips and interactions was provided in the dashboard.                                            
3) This dashboard can be used for both high-level and in-depth analysis of KPIs across various dimensions.                                                            




                                  
