STORAGE SERVICES



Amazon EC2 Instance storage and Amazon Elastic Block storage


![image](https://user-images.githubusercontent.com/77662117/224310758-8a5b46c0-66bf-44ea-b648-e076c86bd619.png)


The internal storage is called instance store and the external connected storage is called Amazon Elastic Block Store or Amazon EBS. 

Because instance store is directly attached to an EC2 instance, it's lifecycle is tied to the lifecycle of your instance. That means if you stop or terminate an instance, all data in instance store is gone. It can no longer be used or accessed. This is one of the biggest downside of the instance store whereas if your data is stored on EBS, it is safe even if you terminate the instance.
If an accident happens and the instance goes down, you still have your data on your EBS volume. This is what we refer to as persistent storage. You can stop or terminate your instance and your EBS volume can still exist with your data on it. EBS is often the right storage type for workloads that require persistence of data.


For backup of the data, snapshots are used.




DATABASES

![image](https://user-images.githubusercontent.com/77662117/224470373-e268bf14-84e9-4ff1-b3b3-0cb147b9f286.png)

MONITORING
The act of collecting, analyzing, and using data to make decisions or answer questions about your IT resources and systems is called monitoring.

Amazon CloudWatch
Amazon CloudWatch is a monitoring and observability service that collects data. CloudWatch provides actionable insights into your applications, and enables you to respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. This unified view is important. 

You can use CloudWatch to:

         1.Detect anomalous behavior in your environments.
         2.Set alarms to alert you when something’s not right.
         3.Visualize logs and metrics with the AWS Management Console.
         4.Take automated actions like scaling.
         5.Troubleshoot issues.
         6.Discover insights to keep your applications healthy.


Amazon CloudWatch Alarms
CloudWatch Alarms allow you to create thresholds for the metrics that you are monitoring. And these thresholds can define normal boundaries for the values of the metrics. If a metric crosses a boundary for a period of time, then the alarm would be triggered. And you can then take a couple of different automated actions after an alarm is triggered





