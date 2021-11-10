Pre-Requisites
- Upload artifact into Nexus server
- Setup Ansible Environment
Provide sudo permission for jenkins at below path
vi /etc/sudoers

jenkins ALL=(ALL)       NOPASSWD: ALL
image

Create New job with 'Jenkinsfile-NexusCD' file content
Click on Build to download artifact using ansible
