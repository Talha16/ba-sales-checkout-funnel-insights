# Metrics & Dashboard Requirements – Checkout Funnel Insights

## Purpose of the Dashboard
The purpose of this dashboard is to provide stakeholders with visibility into sales performance and completed checkout outcomes, enabling data-driven decisions to improve revenue and customer experience.

## Target Audience
- Business stakeholders
- Product owners
- Operations and marketing teams

## Key Metrics Definitions

### Total Revenue
- Definition: Sum of revenue from all completed transactions.
- Business Use: Measures overall sales performance over time.

### Number of Orders
- Definition: Count of unique invoices representing completed checkouts.
- Business Use: Indicates transaction volume and demand trends.

### Average Order Value (AOV)
- Definition: Total Revenue ÷ Number of Orders.
- Business Use: Helps evaluate purchasing behavior and pricing effectiveness.

### Revenue Trend Over Time
- Definition: Revenue aggregated by day or month.
- Business Use: Identifies seasonal patterns and growth or decline trends.

### Top Products by Revenue
- Definition: Products ranked by total revenue contribution.
- Business Use: Supports inventory planning and merchandising decisions.

### Revenue by Country
- Definition: Revenue aggregated by customer country.
- Business Use: Identifies geographic performance differences.

## Dashboard Requirements

### DR-1: Overview Section
- Display total revenue, total orders, and average order value.
- Metrics should update dynamically based on selected date filters.

### DR-2: Trend Analysis
- Display revenue trends over time using a line chart.
- Allow filtering by date range.

### DR-3: Product Performance
- Display top products by revenue using a bar chart or table.
- Allow sorting by revenue or quantity sold.

### DR-4: Geographic Analysis
- Display revenue by country.
- Support basic filtering by country where applicable.

## Assumptions
- Only completed orders are included in calculations.
- Returned or cancelled orders are excluded where data permits.

## Limitations
- Checkout abandonment and payment failure metrics are not available due to data constraints.
- Insights focus on post-purchase performance only.
