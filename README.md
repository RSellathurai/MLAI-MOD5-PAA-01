# MLAI-MOD5-PAA-01
Module 5 Practical Application Assignment - 01

# Driving Coupon Acceptance Analysis

## Overview

The purpose of this report is to analyze and identify the factors that influence a driver's decision to accept coupons delivered to their cell phone while driving.

## Data Description

The dataset includes attributes divided into user attributes, contextual attributes, and coupon attributes:

- **User Attributes:**
  - Gender: male, female
  - Age: below 21, 21 to 25, 26 to 30, etc.
  - Marital Status: single, married partner, unmarried partner, widowed
  - Number of children: 0, 1, more than 1
  - Education: high school, bachelor's degree, associate degree, graduate degree
  - Occupation: architecture & engineering, business & financial, etc.
  - Annual income: less than $12500, $12500 - $24999, $25000 - $37499, etc.
  - Frequency of visits to bars, coffee houses, takeaway food places, and inexpensive restaurants

- **Contextual Attributes:**
  - Driving destination: home, work, no urgent destination
  - Location of user, coupon, and destination
  - Weather: sunny, rainy, snowy
  - Temperature: 30F, 55F, 80F
  - Time: 10 AM, 2 PM, 6 PM
  - Passenger: alone, partner, kids, friends

- **Coupon Attributes:**
  - Time before it expires: 2 hours, one day

## Key Findings

### Distribution of coupons
To analyze the distribution of the "coupon" column within the dataset, it is recommended to employ a bar plot. This visualization technique effectively illustrates the frequency of each unique value present in the "coupon" column, providing a clear and concise representation of the data. By plotting the counts of each coupon type, one can easily discern patterns and draw insights regarding the prevalence of different coupons.
![Bar Plot of Coupons](MLAI-MOD5-PAA-01/images/plots/distribution_of_coupons.png)


### Proportion of Accepted Coupons

- The overall acceptance rate for coupons is 56.84%.

### What is the difference between the drivers who accepted the Bar coupons and who does not.

#### Frequency of Bar Visits

- Drivers who visit bars more than once a month have a higher acceptance rate for bar coupons.
- Drivers traveling without kids and who go to bars frequently show an even higher acceptance rate.

#### Specific Conditions for Higher Acceptance Rates

Drivers satisfying any of the following conditions have a higher acceptance rate of 61.03%

1. Visit bars more than once a month, have passengers that are not kids, and are not widowed.
2. Visit bars more than once a month and are under the age of 30.
3. Visit inexpensive restaurants more than four times a month and have an annual income of less than $50,000.

## Detailed Analys



