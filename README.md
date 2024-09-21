# AWS Native Cross-account Observability Dashboard

<br>

![License](https://img.shields.io/badge/License-MIT-green) ![AWS](https://img.shields.io/badge/AWS-AWS_Native_Observability-orange) ![Grafana](https://img.shields.io/badge/Grafana-Dashboard-skyblue) ![Grafana](https://img.shields.io/badge/Grafana-11-skyblue) ![#AWSAlwaysFreeChallenge](https://img.shields.io/badge/AWS-AlwaysFreeChallenge-orange)

Welcome to the official site for the <mark>**AWS Native Cross-account Observability Dashboard**</mark>.  
This project provides A comprehensive observability solution for AWS environments, meticulously designed following <mark>**the AWS Well-Architected Framework**</mark>. (`SEC01-BP01`: a multi-account strategy, `SEC04-BP01`: centralizing logs, etc.)[^1]

<br>

![image](./assets/SS-AWS_Native_Cross-account_Observability_Dashboard.jpg)

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
  - [🪩 More Screenshots](#-more-screenshots)
    - [🚀AWS Configuration Management](#aws-configuration-management-1)
      - [✰ 🟢Free Tier \& Cost Explorer](#-free-tier--cost-explorer)
      - [✰ 🔴AWS Organizations Insights](#-aws-organizations-insights)
      - [✰ 🔴AWS Identity Center Dashboard](#-aws-identity-center-dashboard)
      - [✰ Multi-account 🔴IAM Insights](#-multi-account-iam-insights)
      - [✰ ☁️Centralized 🔴CloudTrail Logs](#-️centralized-cloudtrail-logs)
      - [✰ Inspecting JSON Details](#-inspecting-json-details)
    - [🚀AWS Serverless Overview](#aws-serverless-overview-1)
      - [✰ ☁️Centralized Observability Metrics (🔴API-Gateway)](#-️centralized-observability-metrics-api-gateway)
      - [✰ ☁️Centralized Observability Metrics (🟠Lambda)](#-️centralized-observability-metrics-lambda)
      - [✰ ☁️Centralized Observability Metrics (🔴CloudWatch Logs)](#-️centralized-observability-metrics-cloudwatch-logs)
    - [🚀AWS Serverless Observability Monitoring👀](#aws-serverless-observability-monitoring-1)
      - [✰ ☁️Centralized 🔴CloudWatch Logs insights (🔴API-Gateway)](#-️centralized-cloudwatch-logs-insights-api-gateway)
      - [✰ ☁️Centralized 🔴CloudWatch Logs insights (🟠Lambda)](#-️centralized-cloudwatch-logs-insights-lambda)
      - [✰ ☁️Centralized 🔵X-Ray](#-️centralized-x-ray)
      - [✰ ☁️Centralized 🔴CloudTrail](#-️centralized-cloudtrail)
  - [🪩 Getting Started](#-getting-started)
  - [🪩 License](#-license)

---

<br>

## 🪩 Overview

The <mark>**AWS Native Cross-account Observability Dashboard**</mark> is composed of three parts and integrates seamlessly with **the AWS Management Console** (🔴CloudWatch Logs Insights / 🔴CloudTrail / 🔵X-Ray).  

- The **🚀AWS Configuration Management** provides deep insights into Identity and Access Management within a complex AWS environment using a multi-account strategy.  
- **Centralized Monitoring for AWS Services**:
  - The **🚀AWS Serverless Overview** / **🚀AWS Serverless Observability Monitoring👀** offer deep insights into the **AWS Serverless World**, based on the principles of <mark>Cloud Native Observability theory</mark> (Logs, Metrics (RED/USE patterns), Traces, Service maps, etc.).[^2]

---

<br>

### ☻ The #AWSAlwaysFreeChallenge

This project, as part of the <mark>**#AWSAlwaysFreeChallenge**</mark>, aims to drive innovation through knowledge and advanced techniques, leveraging open-source solutions to provide alternatives or even superior functionality compared to expensive ($4-5 digits/mo)[^3] AWS Premium Services🥲 (e.g., Amazon OpenSearch, Amazon Athena, Managed Grafana).  
Through this challenge, we hope to make low-cost, high-functioning solutions more accessible to a wider range of companies and developers.

---

<br>

## 🪩 Key Features

---

<br>

### 🚀AWS Configuration Management 

![image](./assets/SS-AWS_Configuration_Management.jpg)
 
|✅ Features| [☀️**Grafana's download site**](https://grafana.com/grafana/dashboards/21814-aws-configuration-management/) |
|---|---|
|🟢**Cost and Usage Tracking:**   |Visualize your AWS Free Tier usage and associated costs to manage your cloud expenditure effectively.|
|🔴**AWS Organizations Insights:**     |Monitor organizational units, accounts, policies, and access reports, enabling you to manage your AWS environment efficiently.|
|🔴**AWS Identity Center Dashboard:**   |Visualize workforce user assignments, permission sets, and identity store details.|
|🔴**IAM of Multi-Account AWS Environment:** |Gain detailed insights into IAM roles, policies, and user activities from **all accounts** to enhance security and compliance.|
|Centralized **🔴CloudWatch** and **🔴CloudTrail Logs:** |Monitor and filter the latest AWS CloudTrail requests, including details from AWS Organizations, Identity Center, and IAM.|

---

<br>

### 🚀AWS Serverless Overview

![image](./assets/SS-AWS_AWS_Serverless_Overview.jpg)

|✅ Features|[☀️**Grafana's download site**](https://grafana.com/grafana/dashboards/21933-aws-serverless-overview/) |
|---|---|
|🔴**API Gateway Performance Monitoring:**  |- **Longest Running API Requests**: Identify and track the top 25 longest-running API requests. Quickly spot which API paths are contributing to high response times.<br>- **Error Monitoring**: Analyze the API paths with the most 4xx and 5xx errors. Instantly view details such as HTTP methods and IP addresses for effective troubleshooting.<br>- **Popular API Paths**: Gain insights into your most frequently hit API paths to help optimize performance and resource allocation.|
|🟠**AWS Lambda Performance Insights:**   |- **Global Concurrent Executions**: Monitor concurrent executions for each Lambda function in real time. Identify spikes or underutilization to optimize scaling.<br>- **Duration Metrics**: View the average and maximum execution durations for Lambda functions. Easily spot slow-running functions that may need optimization.<br>- **Invocation and Error Tracking**: Keep track of invocations and any Lambda errors, allowing for real-time troubleshooting. Understand how often functions are invoked and their error rates.|
|🔴**CloudWatch Logs Insights:** |- **Incoming Log Events**: Visualize the rate of log events (count/sec) and bytes/sec from various AWS services such as API Gateway and Lambda. This helps in analyzing data ingestion patterns.<br>- **Error and Throttle Analysis**: Monitor delivery errors, forward logs, and throttling, allowing for efficient troubleshooting of any data delivery issues from CloudWatch Logs.<br>- **Real-time Monitoring**: See the real-time flow of logs to CloudWatch for each service, helping you stay ahead of potential issues and performance bottlenecks.|
|Centralized **🔴CloudTrail Logs:** |- **Cross-Service Correlation**: Track recent AWS API requests. Easily identify and troubleshoot issues across multiple services, including who called the API and from where.|

---

<br>

### 🚀AWS Serverless Observability Monitoring👀

![image](./assets/SS-AWS_AWS_Serverless_Observability_Monitoring.jpg)

|✅ Features|[☀️**Grafana's download site**](https://grafana.com/grafana/dashboards/21935-aws-serverless-security-and-access-logs/) |
|---|---|
|🔴**API Gateway Request and Error Monitoring:**  |- **Track Recent API Gateway Requests**: View the latest _300_ API Gateway requests with detailed metadata, including IP addresses, request methods, and response statuses.<br>- **Error Analytics**: Spot errors (4xx and 5xx) instantly, with the ability to drill down into error details for troubleshooting.|
|🟠**AWS Lambda Deep Insights:**   |- **Track Recent Lambda Executions**: Examine detailed logs for the most recent Lambda invocations, including execution status, request ID, and X-Ray trace information.<br>- **Enhanced Lambda Debugging**: Easily filter and find Lambda execution logs tied to specific API requests using `correlation IDs` from API Gateway and `trace IDs`.|
|🔵**AWS X-Ray Trace Monitoring:** |- **Real-time Trace Visualization**: Get a complete visual breakdown of API Gateway requests and Lambda invocations using X-Ray traces. Trace the path of a request as it moves through API Gateway, Lambda, and DynamoDB using `Service Map`.<br>- **Detailed Latency Breakdown**: Understand the latency of each service involved in a transaction, helping you identify performance bottlenecks at a glance with the `Flame Graph`.|
|**Centralized 🔴CloudTrail Logs:** |- **Cross-Service Correlation**: Track recent AWS API requests. Easily identify and troubleshoot issues across multiple services, including who called the API and from where.|

---

<br>

## 🪩 More Screenshots

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

#### ✰ 🔴AWS Organizations Insights

![AWS Organizations Overview](./assets/SS-Organizations.jpg)

---

<br>

#### ✰ 🔴AWS Identity Center Dashboard

![Identity Center Dashboard](./assets/SS-IdentityCenter.jpg)

---

<br>

#### ✰ Multi-account 🔴IAM Insights

![IAM Overview](./assets/SS-IAM.jpg)

>|Role|Customer Managed Policies|Users|
>|---|---|---|
>|- AccountID<br> - Arn<br> - AssumeRolePolicyDocument<br> - AttachedManagedPolicies<br> - CreateDate<br> - InstanceProfileList<br> - Path<br> - PermissionsBoundary<br> - RoleId<br> - RoleLastUsed<br> - RoleName<br> - RolePolicyList<br> - Tags|- AccountID<br>- Arn<br>- AttachmentCount<br>- CreateDate<br>- DefaultVersionId<br>- IsAttachable<br>- Path<br>- PermissionsBoundaryUsageCount<br>- PolicyId<br>- PolicyName<br>- PolicyVersionList<br>- UpdateDate<br><br>|- AccountID<br>- Arn<br>- AttachedManagedPolicies<br>- CreateDate<br>- GroupList<br>- Path<br>- PermissionsBoundary<br>- Tags<br>- UserId<br>- UserName<br><br><br><br>|

---

<br>

#### ✰ ☁️Centralized 🔴CloudTrail Logs

![CloudTrail Logs](./assets/SS-CloudTrail.jpg)

>|CloudTrail|
>|---|
>|- Event Time<br>- 🌐Region<br>- Event Source<br>- Event Name<br>- Event Type<br>- 👤User Ident. Type<br>- 👥Invoked By<br>- 🐾From<br>- 🐾User Agent<br>- ➡️👤Recipient Account ID<br>- Event ID<br>- Request ID<br>- 👀Details<br>- Event Version<br>- @logStream|
---

<br>

#### ✰ Inspecting JSON Details
![Inspecting JSON Details](./assets/SS-Inspect.jpg)

---

<br>

### 🚀AWS Serverless Overview

---

<br>

#### ✰ ☁️Centralized Observability Metrics (🔴API-Gateway)

![Centralized Observability Metrics](./assets/SS-Obs-Perf-APIGateway.jpg)

---

<br>

#### ✰ ☁️Centralized Observability Metrics (🟠Lambda)

![Centralized Observability Metrics](./assets/SS-Obs-Perf-Lambda.jpg)

---

<br>

#### ✰ ☁️Centralized Observability Metrics (🔴CloudWatch Logs)

![Centralized Observability Metrics](./assets/SS-Obs-Perf-CWLs.jpg)

---

<br>

### 🚀AWS Serverless Observability Monitoring👀

---

<br>

#### ✰ ☁️Centralized 🔴CloudWatch Logs insights (🔴API-Gateway)

![Centralized CloudWatch Logs insights](./assets/SS-Obs-CWLs-APIGateway.jpg)

>👀 **More detail of it**
>
>![Centralized Observability Metrics](./assets/SS-Obs-CWLs-APIGateway-Detail.jpg)

---

<br>

#### ✰ ☁️Centralized 🔴CloudWatch Logs insights (🟠Lambda)

![Centralized CloudWatch Logs insights](./assets/SS-Obs-CWLs-Lambda.jpg)

---

<br>

#### ✰ ☁️Centralized 🔵X-Ray

![Centralized X-Ray](./assets/SS-Obs-CWLs-XRAY.jpg)

|Service Map|Frame Graph|
|---|---|
|![Centralized X-Ray](./assets/SS-Obs-CWLs-XRAY-SM.jpg)|![Centralized X-Ray](./assets/SS-Obs-CWLs-XRAY-Graph.jpg)|

---

<br>

#### ✰ ☁️Centralized 🔴CloudTrail

![Centralized 🔴CloudTrail](./assets/SS-Obs-CloudTrail.jpg)

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

Thank you for using the **AWS Native Cross-account Observability Dashboard**.  
We are committed to helping you maintain robust, secure, and cost-efficient AWS environments as part of the <mark>**#AWSAlwaysFreeChallenge**</mark>.🙃 

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

[^2]: The Cloud Native Observability theory
- |||
  |---|---|
  |![image](./assets/304_Kubernetes.014.jpeg)|![image](./assets/304_Kubernetes.015.jpeg)|

[^3]: - The Pricing list😣 
- [**Amazon OpenSearch Service Pricing**](https://aws.amazon.com/opensearch-service/pricing/)
- [**Amazon Athena Pricing**](https://aws.amazon.com/athena/pricing/)
- [**Amazon Managed Grafana pricing**](https://aws.amazon.com/grafana/pricing/)
- [**Amazon CloudWatch Pricing**](https://aws.amazon.com/cloudwatch/pricing/)
- [**AWS CloudTrail pricing**](https://aws.amazon.com/cloudtrail/pricing/)
- [**AWS X-Ray Pricing**](https://aws.amazon.com/xray/pricing/)

---