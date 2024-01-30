### How to Push file to awscode commit using AWS CLI
#### Pre-requesite
- Must have User account(IAM) with added permission to access Codecommit
- Must have aws access key and secret access key
#### Install AWS CLI
* `sudo apt update`
* `curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"`
* `sudo apt install zip`
* `unzip awscliv2.zip`
* `sudo ./aws/install`
#### Configure it to AWS account
* `aws configure`
* ` git config --global user.name "test"`
* `git config --global user.email arbabkhan579@gmail.com`
Note: "test" is my username and "arbabkhan579@gmail.com" is my email
![Screenshot-2024-01-30-235354.png](https://i.postimg.cc/xjZs8RMx/Screenshot-2024-01-30-235354.png)
#### Clone the repo from aws to my local machine
* `git clone https://git-codecommit.us-east-1.amazonaws.com/v1/repos/demo-repository`
![Screenshot-2024-01-30-235747.png](https://i.postimg.cc/sgRj755y/Screenshot-2024-01-30-235747.png)
#### Create a demo.txt file and push to AWS CodeCommit
![Screenshot-2024-01-30-235543.png](https://i.postimg.cc/hv69p2c2/Screenshot-2024-01-30-235543.png)
#### demo.txt file is updated on my AWS repo
![Screenshot-2024-01-31-000056.png](https://i.postimg.cc/0yQ6XLVZ/Screenshot-2024-01-31-000056.png)
