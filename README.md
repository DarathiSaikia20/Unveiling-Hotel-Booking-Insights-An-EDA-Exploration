<h1 align="center"> Unveiling Hotel Booking Insights: An EDA Exploration </h1>

<p align="center"> 
<img src="GIF/google play.gif" alt="Animated gif" height="282px">
</p>


## Table Of Contents

- **Project-Description**
- **Project Files Description**
- **Dataset Contents**
- **Variables Details Of Dataset**
- **Problem Statements**
- **Technologies Used**
- **Steps Involved**
- **Key Insights**
- **Conclusion**

## 📋 Project Description
The primary focus of this project was to conduct a comprehensive analysis of a hotel booking dataset comprising 119,390 rows and 32 columns.The goal was to reveal insights into booking trends and cancellations.In addition to data cleaning and preparation, we visualized booking patterns, hotel performance, and geographical distribution. 
Leveraging these insights, our goal was to optimize resource allocation, refine marketing strategies, and enhance customer satisfaction, ultimately driving positive business growth within the hospitality industry

********************************************************************************************************************************************************************

##  💾 Project Files Description

This project comprises a Google Colaboratory notebook and a dataset in CSV format.

 - Input File: Hotel Booking CSV - Contains comprehensive information regarding hotel bookings.
 - Output File:Google Colab - All project outputs are visible within the provided Colab notebook

********************************************************************************************************************************************************************

## Dataset Contents

- The dataset comprises a single CSV file containing information regarding hotel bookings.
- The key variables includes:

  
| Variable                       | Details                                                                                                         |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------|
| hotel                          | Type of hotel: "Resort Hotel" or "City Hotel"                                                                     |
| is_canceled                    | Binary variable: 1 (canceled), 0 (not canceled)                                                                   |
| lead_time                      | Number of days between booking date and arrival date                                                              |
| arrival_date_year              | Year of the arrival date                                                                                          |
| arrival_date_month             | Month of the arrival date                                                                                         |
| arrival_date_week_number       | Week number of the arrival date                                                                                   |
| arrival_date_day_of_month      | Day of the arrival date                                                                                           |
| stays_in_weekend_nights        | Number of weekend nights stayed or booked at the hotel                                                           |
| stays_in_week_nights           | Number of weeknights stayed or booked at the hotel                                                                |
| adults                         | Number of adults included in the booking                                                                          |
| children                       | Number of children included in the booking                                                                        |
| babies                         | Number of babies included in the booking                                                                          |
| meal                           | Type of meal booked: "Undefined/SC", "BB" (Bed & Breakfast), "HB" (Half board), "FB" (Full board)                |
| country                        | Country of origin of the guest                                                                                    |
| market_segment                 | Market segment designation, e.g., "Online TA" (Online Travel Agents), "Groups" (group bookings)                  |
| distribution_channel           | Booking distribution channel: "TA" (Travel Agents), "Direct" (direct bookings), "Corporate" (corporate bookings)  |
| is_repeated_guest              | Binary variable: 1 (repeated guest), 0 (first-time guest)                                                         |
| previous_cancellations         | Number of previous booking cancellations by the guest                                                             |
| previous_bookings_not_canceled | Number of previous bookings not canceled by the guest                                                             |
| reserved_room_type             | Code for the type of room reserved                                                                                 |
| assigned_room_type             | Code for the type of room assigned to the booking                                                                  |
| booking_changes                | Number of changes or modifications made to the booking                                                            |
| deposit_type                   | Type of deposit made for the booking: "No Deposit," "Non Refund," "Refundable"                                    |
| agent                          | ID of the travel agency that made the booking                                                                      |
| company                        | ID of the company/entity that made the booking or is responsible for payment                                      |
| days_in_waiting_list           | Number of days the booking was on the waiting list before confirmation                                             |
| customer_type                  | Type of booking: "Contract," "Group," "Transient," "Transient-Party"                                               |
| adr                            | Average Daily Rate: average rental income per paid occupied room                                                   |
| required_car_parking_spaces    | Number of car parking spaces required by the guest                                                                 |
| total_of_special_requests      | Number of special requests made by the guest                                                                       |
| reservation_status             | Last reservation status: "Canceled," "Check-Out," "No-Show"                                                        |
| reservation_status_date        | Date of the last status update                                                                                    |

********************************************************************************************************************************************************************

## 📋Problem Statements

  - Identify the month with the highest number of bookings.
  - Determine which hotel category exhibits the highest number of bookings, cancellations, and revenue.
  - Analyze the country with the highest number of bookings.
  - Investigate which distribution channel demonstrates the highest number of bookings along with cancellations.
  - Examine which type of hotel room generates the most revenue across different hotels.
  - Assess which customer category predominantly engages in hotel bookings.
  - Discover the preferred type of hotel for longer stays based on customer behavior.
  - Understand the impact of lead times on booking patterns.
  - Identify the most preferred meal type by customers.
  - Analyze the type of car parking allocation most frequently required by customers.

********************************************************************************************************************************************************************

## 🚀 Technologies and Libraries Used in the Project 📚
1. Python
2. Numpy library
3. Pandas library
4. Matplotlib
5. Seaborn

********************************************************************************************************************************************************************

## 📖	Steps Involved

  - **Data Cleaning** :
        Addressing missing values by dropping columns with a high number of missing values and handling other columns with relatively lower missing values
        using median and mode for numeric and text columns, respectively.

 - **Data Type Conversion and Feature Engineering** :
        Convert the data type of the "children" column from float to int64 for better data representation.
        Introduce new columns for further analysis, including 'arrival_date', 'total_stays', 'revenue', 'reserved_room_assigned', 'total_person', and 'customer_category'.

  - **Exploratory Data Analysis (EDA)** :
        After preparing the data for analysis, conduct visualizations to understand the relationships between variables and uncover valuable insights for positive business impact.


    - **Key Insights from EDA** :

      - Months of July and August exhibit the highest booking activity.
      - Travel agencies (TA) show a high range of bookings.
      - City hotel is the preferred choice for customers, despite experiencing high cancellation rates.
      - Room type significantly impacts revenue for each hotel category.
      - Couples are the primary demographic trending towards hotel bookings.
      - Resort hotels are preferred over city hotels for longer stays.
      - Bed & Breakfast (BB) is the most preferred meal type by customers.
      - Parking allocation is not a primary factor, showing low requirements.
      - Customers from Portugal are trending towards hotel bookings.

These steps encompass the process of preparing, analyzing, and extracting meaningful insights from the dataset, providing valuable information for business growth and decision-making.

********************************************************************************************************************************************************************

## 📋 Conclusion:

The EDA insights present clear opportunities for business growth in the hotel industry. By capitalizing on seasonal booking trends, optimizing partnerships with influential booking channels, and aligning services with customer preferences, the business can maximize revenue. Understanding customer demographics and their needs allows for targeted marketing and personalized experiences, while recognizing low demand for parking allocation influences resource planning. Identifying trends in customer origins guides international marketing efforts. 
These insights provide a roadmap for strategic decision-making, customer-centric services, and targeted marketing efforts to foster business growth within the hotel industry.




























    
