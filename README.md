# Understanding What Drives Reviews: Strategic Insights for Airbnb Listings in Bangkok

This repository contains an exploratory data analysis (EDA) project on Airbnb listings in Bangkok. The goal of this project is to identify the characteristics of listings that have received reviews versus those that have not, and to provide data-driven recommendations for host optimization and platform strategy.

---

## Problem Statement

**What are the characteristics of Airbnb listings in Bangkok that have received reviews, compared to those that have not?**

This analysis aims to:

- Identify accommodation types that are more attractive to users.
- Highlight districts/neighbourhoods with higher rental potential.
- Optimize listing availability to increase visibility and engagement.
- Recommend strategies to support underperforming listings.

---

## Dataset Overview

The dataset includes:

- Listing details: `room_type`, `price`, `availability_365`, `minimum_nights`, etc.
- Review-related data: `number_of_reviews`, `reviews_per_month`, `last_review`.
- Geolocation data: `neighbourhood`, `latitude`, `longitude`.
Data scope: 15,845 listings in Bangkok

---

## 🛠️ Key Steps in the Workflow

1. **Data Cleaning**
   - Handle missing values (fill or drop based on context)
   - Drop unnecessary/duplicate columns

2. **Feature Engineering**
   - Create `has_review` (binary feature)
   - Convert date and ID types
   - Bin `minimum_nights` into categories

3. **Exploratory Data Analysis**
   - Comparison between reviewed and unreviewed listings
   - Analysis on:
     - Favourite Neighbourhood
     - Room type vs review status
     - Price distribution
     - Availability patterns
     - Minimum nights mostly reviewed

---

## Key Findings

- **63%** of listings have received at least one review.
- Mostly located in strategic neighbourhoods such as Khlong Toei and Vandhana, which also have the highest total number of listings.
- Active or reviewed room is frequently consist of Private rooms or Entire homes/apartments, while inactive listings tend to be Shared rooms or Hotel rooms.
- Active listings are not always available 365 days a year, often due to frequent bookings, whereas inactive listings are often available year-round but receive little interest.
- Active listings tend to be more attractive and competitive in terms of price, location, and room type.
- Active listings more commonly set shorter minimum stays, such as 2–3 nights or 4–7 nights.
- Listings with a minimum stay of 91+ nights are far less likely to receive reviews.

---

## Recommendations

1. Focus promotion on strategic neighbourhoods like **Khlong Toei** and **Vadhana**.
2. Prioritize listing types like **Entire home/apt** and **Private room**.
3. Promote **moderately priced** listings using automated pricing tools.
4. Encourage realistic **availability windows** (avoid full 365 days).
5. Use `reviews_per_month` as a **key performance metric** for visibility.
6. Support **new hosts** with onboarding and special promotion programs.
7. Recommend **flexible minimum night settings** (2–7 nights ideal).

---

## Theoretical Framework

This project briefly references **Expectancy Disconfirmation Theory (EDT)** to explain how price and expectations influence review behavior.

---

## Tableau Dashboard
You can access the dashboard from link below:
https://public.tableau.com/views/Capstone2_17511871934220/HostAnalysis?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


