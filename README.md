### Background and Context
AllLife Bank has a growing customer base. Majority of these customers are liability customers (depositors) with varying size of deposits. The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, the management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors).

A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with a minimal budget.

The task is to to build a model that will help marketing department to identify the potential customers who have higher probability of purchasing the loan. This will increase the success ratio while at the same time reduce the cost of the campaign.

### Objective
- To predict whether a liability customer will buy a personal loan or not.

- Which variables are most significant.

- Which segment of customers should be targeted more.

### Data Dictionary
- ID: Customer ID

- Age: Customer’s age in completed years

- Experience: #years of professional experience

- Income: Annual income of the customer (in thousand dollars)

- ZIP Code: Home Address ZIP code.

- Family: the Family size of the customer

- CCAvg: Avg. spending on credit cards per month (in thousand dollars)

 -Education: Education Level. 1: Undergrad; 2: Graduate;3: Advanced/Professional

- Mortgage: Value of house mortgage if any. (in thousand dollars)

- Personal_Loan: Did this customer accept the personal loan offered in the last campaign?

- Securities_Account: Does the customer have securities account with the bank?

- CD_Account: Does the customer have a certificate of deposit (CD) account with the bank?

- Online: Do customers use internet banking facilities?

- CreditCard: Does the customer use a credit card issued by Universal Bank?


### Recommendations

Our final decision tree model provided us with the best recall score which is the important metric in evaluating this particular classification problem as earlier explained. As such, we will go ahead and recommend this model to AllLife Bank's Marketing team as a basis for targetting personal loan customers.

The most significant features when deciding on which customers to target are: Income, CCAvg, Family_3, Family_4, Education_2, Education_3. Using this, AllLife Bank can build a customer profile of customers who are most likely to accept the loan offer. This profile could look like this:

A personal loan customer on average earns about 148,000 dollars annually and spends about 3,900 dollars on credit cards bills monthly. These customers have a family size of 3 or 4 and are most likely to have achieved graduate or advanced levels of education.

These are affluent and highly educated customers with large families. This segment represents a small percentage of their customer base but can be worth as much as 80% of the revenue brought in from loan interests. There is therefore a huge incentive for the bank in attracting customers of this nature. A major strategy AllLife's marketing team could employ is Relationship Management. These types of customers tend to require personalized relationships with the bank. They want time to be taken out to understand their peculiar needs, wants, preferences and behavior and also seek real tangible value.

A way to do this while also incentivizing the customer to purchase a loan is by employing loyalty programs that reward customers for actively engaging with and using the bank. These rewards could come in the form of reduced loan and mortgage interest rates, and even slightly increased interest rates on CD and savings accounts. The way it could work would be that Customers would have to enroll in specific loyalty programs to qualify and have to be in the most active customers. This works because it costs little to initiate and it offers the customer real tangible value

AllLife Bank can differentiate themselves significantly by employing this model. By knowing which customers to target, the bank drastically reduces the cost of acquisition. By also understanding the core needs of these customers, they stand a very good chance in retaining these customers and possibly pushing more products like their CD and Securities accounts over time.
