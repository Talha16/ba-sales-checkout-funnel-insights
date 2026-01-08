# Dataset Understanding & Funnel Mapping

## Dataset Overview
This analysis uses a public e-commerce transaction dataset containing historical order-level data, including product, pricing, customer, and transaction date information.

The dataset does not include user clickstream events (e.g., page views, add-to-cart events), but it provides sufficient data to analyze completed purchases and revenue trends.

## Data Characteristics
- Each record represents a completed transaction line item
- Multiple line items may exist per order (invoice)
- Data includes customer and geographic attributes
- No direct indicators of abandoned carts or failed checkouts

## Funnel Alignment (Conceptual)

| Funnel Stage              | Data Availability | Notes |
|--------------------------|------------------|------|
| Product Viewed           | ❌ Not available | Requires clickstream data |
| Add to Cart              | ❌ Not available | Requires event tracking |
| Proceed to Checkout      | ❌ Not available | Requires session data |
| Payment Attempted        | ❌ Not available | Not captured |
| Order Confirmed          | ✅ Available     | Invoices represent successful orders |

## Implications
- Analysis will focus on **post-purchase performance** rather than full funnel drop-off.
- Checkout abandonment metrics will be discussed conceptually, not calculated.
- Insights will emphasize revenue, order volume, customer behavior, and trends.

## Assumptions
- Each invoice represents a successfully completed checkout.
- Cancellations or returns are excluded or filtered where applicable.
- Customer ID availability may be limited for guest checkouts.

## Limitations
- Inability to measure cart or checkout abandonment directly
- No visibility into payment failures or address validation errors
- Funnel analysis is limited to the final conversion stage
