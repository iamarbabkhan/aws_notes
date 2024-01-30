### How to create Ec2 using CLI
#### Pre-requesite
- Must have aws access key and secret access key
#### Install AWS CLI
* `sudo apt update`
* `curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"`
* `sudo apt install zip`
* `unzip awscliv2.zip`
* `sudo ./aws/install`
#### Configure it to AWS account
* `aws configure`
#### Cmd to create ec2
Copy the pem file
* `scp -i  /home/mobaxterm/Desktop/arbab/test.pem /home/mobaxterm/Desktop/arbab/test.pem ubuntu@54.89.245.139:/home/ubuntu`
* `aws ec2 run-instances --image-id ami-xxxxxxxx --count 1 --instance-type t2.micro --key-name test --security-group-ids sg-xxxxxxx --subnet-id subnet-xxxxxxx --tag-specifications 'ResourceType=instance,Tags=[{Key=Name,Value=demo}]' --region us-east-1`
![Screenshot-2024-01-31-003500.png](https://i.postimg.cc/s2MRnz7s/Screenshot-2024-01-31-003500.png)
![Screenshot-2024-01-31-003610.png](https://i.postimg.cc/cH7khk9d/Screenshot-2024-01-31-003610.png)
#### Shut down instalces
 aws ec2 terminate-instances --instance-ids i-04341fe4fb87fdc73 --region us-east-1
 ![Screenshot-2024-01-31-004236.png](https://i.postimg.cc/0j1BxR3g/Screenshot-2024-01-31-004236.png)
