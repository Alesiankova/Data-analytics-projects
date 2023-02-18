## Project - "A/B test. Hypothesis testing for an online store"
___
### Project description
For a large online store, together with the marketing department, a list of hypotheses was prepared to increase revenue.

During the project: 
- 9 hypotheses were prioritized to increase revenue by ICE and RICE frameworks. 
- I analyzed the results of the A/B test, built graphs of cumulative revenue, average check, conversion by group, and then calculated the statistical significance of differences in conversions and average checks for raw and cleaned data. 

Based on the analysis, I decided that it was not advisable to continue the test.
___
### Data description
File /datasets/hypothesis.csv :
- Hypothesis - a brief description of the hypothesis;
- Reach - user coverage on a 10-point scale;
- Impact - impact on users on a 10-point scale;
- Confidence - confidence in the hypothesis on a 10-point scale;
- Efforts - the cost of resources to test the hypothesis on a 10-point scale. The larger the Efforts value, the more expensive it is to test the hypothesis.

File /datasets/orders.csv :
- transactionId - order identifier;
- visitorId - identifier of the user who made the order;
- date — date when the order was made;
- revenue — order revenue;
- group — the A/B test group the order belongs to.

File /datasets/visitors.csv. Download dataset
- date - date;
- group — A/B test group;
- visitors - the number of users on the specified date in the specified A/B test group
___
### Used libraries/methods
Pandas, Matplotlib, SciPy, A/B testing, testing of statistical hypotheses
