Pre-Requisites:
- Install GIT and Maven
- Install Jenkins
- Configure GIT and Maven with Jenkins
- Create SMTP Credentials in SES
- Verify Emails Address in SES
Install Java
yum install java-1.8.0-openjdk -y
Install Jenkins:
sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins.io/redhat-stable/jenkins.repo
sudo rpm --import http://pkg.jenkins.io/redhat-stable/jenkins.io.key
sudo yum install jenkins -y
service jenkins start
Create SMTP Credentials in SES and Verify Emails Address in SES
SMTP Credentials and Verifying Email Address

Configure SES with Jenkins
Goto Jenkins --> Manage Jenkins --> Configure System

Please check "System Admin e-mail address" provided or not
image

Provide SES details with jenkins
image

Click on Test Configuration

image

Create jenkins job with Jenkins-SES and Build
image

Go and Check whether you get mail or not

Note:
If we provide other Email ID's which not varified with in SES, jenkins build will fail
