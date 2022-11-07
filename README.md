# Cloud Computing 

## What is Cloud Computing ?

- Cloud computing is the on-demand delivery of IT resources over the Internet with pay-as-you-go pricing
- Instead of buying, owning, and maintaining physical data centers and servers, you can access technology services, such as computing power, storage, and databases, on an as-needed basis from a cloud provider like Amazon Web Services (AWS) or Microsoft Azure.

## What are it's benefits ?

- Agility : The cloud gives you easy access to a broad range of technologies so that you can innovate faster and build nearly anything that you can imagine.
- Elasticity : With cloud computing, you don’t have to over-provision resources up front to handle peak levels of business activity in the future. Instead, you provision the amount of resources that you actually need. You can scale these resources up or down to instantly grow and shrink capacity as your business needs change.
- Cost savings
- Deploy globally in minutes

## What is a AWS ?

- AWS is one of the main cloud provides. They provides many different services to clients to use on the cloud.

![aws-diagram](https://user-images.githubusercontent.com/115224560/199456780-8c8f32cc-4b5f-45f8-9c37-fb1764c4e775.png)


## IaaS - PaaS - Saas

- IaaS contains the basic building blocks for cloud IT. It typically provides access to networking features, computers (virtual or on dedicated hardware), and data storage space. IaaS gives you the highest level of flexibility and management control over your IT resources. It is most similar to the existing IT resources with which many IT departments and developers are familiar. 

- PaaS removes the need for you to manage underlying infrastructure (usually hardware and operating systems), and allows you to focus on the deployment and management of your applications. This helps you be more efficient as you don’t need to worry about resource procurement, capacity planning, software maintenance, patching, or any of the other undifferentiated heavy lifting involved in running your application. 

- SaaS SaaS provides you with a complete product that is run and managed by the service provider. In most cases, people referring to SaaS are referring to end-user applications (such as web-based email). With a SaaS offering, you don’t have to think about how the service is maintained or how the underlying infrastructure is managed. You only need to think about how you will use that particular software. 

![IaaS-PaaS-SaaS](https://user-images.githubusercontent.com/115224560/199247309-b177928a-9c63-401d-a8a0-49fff9781f3f.png)

![saas-paas-iaas-difference-1](https://user-images.githubusercontent.com/115224560/199457382-5418e009-6894-43be-b5b9-9b74627eb39d.png)



## Cap-ex vs Op-ex

- CapEx is defined as business expenses incurred in order to create long-term benefits in the future, such as purchasing fixed assets like a building or equipment. Some examples of IT items that fall under this category would be whole systems and servers, printers and scanners, or air conditioners and generators. You buy these items once and they benefit your business for many, many years. Maintenance of such items is also considered CapEx, as it extends their lifetime and usefulness.

- OpEx is your operating costs, the expenses to run day-to-day business, like services and consumable items that get used up and are paid for according to use. This includes printer cartridges and paper, electricity, and even yearly services like website hosting or domain registrations. These things are necessary for your business’s success but are not considered major long-term investments like CapEx items.


![capex-opex](https://user-images.githubusercontent.com/115224560/199247347-ad8851be-dbd4-468d-8aba-7d49f3bdd1e4.jpeg)


## Disaster Recovery 

### What is it? 

Disaster recovery is the process by which an organization anticipates and addresses technology-related disasters. IT systems in any company can go down unexpectedly due to unforeseen circumstances, such as power outages, natural events, or security issues. Disaster recovery includes a company's procedures and policies to recover quickly from such events.

### What are the best disaster recovery methods?

- Backup: Backing up data is one of the easiest methods of disaster recovery that all businesses implement. Backing up important data entails storing data offsite, in the cloud, or on a removable drive. You should back up data frequently to keep it up to date. For example, by backing up to AWS, businesses get a flexible and scalable infrastructure that protects all data types. 

- Data center disaster recovery: In the event of certain types of natural disasters, appropriate equipment can protect your data center and contribute to rapid disaster recovery. For example, fire suppression tools help equipment and data survive through a blaze, and backup power sources support businesses’ continuity in case of power failure. Similarly, AWS data centers have innovative systems that protect them from human-made and natural risks.

- Disaster recovery as a service: Disaster recovery services like AWS Elastic Disaster Recovery can move a company’s computer processing and critical business operations to its own cloud services in the event of a disaster. Therefore, normal operations can continue from the provider’s location, even if on-premises servers are down. Elastic Disaster Recovery also protects from Regions in the cloud going down. 

### What is S3 ?

- Amazon Simple Storage Service **(Amazon S3)** is an object storage service that offers industry-leading scalability, data availability, security, and performance. You can use Amazon S3 to store and retrieve any amount of data at any time, from anywhere.

- To get the most out of **Amazon S3**, you need to understand a few simple concepts. Amazon S3 stores data as **objects** within **buckets**. An object consists of a file and optionally any metadata that describes that file. To store an object in Amazon S3, you upload the file you want to store to a bucket. When you upload a file, you can set permissions on the object and any metadata.

- **Buckets are the containers for objects**. You can have one or more buckets. For each bucket, you can control access to it (who can create, delete, and list objects in the bucket), view access logs for it and its objects, and choose the geographical region where Amazon S3 will store the bucket and its contents.


- In simple words S3 is a storgae faciliservicety supplied by AWS for Customers of all sizes and industries. 

### S3 Benefits

- **Budget-friendly**
- **High scalability**: Scalability is the measure to increase or decrease the resource as per need.
- **Durability**: Durabilityis the measurement of the likelihood of data loss.
- **High availability**: Availability is the measure of how readily a service can be used.
- & more

## Monitoring & Alert Management

### Cloud Watch 

![image](https://user-images.githubusercontent.com/115224560/200277696-b18e677b-837d-4eb7-8751-16f97918c444.png)

![image-2](https://user-images.githubusercontent.com/115224560/200277719-fa637387-3d4c-495a-ad9a-89be744ebc0d.png)

## CloudWatch

- Used to Observe and monitor AWS resources and applications.
- Enables us to set alarms and automate actions based on predefined thresholds.
- We can also use machine learning algorithms to detect any different behavior in our metrics.
- We can easily start Amazon EC2 Auto Scaling automatically or stop an instance.