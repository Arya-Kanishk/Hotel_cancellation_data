# Hotel_cancellation_data
  This notebook analyzes a hotel booking dataset to understand patterns and factors influencing cancellations. The dataset includes various features related to bookings, customer demographics, and stay details. The objective is to extract insights and build predictive models to minimize cancellations and optimize hotel operations.

## Dataset Description
The dataset contains the following columns:

hotel: The type of hotel (city hotel or resort hotel).
is_canceled: Indicates if the booking was canceled (1) or not (0).
lead_time: The number of days between the booking date and the arrival date.
arrival_date_year: The year of arrival date.
arrival_date_month: The month of arrival date.
arrival_date_week_number: The week number of the arrival date.
arrival_date_day_of_month: The day of the month of the arrival date.
stays_in_weekend_nights: Number of weekend nights (Saturday and Sunday) the guest stayed or booked to stay at the hotel.
stays_in_week_nights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel.
adults: Number of adults.
children: Number of children.
babies: Number of babies.
meal: Type of meal booked (e.g., BB - Bed & Breakfast, HB - Half Board, FB - Full Board).
country: Country of origin of the guest.
market_segment: Market segment designation (e.g., Direct, Corporate, Online TA).
distribution_channel: Booking distribution channel (e.g., Direct, TA/TO).
is_repeated_guest: Indicates if the guest is a repeated guest (1) or not (0).
previous_cancellations: Number of previous bookings that were canceled by the customer prior to the current booking.
previous_bookings_not_canceled: Number of previous bookings not canceled by the customer prior to the current booking.
reserved_room_type: Code of room type reserved.
assigned_room_type: Code of room type assigned.

booking_changes: Number of changes/amendments made to the booking.
deposit_type: Type of deposit made (e.g., No Deposit, Non Refund, Refundable).
agent: ID of the travel agent who made the booking.
company: ID of the company/entity that made the booking or responsible for the booking.
days_in_waiting_list: Number of days the booking was in the waiting list before it was confirmed to the customer.
customer_type: Type of booking (e.g., Contract, Group, Transient).
adr: Average Daily Rate, as defined by dividing the sum of all lodging transactions by the total number of staying nights.
required_car_parking_spaces: Number of car parking spaces required by the customer.
total_of_special_requests: Total number of special requests made by the customer (e.g., high floor, crib, etc.).
reservation_status: Reservation last status (e.g., Canceled, Check-Out, No-Show).
reservation_status_date: Date at which the last status was set.
