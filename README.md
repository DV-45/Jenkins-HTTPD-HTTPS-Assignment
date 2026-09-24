# Jenkins-HTTPD-HTTPS
Jenkins assignment - HTTPD, HTTPS and index.html deployment
# Jenkins HTTPD HTTPS Assignment

## Assignment Objective

Create a Jenkins job that automatically performs the following tasks on an Amazon Linux EC2 server:

1. Install Apache HTTPD.
2. Install HTTPS/SSL support using `mod_ssl`.
3. Create a self-signed SSL certificate for lab purposes.
4. Create and deploy `index.html`.
5. Configure Apache HTTPD for HTTPS.
6. Start and enable the HTTPD service.
7. Verify HTTP and HTTPS access.
8. Execute the complete deployment through Jenkins.

---

## Environment

- Jenkins
- Amazon Linux 2023
- AWS EC2
- Apache HTTPD
- OpenSSL
- Git / GitHub

---

## Repository Structure

```text
Jenkins-HTTPD-HTTPS-Assignment/
│
├── README.md
├── install-httpd-https.sh
├── index.html
├── .gitignore
│
└── screenshots/
    ├── 01-jenkins-dashboard.png
    ├── 02-create-job.png
    ├── 03-job-configuration.png
    ├── 04-build-success.png
    ├── 05-console-output.png
    ├── 06-httpd-status.png
    ├── 07-index-page.png
    ├── 08-https-page.png
    └── 09-security-group.png
