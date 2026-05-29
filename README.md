🚖 Ola Customer Booking Analysis (Power BI Dashboard)
📌 Project Overview
This project presents an Exploratory Data Analysis (EDA) of Ola customer bookings using Power BI.
The aim is to uncover patterns in customer ride behavior, booking success rates, cancellations, vehicle preferences, payment methods, and revenue distribution.

By leveraging interactive dashboards, this project provides actionable insights to improve:

Fleet allocation
Customer satisfaction
Revenue optimization
Operational efficiency
📊 Dataset Description
The dataset contains 100,000+ booking records with details about customers, rides, payments, and cancellations.

Columns in the Dataset
Column Name	Description	Key Role
Date	Date of the booking	-
Time	Time of the booking	-
Booking_ID	Unique identifier for each booking	Primary Key
Booking_Status	Status of booking: Success, Canceled by Driver, Canceled by Customer, Driver Not Found	-
Customer_ID	Unique identifier for each customer	Foreign Key
Vehicle_Type	Type of vehicle booked (Sedan, SUV, Auto, Bike, E-Bike, etc.)	-
Pickup_Location	Ride starting point	-
Drop_Location	Ride destination	-
V_TAT	Vehicle Turnaround Time – time taken by vehicle to reach customer	-
C_TAT	Customer Turnaround Time – time taken by customer to board vehicle	-
Canceled_Rides_by_Customer	Flag/Count of rides canceled by customers	-
Canceled_Rides_by_Driver	Flag/Count of rides canceled by drivers	-
Incomplete_Rides	Flag indicating incomplete rides (not finished successfully)	-
Incomplete_Rides_Reason	Reason why the ride was incomplete (technical issue, wrong address, etc.)	-
Booking_Value	Value of the booking in local currency	-
Payment_Method	Mode of payment (Cash, UPI, Credit Card, Debit Card)	-
Ride_Distance	Distance travelled during the ride (in km)	-
Driver_Ratings	Rating given to the driver by the customer	-
Customer_Rating	Rating given to the customer by the driver	-
Vehicle Images	Image reference for the booked vehicle type	-
📈 Dashboard Features
The dashboard is divided into 5 key sections:

1️⃣ Overall Performance
Total Bookings: 103,024
Total Booking Value: ₹35M
Booking Status Breakdown (62% Success, ~18% Driver Canceled, ~10% Customer Canceled, ~10% Driver Not Found)
Ride Volume Trend over time
📌 Insight: A majority of bookings are successful, but cancellations by drivers contribute to lost revenue.
<img width="2075" height="1200" alt="image" src="https://github.com/user-attachments/assets/1ac3534c-3359-4cc1-92c2-46a393534fc0" />
2️⃣ Vehicle Type Analysis
Booking Value and Success Value split by vehicle type
Avg. Distance and Total Distance traveled
Comparison of Sedan, SUV, Auto, Bike, E-Bike performance
📌 Insight: Premium vehicles (Sedan, Plus) generate higher booking values, while E-Bikes show promising efficiency with good distance coverage.
<img width="2075" height="1200" alt="image" src="https://github.com/user-attachments/assets/67830d26-84cd-45f9-8d61-3749f0a6103f" />
3️⃣ Revenue Insights
Revenue split by Payment Method (Cash dominates, followed by UPI)
Top 5 Customers contributing to revenue
Ride Distance trend by date
📌 Insight: Digital payments (UPI) are rising but still lag behind cash. Targeting loyal high-value customers can improve retention.
<img width="2075" height="1200" alt="image" src="https://github.com/user-attachments/assets/b8f14bd8-2ee2-447c-8cac-8d6528c4f214" />



4️⃣ Cancellation Analysis
Cancellation Rate: 28.08%
Split of cancellations by Drivers vs. Customers
Reasons for cancellations (wrong address, AC not working, change of plans, driver not moving, etc.)
📌 Insight: Driver-related issues are the biggest reason for cancellations, highlighting an operational challenge.
<img width="2075" height="1200" alt="image" src="https://github.com/user-attachments/assets/cce9e881-f956-4911-a823-2d1d6f07acc3" />


5️⃣ Ratings Analysis
Driver Ratings vs. Customer Ratings by Vehicle Type
Average Ratings hover around 4.0, but Bikes and E-Bikes slightly underperform
📌 Insight: Consistent ratings show reliability, but Bikes/E-Bikes need service quality improvement.

Ola Customer Booking Analysis_page-0005
<img width="2075" height="1200" alt="image" src="https://github.com/user-attachments/assets/816e11ba-8d61-4a6c-bb8b-c98f5fee0d1e" />

🛠️ Tools & Technologies
Data Source: Excel (Bookings-100000-Rows.xlsx)
Visualization Tool: Microsoft Power BI (Ola Customer Booking Analysis.pbix)
Techniques: DAX measures, calculated columns, slicers, filters, drill-downs
✅ Key Takeaways
Ola has a strong success rate, but driver cancellations remain a concern.
Cash is still dominant in payments, suggesting an opportunity to push digital adoption.
Sedan and Premium vehicles generate the most value, but E-Bikes show efficiency potential.
Customer loyalty programs can be designed targeting high-value repeat customers.
Reducing operational issues (driver delays, cancellations, AC problems) will directly boost revenue and satisfaction.

