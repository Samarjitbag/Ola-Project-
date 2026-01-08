### **Project Title: End-to-End OLA Ride Data Analytics & Performance Dashboard**

**Overview**
This project provides a 360-degree view of ride-booking operations using a raw dataset of approximately **80,000 rows** from Excel. I utilized **SQL** to clean the data and resolve inconsistencies, then built an interactive **Power BI** dashboard to visualize key performance indicators (KPIs), revenue trends, and customer feedback.

**Key Dashboard Modules & Insights**

* **1. Overall Performance:**
* Visualizes high-level metrics including **54.5K Total Bookings** and **19M Total Booking Value**.
* Tracks ride volume trends over time to identify daily demand fluctuations.


* **2. Vehicle Type Analysis:**
* Provides a comparative table of vehicle performance (e.g., Prime Sedan, Auto, Bike).
* Highlights high-value categories, showing that **Prime Sedans** and **SUVs** drive the highest revenue (over 4M each), while **Autos** serve shorter distances (avg. 10km) compared to other vehicles (~25km).


* **3. Revenue Intelligence:**
* **Payment Analysis:** A bar chart breakdown of "Revenue by Payment Method" identifies the most popular transaction types (likely Cash/UPI) driving cash flow.
* **Customer Value:** Features a "Top 5 Bookings" leaderboard to track high-value customers (e.g., Customer CID933539 generated 5,314 in value).
* **Ride Distance:** Tracks daily ride distance peaks to correlate travel length with revenue spikes.


* **4. Cancellation Insights:**
* Drills down into the **28.07% Cancellation Rate** to understand the "Why" behind lost revenue.
* **Customer Reasons:** Identifies "Driver is not moving towards pickup" (30.31%) and "Change of plans" as top reasons for customer cancellations.
* **Driver Reasons:** Highlights "Personal & Car related issues" (34.88%) as the primary cause for driver cancellations.


* **5. Ratings & Feedback:**
* Monitors service quality with a side-by-side comparison of **Driver vs. Customer Ratings**.
* Shows consistent satisfaction levels across all vehicle types, with ratings stabilizing between **3.98 and 4.01** for both drivers and customers.



**Tech Stack**

* **Data Source:** Excel (80,000+ rows)
* **Data Transformation:** SQL (Complex data cleaning, handling nulls, and logic validation)
* **Visualization:** Microsoft Power BI (DAX, Interactive Slicers, Custom Tooltips)

