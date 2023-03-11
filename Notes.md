STORAGE SERVICES



Amazon EC2 Instance storage and Amazon Elastic Block storage


![image](https://user-images.githubusercontent.com/77662117/224310758-8a5b46c0-66bf-44ea-b648-e076c86bd619.png)


The internal storage is called instance store and the external connected storage is called Amazon Elastic Block Store or Amazon EBS. 

Because instance store is directly attached to an EC2 instance, it's lifecycle is tied to the lifecycle of your instance. That means if you stop or terminate an instance, all data in instance store is gone. It can no longer be used or accessed. This is one of the biggest downside of the instance store whereas if your data is stored on EBS, it is safe even if you terminate the instance.
If an accident happens and the instance goes down, you still have your data on your EBS volume. This is what we refer to as persistent storage. You can stop or terminate your instance and your EBS volume can still exist with your data on it. EBS is often the right storage type for workloads that require persistence of data.


For backup of the data, snapshots are used.




DATABASES

![image](https://user-images.githubusercontent.com/77662117/224470373-e268bf14-84e9-4ff1-b3b3-0cb147b9f286.png)





