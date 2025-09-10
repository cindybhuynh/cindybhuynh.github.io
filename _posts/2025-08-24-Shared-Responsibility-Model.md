---
layout: post
title: Shared Responsibility Model
---

The Amazon Web Services (AWS) shared responsibility model is a concept that allows the customer and AWS to protect the cloud's security. Both the customer and AWS are responsible for ensuring that your workload is secure. 

A simple differentiation between the responsibilities is that AWS protects the security **of** the cloud and the customer protects the security **in** the cloud.

Here's a diagram that shows the difference between AWS and the customer's responsibility:
![Diagram showing the difference between AWS and customer's responsibility](https://d1.awsstatic.com/onedam/marketing-channels/website/aws/en_US/product-categories/security-identity-compliance/compliance/approved/images/7a404923-5572-409c-b30e-6d44706bcd89.4ae6daa1c586799e6826be45e73950fc180a0e8c.jpeg)

## Home Security Analogy
One way to think about the difference in responsibilities is with a home security analogy.
The builder is AWS, and the homeowner is the customer:
* The builder ensures that the house is well built and that the door lock works properly.
* The homeowner needs to remember to lock the door each time it is used.

Similarly, AWS provides the hardware and the data centers to store the customer's data.
But the customer needs to protect the security with an encryption key.

## AWS Responsibility in the Cloud
AWS is responsible for the physical layer of the cloud, including but not limited to:
* Hardware
* AWS Global Infrastructure
* Storage
* Database
* Network Software Updates

Each function has security systems in place to protect the physical cloud.

## Customer Responsiblity
The customer's responsibility is dependent on the AWS Cloud services they choose. 
Customers are responsible for managing data and encryption. They can choose who has access to what data on their applications. 

How much data should the customer give users and workers access to? This depends on the type of application and whether data needs to be private. 

For workers and people who require access to the data to do their job, the customer should use AWS Identity and Access Management (IAM) tools.

### IAM Tools
IAM tools are used to secure data and manage workforce permissions. 
With IAM tools, the customer can:
* Set and manage detailed permissions
* Manage workload identities across AWS accounts
* Use temporary security credentials to access AWS resources
* Analyze access history and verify users

With IAM tools the customer and fine-tune their security to ensure proper data encryption. The customer may need to secure other points of access, such as the operating system (OS), depending on the AWS Cloud services used. 

The customer can shift their focus to implementing new ideas and improving their application without worrying about the security of the hardware of the AWS cloud.

## More Resources
Below are some resources to learn more about the shared responsibility model and IAM tools:

[AWS - Shared Responsibility Model](https://aws.amazon.com/compliance/shared-responsibility-model/)

[AWS - Identity and Access Management](https://aws.amazon.com/iam/)
