# Hotel-Booking-Cancellations-and-ADR

#### 1. Introduction
This report analyzes hotel booking data, focusing on the Average Daily Rate (ADR) trends for both canceled and non-canceled reservations. The analysis spans from January 2016 to September 2017 and aims to uncover patterns and insights that can inform hotel management strategies.

#### 2. Data Overview
The dataset includes various details about hotel reservations, such as booking dates, cancellation status, and the daily rates charged to customers. The primary variables of interest for this analysis are:
- **`reservation_status_date`**: The date when the reservation status was updated.
- **`is_canceled`**: A binary variable indicating whether the reservation was canceled.
- **`adr`**: The Average Daily Rate charged per reservation.

#### 3. Data Filtering and Grouping
To understand the trends in ADR for both canceled and non-canceled reservations, the data was filtered to include only the reservations made between January 2016 and September 2017. The average ADR was then calculated for each day within this period for both groups.

#### 4. Findings

##### 4.1 ADR Trends for Canceled Reservations
- **Trend Observation**: The ADR for canceled reservations showed noticeable fluctuations over the analyzed period. Several peaks and troughs indicate that certain periods experienced higher cancellation rates at varying daily rates.
- **Insight**: The spikes in ADR could be associated with specific events, seasons, or promotional periods where higher rates might lead to higher cancellations due to changes in customer plans or price sensitivity.

##### 4.2 ADR Trends for Non-Canceled Reservations
- **Trend Observation**: The ADR for non-canceled reservations displayed a relatively stable trend compared to canceled reservations. However, some seasonal variations were evident, with slight increases during peak travel seasons.
- **Insight**: The stability in ADR for non-canceled reservations suggests that customers who follow through with their bookings are less affected by price changes or may have booked during promotional periods offering better rates.

#### 5. Comparative Analysis
When comparing the ADR trends for canceled and non-canceled reservations:
- **Higher ADR in Canceled Reservations**: On average, canceled reservations had a higher ADR compared to non-canceled ones. This could be due to last-minute cancellations of high-value bookings or price-sensitive customers canceling when rates increase.
- **Seasonal Patterns**: Both categories exhibited seasonal patterns, with higher ADRs during holiday seasons and significant events. However, non-canceled reservations showed more resilience to these fluctuations.

#### 6. Visual Representation

![ADR Trends](path_to_generated_plot.png)

The above plot illustrates the ADR trends for canceled and non-canceled reservations over the analyzed period. The red line represents the ADR for canceled reservations, while the green line represents non-canceled reservations.

#### 7. Conclusion
The analysis provides valuable insights into the pricing and cancellation behavior of hotel customers. Key takeaways include:
- Higher ADRs are more susceptible to cancellations, suggesting a need for strategic pricing during peak periods.
- Non-canceled reservations maintain more stable ADR trends, indicating a more consistent revenue stream from these customers.

These insights can help hotel management optimize their pricing strategies, enhance promotional efforts, and implement policies to minimize cancellations, ultimately improving overall revenue and customer satisfaction.
