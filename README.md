Customer Retention & Churn Analysis — Power BI Dashboard
Internship Task: Customer Retention & Churn Analysis 
Tool used: Power BI 
File: bank_marketing_analysis.pbix 
Dataset: Bank Marketing dataset (bank-additional-full, 41,188 records, 21 columns) — a bank's term-deposit telemarketing campaign data, used here as the subscription-based business dataset requested in the task. The target column y (subscribed / did not subscribe) plays the role of the "retained vs. churned" outcome.
________________________________________
1. About the Task
The brief asked for a real-world analysis of customer/subscription data to explain why customers leave and what keeps them engaged, covering:
•	Churn rates and retention trends
•	Customer cohorts (by segment/profile)
•	Customer lifetime patterns
•	Key retention drivers
•	Actionable recommendations to reduce churn
The final deliverable required was a retention analysis dashboard or report, presentable to a product manager, founder, or business stakeholder — not just charts, but insight-driven conclusions.

2. How the Task Parameters Map to This Dashboard
Task Parameter	Where it's covered	Dashboard Page
Overall churn / retention rate	Total, subscribed, and non-subscribed customer cards + pie chart	Page 1
Customer segments most likely to churn	Subscription by job, education vs. subscription, marital status vs. subscription	Page 1
Customer lifetime / demographic patterns	Age distribution, contact type, loan status	Page 2
Timing / seasonal retention trends	Contacts by month, average Euribor rate by month	Page 2
Retention drivers (past behavior)	Previous campaign outcome, employment variation rate, contact duration vs. outcome	Page 3
Filters for exploration	Job, contact type, and marital status slicers	Pages 1 & 3
		

3. Dashboard Pages
Page 1 — Overview & Segments
•	KPI cards: Total Customers, Subscribed ("Yes"), Not Subscribed ("No").
•	Pie chart: Overall subscription split.
•	Bar chart: Subscription by job role.
•	Clustered column chart: Education vs. Subscription.
•	Column chart: Marital status vs. Subscription.
•	Slicers: Job, Contact type.

Page 2 — Demographics & Contact Patterns
•	Area chart: Age distribution.
•	Column chart: Contacts by month.
•	Donut chart: Contact type (cellular vs. telephone).
•	Pie charts: Housing loan status, personal loan status.
•	Line chart: Average Euribor rate by month.

Page 3 — Campaign & Retention Drivers
•	Line chart: Employment variation rate trend.
•	Bar chart: Previous campaign outcome vs. subscription.
•	Line chart: Contact duration by number of campaign contacts and outcome.
•	Slicer: Marital status.

4. Key Insights
•	Overall conversion rate is low: Only 11.3% of customers (4,640 of 41,188) subscribed — the large majority represent "churn" from the offer.
•	Occupation is a strong driver: Students (31.4%) and retirees (25.2%) subscribe at far higher rates than blue-collar (6.9%) or services (8.1%) workers — likely reflecting more disposable time/income flexibility.
•	Education matters less sharply, but trends similarly: University-degree holders (13.7%) and illiterate customers (22.2%, small sample) convert better than customers with only basic schooling (7.8–10.3%).
•	Marital status has a mild effect: Singles (14.0%) outperform married (10.2%) and divorced (10.3%) customers.
•	Contact channel is decisive: Cellular contact converts at 14.7% vs. just 5.2% for landline/telephone — nearly 3x better.
•	Past relationship is the single biggest predictor: Customers with a successful previous campaign outcome convert at 65.1%, versus 8.8% for those with no prior contact and 14.2% for those with a prior failure.
•	Engagement length correlates with conversion: Average call duration for subscribers is 553 seconds vs. 221 seconds for non-subscribers, while subscribers needed fewer total campaign touches on average (2.05 vs. 2.63) — indicating quality of conversation matters more than contact frequency.
•	Macroeconomic timing plays a role: Subscription volume was highest in May, and conversion trends move inversely with the Euribor rate — campaigns during lower interest-rate months (Sept, Oct, Dec) coincided with fewer but potentially higher-intent contacts.

5. Actionable Recommendations
1.	Prioritize cellular contact over landline — Reallocate telemarketing effort toward mobile numbers, which convert at nearly 3x the rate.
2.	Segment campaigns by occupation — Target students and retirees with tailored, lower-commitment offers; use different messaging or incentives for blue-collar/services segments where conversion is structurally lower.
3.	Re-engage past successful customers first — The 65% conversion rate among prior successes makes this segment the highest-ROI list to recontact.
4.	Cap contact frequency, protect call quality — More calls did not mean more conversions; train agents to hold longer, higher-quality conversations rather than maximizing touchpoints.
5.	Time campaigns around favorable rate conditions — Factor in Euribor trends when planning major campaign pushes, since customer receptiveness shifts with the broader rate environment.
6. Files in This Submission
•	bank_marketing_analysis.pbix — Full interactive Power BI dashboard

________________________________________
Prepared as part of the Data Science & Analytics internship — Customer Retention & Churn Analysis task.

