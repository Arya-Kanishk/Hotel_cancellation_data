# Hotel_cancellation_data
  This notebook analyzes a hotel booking dataset to understand patterns and factors influencing cancellations. The dataset includes various features related to bookings, customer demographics, and stay details. The objective is to extract insights and build predictive models to minimize cancellations and optimize hotel operations.

## Dataset Description
The dataset contains the following columns:

 - hotel: The type of hotel (city hotel or resort hotel).
 - is_canceled: Indicates if the booking was canceled (1) or not (0).
 - lead_time: The number of days between the booking date and the arrival date.
 - arrival_date_year: The year of arrival date.
 - arrival_date_month: The month of arrival date.
 - arrival_date_week_number: The week number of the arrival date.
 - arrival_date_day_of_month: The day of the month of the arrival date.
 - stays_in_weekend_nights: Number of weekend nights (Saturday and Sunday) the guest stayed or booked to stay at the hotel.
 - stays_in_week_nights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel.
 - adults: Number of adults.
 - children: Number of children.
 - babies: Number of babies.
 - meal: Type of meal booked (e.g., BB - Bed & Breakfast, HB - Half Board, FB - Full Board).
 - country: Country of origin of the guest.
 - market_segment: Market segment designation (e.g., Direct, Corporate, Online TA).
 - distribution_channel: Booking distribution channel (e.g., Direct, TA/TO).
 - is_repeated_guest: Indicates if the guest is a repeated guest (1) or not (0).
 - previous_cancellations: Number of previous bookings that were canceled by the customer prior to the current booking.
 - previous_bookings_not_canceled: Number of previous bookings not canceled by the customer prior to the current booking.
 -  reserved_room_type: Code of room type reserved.
 - assigned_room_type: Code of room type assigned.
 - booking_changes: Number of changes/amendments made to the booking.
 - deposit_type: Type of deposit made (e.g., No Deposit, Non Refund, Refundable).
 - agent: ID of the travel agent who made the booking.
 - company: ID of the company/entity that made the booking or responsible for the booking.
 - days_in_waiting_list: Number of days the booking was in the waiting list before it was confirmed to the customer.
 - customer_type: Type of booking (e.g., Contract, Group, Transient).
 - adr: Average Daily Rate, as defined by dividing the sum of all lodging transactions by the total number of staying nights.
 - required_car_parking_spaces: Number of car parking spaces required by the customer.
 - total_of_special_requests: Total number of special requests made by the customer (e.g., high floor, crib, etc.).
 - reservation_status: Reservation last status (e.g., Canceled, Check-Out, No-Show).
 - reservation_status_date: Date at which the last status was set.

## To extract data from an API, you'll typically follow these steps:
 - Understand the API Documentation: Review the API documentation to understand the endpoints, request methods, required parameters, and authentication mechanisms.
 - Set Up Your Environment: Ensure you have the necessary libraries installed. For Python, common libraries include requests for making HTTP requests and json for handling JSON data.
 - Make the API Request: Use the requests library to make a GET or POST request to the API endpoint.
 - Handle the Response: Check the response status code to ensure the request was successful. If successful, parse the JSON data from the response.
 - Process the Data: Depending on your needs, you can process, analyze, or store the extracted data.
## Types of Data
 - Categorical data refers to a data type that can be stored into groups/categories/labels.
 - Examples of categorical variables are : age group, educational level,blood type etc.

 - Numerical data refers to the data that is in the form of numbers,
 - Examples of numerical data are height, weight, age etc.

 - Numerical data has two categories: discrete data and continuous data
 - Discrete data : It basically takes countable numbers like 1, 2, 3, 4, 5, and so on. In case of infinity, these numbers will keep going on. Age of a fly : 8 , 9 day etc..
 - Continuous data : which is continuous in nature amount of sugar , 11.2 kg, temp of a cit, your bank balance !
 - For example, salary levels and performance classifications are discrete variables, whereas height and weight are continuous variables.

 - Categorical data has : Object & bool data-types
 - Numerical data have : Integer & Float data-type
 - Variations of int are : ('int64','int32','int16') in numpy library.
 - Int16 is a 16 bit signed integer , it means it can store both positive & negative values
 - -- int16 has has a range of (2^15 − 1) to -2^15 -- int16 has a length of 16 bits (2 bytes).. ie Int16 uses 16 bits

 - Int32 is a 32 bit signed integer , it means it stores both positive & negative values
 - -- int32 has has a range of (2³¹ − 1) to -2^31 -- int32 has a length of 32 bits (4 bytes),, ie Int32 uses 32 bits

 - Int64 is a 64 bit signed integer , it means it can store both positive & negative values
 - -- int64 has has a range of (2^63 − 1) to -2^63 -- int64 has a length of 64 bits (8 bytes) , ie Int64 uses 64 bits.

 - The only difference is that int64 has max range of storing numbers , then comes int32 , then 16 , then int8

 - That means that Int64’s take up twice as much memory-and doing operations on them may be a lot slower in some machine architectures.

However, Int64’s can represent numbers much more accurately than 32 bit floats.They also allow much larger numbers to be stored..
