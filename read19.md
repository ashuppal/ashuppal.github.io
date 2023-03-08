#### AWS SQS vs SNS

What is the difference betweeen SQS and SNS?
SQS and SNS are important components for scalable, large scale, distributed, cloud-based applications:
SNS is a distributed publish-subscribe service.
SQS is distributed queuing service.  
  
What are some use cases for both SNS and SQS?
Choose SNS if:
You would like to be able to publish and consume batches of messages.
You would like to allow same message to be processed in multiple ways.
Multiple subscribers are needed.
  
Choose SQS if:
You need a simple queue with no particular additional requirements.
Decoupling two applications and allowing parallel asynchronous processing.
Only one subscriber is needed.
  
#### AWS SNS and SQS

Describe how to use SQS and SNS in a “fanout” pattern.
By using SQS and SNS in a fanout pattern, you can distribute transaction requests to multiple processing systems or services,
allowing you to scale and optimize your transaction processing workflow.
  
Explain how “push notifications” work, using SNS. (ref:https://aws.amazon.com/sns/)
Push notifications are a way for mobile apps or other services to send real-time updates to their users or subscribers. Amazon Simple Notification Service (SNS) provides a reliable and scalable push notification service that can be integrated with mobile apps or other services.                                                   
  
#### SQS and SNS Basics

How might a large scale, distributed application make use of a Queue system like SQS?(ref:https://aws.amazon.com/blogs/aws/scaling-with-amazon-sqs/)
A large scale, distributed application can make use of a queue system like Amazon Simple Queue Service (SQS) in many ways to handle high volume of incoming requests or tasks, decouple application components, and improve overall reliability and scalability of the application.                                                                                      
                                                   
