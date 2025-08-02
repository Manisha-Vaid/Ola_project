# Ola_project
1. OVERALL
   Ride Volume Over Time: A time-series chart showing the number of rides per day or week.
   Booking Status Breakdown: A pie or doughnut chart displaying the proportion of different booking statuses (success, cancelled by the customer, cancelled by the driver, etc.).
   
2. VEHICLE TYPE
   Top 5 Vehicle Types by Ride Distance: A bar chart ranking vehicle types based on the total distance covered.
3. REVENUE
   Revenue by Payment Method: A stacked bar chart displaying total revenue based on payment methods (Cash, UPI, Credit Card, etc.).
   Top 5 Customers by Total Booking Value: A leaderboard visual listing customers who have spent the most on bookings.
   Ride Distance Distribution Per Day: A histogram or scatter plot showing the distribution of ride distances for different Dates.
4. CANCELETION
   canceled by driver - pie chart displaying how many canceled or reason 
   canceled by customer rate - pie chart displaying how many canceled or reason
5. DRIVER RATINGS
   Customer vs. Driver Ratings: i using card to show all ratings of each vehicle type
   
#THE DASHBOARD WAS BUILT USING THE FOOLOWING TOOLS AND TECHNOLOGIES
Power BI desktop - Main data visualization platform used for report creation.
power query- data transormation and cleaning layer for reshaping creation
Data modeling - Manage Relationships

#SQL
I used sql for data manupulaion and data cleaning , and i also used create view.
Here's my commands

#1. Retrieve all successful bookings:
Select * From Successful_Bookings;
#2. Find the average ride distance for each vehicle type:
Select * from ride_distance_for_each_vehicle;
#3. Get the total number of cancelled rides by customers:
Select * from cancelled_rides_by_customers;
#4. List the top 5 customers who booked the highest number of rides:
Select * from Top_5_Customers;
#5. Get the number of rides cancelled by drivers due to personal and car-related issues:
Select * from Rides_cancelled_by_Drivers_P_C_Issues;
#6. Find the maximum and minimum driver ratings for Prime Sedan bookings:
Select * from Max_Min_Driver_Rating;
#7. Retrieve all rides where payment was made using UPI:
Select * from UPI_Payment;
#8. Find the average customer rating per vehicle type:
Select * from AVG_Cust_Rating;
#9. Calculate the total booking value of rides completed successfully:
Select * from total_successful_ride_value;
#10. List all incomplete rides along with the reason:
Select * from Incomplete_Rides_Reason;
