# Module 2: Compute in the Cloud

## Amazon EC2 Instance Types
1. **General Purpose**: Balance of compute, memory, and networking resources. Use cases are <u>application servers</u>, <u>gaming servers</u>, <u>backend servers for enterprise applications</u>, and <u>small to  medium databases</u>.
2. **Compute Optimized**: Ideal for compute-bound applications that benefit from high-performance processors. Use cases are <u>high-performance web servers,</u> <u>compute-intensive application servers</u>, <u>batch processing workloads,</u> and <u>dedicated gaming servers,</u>.
3. **Memory Optimized**: Designed to deliver fast performance for workloads that process large datasets in memory. Suppose that you have a workload that requires large amounts of data to be preloaded before running an application.
4. **Accelerated Computing**: Uses hardware acceleration (GPU), floating-point number calculations, graphics processing, and data pattern matching.
5. **Storage Optimized**: Designed for workloads that require high, sequential read and write access to large datasets on local storage. Use cases are <u>distributed file systems</u>, <u>data warehousing applications</u>, and <u>high-frequency online transactiion processing systems</u>. The term **Input/Output Operations Per Second** (IOPS) indicates how many different I/O operations a device can perform in 1 second.

## Amazon EC2 Auto Scaling
The problem with physical servers is that they don't scale automatically based on customer demand. There are times when the number of users is low, medium, or high. Choosing a medium-sized server may not handle peak usage effectively, while choosing a high-capacity server often leads to underutilization during off-peak periods. 

**Auto Scaling** adds new instances to the application when need necessary and terminate them when no longer needed. Capacities: **{Minimum, Desired, Maximum}**

## Directing Traffic with Elastic Load Balancing


## Messaging and Queuing

