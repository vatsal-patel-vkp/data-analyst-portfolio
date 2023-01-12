# Hotel Bookiing Analysis

Have you ever thought about the best time of year to book a hotel room? Or what is the best length of stay to get the best daily rate? What if you could predict whether or not a hotel would receive an unusually high number of special requests? This hotel booking dataset can assist you in answering those questions!
This data set contains booking information for a city hotel and a resort hotel, including when the booking was made, length of stay, number of adults, children, and/or babies, and number of available parking spaces, among other things. The data contains no personally identifiable information.

### Dataset Exploration
 We have total 119390 rows and 32 columns.
 
### Data Description:
**hotel:** Hotel(Resort Hotel or City Hotel)

**is_canceled:** Value indicating if the booking was canceled (1) or not (0)

**lead_time:** Number of days that elapsed between the entering date of the booking into the PMS and the arrival date*

**arrival_date_year:** Year of arrival date

**arrival_date_month:** Month of arrival date

**arrival_date_week_number:** Week number of year for arrival date

**arrival_date_day_of_month:** Day of arrival date

**stays_in_weekend_nights:** Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel

**stays_in_week_nights:** Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel

**adults:** Number of adults

**children:** Number of children

**babies:** Number of babies

**meal:** Type of meal booked. Categories are presented in standard hospitality meal packages:

**country:** Country of origin.

**market_segment** Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”

**distribution_channel:** Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”

**is_repeated_guest:** Value indicating if the booking name was from a repeated guest (1) or not (0)

**previous_cancellations:** Number of previous bookings that were cancelled by the customer prior to the current booking

**previous_bookings_not_canceled:** Number of previous bookings not cancelled by the customer prior to the current booking

**reserved_room_type:** Code of room type reserved. Code is presented instead of designation for anonymity reasons.

**assigned_room_type:** Code for the type of room assigned to the booking.

**booking_changes:** Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation

**deposit_type:** Indication on if the customer made a deposit to guarantee the booking.

**agent:** ID of the travel agency that made the booking

**company:** ID of the company/entity that made the booking or responsible for paying the booking.

**days_in_waiting_list:** Number of days the booking was in the waiting list before it was confirmed to the customer

**customer_type:** Type of booking, assuming one of four categories

**adr:** Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights

**required_car_parking_spaces:** Number of car parking spaces required by the customer

**total_of_special_requests:** Number of special requests made by the customer (e.g. twin bed or high floor)*

**reservation_status:** Reservation last status, assuming one of three categories

**Canceled:** booking was canceled by the customer

**Check-Out:** customer has checked in but already departed

**No-Show:** customer did not check-in and did inform the hotel of the reason why

**reservation_status_date:** Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel

## EDA (Exploratory Data Analysis)
**Univariate Analysis**

### 1) Which type of hotel is in the dataset?
       Two types : City Hotel and Resort Hotel.
       
### 2) In which month has the highest bookings/total guest by hotel happened?
       July and August months had the most Bookings. Summer vaccation can be the reason for the bookings.
       
### 3) Which type of food is mostly preferred by the guests?
       
   #### Types of meal in hotels:
   - BB - (Bed and Breakfast)
   - HB - (Half Board)
   - FB - (Full Board)
   - SC/Undefined - (Self Catering)
   
   #### Observation
 - So the most preferred meal type by the guests is BB( Bed and Breakfast)** 
 - HB- (Half Board) and SC- (Self Catering) are equally preferred.**
 
 ### 4) What is the total number of required_car_parking_spaces?
 
 - Here is_cancelled = 0 means guest don't required parking and is_cancelled = 1 means parking required.
        
   #### Observation
 - For city hotels and resort hotels majority of the guest did not reqired parking space but few required parking space.

#### 5) Which Hotels has the most repeated guests?
- City Hotel has slightly more repeated guests than the Resort Hotels.

#### 6) Which year has the most booking cancelled or most booking cancelled ?
- Year 2015 had the highest booking cancelled compare to guest who did not cancelled their bookings.
- There was signigicant dropped in the cancellation of the booking in the year 2016 while the more booking was done which was highest among year 2015 and 2017.
- In the year 2017 there was continously dropped in the booking cancellation however there slight declined in the booking which was not cancelled after the year 2016.

   

       

    
