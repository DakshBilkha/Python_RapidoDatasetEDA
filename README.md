# Python_RapidoDatasetEDA

**Title: Analysis of Rapido Ride Services in Bangalore**
**Objective**:
This project aims to analyze ride service trends, pricing structures, cancellation patterns, and customer payment preferences for Rapido in Bangalore over a two-month period. By examining key metrics such as ride duration, distance, fare components, and payment methods, this study provides insights into transportation patterns, service utilization, and ride economics.

**Dataset Overview**:
The dataset contains comprehensive ride records from Rapido’s various services in Bangalore, including:

Bike
Bike Lite
Cab Economy
Auto
Parcel Delivery
Each ride entry includes details such as source and destination, ride duration, distance, fare charges, payment method, and ride status.

**Key Data Fields**:
Services: Five different ride categories with the following distribution:

Bike – Standard bike ride service
Bike Lite – Economical bike ride service
Cab Economy  – Standard cab ride service
Auto – Auto-rickshaw service
Parcel  – Parcel delivery service

**Ride Details**:
Date & Time: Rides occurred over a two-month period at random times.
Source & Destination: Various locations across Bangalore.
Duration: Ride times range from 10 to 120 minutes.
Distance: Trips range from 1 km to 50 km.

**Ride Status**:
Completed (90%)
Cancelled (10%)

**Fare Breakdown**:
Base Fare: ₹50 – ₹1000 (null for cancellations)
Miscellaneous Charges: ₹0 – ₹50 (tolls, surcharges)
Total Fare: Sum of base fare + misc. charges (null for cancellations)

**Payment Methods**: (For completed rides only)
Amazon Pay
QR Scan
GPay
Paytm
