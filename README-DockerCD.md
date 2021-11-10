Pre-Requisites
Ansible Setup (Install Jenkins in Master)
Step1:
Provide sudo permission for jenkins at below path vi /etc/sudoers

jenkins ALL=(ALL)       NOPASSWD: ALL
image

Step2:
Create new job with Jenkinsfile-DockerCD content

Step3: To create Container:
Click on Build by providing action as "Create" and image tag

image

Step4: To remove container
Click on Build by providing action as "Remove" and image tag



