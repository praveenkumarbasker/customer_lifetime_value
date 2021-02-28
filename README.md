# customer_lifetime_value
Assessing Customer Lifetime Value
It was late one afternoon in May and Kevin Starke, the Head of Marketing Analytics for Home
Alarm, had just returned to his office after listening to a presentation by a team of students.
Home Alarm was one of the largest privately held alarm security services companies in the US.
The company had grown rapidly over the last 10 years and now had more than 80,000
residential and commercial customers. Home Alarm offered customers a complete range of
security solutions, including intrusion detection, fire detection, access control, and video
surveillance.
Home Alarm had provided data to the students as part of a class project to identify the major
factors driving customer churn. Due to its excellent customer service Home Alarm had a much
lower customer churn rate than its publicly traded competitors. Nonetheless, Kevin Starke and
Home Alarm’s CEO were curious to see whether the students would be able to come up with
ideas to further reduce customer churn.
Kevin reflected on the findings the students presented to the executive team. Many of the
results confirmed what Kevin knew from experience. For example, customers with better credit
ratings tended to be more long-term customers. However, one finding had sparked his interest
because it was something that he could easily imagine operationalizing on a large scale. The
students had found that residential consumers that were signed up for autopay, i.e., whose
payments were automatically deducted at the end of each month from a checking account or a
credit card, were less likely to cancel their service than consumers who received a monthly statement and paid by check. Contracts for residential customers were renewed (or canceled)
annually.
The implication was clear to Kevin: perhaps new residential customers should be encouraged to
sign up for autopay; it might even be worthwhile trying to convert existing customers to autopay.
Regrettably, while the students had presented evidence that customers on autopay were less
likely to churn, they had not been able to quantify how important the effect was. In particular,
Kevin wanted to know how much more profitable a customer using autopay was compared to a
customer that did not use autopay. The answer to this question seemed key to Kevin because it
would tell him how much he could spend on sales force and customer incentives to sign up
customers for autopay. Before he brought the idea to his CEO, Kevin wanted to make sure
there was enough money in autopay to make it worthwhile for the company.
Kevin knew he had to calculate the added value of autopay customers. However, if what the
students had said about churn was true, he knew that it would not be enough to simply compare
the current revenue of the two groups. If the effect of autopay was to retain customers longer,
any difference in the customer value would only become apparent over time. Clearly, the right
approach was to calculate the CLV of a typical customer with and without autopay.
The necessary data would have to come from Mark Pohl, Customer Care Center Manager at
Home Alarm and the database guru at the company. Kevin asked Mark to get him information
on all customers who signed up with Home Alarm during the month of January nine years ago.
Kevin wanted to know:
 How many residential customers with and without autopay started service in January
nine years ago?
 How many customers with and without autopay were still active 1, 2, 3, 4, 5, 6, 7, 8
and 9 years after starting service?
 What was the typical installation charge and installation cost for customers with and
without autopay?
 What was the average recurring monthly revenue (RMR) for customers with and
without autopay?
Kevin remembered the key idea behind CLV calculation: The CLV was the value of a customer
going forward, taking into account that they might become inactive, and taking into account that
(because of the time value of money) profits achieved further into the future were less valuable
to Home Alarm than the same profits made closer to the present. The purpose of the historical
data Mark provided was to get an estimate of the churn rates by customers with and without
autopay during their first, second, to ninth years after signing up for service with Home Alarm.
The business was pretty stable, so the historical data should provide good estimates of future
churn rates.
Mark delivered the data at the end of the next day Attrition notifications during: Not on autopay On autopay
Year 1 8.4% 3.2%
Year 2 12.2% 7.0%
Year 3 16.2% 9.7%
Year 4 15.4% 10.3%
Year 5 13.4% 9.5%
Year 6 12.0% 7.8%
Year 7 11.1% 6.9%
Year 8 9.6% 5.9%
Year 9 8.6% 5.3%
Initial RMR $30.63 $30.14
Note: The percentages in the table reflect the customers that notified Home Alarm that they
would not renew their contract for the following year (i.e., 3.2% of autopay customers active in
year 1 did not renew for year 2).
Kevin noticed that historically, residential customers with and without autopay had about the
same initial RMR of $30. Hence, for the CLV calculation it would be safe to assume the same
RMR for both groups. However, because of general rate increases the average RMR for
customers was going to be $40 during the coming year, so that $480 would be the right number
for the first full year of the CLV calculation. For each subsequent year the revenue from each
customer could be assumed to increase by 3% due to general rate increases.
There were a few more decisions to make:
 First, what discount rate should be used for the CLV calculation? Home Alarm had
traditionally assumed an annual discount rate of 10%, so that seemed the right number to
use.
 Second, what were the costs of service? Kevin decided to use the rule of thumb that
variable cost were 15% of RMR, i.e., $6 per month, increasing by 3% each year due to
general rate increases.
 Third, Home Alarm spent about 5% of RMR on marketing to each existing customer. This
amounted to $2 per month and increased at 3% per year due to general rate increases.
Home Alarm did not assign any marketing cost to the time of sign-up.
 Finally, Kevin looked up a typical installation charge in case that was needed for the CLV
calculations. The company charged $195 for installation but the cost to the firm was $492 on
average.
Kevin scheduled a meeting with his CEO to present his findings. Now he needed to do the CLV
calculations so he would be prepared.
Preparation Questions
Consider existing residential customers who are about to start their 2nd year with Home
Alarm:
1. What is the CLV (looking 8 years out) of a customer who uses autopay? (9 points)
2. What is the CLV (looking 8 years out) of a customer who does not use autopay? (9 points) 
Page 4
3. What is the maximum amount Home Alarm should spend on incentives to convert an
existing customer to autopay? (6 points)
4. Suggest three marketing actions Home Alarm should consider to convert existing customers
to autopay who are about to start their second year with Home Alarm. Be specific about
incentive amounts you recommend using (if any). (6 points)
Hints
1. “Today” in an CLV calculation defines the customer base or cohort you will use. This means
that the probability that a consumer is active “Today” is always 100%. “Today” may or may
not have revenue and costs associated with it, depending on the problem. Finally, "Today" is
never discounted
2. The relevant attrition rate for year 1 of your CLV calculation need not be the attrition rate
during a customer’s first year of service with the firm
3. All submitted calculations must be done in Python and submitted through GitLab
Write-up Instructions
 I strongly encourage you to describe assumptions, calculation steps, etc. very clearly in your
Jupyter notebook. It is in your best interest that we don’t have to struggle to figure out where
your numbers came from 
