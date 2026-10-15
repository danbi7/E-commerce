# Business Requirements Document: Delivery Delay Early-Warning System

## 1. Business Objective
Reduce late-delivery-driven 1–2 star reviews by 12.4% by proactively flagging at-risk orders before they miss the estimated delivery window.

## 2. Background / Problem Statement
Analysis of 100K Olist orders shows that 6.8% of deliveries arrive after the estimated date, and these late deliveries are associated with a 14x higher rate of 1–2 star reviews (32.4% vs. 2.3%). Late delivery rates vary sharply by region (up to 21% in Alagoas vs. under 3% in Amazonas). This indicates that the root cause is regional logistics performance rather than a platform-wide issue.

## 3. Scope
### In Scope
- Estimating late delivery
- Flagging at-risk orders
- Dashboard
- Regional risk score

### Out of Scope
- Changing the delivery company contract
- Live system integration(Static hisotrical data)
- Push alarm to the customers

## 4. Assumptions
- Past delivery pattern is valid for estimating the future risk
- Ops team have a process to intervene in flagged order

## 5. Constraints
- Static/Historical dataset
- Prototype level impelmentation (Personal project)

## 6. Stakeholders
[Stakeholder Anaylsis](stakeholder-analysis.md)

## 7. Success Criteria
- Flag at-risk orders 24h+ before the delivery deadline
- Reduce late-delivery-driven 1–2 star reviews by 12.4%