# HOTEL-BOOKING-SYSTEM
Developing Project Based on Java and Database with General Hotel  booking, its facilities ,various Services to Peoples and Employee of Hotels.
 
 1. Admin Module to add Users  - This module will  be developed by (1) or (2) associates in group
2. Receptionist Module - This module will  be developed by 2 associates in group
3. Customer Module - This module will  be developed by 1 associates in group
4. Report Module - This module will  be developed by 1 associates in group


"USER" -
LOGIN_ID
PASSWORD
LAST_MODIFIED_DATE
ROLE  (Receipnist, Guest, Admin) -- CHECK/ENUM

User----1:M-----Roooms

"ROOM"
ROOM_NO 
TYPE (Normal, Deluxe, Super Deluxe, Executive Suite)
TELEVISION
AIR_CONDITIONER
WASHIN_MACHINE
KITECH
CHARGES

"BOOKIN_INFOMATION"
BOOKING_ID --- PRIMARY KEY FO BOOKING_INFORMATION
GUEST_ID -- FK for USERID
ROOOM_ID --- FK fro ROOM_NO
CHECKIN_DATE  -- DEFAUL TIME is 12.00noon
CHECKOUT_DATE -- DEFAUL TIME is 12.00noon
ID_PROOF
VEHICLE_NO
MOBILE_NO
ADDRESS_COMING_FROM
REASON_FOR_STAY


"ROOM_SERVICES"
BOOKING_ID --- FK from BOOKING_INFORMATION
SERVICE_TYPE (Food, Laundry, Meal, Bevarages, Cab)
CHARGES
DATETIME_OF_SERVICES  

Admin Module to add Users

♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦
------------------- Hotel 18° --------------------
♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦
                  Welcome Admin!

      Please Choose from below options-

      1. Add User with Types(Admin, Receptionist, Customer/Guest)
      2. Update User with Types(Admin, Receptionist, Customer/Guest)
      3. Delete User with Types(Admin, Receptionist, Customer/Guest)
      4. Search User with Types(Admin, Receptionist, Customer/Guest)
      5. Search All Users with Types(Admin, Receptionist, Customer/Guest)

      Press (n) to exit...

♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦

Receptionist Module

♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦
------------------- Hotel 18° --------------------
♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦
                  Welcome Receptionist!

      Please Choose from below options-

      1. See Availabel Rooms
      2. Check customer registration
      3. Booking by Receipnist (10% off)
      4. Show Room Types (Normal, Deluxe, Super Deluxe, Executive Suite)
      5. See total bill for specific customer

      Press (n) to exit...

♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦


Customer Module

♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦
------------------- Hotel 18° --------------------
♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦
                  Welcome Guest!

      Please Choose from below options-

      1. Register as New Customer
      2. Book Room with Types (Normal, Deluxe, Super Deluxe, Executive Suite)
      3. Check Room Details
      4. Check Bills (Till Date)
      5. Pay Bills & Checkout

      Press (n) to exit...

♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦

Report Module

♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦
------------------- Hotel 18° --------------------
♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦
                  Welcome Guest!

      Please Choose from below options-

      1. View Report by individual Customer
      2. Check Bills (Till Date) of specific Customer
      3. Check Total Revenue (Till Date) All Customer

      Press (n) to exit...

♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦♦

