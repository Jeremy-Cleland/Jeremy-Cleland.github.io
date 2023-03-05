# Class 17 Reading Notes |  AWS: S3 and Lambda

## [AWS S3](https://aws.amazon.com/s3/)

- Q: What is Amazon S3?

  - A: Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance. Customers of all sizes and industries can store and protect any amount of data for virtually any use case, such as data lakes, cloud-native applications, and mobile apps.

  ![Alt text](https://d1.awsstatic.com/s3-pdp-redesign/product-page-diagram_Amazon-S3_HIW.cf4c2bd7aa02f1fe77be8aa120393993e08ac86d.png)

- Q: Name some use cases for Amazon S3.

  - A:
  
    - Data Lake: Run big data analytics, artificial intelligence (AI), machine learning (ML), and high performance computing (HPC) applications to unlock data insights.

    - Back up and restore critical data: Meet Recovery Time Objectives (RTO), Recovery Point Objectives (RPO), and compliance requirements with S3’s robust replication features.

    - Archive data at the lowest cost: Move data archives to the Amazon S3 Glacier storage classes to lower costs, eliminate operational complexities, and gain new insights.

    - Run cloud-native applications: Build fast, powerful mobile and web-based cloud-native apps that scale automatically in a highly available configuration.

- Q: Name some benefits of using Amazon S3.

  - A: Wide range of storage classes, security and scabiity.

## [AWS Lambda Basics](https://www.serverless.com/aws-lambda)

- Q: What is AWS Lambda?

  - A: AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). Users of AWS Lambda create functions, self-contained applications written in one of the supported languages and runtimes, and upload them to AWS Lambda, which executes those functions in an efficient and flexible manner.

- Q: Name some use cases for AWS Lambdas.

  - A:
    - Scalable APIs
    - Data processing

- Q: Describe “serverless” to a non-technical friend.

  - A: Amazon Lambdas' concept of serverless as not needing to maintain your own servers. And so “serverless” doesn’t mean that there are no servers involved: it just means that the servers, the operating systems, the network layer and the rest of the infrastructure have already been taken care of, so that you can focus on writing application code.

## [CDN](https://cyberhoot.com/cybrary/content-delivery-network-cdn/)

- Q: What is a CDN?

  - A: A Content Delivery Network (CDN) is a geographically distributed group of servers that work together to provide fast delivery of Internet content. A CDN allows for the fast transfer of data needed for loading Internet content including HTML pages, javascript files, stylesheets, images, and videos.[^1](https://cyberhoot.com/cybrary/content-delivery-network-cdn/)

- Q: How does a CDN work with relation to the website visitor?

  - A: CDNs cache copies of a website to a network of servers that deliver content to the user based on where they are located. CDNs will also communicate with the originating server to deliver any content that has not been previously cached.

- Q: What are the benefits of employing a CDN?

  - A: Employing a CDN doesn’t only speed up the delivery of Internet content, it helps protect your website against certain forms of cyber attacks, such as Denial of Service attacks. It protects against these threats because CDNs allow for the handling of more traffic and withstanding hardware failure better than many origin servers.[Cloudflare](https://www.cloudflare.com/learning/cdn/what-is-a-cdn/)

## Things I want to know more about

React Hooks
