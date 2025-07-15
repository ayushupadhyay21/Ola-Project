📊 Ola Ride Booking and Cancellation Analysis Project
🗂️ Project Overview
This project analyzes and visualizes ride booking data from Ola Cabs. It covers data ingestion, cleaning, transformation using SQL, and interactive visual representation via Power BI. The goal is to uncover patterns in user behavior, ride cancellations, driver performance, and payment methods — enabling stakeholders to make data-driven decisions.

🔧 Project Structure

📁 Ola Project/
├── Ola Database.csv          # Raw dataset containing booking records
├── Sql problems.sql          # SQL scripts for analysis and data modeling
├── Ola Project Dashboard.pbix # Power BI dashboard file
└── README.md                 # Project documentation
📑 Dataset Description
The Ola Database.csv contains detailed records of Ola ride bookings. Each row represents a booking and includes:

Booking_ID

Customer_ID

Booking_Status

Ride_Distance

Vehicle_Type

Driver_Ratings

Customer_Rating

Payment_Method

Booking_Value

canceled_Rides_by_Driver

Incomplete_Rides

Incomplete_Rides_Reason

🧮 SQL Analysis
The Sql problems.sql file performs data transformation and business queries. Key views and insights generated:

Successful Bookings
View: Successful_Bookings
→ All completed bookings.

Average Ride Distance per Vehicle Type
View: ride_distance_for_each_vehicle
→ Highlights vehicle-wise distance trends.

Customer Cancellations
View: cancelled_rides_by_customers
→ Total rides cancelled by customers.

Top 5 Customers by Rides
View: Top_5_Customers
→ Identifies high-frequency users.

Driver Cancellations (Personal/Car Issues)
View: Rides_cancelled_by_Drivers_P_C_Issues
→ Analyzes operational reliability.

Prime Sedan Driver Rating Range
View: Max_Min_Driver_Rating
→ Shows extremes of driver quality for Prime Sedan.

UPI Payment Rides
View: UPI_Payment
→ Popularity of UPI as a payment method.

Average Customer Rating per Vehicle Type
View: AVG_Cust_Rating
→ Evaluates customer satisfaction per vehicle.

Total Booking Value (Successful Rides)
View: total_successful_ride_value
→ Revenue contribution from completed rides.

Incomplete Rides with Reasons
View: Incomplete_Rides_Reason
→ Identifies common ride failure reasons.

These queries are helpful for data validation and forming dimensions and measures in BI tools.

📊 Power BI Dashboard
The Ola Project Dashboard.pbix file includes:

📌 Key Dashboards
Booking Overview: Total bookings, successful vs. cancelled ride count.

Customer Behavior: Top customers, ride frequency.

Vehicle Analysis: Ride distribution by vehicle type, average distances.

Payment Methods: Mode of payments used.

Driver & Customer Ratings: Visualization of feedback metrics.

Cancellation Reasons: Segregation of cancellation causes (driver/customer).

🎯 Dashboard Goals
Provide decision-makers a high-level view of operations.

Pinpoint operational bottlenecks (e.g., cancellations, delays).

Identify trends for marketing (top users, preferred vehicles).

Suggest improvements in service quality based on ratings.

✅ Tools & Technologies Used
SQL – Data querying, transformation, and logic building

Power BI – Interactive dashboard creation

Excel/CSV – Raw data storage and initial inspection

📌 How to Use
Open Ola Database.csv in any spreadsheet software or load into SQL DB.

Run Sql problems.sql to generate views in your SQL engine.

Open Ola Project Dashboard.pbix in Power BI Desktop to explore dashboards.

🧠 Insights & Outcomes
The majority of cancellations are customer-initiated.

Prime Sedan rides show the widest range of driver ratings.

UPI is a leading payment method.

Only a handful of customers contribute to a large volume of rides.

🙋 Author
Ayush Upadhyay
B.Tech in Computer Science | Aspiring Data Analyst
Skills: SQL, Python, Power BI, Excel
Completed: Samsung Innovation Campus – Big Data

