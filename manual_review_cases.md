# Manual Review Cases: 10 Specific Customers
A manual audit of edge cases where the algorithm requires human oversight.

## Group A: "High Maintenance" (Rich but Angry)
Logic: Customers with Top 20% Spending ($5000+) but >3 Support Tickets.
Strategy: These are our most dangerous customers. They fund the business but are actively detracting from our brand reputation.

| Customer ID | Spend (LTV) | Tickets | Recency | Recommended Action |
| :--- | :--- | :--- | :--- | :--- |
| CUST00042 | $7,919 | 6 | 45 Days | Immediate Phone Call. This user has submitted 6 tickets. Do not send marketing emails. Have a Senior Support Agent call to resolve pending issues. |
| CUST00075 | $7,714 | 4 | 43 Days | Gift Card Apology. They buy often (11 times) but complain often. Send a $50 "Apology" credit with a personal note. |
| CUST00081 | $5,805 | 3 | 40 Days | Ticket Audit. Review their 3 tickets. If they are about shipping, upgrade their next shipping to Express for free. |
| CUST00144 | $8,510 | 3 | 41 Days | VIP Support Lane. Tag this account in the CRM so their future tickets skip the queue. |

## Group B: "Discount Addicts" (Profit Eaters)
Logic: "Champions" who only buy when the discount is > 30%.
Strategy: We are losing margin on these users. We need to test if they are loyal to the product or the price.

| Customer ID | Spend (LTV) | Avg Discount | Frequency | Recommended Action |
| :--- | :--- | :--- | :--- | :--- |
| CUST00030 | $3,884 | 34% | 7 | Suppress Coupons. Stop sending 30% off codes. Send a "New Arrival" email with full price to see if they convert. |
| CUST00242 | $4,040 | 30% | 7 | Bundle Only. Only offer discounts if they buy a bundle (AOV > $100) to protect margin. |
| CUST00315 | $11,129 | 32% | 12 | VIP Tier. They are a massive spender ($11k). Even with discounts, they are profitable. Keep them happy. |

## Group C: "Risky Newcomers" (Bad First Impressions)
Logic: "New Potential" customers who already filed a support ticket.
Strategy: If a new customer complains on their 1st or 2nd order, they are 90% likely to churn.

| Customer ID | Spend (LTV) | Tickets | Frequency | Recommended Action |
| :--- | :--- | :--- | :--- | :--- |
| CUST00002 | $1,713 | 1 | 3 | Service Recovery. Send a "How did we do?" survey. If feedback is poor, offer a seamless return. |
| CUST00027 | $2,666 | 1 | 2 | Educational Content. Ensure they know how to use the product. The ticket might be a "usage" question. |
| CUST00028 | $1,853 | 1 | 3 | Monitor. No action yet, but flag for "At Risk" if they don't buy in 60 days. |
