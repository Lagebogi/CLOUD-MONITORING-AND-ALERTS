# CLOUD-MONITORING-AND-ALERTS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: ANURAG JAYAN

*INTERN ID*: CT6WUHD

*DOMAIN*: CLOUD COMPUTING

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH KUMAR

*Description* : For this assignment, we set up cloud monitoring and alerts in AWS using Amazon CloudWatch to track the performance of a cloud-based application. First, we launched an EC2 instance to act as our application server. Then, we configured CloudWatch Metrics to monitor important system data like CPU usage, memory, disk activity, and network traffic. To get more detailed monitoring, we installed the CloudWatch Agent on the EC2 instance, which helped collect extra system logs and performance details. Next, we created CloudWatch Alarms to automatically detect issues, such as high CPU usage. To ensure we got alerts when something went wrong, we connected the alarms to Amazon SNS (Simple Notification Service), which sent email and SMS notifications when an alarm was triggered. To make it easier to see and analyze system performance, we designed a CloudWatch Dashboard that displayed real-time graphs and reports. We then tested the setup by creating high CPU usage with the stress command to check if the alarms worked correctly and if notifications were sent. We also fixed an "Insufficient Data" error by adjusting the alarm settings and making sure the instance was generating enough data. Finally, we documented all the steps, took screenshots of the CloudWatch setup, alarm settings, notifications, and dashboards, and created a demo to showcase our monitoring system. This project helped us understand how to use AWS CloudWatch to keep track of cloud resources, detect issues early, and respond quickly to performance problems.

*OUTPUT*: 
