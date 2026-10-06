# Ride Demand and Cancellation Analysis

## Project Overview

This project analyzes ride-sharing data to understand demand patterns, cancellation behavior, and operational performance across different cities and time periods. The analysis helps identify supply-demand imbalances, peak demand hours, and areas where operational improvements can reduce ride cancellations and improve customer experience.

## Business Problem

Ride-sharing platforms often face challenges such as:

* High ride cancellation rates.
* Driver shortages during peak demand periods.
* Uneven demand across cities.
* Supply-demand mismatches affecting ride fulfillment.
* Reduced customer satisfaction due to ride unavailability.

Without proper analysis, these issues can negatively impact revenue, customer retention, and operational efficiency.

## Project Objective

* Analyze ride demand across cities and time periods.
* Identify cancellation trends and operational bottlenecks.
* Evaluate city-wise ride fulfillment performance.
* Understand the relationship between demand and cancellations.
* Provide recommendations to improve driver allocation and reduce cancellations.

## Tools Used

* Python
* Pandas
* Matplotlib
* Google Colab
  
## Dataset

This project uses a **ride-sharing dataset** containing around**1k ride records** designed to simulate real-world ride-hailing operations.

The dataset includes information such as:
- Ride ID
- Date & Time
- City
- Pickup & Drop Location
- Distance
- Fare Amount
- Surge Multiplier
- Customer Rating
- Ride Status
- Payment Method
- Ride Type

**Dataset Location:** [ride_sharing_dataset.xlsx](Ride_Sharing_Dataset/ride_sharing_dataset.xlsx)`

## Dashboard Visual Analysis

### City-wise Ride Demand

Compares ride demand across different cities to identify major markets and areas with lower platform usage.

<img width="571" height="525" alt="image" src="https://github.com/user-attachments/assets/e106d0f7-864b-46e8-afa3-5dc43b2525f2" />

### Hour-wise Ride Demand and Cancellation Trend

Analyzes ride demand and cancellations throughout the day to identify peak demand periods and operational pressure points.

<img width="607" height="469" alt="image" src="https://github.com/user-attachments/assets/b8ed7752-0767-4618-b3da-f5f800fab956" />

### City-wise Cancellations

Shows the total number of cancelled rides across cities to identify locations experiencing ride fulfillment challenges.

<img width="570" height="540" alt="image" src="https://github.com/user-attachments/assets/42359ee6-96d5-4dd3-a0b9-bf3e878b5d2a" />

### Ride Type-wise Cancellations

Compares cancellations across ride categories to determine whether specific ride types contribute disproportionately to cancellation volume.

<img width="570" height="503" alt="image" src="https://github.com/user-attachments/assets/aedaa5fd-dcb7-4ff8-a5fe-3743b2399f85" />

### City-wise Cancellation Rate

Measures the percentage of rides cancelled in each city to evaluate operational performance independent of ride volume.

<img width="570" height="540" alt="image" src="https://github.com/user-attachments/assets/30e22e8f-b92a-4a8e-9526-04b6d73afc82" />

### Hour-wise Cancellation Rate

Tracks cancellation rates throughout the day to identify periods where driver availability may not be sufficient to meet demand.

<img width="570" height="469" alt="image" src="https://github.com/user-attachments/assets/14ce024f-c0eb-42f9-83cc-8fe96725e35f" />

## Key Findings

* Hyderabad shows the lowest ride demand but experiences a relatively high cancellation rate, indicating supply-demand imbalance.
* Ride demand peaks during evening commute hours, reflecting increased transportation needs after work hours.
* Cancellation rates are highest during morning commute periods, indicating insufficient ride availability during peak hours.
* Bangalore demonstrates comparatively stronger ride fulfillment performance with lower cancellation rates.

## Business Recommendations

* Increase driver availability during peak demand periods, particularly morning and evening commute hours.
* Implement incentive programs to encourage driver participation during low-supply periods.
* Improve driver allocation strategies in cities with higher cancellation rates.

## Business Impact

* Supports data-driven driver allocation and workforce planning.
* Enables proactive actions to reduce cancellations and improve customer experience.
* Assists ride-sharing platforms in optimizing supply-demand balance across cities and time periods.
