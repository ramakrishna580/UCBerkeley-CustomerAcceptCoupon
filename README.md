# Coupon Acceptance Analysis

## Project Overview

This project analyzes customer behavior from a driving coupon dataset. The goal is to understand which factors influence whether a driver accepts or rejects a coupon while driving. 
The analysis focuses on customer attributes, driving context, coupon type, passenger type, weather, time of day, and prior behavior.

The dataset includes several types of coupons, including coffee house, bar, carry out/take away, inexpensive restaurant, and expensive restaurant coupons.

## Key Question

What factors make a driver more likely to accept a coupon?

## Dataset

The dataset was provided as part of the Practical Application 1 assignment and originates from the UCI Machine Learning Repository. It contains survey responses collected through Amazon Mechanical Turk.

The target variable is `Y`:

* `1` = customer accepted the coupon
* `0` = customer rejected the coupon

## Summary of Findings

Overall, more than half of customers accepted the coupons. Acceptance rates varied significantly depending on coupon type, customer behavior, passenger type, destination, and context.

### Bar Coupon Findings

Drivers were more likely to accept bar coupons when they:

* Already visited bars more frequently
* Were younger adults
* Did not have children in the car
* Were not widowed
* Were traveling with friends or a partner
* Frequently visited inexpensive restaurants
* Had lower-to-middle income levels

The strongest indicator of bar coupon acceptance was prior bar-going behavior. Drivers who already went to bars at least once a month were much more likely to accept a bar coupon than those who rarely or never went to bars.

### Coffee House Coupon Findings

For coffee house coupons, customers were more likely to accept when they already visited coffee houses regularly. Acceptance also appeared stronger among customers with no urgent destination and during favorable driving conditions.

## Visualizations Used

The analysis includes:

* Bar plot of coupon type distribution
* Histogram of temperature
* Bar coupon acceptance comparison charts
* Coffee house acceptance comparison charts
* Summary tables showing acceptance rates by customer segment

## Actionable Recommendations

Businesses should target coupons based on customer habits and driving context.

For bar coupons:

* Target drivers who already visit bars at least once per month.
* Avoid targeting drivers traveling with children.
* Prioritize social travel situations, such as drivers with friends or partners.
* Younger adults may be more responsive to bar coupons.

For coffee house coupons:

* Target customers who already visit coffee houses.
* Focus on drivers with flexible destinations.
* Morning and afternoon offers may be more effective.


## Next Steps

Future analysis could include below steps/points to consider:

1. Building a machine learning model to predict coupon acceptance.
2. Testing whether the observed differences are statistically significant.
3. Comparing all coupon types, not just bar and coffee house coupons.
4. Studying the effect of coupon expiration time.
5. Exploring weather, distance, and direction of travel in more detail.

## Conclusion

The analysis shows that coupon acceptance is strongly influenced by prior customer behavior and driving context. Customers are more likely to accept coupons for places they already visit. 
Therefore, targeted coupon delivery based on customer habits, passenger type, and travel situation can improve coupon acceptance rates.
