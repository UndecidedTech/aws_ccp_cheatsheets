Practice Exam from Digital Cloud (https://learn.digitalcloud.training)
2025-06-17

Q. According to the shared responsibility model, which security-related task is the responsibility of the customer?
A. Maintaining Server-side encryption

Explanation: 
https://digitalcloud.training/aws-shared-responsibility-model/

Q. Which of the following is an advantage for a company running workloads in the AWS cloud vs on-premises (Select 2).
A.
* Less staff time is required to launch new workloads
* Increased productivity for application development teams

https://digitalcloud.training/aws-cloud-computing-concepts/

Q.A Cloud Practicioner requires point-in-time recovery (PITR) for an Amazon Dynamo DB table.
Who is responsible for configuring and performing backups?
A. The customer is responsible for configuring and AWS is responsible for performing backups.

Explanation: Point-in-time recovery (PITR) provides continuous backups of your DynamoDB table data.
When enabled, DynamoDB maintains incremental backups of your table for the last 35 days until you explicitly turn it off.
It is a customer responsibility to enable PITR on and AWS is responsible for actually performing the backups.
https://digitalcloud.training/aws-database-services/


Q. AWS are able to continue to reduce their pricing due to:
A. Economies of scale

Explanation: By using cloud computing, you can achieve a lower variable cost than you can get on your own. Because usage from hundreds of thousands of customers is aggregated in the cloud, providers such as AWS can achieve higher economies of scale, which translates into lower pay as-you-go prices.
https://digitalcloud.training/aws-cloud-computing-concepts/

Q. How can a company separate costs for storage, Amazon EC2, Amazon S3, and other AWS services by department?
A. Add department-speciﬁc tags to each resource

Explanation:A tag is a label that you or AWS assigns to an AWS resource. Each tag consists of a key and a value. For each resource, each tag key must be unique, and each tag key can have only one value.
You can use tags to organize your resources, and cost allocation tags to track your AWS costs on a detailed level. After you activate cost allocation tags, AWS uses the cost allocation tags to organize your resource costs on your cost allocation report, to make it easier for you to categorize and track your AWS costs.
AWS provides two types of cost allocation tags, an AWS generated tags and user-defined tags. AWS defines, creates, and applies the AWS generated tags for you, and you define, create, and apply user-defined tags. You must activate both types of tags separately before they can appear in Cost Explorer or on a cost allocation report.
https://digitalcloud.training/aws-billing-and-pricing/

Q. A company requires a dashboard for reporting when using a business intelligence solution. Which AWS service can a Cloud Practitioner use?
A. Amazon QuickSight

Explanation: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
QuickSight lets you easily create and publish interactive BI dashboards that include Machine Learning-powered insights.
QuickSight dashboards can be accessed from any device, and seamlessly embedded into your applications, portals, and websites.
https://quicksight.aws.amazon.com/

Q. Which AWS service or feature can be used to restrict the individual API actions that users and roles in each member account can access?
A. AWS Organizations

Explanation: AWS Organizations offers Service control policies (SCPs) which are a type of organization policy that you can use to manage permissions in your organization.
SCPs offer central control over the maximum available permissions (API actions) for all accounts in your organization.
SCPs help you to ensure your accounts stay within your organization’s access control guidelines.
SCPs are available only in an organization that has all features enabled.
https://digitalcloud.training/certification-training/aws-certified-cloud-practitioner/management-governance/

Q. A company needs protection from distributed denial of service (DDoS) attacks on its website and assistance from AWS experts during such events.
Which AWS managed service will meet these requirements?
A. AWS Shield Advanced

Explanation: AWS Shield Advanced provides enhanced detection and includes a specialized support team for customers on Enterprise or Business support plans.
The AWS DDoS Response Team (DRT) are available 24/7 and can be engaged before, during, or after a DDoS attack.
https://digitalcloud.training/aws-security-services/

Q. A manager is planning to migrate applications to the AWS Cloud and needs to obtain AWS compliance reports.
How can these reports be generated?
A.Download the reports from AWS Artifact.

Explanation: AWS Artifact is your go-to, central resource for compliance-related information that matters to you.
It provides on-demand access to AWS’ security and compliance reports and select online agreements.
Reports available in AWS Artifact include Service Organization Control (SOC) reports, Payment Card Industry (PCI) reports, and certifications from accreditation bodies across geographies and compliance verticals that validate the implementation and operating effectiveness of AWS security controls.
Agreements available in AWS Artifact include the Business Associate Addendum (BAA) and the Nondisclosure Agreement (NDA).

Q. Which AWS Support plan provides access to architectural and operational reviews, as well as 24/7 access to Cloud Support Engineers through email, online chat, and phone?
A. Enterprise

Explanation: Only the enterprise plan provides Well-Architected Reviews and Operational Reviews. 24/7 access to Cloud Support Engineers through email, online chat, and phone is offered on the business and enterprise plans.
https://digitalcloud.training/aws-billing-and-pricing/

Q. Which AWS services can be used as infrastructure automation tools? (Select TWO.)
A.
* AWS CloudFormation
* AWS OpsWorks

Explanation: AWS CloudFormation provides a common language for you to model and provision AWS and third party application resources in your cloud environment.
AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all regions and accounts.
AWS OpsWorks is a configuration management service that provides managed instances of Chef and Puppet.
Chef and Puppet are automation platforms that allow you to use code to automate the configurations of your servers.
OpsWorks lets you use Chef and Puppet to automate how servers are configured, deployed, and managed across your Amazon EC2 instances or on-premises compute environments.
https://digitalcloud.training/additional-aws-services/

Q.A company needs to publish messages to a thousands of subscribers simultaneously using a push mechanism.
Which AWS service should the company use?
A.Amazon Simple Notification Service (Amazon SNS)

Explanation: Amazon SNS is a publisher/subscriber notification service that uses a push mechanism to publish messages to multiple subscribers.
Amazon SNS enables you to send messages or notifications directly to users with SMS text messages to over 200 countries, mobile push on Apple, Android, and other platforms or email (SMTP).
https://digitalcloud.training/aws-application-integration/

Q. A company has a website that delivers static content from an Amazon S3 bucket to users from around the world. Which AWS service will deliver the content with low latency?
A. Amazon CloudFront

Explanation: Amazon CloudFront is a content delivery network (CDN) and can use an Amazon S3 bucket configured as a static website as an origin for the content is caches globally.
CloudFront reduces latency for global users by serving the requested content from a local cache.
https://digitalcloud.training/aws-content-delivery-and-dns-services/

Q. Which task can a user complete using the AWS Cost Management tools?
A. Create budgets and receive notifications if current or forecasted usage exceeds the budgets.

Explanation: The AWS Cost Management tools includes services, tools, and resources to organize and track cost and usage data, enhance control through consolidated billing and access permissions, enable better planning through budgeting and forecasts, and further lower costs with resources and pricing optimizations.
https://digitalcloud.training/certification-training/aws-certified-cloud-practitioner/aws-billing-and-pricing/

Q. A cloud practitioner needs to migrate a 70 TB of data from an on-premises data center into the AWS Cloud. The company has a slow and unreliable internet connection.
Which AWS service can the cloud practitioner leverage to transfer the data?
A. AWS Snowball

Explanation: AWS Snowball is a method of transferring the data using a physical device.
A Snowball Edge device can hold up to 80 TB so a single device can be used.
This transfer method completely avoids the slow and unreliable internet connection.

Q. A Cloud Practitioner is re-architecting a monolithic application.
Which design principles for cloud architecture do AWS recommend? (Select TWO.)
A. 
* Implement loose coupling.
* Design for scalability.

Explanation: Dependencies such as queuing systems, streaming systems, workflows, and load balancers are loosely coupled.
Loose coupling helps isolate behavior of a component from other components that depend on it, increasing resiliency and agility
AWS recommend that you architect applications that scale horizontally to increase aggregate workload availability.
This scaling should be automatic where possible.

Q. Which of the following statements is correct about Amazon S3 cross-region replication?
A. S3 buckets conﬁgured for cross-region replication can be owned by a single AWS account or by different accounts

Explanation: 
Replication enables automatic, asynchronous copying of objects across Amazon S3 buckets.
Buckets that are configured for object replication can be owned by the same AWS account or by different accounts.
You can copy objects between different AWS Regions or within the same Region.
Both source and destination buckets must have versioning enabled.
The source bucket owner must have the source and destination AWS Regions enabled for their account.
The destination bucket owner must have the destination Region-enabled for their account.
https://digitalcloud.training/aws-storage-services/

Q.A user has an AWS account with a Business-level AWS Support plan and needs assistance with handling a production service disruption.
Which action should the user take?
A. Open a production system down support case

Explanation: (NOTE: Technical Account Manager only comes with the enterprise support plan)
The Business support plan provides a service level agreement (SLA) of < 1 hour for production system down support cases.
https://digitalcloud.training/aws-billing-and-pricing/

Q. The ability to horizontally scale Amazon EC2 instances based on demand is an example of which concept?
A. Elasticity

Explanation: Elasticity is the ability to dynamically adjust the capacity of a service or resource based on demand.
Scaling can be vertical (e.g. increase instance size) or horizontal (e.g. add more EC2 instances).
https://digitalcloud.training/architecting-for-the-cloud/

Q. Under the AWS shared responsibility model, which of the following is an example of security in the AWS Cloud?
A. Firewall configuration

Explanation: Firewall configuration is an example of “security in the cloud”.
This is the customer’s responsibility, not an AWS responsibility.
https://digitalcloud.training/aws-shared-responsibility-model/



