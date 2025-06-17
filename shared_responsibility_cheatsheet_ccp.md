AWS Shared Responsibility Model Cheatsheet
2025-06-17

https://digitalcloud.training/aws-shared-responsibility-model/

AWS Shared Responsibility Model:
defines what you (as an AWS account holder/user) and AWS are responsible for when it comes to security and compliance.

The idea is that it's shared across the parties.
This model can help relieve customer's operational burdens as AWS operates, manages, and controls the compoents
from the host operating system and virtualization layer down to the physical security of the facilities in which the service operates.

Customer on the other hand, assumes responsibility for the guest operating system (including updates and security patches),
other application software, as well as the config. of the AWS provided security group firewall.

The Idea is "AWS is responsible for the SECURITY OF THE CLOUD"
    * AWS is responsible for protecting the infrastructure that runs all the services in AWS Cloud
    * This Infra. is composed of hardware, software, networking, and facilities that run AWS Cloud services

![Shared Model](https://digitalcloud.training/wp-content/uploads/2022/02/aws-shared-responsibility-model.jpeg "Shared Cloud Model")

Example: EC2 network level security (NACLs, security groups), operating system patches and updates,
IAM user access management, and client and server-side data encryption

Patch Management: AWS is responsible for patching and fixing flaws within the infrastructure,
customers are responsible for patching guest OS and apps

Config Management: AWS maintains the config of its own infra devices, customer is responsible for configuring their own guest OS's, databases, and apps

Awareness & Training: AWS trains AWS employees, but a customer must train it's own employees.

Examples of customer specific controls include:

Service and Communications Protection or Zone Security which may require a customer to route or zone data within specific security environments.

