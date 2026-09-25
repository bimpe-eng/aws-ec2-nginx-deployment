\# AWS EC2 Nginx Web Server Deployment



\## Project Overview



Deployed a static HTML website on an AWS EC2 instance running Amazon Linux 2023, using Nginx as the web server.



\## Technologies Used



\- Amazon Web Services (AWS EC2)

\- Amazon Linux 2023

\- Nginx

\- Linux CLI

\- SSH and SCP

\- Git and GitHub



\## Deployment Steps



1\. Launched an EC2 instance in the us-east-2 (Ohio) region.

2\. Configured security group inbound rules for SSH (22) and HTTP (80).

3\. Connected to the instance using SSH and a private key.

4\. Installed and enabled Nginx.

5\. Verified the Nginx service using systemctl.

6\. Backed up the default index.html file.

7\. Created a custom HTML webpage.

8\. Verified the deployment using curl and a web browser.

9\. Transferred the HTML file to the local computer using SCP.

10\. Committed and pushed the project to GitHub.



\## Verification Commands



```bash

nginx -v

sudo systemctl status nginx

curl localhost

```



\## Troubleshooting



Encountered SSH connection timeouts and authentication errors.



Resolved these issues by checking security group rules, verifying the instance's public IP address, and using the correct SSH private key.



\## Key Learning Outcomes



\- Linux server administration

\- EC2 instance configuration

\- SSH authentication and security groups

\- Web server deployment

\- File transfers using SCP

\- Git version control and GitHub integration



