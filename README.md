# FUTURE_DS_03

Funnel analysis from the uploaded bank marketing data

traffic → lead → customer

Because this dataset is campaign-level marketing contact data, there is no separate web-traffic table inside it, so I used the full contacted population as the top-of-funnel traffic base. The target variable y is the conversion outcome, so it works well as the customer stage.


Core funnel metrics
Traffic: 41,188
Leads contacted: 41,188
Customers converted: 4,640
Traffic-to-lead conversion: 100.0%
Lead-to-customer conversion: 11.3%
Drop-off from lead to customer: 88.7%
So the main loss point is not lead capture, but lead conversion after contact.



Biggest drop-off insight
The funnel collapses after the contact stage. In practical terms, that means the business is successfully reaching people, but most of those contacts are not converting into customers.




Channel performance
The dataset shows a major performance gap by contact channel:

Cellular: 14.7% conversion
Telephone: 5.2% conversion
That is a very large difference, and it suggests that cellular outreach is much more effective than telephone outreach for driving conversions.




Campaign performance
Best-performing campaign groups in the data:

Campaign 1: 13.0%
Campaign 2: 11.5%
Campaign 3: 10.7%
Campaign 4: 9.4%
Performance generally weakens as campaign count increases, which may indicate diminishing returns from repeated outreach.




Time period patterns
Conversion varies a lot by month:
March: 50.5%
December: 48.9%
September: 44.9%
October: 43.9%
May: 6.4%
May is especially weak, while late-year and spring months are much stronger.



Visual Summary
<img width="989" height="390" alt="image" src="https://github.com/user-attachments/assets/a734d494-21e8-476d-a2c4-935c3c8898f9" />






Recommended actions
1. Prioritize cellular outreach
Cellular contacts convert nearly 3x better than telephone contacts, so budget and staffing should shift toward the better-performing channel.

2. Reduce low-performing repeat touches
The campaign pattern suggests repeated contact attempts have diminishing returns. Focus on more targeted first and second touches instead of high-volume repetition.

3. Time campaigns more intelligently
If operationally possible, concentrate acquisition and conversion efforts in stronger months like March, September, October, and December, and treat May as a low-priority period.

4. Segment by campaign and channel
Build separate playbooks for:

cellular vs telephone
high-converting vs low-converting campaigns
high-response months vs weak months
That will help you allocate effort where conversion probability is highest.



