# Employee Churn Analysis

This project aims to analyze employee churn and identify the factors contributing to employee turnover. By leveraging machine learning models, we predict which employees are at risk of leaving the company and provide actionable insights to improve retention strategies.

[Dashboard link](https://lookerstudio.google.com/reporting/eaa55797-2ad1-4b05-b9a6-c79ea9c61a38)

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Approach](#approach)
- [Machine Learning Workflow](#machine-learning-workflow)
- [Dashboard Wireframe](#dashboard-wireframe)
- [Key Questions and Insights](#key-questions-and-insights)
- [Conclusion and Recommendations](#conclusion-and-recommendations)
- [License](#license)

## Introduction

Understanding why employees leave and identifying those at risk of leaving are crucial for maintaining organizational stability and productivity. Employee churn analysis helps HR departments pinpoint the factors contributing to employee turnover and implement effective retention strategies.

## Problem Statement

The company is experiencing issues with retaining employees. The objective is to identify employees at risk of leaving and understand the underlying reasons for their potential departure.

## Approach

1. **Pilot Program with New Employees**
   - Selected a pilot group of new employees to test the model.
   - Built an Auto ML model trained on historical data of past employees.

2. **Model Selection**
   - Compared various machine learning models.
   - Chose Random Forest, which achieved 93% accuracy on new data.

## Machine Learning Workflow

1. **Data Split**
   - Train the model on 70% of existing employee data.
   - Test and tune the ML model on the remaining 30% to ensure accuracy.

2. **Prediction**
   - Use the validated ML model to predict which employees are at risk of leaving.
  
## Dashboard Wireframe
<img src="workflow.jpg"/>

## Key Questions and Insights

1. **What is causing employees to leave?**
   - Job satisfaction is the primary factor influencing employee departures.
   - Key retention factors include tenure, number of projects handled, moderate working hours, and high performance evaluations.
   - The occurrence of work accidents does not significantly impact the decision to stay or leave.

2. **Who is predicted to leave (highest probability)?**
   - Employees in the management department are most likely to leave, followed by those in the support department.

3. **Are employees satisfied?**
   - Employees in IT, product management, sales, accounting, HR, and marketing departments are satisfied, as no immediate churn is predicted from these departments.

4. **What departments have the most churn?**
   - The highest churn rate is in the management department (20% predicted to leave).
   - The support department follows with 13% predicted to leave.

## Conclusion and Recommendations

To enhance employee retention, the company should:
- Implement and enhance employee recognition programs to acknowledge and reward contributions.
- Focus on boosting job satisfaction through initiatives that address employee needs and concerns.
- Introduce professional development programs to foster growth and career advancement.
- Recognize and reward long-term employees to reinforce loyalty and commitment.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
