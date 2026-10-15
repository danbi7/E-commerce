# Functional Requirements

| ID | Requirement | Source (Finding) |
|---|---|---|
| FR-01 | The system shall calculate an at-risk score for each in-transit order based on destination state, product category, seller, and elapsed shipping time. | 3.2, 3.3 |
| FR-02 | The system shall flag an order as "at risk" when the score exceeds a configurable threshold, at least 24h before the estimated delivery date. | 3.1 |
| FR-03 | The dashboard shall display late-delivery rate by state, category, and seller. | 3.2, 3.3 |
| FR-04 | The dashboard shall display the relationship between delay days and review score. | 3.4 |
| FR-05 | The system shall provide an Ops-facing list of at-risk orders, sortable by risk score and region. | 3.2 |
| FR-06 | The system shall recalculate at-risk flags daily. | NFR link |
| FR-07 | The system shall generate a seller scorecard (late rate, avg review score). | 3.3 |
| FR-08 | The system shall send automated delay notifications to customers with at-risk orders. | 3.4 |