### IAM
AWS Identity and Access Management.
![iam](https://www.msp360.com/resources/wp-content/uploads/2018/10/scheme-2-1024x541.png)
* users
* group
* policies
* roles
### Ec2 Instances
Amazon Elastic Compute Cloud. It creates virtual server over cloud.
![ec2 types](https://miro.medium.com/v2/resize:fit:720/1*Di1BLg9vNP8oaJmLPJfRYQ.png)
### Vpc
A virtual private cloud (VPC) is a secure, isolated private cloud hosted within a public cloud.
![vpc](https://k21academy.com/wp-content/uploads/2020/11/Picture2-2.png)
#### Vpc Component
* Region
* Availability Zones
* internet gateway
* public subnet
* load balancer
* route tables
* security group
* private subnet
1. Nat gateway- its helping to the server to the download resources from internet and  mask and change the actual ip address
2. Network access control list (Nacl): an optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of one or more subnets
3. Security group is applied inbound and outbout traffic rules for the ec2 instance.
4. Nacl is applied inbound and outbout traffic rules for the subnet.
### Route 53
Its a  Domain Name System (DNS) web service.
#### Services:
1. Domains registration
2. Hosted zones: it stored all dns info
3. Health check
### Aws S3 Bucket
#### Amazon Simple Storage Service(S3)
It allows users to store and retrieve data from anywhere on the web.
#### Advantages of S3
- Durability and availability
- Scalability
- Security
- Cost-effective
### Aws Cloud Formation Template (CFT)
Its a aws service which create, managed aws resources using templates 
#### CLI vs Aws CFT
Cli: its only use to perform some short and quick action on aws
Cft: create resources and huge stacks
#### services
- Drift detection
- Templates: Yaml, json
- Declarative: you specify what you want
- Stacks: a collection of aws resources created and managed as a single unit.
- Version Control: templates can be stored and version controlled

### CI/CD
#### Aws code commit:
Its a version control system service by amazon. It only create private repository in aws
#### Aws code pipeline:
#### Aws code build:
#### Aws code deploy:

### Aws CloudWatch:
Amazon CloudWatch is a monitoring and management service. it collect and track metrics, collect and monitor log files, and set alarms.

### Aws Lambda
its a aws selverless compute service without managing severs.

### Aws Cost Optimazation:
AWS cost optimization managing AWS resources that maximizes efficiency and minimizes unnecessary spending

### Aws Cloud Front
Amazon CloudFront is a content delivery network(cdn) operated by Amazon Web Services. It helps deliver content, such as web pages, videos, images, and other static or dynamic assets, to users with low latency and high transfer speeds.
![cdn](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTpM6VAuJ5ulw0QAWt9yfm34cEQtehm-Zls6Q&usqp=CAU)
### Aws Elastic Container Registery (ECR)
It stores container images online. Like dockerhub 
#### ECR vs DockerHub
- Mostly for private container registery the organization are use ECR
- For public container registery the organization are use dockerhub

### Aws Elastic Container Service(ECS)
its a container orchestration service provided by aws.
- its only restricted to aws
- AWS Fargate is a serverless compute engine for containers

### Aws Elastic Kubernetes Service (EKS)
Aws Eks is a fully managed kubernetes service.
Eks is a control Plane 

### Aws secret manager
It helps to securely manage and rotate access to sensitive information such as database or application credentials, OAuth tokens, API keys.

- Systems manager
- Secret manager
1. Aws secret manager is only restricted to aws.
2. Hashicorp vault is supported multi cloud or hybrid cloud.
### Aws load balancer
- Application load balancer
- Network load balancer
- Gateway load balancer
