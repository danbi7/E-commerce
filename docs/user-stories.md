**US-01** As an Ops Manager, I want to see a list of at-risk orders sorted by region so that I can prioritize carrier follow-up in high-risk states like AL and MA.
- Acceptance: list shows order ID, state, risk score, days to estimated delivery; sortable by risk score.

**US-02** As an Ops Manager, I want to see which sellers have the highest late-delivery rate so that I can prioritize outreach.
- Acceptance: Report/dashboard displays seller name/ID, total fulfilled orders, late-delivery rate (%), and total late count over a selectable time period (e.g., 30/60/90 days); list is sortable by late-delivery rate in descending order and filterable by minimum order volume.

**US-03** As a Customer Support Lead, I want to know which orders are likely to be late before customers complain so that I can prepare proactive responses.
- Acceptance: CS queue/view flags orders where predicted risk score exceeds threshold prior to the estimated delivery date; displays order ID, customer contact info, carrier status, original vs. updated ETA, and recommended proactive outreach template.

**US-04** As a Seller, I want to see my own late-delivery rate versus the platform average so that I can improve my shipping process.
- Acceptance: Seller analytics dashboard shows seller's rolling 30-day late-delivery rate side-by-side with the platform category average (as a percentage and visual benchmark); displays primary delay root causes (e.g., late dispatch vs. carrier transit delay).

**US-05** As a Customer, I want to be notified when my order is likely to be late so that I know what to expect.
- Acceptance: An automated notification (email/push/SMS) is triggered as soon as carrier tracking or the predictive model marks the order delayed; message includes the updated delivery date window, tracking link, and customer support direct link.
