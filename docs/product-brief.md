# Product Brief: Delivery Risk Early-Warning

## Problem
Late delivery is a measurable driver of customer dissatisfaction. In the
Olist dataset, **6.8%** of delivered orders arrived after the estimated
delivery date. Late orders averaged a **2.27** review score versus **4.29**
for on-time orders, and orders with 1–2★ reviews were roughly **14x** more
likely to have been late (32.4% vs. 2.3%). Late rates also vary sharply by
region (21.4% in AL vs. under 3% in AM), but there is currently no
mechanism to identify at-risk orders before they miss the deadline.

## Success Metrics
1. **Early detection:** ≥70% of orders that end up late are flagged ≥24h
   before the estimated delivery date (target: 70%; baseline: 0%, no flagging today)
2. **Customer satisfaction:** Reduce late-delivery-associated 1–2★ reviews
   by 20% within 90 days of launch (baseline: 32.4% of 1–2★ reviews are
   linked to late delivery)
3. **Ops efficiency:** Reduce time to identify high-risk sellers/regions
   from manual ad-hoc analysis (hours) to under 5 minutes via the dashboard

*Targets are hypothetical, set as reasonable goals informed by the
Current-State Analysis. They cannot be validated on a static historical
dataset, but metric 1 can be backtested on the Olist data.*

## MVP (v1)
- FR-01 At-risk scoring
- FR-02 Flag orders ≥24h before deadline
- FR-03 KPI dashboard (late rate by state/category/seller)
- FR-05 Ops at-risk order list
- FR-06 Daily recalculation

## v2
- FR-07 Seller scorecard
- FR-08 Automated customer delay notification
- FR-04 Delay vs. review score analytics view
- Real-time order data integration (replacing daily batch)

## Out of Scope
- Carrier contract changes or carrier performance enforcement
- Changes to estimated-delivery-date calculation logic