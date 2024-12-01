# This doc presents the learning dump from the coursera course MLops

## 1. Introduction to MLOps

25 rule of MLOps

- 25% of each [Devops, Data Engineering, models building, business problem framing]
- Concept of primart and secondary investment
  - Primary investmment: Checking the need for the required technology which has characteristics like being popular, low cost, easy to use, and has a large community
    - Eg: AWS for cloud computing since its the leader cloud provider in market.
  - Secondary investment: This technology selected should solve one problem well like snowflake for data warehousing, airflow for workflow management, etc.
  - Investment : Technology innovation, Research and dev.
- (Note: Markdown lint is only for checking the markdown syntax, while markdown all in one is for auto completion of markdown syntax)
- Certification:
  - AWS Machine Learning Specialty
  - AWS Data Analytics Specialty
  - Snowflake architect
  - certified kubernetes administrator
  - AWS Solutions Architect

Upcoming ML future trends:

- Github codespaces
- EFS for AWS (network file system)
- Edge based machine learning
- ONXX model format
- AutoML / Kaizen ML
- Production first mindset

### 1.1. DevOps

Key components of DevOps

Software Engineering Best Practices: These are essential guidelines and checklists that help ensure quality and efficiency in software development projects.
Cultural Mandate: The concept of Kaizen, which means continuous improvement, is vital for fostering a culture that embraces ongoing enhancement within the organization.
The role of automation

Continuous Integration/Continuous Delivery (CI/CD): Automation is crucial for enabling the continuous delivery of code, streamlining the development process.
Infrastructure as Code: This concept supports automation by allowing infrastructure management through code, enhancing consistency and efficiency.
Reinforcing the feedback loop

Feedback Loop: The combination of best practices, culture, and automation creates a feedback loop that is essential for successful DevOps implementation.
Interdependence: Each component is interconnected; lacking any one of them means the DevOps approach cannot be fully realized.

### 1.2. Data Ops

Understanding DataOps

DataOps is rooted in the principles of DevOps, focusing on automation and enhancing the software engineering lifecycle.
It aims to improve data systems, making them cleaner and more efficient over time.

## 2. ML ops workflow

### 2.1. Light work flow

- Github -> Cloud build -> API / Prediction service

### 2.2. Heavy work flow

- Data centric approach
  - AutoML
  - Data Labeling
  - Data Drift
  - Piperline orchestration
  - Data Management (BigQuery)
  - Prediction service
  - feature store: For storeing important features after feature engineering.

## 3. ML Hieracrhy of Needs

Everthing Automation

1) ML Ops => [Probelm Framing, Pattern Discovery, Prediction, Bussiness ROI]
2) Platform Automation => [Feature store, Data Drift]
3) Data Ops => [Visualization, Data Management Platform (BigQuery)]
4) DevOps => [Infrastructure as code, CI/CD]

Note: Be vigilant of data poisoning attacks, which can occur through multiple attack vectors and compromise model integrity.
