#### AWS EC2

What is an EC2 Instance?
An EC2 (Elastic Compute Cloud) instance is a virtual machine (VM) provided by Amazon Web Services (AWS) that allows users to run applications in the cloud. 
It provides scalable compute capacity in the AWS cloud and is designed to make web-scale cloud computing easier for developers.
  
Name 2 use cases for EC2.
  1. Run cloud-native and enterprise applications
  2. Scale for HPC applications
  
Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.
It offers more flexibility and control over the infrastructure.
  
#### EC2 For Humans

Where can we find EC2 on the AWS Console?
Services ->EC2 ->Compute
  
Explain the general difference between T2 Micro and XL.
T2 Micro is the smallest instance type in the T2 family and is designed for low to moderate workloads.
It provides 1 virtual CPU and 1 GiB of memory, making it suitable for basic tasks like web servers, small databases, and development environments.
T2 XL, on the other hand, is a larger and more powerful instance type, with 4 virtual CPUs and 16 GiB of memory.
  
Explain a “Compute Cycle” to a non-technical friend.
A "Compute Cycle" refers to the amount of time it takes a computer or server to perform a single task or operation.
  
#### Elastic Beanstalk

What is Elastic Beanstalk?
Elastic Beanstalk is a fully-managed service provided by Amazon Web Services (AWS) that makes it easy to deploy, run, and scale web applications and services in the cloud.
  
Describe the relationship between EC2 and Elastic Beanstalk.
EC2 is a core service that provides resizable compute capacity in the cloud. It allows you to create and manage virtual servers, known as instances, on which you can deploy your applications.Elastic Beanstalk, on the other hand, is a higher-level service that sits on top of EC2 and provides a platform for deploying and managing web applications.

Name some benefits of using Elastic Beanstalk.
Simplifies application deployment, Easy to scale, Cost-effective, Supports multiple languages and platforms.
