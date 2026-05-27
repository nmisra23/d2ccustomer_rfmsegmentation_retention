# Edge Case Manual Review Ledger

The following 10 edge cases present conflicting dataset signals that bypass standard automated classification logic. 

### 1. Customer ID: CUST00102 — The Outlier B2B Wholesaler
* **Metrics:** Recency: 2 days, Frequency: 1 order, Gross Spend: ₹24,789.38, Tickets: 0.
* **Anomaly Profile:** Trapped in the automated "New Customer" cohort due to a frequency score of 1. However, their single transaction represents the single largest gross purchase outlier in company history.
* **Resolution:** Suppress from automated consumer onboarding email loops. Assign to corporate/wholesale client managers for direct personal account onboarding.

### 2. Customer ID: CUST00489 — The Costly Serial Returner
* **Metrics:** Recency: 4 days, Frequency: 28 orders, Gross Spend: ₹18,400, Return Rate: 0.93.
* **Anomaly Profile:** Ranked as a high-value "Champion" by automated scripts. However, a 93% return rate creates an operational deficit via round-trip reverse logistics overheads.
* **Resolution:** Halt premium promotional offers. Blacklist the account from free return shipping campaigns, shifting their return policy to store-credit-only terms.

### 3. Customer ID: CUST00812 — The Onboarding Service Failure
* **Metrics:** Recency: 58 days, Frequency: 1 order, Gross Spend: ₹350, Support Tickets: 6, Sentiment Score Average: -0.92.
* **Anomaly Profile:** Automated rules filter this account into the low-priority "Dormant" category. However, data logs reveal 6 support tickets raised inside their first week of signup, indicating a severe platform onboarding issue.
* **Resolution:** Assign an active customer service agent to make direct contact, resolve the unresolved complaint, and offer an account credit incentive.

### 4. Customer ID: CUST01211 — The Silent Platform Defector
* **Metrics:** Recency: 92 days, Frequency: 45 orders, Gross Spend: ₹14,200, Tickets: 1 (Reopened: 1, Resolution Hours: 74.2).
* **Anomaly Profile:** Flagged as an "At-Risk" profile due to a recent dip in recency scores. Crucially, their abrupt transition from shopping weekly to complete inactivity aligns with a support ticket that took 74.2 hours to resolve.
* **Resolution:** Treat as a severe service recovery case. Issue a direct personalized apology on behalf of management along with a high-value gesture-of-goodwill credit.

### 5. Customer ID: CUST01550 — The High-Volume Dropshipping Node
* **Metrics:** Recency: 1 day, Frequency: 210 orders, Gross Spend: ₹38,000, Web Sessions (30d): 1, Delivery Days Average: 2.
* **Anomaly Profile:** Marked as a top tier "Champion." However, maintaining 210 distinct transactions while recording only 1 web session point to API-automated dropshipping behaviors utilizing your retail fulfillment framework.
* **Resolution:** Do not distribute direct consumer engagement discounts. Shift this user profile onto commercial wholesale margin agreements.

### 6. Customer ID: CUST00319 — The Cyclical Corporate Buyer
* **Metrics:** Recency: 355 days, Frequency: 1 order, Gross Spend: ₹6,800, Last Visit Days Ago: 2 days.
* **Anomaly Profile:** High recency values classify this account as "Dormant." Yet, their web logs reveal they suddenly returned to the web store 2 days ago, exactly 12 months after their first major purchase.
* **Resolution:** This pattern points to predictable annual corporate gifting habits. Avoid bulk discount spam and deploy a premium, high-margin product brochure.

### 7. Customer ID: CUST01944 — The Unprofitable Discount Harvester
* **Metrics:** Recency: 12 days, Frequency: 15 orders, Gross Spend: ₹1,800, Average Discount Percent: 0.70.
* **Anomaly Profile:** Appears as a highly engaged, "Loyal Customer." However, cross-referencing their discount tracking metrics reveals they only execute checkouts when items hit peak markdown levels (70% off), generating razor-thin net margins.
* **Resolution:** Strip this user from active premium acquisition budgets. Route their profile exclusively into low-cost, automated push notifications for clearance items.

### 8. Customer ID: CUST00722 — The High-Cost Support Sponge
* **Metrics:** Recency: 22 days, Frequency: 2 orders, Gross Spend: ₹290, Support Tickets: 18, Resolution Hours Average: 12.4.
* **Anomaly Profile:** Classified under the low-value "Discount-Sensitive" tier. However, their 18 customer service tickets create support labor costs that heavily outweigh their cumulative lifetime revenue contribution.
* **Resolution:** Restrict access to real-time support infrastructure channels (such as call/chat). Route all their requests into automated self-service help centers.

### 9. Customer ID: CUST01155 — The Frictionless Churn Case
* **Metrics:** Recency: 64 days, Frequency: 54 orders, Gross Spend: ₹12,000, Support Tickets: 0, Return Rate: 0.00.
* **Anomaly Profile:** Retained inside "Loyal" segments by statistical weight models despite a sudden stop in activity. They dropped off without leaving negative feedback or support tickets.
* **Resolution:** This points to immediate migration to a competitor. Target this account with an competitive, high-value win-back offer alongside a feedback survey.

### 10. Customer ID: CUST02367 — The Conflicting Size Exchange Profile
* **Metrics:** Recency: 3 days, Frequency: 14 orders, Gross Spend: ₹5,100, Tickets: 8 (Issue Type: wrong_item), Return Rate: 0.62.
* **Anomaly Profile:** Caught between the "High-Value Unhappy" and "Serial Returner" rules due to high ticket counts and high return rates. Inspection of the ticket categories shows these are simple size exchanges, not angry complaints.
* **Resolution:** Do not implement return restrictions. Provide this user with personalized digital fit finder tools or product sizing consultations to maintain their high order volumes while lowering operational return rates.