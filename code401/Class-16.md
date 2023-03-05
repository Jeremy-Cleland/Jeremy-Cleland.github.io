# Class 16 Reading Notes | AWS: Cloud Servers

## [AWS EC2](https://aws.amazon.com/ec2/)

- Q: What is an EC2 Instance?

  - A: Amazon Elastic Compute Cloud (Amazon EC2) offers the broadest and deepest compute platform, with over 500 instances and choice of the latest processor, storage, networking, operating system, and purchase model to help you best match the needs of your workload. We are the first major cloud provider that supports Intel, AMD, and Arm processors, the only cloud with on-demand EC2 Mac instances, and the only cloud with 400 Gbps Ethernet networking. We offer the best price performance for machine learning training, as well as the lowest cost per inference instances in the cloud. More SAP, high-performance computing (HPC), ML, and Windows workloads run on AWS than any other cloud.

- Q: Name 2 use cases for EC2.

  - A:
    - Run cloud-native and enterprise applications: Amazon EC2 delivers secure, reliable, high-performance, and cost-effective compute infrastructure to meet demanding business needs.

    - Scale for HPC applications: Access the on-demand infrastructure and capacity you need to run HPC applications faster and cost-effectively.

    - Develop for Apple platforms: Build, test, and sign on-demand macOS workloads. Access environments in minutes, dynamically scale capacity as needed, and benefit from AWS’s pay-as-you-go pricing.

    - Train and deploy ML applications: Amazon EC2 delivers the broadest choice of compute, networking (up to 400 Gbps), and storage services purpose-built to optimize the price performance for ML projects.

- Q: Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.

  - A: Amazon EC2 is fully compatible with any OS. Most others providers only work with a predefined Linux distro. 

## [EC2 For Humans](https://www.youtube.com/watch?v=lZMkgOMYYIg)

- Q: Where can we find EC2 on the AWS Console?

  - A: Compute > EC2 > Amazon Machine Image > from there you set up the instance type 

- Q: Explain the general difference between T2 Micro and XL.

  - A:

    - **T2.micro:** 1 vCPU | 0.5 GB RAM | 3 CPU credits/ hr | On-Demand Price/hr: $0.0058

    - **T2.xlarge:** 4 vCPU | 16.0 GB RAM | 54 CPU credits/ hr | On-Demand Price/hr: $0.1856

- Q: Explain a “Compute Cycle” to a non-technical friend.

  - A: A computing cycle consists of the steps that a computer’s processor executes whenever it receives a machine language instruction. It is the most basic CPU operation, and modern CPUs are able to perform millions of machine cycles per second. The cycle consists of three standard steps: fetch, decode and execute. In some cases, store is also incorporated into the cycle.

## [Elastic Beanstalk](https://www.youtube.com/watch?v=SrwxAScdyT0)

- Q: What is Elastic Beanstalk?

  - A: Elastic Beanstalk is a service for deploying and scaling web applications and services. Upload your code and Elastic Beanstalk automatically handles the deployment—from capacity provisioning, load balancing, and auto scaling to application health monitoring.

- Q: Describe the relationship between EC2 and Elastic Beanstalk.

  - A: Elastic BeanStalk manasgues the EC2 instance 

- Q: Name some benefits of using Elastic Beanstalk.

  - A:
    - Makes it even easier for developers to quickly deploy and manage applications in the AWS Cloud
    - Automates the details of capacity provisioning, load balancing, auto scaling, and application deployment, creating an environment that runs a version of your application

## Things I want to know more about

Dig back into React.js