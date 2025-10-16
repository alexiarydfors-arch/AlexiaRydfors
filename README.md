# AlexiaRydfors

# Practical Application 1 — Will the Customer Accept the Coupon?

This repository explores which drivers are most likely to accept mobile coupons using the UCI "In-vehicle coupon recommendation" dataset. The analysis focuses on overall acceptance as well as deep dives on **Bar** coupons and an **Independent Investigation** on **Coffee House** coupons.

## Key Takeaways

- **Overall acceptance rate (all coupons):** 0.568
- **Bar coupons acceptance:** 0.410
- Among bar coupons, those who **visit bars more than 3×/month** show a **higher** acceptance rate (0.769) than those visiting **≤3×/month** (0.371).
- Drivers who **visit bars frequently (>3×/mo)** **and** are **older than 25, but less than 30** tend to accept at higher rates than others in the bar-coupon group.
- When the bar-going driver **does not have kids as passengers** and is **not in farming/fishing/forestry**, acceptance is above the bar baseline.

**Coffee House (independent investigation):** 
- In general, there is a higher acceptance rate for those who **visit Coffee Houses more than 4x/week** than those who rarely get coffee
- Drivers who have a **friend or partner as passenger** are more likely to accept a coupon
- Drivers are more likely to accept **earlier in the day** (up til around 2pm)

## Actionable Recommendations

- **Target habitual customers** within each category (e.g., frequent bar- or coffee-goers) with timely offers.
- **Consider context**: time-of-day and passenger composition can change acceptance likelihood.
- **Refine segments** using simple thresholds (e.g., visit frequency > 3×/mo) to lift acceptance rates.
- Since mostly younger people tend to accept the Coffee House coupons, **making coupons digital** might boost acceptance rates, as many younger people use their phones to pay for things (e.g., ApplePay)
- Since people going with their partners or a friend correlates to higher rates, having a **BOGO (Buy One, Get One) type coupon** might help, as they are already purchasing in pairs so will be more likely to accepts
- Coffee House coupons are more likely to be accepted by people who frequent Coffee Houses often, so making sure to change and **update the coupons** to keep the attention of these frequent customers is also important 
