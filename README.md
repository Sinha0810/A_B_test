# A_B_test
A/B test to help boost revenue, and analyse the results.

**Project Description** | **Library Used** |
--- | --- | 
As an analyst at online store. You need to work on compiled list of hypotheses that may help boost revenue. You need to prioritize these hypotheses, launch an A/B test, and analyze the results.| Pandas, Datetime, Numpy, Matplotlib, Scipy, Warnings 

## Description of the data:

### Data used in the first part of the project: hypotheses_us
* Hypotheses — brief descriptions of the hypotheses
* Reach — user reach, on a scale of one to ten
* Impact — impact on users, on a scale of one to ten
* Confidence — confidence in the hypothesis, on a scale of one to ten
* Effort — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.

### Data used in the second part of the project: orders_us
* transactionId — order identifier
* visitorId — identifier of the user who placed the order
* date — of the order
* revenue — from the order
* group — the A/B test group that the user belongs to

### visits_us
* date — date
* group — A/B test group
* visits — the number of visits on the date specified in the A/B test group specified

