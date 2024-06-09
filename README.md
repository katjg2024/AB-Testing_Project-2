# AB Testing - Project 2
## Team: Katherine Granados and Taisgaly Velez

## Description

This project aims to analyze the effectiveness of a new process design compared to the old one in terms of completion rates, user engagement, and other relevant metrics. The study involves conducting hypothesis testing and data analysis to evaluate the impact of the new design on user behavior and outcomes.

## Data

The dataset used for this analysis contains information about user interactions with the old and new process designs. It includes variables such as completion status, age, number of calls, client tenure, and other relevant metrics.

## Analysis and Hypotheses Testing

In this section, we conducted various analyses and performed hypothesis testing to evaluate the effectiveness of the experimental changes.

### Hypothesis 1: Completion Rate Comparison

Null Hypothesis: The completion rate for the Test group (new design) is equal to the completion rate for the Control group (old design).

Alternative Hypothesis: The completion rate for the Test group (new design) is not equal to the completion rate for the Control group (old design).

#### Results:

- Control Completion Ratio: 0.66
- Test Completion Ratio: 0.69
- Z-statistic: -13.87
- P-value: 1.03e-43

Hypothesis 1: We reject the null hypothesis. There is a statistically significant difference in the completion rates between the Test group (new design) and the Control group (old design).

### Hypothesis 2: Impact of Intervention on Completion Rate

Null Hypothesis: The completion rate for the test group is equal to the completion rate for the control group.

Alternative Hypothesis: The completion rate for the test group is different from the completion rate for the control group.

#### Results:

- Test group completion rate: 69.29%
- Control group completion rate: 65.59%
- Percentage increase: 5.65%
- Z-statistic: 8.87
- P-value: 7.02e-19

Hypothesis 2: We reject the null hypothesis. The intervention or change applied to the test group has had a meaningful and statistically significant impact on the completion rate compared to the control group.

### Hypothesis 3: Age Difference between Control and Test Groups

Null Hypothesis: The average age of clients engaging with the new process (test group) is equal to the average age of clients engaging with the old process (control group).

Alternative Hypothesis: The average age of clients engaging with the new process (test group) is not equal to the average age of clients engaging with the old process (control group).

#### Results:

- Control average age for engaging participants: 47.49
- Test average age for engaging participants: 47.06
- Z-statistic: 3.09
- P-value: 0.002

Hypothesis 3: We reject the null hypothesis. There is a statistically significant difference in the average ages between the control and test groups.

### Hypothesis 4: Mean Number of Calls Comparison

Null Hypothesis: The mean number of calls in the last 6 months is equal between the control group and the test group.

Alternative Hypothesis: The mean number of calls in the last 6 months is greater for the control group than for the test group.

#### Results:

- P-value (Start Stage): 9.91e-05
- P-value (Confirm Stage): 0.0095

Hypothesis 4: We reject the null hypothesis in favor of the alternative for Hypothesis 4. This suggests that there is a statistically significant difference in the mean number of calls in the first 6 months between the control and test groups, with that mean being greater for the control group.

### Hypothesis 5: Client Tenure Comparison

Null Hypothesis: The average client tenure (in months) of those engaging with the new process (test group) is equal to the average client tenure of those engaging with the old process (control group).

Alternative Hypothesis: The average client tenure (in months) of those engaging with the new process (test group) is not equal to the average client tenure of those engaging with the old process (control group).

#### Results:

- Control average tenure (in months) for engaging participants: 151.04
- Test average tenure (in months) for engaging participants: 149.33
- Z-statistic: 2.33
- P-value: 0.020

Hypothesis 5: We reject the null hypothesis. There is a statistically significant difference in the mean client tenure (in months) between the control and test groups.


