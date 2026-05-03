# feedmeowplz-site
Project static website CI/CD pipeline on AWS
This lab demonstrates my ability to design, deploy, validate, and troubleshoot a secure static website delivery architecture on AWS. The website is hosted from an Amazon S3 bucket, delivered to users through Amazon CloudFront, mapped to a custom domain with Route 53, protected with HTTPS using AWS Certificate Manager, and deployed automatically from GitHub Actions.
The goal was not only to make a website publicly available. I approached the lab as a small production-style reference architecture: the storage origin remains private, CloudFront is the only public access layer, DNS and TLS are correctly configured for both the root domain and www subdomain, and CI/CD is implemented without storing long-lived AWS access keys in GitHub.

 
