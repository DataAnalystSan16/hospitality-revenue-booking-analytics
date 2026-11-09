# Hospitality Analytics – Bangalore vs Hyderabad
**Revenue Performance Investigation | Power BI DAX Analysis**

## Business question
Why does Bangalore generate more revenue than Hyderabad despite having fewer successful bookings?

## Executive summary
Bangalore generated approximately **₹42.04 crore** compared with Hyderabad's **₹32.52 crore** in the overall city-level results. Bangalore had **32,016** successful bookings; Hyderabad had **34,888**.

The strongest consistent differentiator is Bangalore's higher ADR. It is higher across all four room categories and comparable properties, and translates into higher RevPAR in every room category despite lower occupancy in three categories.

## Analysis performed
Used DAX Query View in Power BI Desktop to examine city, booking-platform, property, room-category and monthly performance.

Measures reviewed: Total Bookings, Total Successful Bookings, Revenue, ADR, Occupancy % and RevPAR.

## Key findings
- **Booking volume:** Hyderabad had 34,888 successful bookings versus Bangalore's 32,016.
- **Revenue:** Bangalore generated ₹420,397,050; Hyderabad generated ₹325,232,870.
- **Direct bookings:** Bangalore had 4,870 direct bookings (about 15.2%); Hyderabad had 5,197 (about 14.9%). The difference is too small to explain the revenue gap on its own.
- **ADR:** Bangalore's ADR was approximately 49–51% higher across Presidential, Premium, Elite and Standard room categories.
- **Occupancy:** Hyderabad had higher occupancy in Elite, Premium and Standard. Bangalore was higher in Presidential.
- **RevPAR:** Bangalore was higher in all four room categories, with an advantage of approximately 41–57%.
- **Property-level comparison:** Bangalore ADR exceeded Hyderabad ADR across all six properties that could be compared directly.
- **Monthly trend:** In May, June and July 2022, Bangalore had higher ADR and RevPAR, while Hyderabad had more bookings in each month.

## Room-category comparison

| Room category | Bangalore ADR | Hyderabad ADR | Bangalore RevPAR | Hyderabad RevPAR |
|---|---:|---:|---:|---:|
| Elite | ₹11,791 | ₹7,903 | ₹6,502 | ₹4,609 |
| Premium | ₹16,039 | ₹10,741 | ₹8,959 | ₹6,286 |
| Presidential | ₹25,242 | ₹16,946 | ₹15,219 | ₹9,722 |
| Standard | ₹8,586 | ₹5,706 | ₹4,738 | ₹3,297 |

## Business interpretation
Bangalore appears to generate stronger room revenue through higher average room rates. Hyderabad fills a slightly larger share of available capacity in three room categories, but Bangalore's higher ADR more than offsets its lower occupancy, resulting in higher RevPAR.

The analysis establishes an association, not the cause of higher ADR. Pricing strategy, demand, discounting, property positioning and customer mix require further investigation.

## Recommendations
- Compare pricing and discounting strategies between Bangalore and Hyderabad properties.
- Look for occupancy opportunities in Bangalore's Elite, Premium and Standard categories without unnecessarily weakening ADR.
- Study Hyderabad's stronger occupancy in three categories and identify practices that may be transferable.
- Use RevPAR alongside ADR and occupancy; do not evaluate performance using booking volume alone.

## Limitations and validation
- The monthly comparison covers May, June and July 2022 only.
- Monthly ADR and RevPAR averages are simple averages of the three monthly values, not weighted full-period measures.
- Repeat-customer behaviour could not be established because a customer identifier was not confirmed in the fields reviewed.
- Platform commission may affect net profitability, but should not be assumed to reduce the Revenue measure used here.
- Validate the definitions and filter context of Revenue, ADR, Occupancy % and RevPAR before publishing.

## Conclusion
Bangalore generated more revenue than Hyderabad despite fewer successful bookings. The most consistent differentiator in the available analysis was Bangalore's higher ADR, which translated into higher RevPAR across every room category. Further analysis should investigate the commercial factors behind the ADR difference and opportunities to balance room rates with occupancy.
