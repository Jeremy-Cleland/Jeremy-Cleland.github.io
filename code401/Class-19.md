# Class 19 Reading Notes | AWS: Events

## [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

- Q: What is the difference between SQS and SNS?

  - A:
  
    - Simple Notification Service: This is a distributed publish-subscribe service.

    ![Alt text](https://miro.medium.com/v2/resize%3Afit%3A1004/format%3Awebp/1%2AmdUPKzrfJFuXa4d43KhKUQ.png)
  
    - Simple Queue Service: This is a distributed queuing service.

    ![Alt text](https://miro.medium.com/v2/resize%3Afit%3A1400/format%3Awebp/1%2A7eL3udb6Cto4I9Ly1sN8oA.jpeg)

- Q: What are some use cases for both SNS and SQS?

  - A:

    - Amazon SNS is a fast, flexible, fully managed push notification service that lets you send individual messages or to bulk messages to large numbers of recipients.

      - SNS : Topic-Subscriber (Pub/Sub system).
      - SNS : Push Mechanism — SNS pushes messages to consumers.
      - SNS : No persistence. Whichever consumer is present at the time of message arrival, get the message and the message is deleted. If no consumers available then the message is lost.
      - SNS : All the consumers are (supposed to be) processing the messages in different ways.


    - SQS is distributed queuing system. Messages are not pushed to receivers. Receivers have to poll SQS to receive messages. Messages can be stored in SQS for short duration of time (max 14 days).
      - SQS: Queue (similar to JMS, MSMQ).
      - SQS : Pull Mechanism — Consumers poll messages from SQS.
      - SQS : Messages are persisted for some duration is no consumer available. The retention period value is from 1 minute to 14 days. The default is 4 days.
      - SQS : All the consumers are supposed to be identical and hence process the messages in exact same way.

## [AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

- Q: Describe how to use SQS and SNS in a “fanout” pattern.

  - A: SNS: The best way to build pub/sub fan out messaging on AWS is to use Amazon SNS. This is using the Pub/sub messaging where messages are broadcasted out to the SQS service

- Q: Explain how “push notifications” work, using SNS.

  - A: Using Amazon Simple Notification Service makes it easy to send messages to all devices subscribed to a topic by calling the same publish function. Amazon SNS allows the publisher to haver 10,000,000 subscribers to a single topic.

## [SQS and SNS Basics

](https://www.youtube.com/watch?v=UesxWuZMZqI)

- Q: How might a large-scale, distributed application make use of a Queue system like SQS?

  - A: Separate Throughput from Latency, Use Batch APIs Wherever Relevant

## Things I want to know more about
