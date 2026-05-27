# Data-Driven Retention Strategy Report

## 💎 Behavioral Segment Taxonomy & Strategic Actions

### 1. High-Value But Unhappy (Custom Non-RFM Signal Segments)
* **Underlying Logic:** Evaluates high spending profiles ($M \ge 4$) that exhibit service friction points ($\ge 2$ support complaints in `support_tickets.csv`). 
* **Tactical Action:** Bypasses marketing bots. Initiates automated escalation to a dedicated executive support tier. Resolves pending logistical/product issues and issues an account retention credit code.
* **Business Value Projection:** Extremely High. Preserves top-quartile customer lifetime value (LTV).

### 2. High-Intent Cart Abandoner (Custom Non-RFM Web Event Segments)
* **Underlying Logic:** Identifies accounts with clean transaction activity ($F \le 2$) but intense recent browsing profiles ($\ge 3$ shopping cart abandonments in `web_events_snapshot.csv`).
* **Tactical Action:** Triggers automated personalized email reminders detailing the items currently held in their checkout cart, backed by a limited-time 10% conversion incentive.
* **Business Value Projection:** Medium-High. Accelerates customer acquisition velocities.

### 3. Champions
* **Underlying Logic:** Top-tier performers showing excellent scores across recency, frequency, and monetary measures ($R \ge 4, F \ge 4, M \ge 4$).
* **Tactical Action:** No general cash discounts. Enrolls them into early product collection launches and invites them to VIP membership tiers.

### 4. Loyal Customers
* **Underlying Logic:** Reliable purchasing habits settling into stable mid-to-high value quintiles.
* **Tactical Action:** Implements cross-category configuration bundles mapping back to their stored `preferred_category` profiles.

### 5. At-Risk Customers
* **Underlying Logic:** High historical spending values, but displaying severe recent inactivity indicators ($R \le 2$).
* **Tactical Action:** Deploys win-back campaigns matching high-margin hero inventory.

### 6. Discount-Sensitive Customers
* **Underlying Logic:** Moderate purchase velocities that depend heavily on seasonal sales periods.
* **Tactical Action:** Targets purely via clearance, margin-optimized promotions, or value-add bundles.

### 7. New Customers
* **Underlying Logic:** High recency values coupled with introductory transaction history ($R \ge 4, F \le 2$).
* **Tactical Action:** Deploys product educational journeys linked to their self-reported `skin_type` values to drive a secondary conversion.

### 8. Dormant Customers
* **Underlying Logic:** Inactive accounts tracking at the lowest tier of our RFM matrices ($R \le 2, F \le 2$).
* **Tactical Action:** Low-cost, automated quarterly reactivation outreach loops.

---

## 💰 Resource Allocation & Budget Prioritization Matrix