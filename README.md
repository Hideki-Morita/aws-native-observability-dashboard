# AWS Native Cross-account Observability Dashboard

<br>

![License](https://img.shields.io/badge/License-MIT-green) ![AWS](https://img.shields.io/badge/AWS-AWS_Native_Observability-orange) ![Grafana](https://img.shields.io/badge/Grafana-Dashboard-skyblue) ![Grafana](https://img.shields.io/badge/Grafana-11-skyblue) ![#AWSAlwaysFreeChallenge](https://img.shields.io/badge/AWS-AlwaysFreeChallenge-orange)

Welcome to the official site for the **AWS Native Cross-account Observability Dashboard**.  
This project provides A comprehensive observability solution for AWS environments, meticulously designed following <mark>**the AWS Well-Architected Framework**</mark>. (`SEC01-BP01`: a multi-account strategy, `SEC04-BP01`: centralizing logs, etc.)[^1]

---

<br>

## 🪩 Table of Contents

- [AWS Native Cross-account Observability Dashboard](#aws-native-cross-account-observability-dashboard)
  - [🪩 Table of Contents](#-table-of-contents)
  - [🪩 Overview](#-overview)
    - [☻ The #AWSAlwaysFreeChallenge](#-the-awsalwaysfreechallenge)
  - [🪩 Key Features](#-key-features)
    - [🚀AWS Configuration Management](#aws-configuration-management)
    - [🚀AWS Serverless Overview](#aws-serverless-overview)
    - [🚀AWS Serverless Observability Monitoring👀](#aws-serverless-observability-monitoring)
  - [🪩 Screenshots](#-screenshots)
    - [🚀AWS Configuration Management](#aws-configuration-management-1)
      - [✰ 🟢Free Tier \& Cost Explorer](#-free-tier--cost-explorer)
      - [✰ 🔴AWS Organizations Overview](#-aws-organizations-overview)
      - [✰ 🔴AWS Identity Center Dashboard](#-aws-identity-center-dashboard)
      - [✰ Multi-account 🔴IAM Overview](#-multi-account-iam-overview)
      - [✰ ☁️Centralized 🔴CloudTrail Logs](#-️centralized-cloudtrail-logs)
      - [✰ Inspecting JSON Details](#-inspecting-json-details)
  - [🪩 Getting Started](#-getting-started)
  - [🪩 License](#-license)

---

<br>

## 🪩 Overview

The **AWS Native Cross-account Observability Dashboard** is composed of three parts and integrates seamlessly with **the AWS Management Console** (🔴CloudWatch Logs Insights / 🔴CloudTrail / 🔵X-Ray).  

- The **🚀AWS Configuration Management** provides deep insights into Identity and Access Management within a complex AWS environment using a multi-account strategy.  
- The **🚀AWS Serverless Overview** / **🚀AWS Serverless Observability Monitoring👀** offer deep insights into the **AWS Serverless World**, based on the principles of Cloud Native Observability theory (Logs, Metrics (RED/USE patterns), Traces, Service maps, etc.).

---

<br>

### ☻ The #AWSAlwaysFreeChallenge

This project, as part of the <mark>**#AWSAlwaysFreeChallenge**</mark>, aims to drive innovation through knowledge and advanced techniques, leveraging open-source solutions to provide alternatives or even superior functionality compared to expensive ($4-5 digits)[^2] AWS Premium Services🥲 (e.g., Amazon OpenSearch, Amazon Athena, Managed Grafana). Through this challenge, we hope to make low-cost, high-functioning solutions more accessible to a wider range of companies and developers.

---

<br>

## 🪩 Key Features

---

<br>

### 🚀AWS Configuration Management

|✅ Features||
|---|---|
|🟢**Cost and Usage Tracking:**   |Visualize your AWS Free Tier usage and associated costs to manage your cloud expenditure effectively.|
|🔴**AWS Organizations Overview:**     |Monitor organizational units, accounts, policies, and access reports, enabling you to manage your AWS environment efficiently.|
|🔴**AWS Identity Center Dashboard:**   |Visualize workforce user assignments, permission sets, and identity store details.|
|🔴**IAM of Multi-Account AWS Environment:** |Gain detailed insights into IAM roles, policies, and user activities from all accounts to enhance security and compliance.|
|**Centralized 🔴CloudWatch and 🔴CloudTrail Logs:** |Monitor and filter the latest AWS CloudTrail requests, including details from AWS Organizations, Identity Center, and IAM.|

---

<br>

### 🚀AWS Serverless Overview

_TBD_

---

<br>

### 🚀AWS Serverless Observability Monitoring👀

_TBD_

---

<br>

## 🪩 Screenshots

Here are some examples of the dashboards you can create with this project. ([**Also Our limited Demo-site is here**🙃](https://solutionarchitect101.grafana.net/public-dashboards/beb94317b8494fe29d94356090e0a003))

---

<br>

### 🚀AWS Configuration Management

---

<br>

#### ✰ 🟢Free Tier & Cost Explorer

![Free Tier & Cost Explorer](./assets/SS-FreeTier.jpg)

---

<br>

#### ✰ 🔴AWS Organizations Overview

![AWS Organizations Overview](./assets/SS-Organizations.jpg)

---

<br>

#### ✰ 🔴AWS Identity Center Dashboard

![Identity Center Dashboard](./assets/SS-IdentityCenter.jpg)

---

<br>

#### ✰ Multi-account 🔴IAM Overview

![IAM Overview](./assets/SS-IAM.jpg)

---

<br>

#### ✰ ☁️Centralized 🔴CloudTrail Logs

![CloudTrail Logs](./assets/SS-CloudTrail.jpg)

---

<br>

#### ✰ Inspecting JSON Details
![Inspecting JSON Details](./assets/SS-Inspect.jpg)

---

<br>

## 🪩 Getting Started

To get started with **the AWS Native Cross-account Observability Dashboard**:

1. Set up the necessary data sources using our [AWS Native Observability Exporters](https://github.com/Hideki-Morita/aws-native-observability-exporters) repository.
2. Clone the repository (or just download the Dashboard source files.) and follow the [installation instructions](./dashboards/Installation.md).

---

<br>

## 🪩 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

<!--

---

<br>

## 🪩 Related Dashboards

This dashboard is part of the AWS Native Observability suite, which includes:

- **[AWS Serverless Overview](#)**: Monitor and visualize your AWS Lambda functions, API Gateway, and other serverless components.
- **[AWS Serverless Security and Access Logs](#)**: Gain insights into access logs and security events for your serverless applications.

---

<br>

## 🪩 Contact

For support or inquiries, please contact us at [your-email@example.com] or open an issue on our [GitHub repository](https://github.com/your-username/aws-native-observability-dashboard).

-->

---

<br>

Thank you for using the **AWS Native Cross-account Observability Dashboard**. We are committed to helping you maintain robust, secure, and cost-efficient AWS environments as part of the <mark>**#AWSAlwaysFreeChallenge**</mark>.🙃 

---

<br>

> 💡 **Note:**

[^1]: The Security piller of AWS Well-Architected Framework
- [**SEC01-BP01**: Separate workloads using accounts](https://docs.aws.amazon.com/wellarchitected/latest/framework/sec_securely_operate_multi_accounts.html)
  - ![image](https://d1.awsstatic.com/product-marketing/organizations/Product-Page-Diagram_Organizational-Foundational-Units.d709f66bf4c45ed1af01360f3d39adecc1a99fb4.png)
  - [**Establishing your best practice AWS environment**](https://aws.amazon.com/organizations/getting-started/best-practices/)
- [**SEC04-BP01**: Configure service and application logging](https://docs.aws.amazon.com/wellarchitected/latest/framework/sec_detect_investigate_events_app_service_logging.html)
  - [**CloudWatch cross-account observability**](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-Unified-Cross-Account.html)
  - [**Guidance for Observability on AWS**](https://aws.amazon.com/solutions/guidance/observability-on-aws/)
    - [PDF](https://d1.awsstatic.com/solutions/guidance/architecture-diagrams/observability-on-aws.pdf)

[^2]: - The Pricing list😣 
- [**Amazon OpenSearch Service Pricing**](https://aws.amazon.com/opensearch-service/pricing/)
- [**Amazon Athena Pricing**](https://aws.amazon.com/athena/pricing/)
- [**Amazon Managed Grafana pricing**](https://aws.amazon.com/grafana/pricing/)
- [**Amazon CloudWatch Pricing**](https://aws.amazon.com/cloudwatch/pricing/)
- [**AWS CloudTrail pricing**](https://aws.amazon.com/cloudtrail/pricing/)
- [**AWS X-Ray Pricing**](https://aws.amazon.com/xray/pricing/)

---