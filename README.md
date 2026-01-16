# AWS Static Website Hosting using Amazon S3 and CloudFront

## About This Project
This project represents my hands-on learning journey with AWS cloud services and how I translate that learning into simple, practical examples for students and beginners.

The goal of this repository is not just to host a website, but to demonstrate how AWS managed services can be used to build reliable and scalable solutions with minimal infrastructure management. I created this project as part of my personal exploration of AWS and now use it as a reference while mentoring learners who are starting their cloud journey.

The website frontend is based on an open-source demo template. All AWS architecture decisions, deployment steps, CI/CD configuration, and documentation in this repository are my own work.

## AWS Services Used
- Amazon S3 – Static website hosting and object storage
- Amazon CloudFront – Performance optimization and content delivery
- AWS IAM – Secure access management

## How the Architecture Works
User requests are routed through Amazon CloudFront, which retrieves static content from an Amazon S3 bucket configured for website hosting.

## How I Deployed It
1. Created an S3 bucket and enabled static website hosting
2. Uploaded website files to the bucket
3. Configured public read access for website content
4. Created a CloudFront distribution with the S3 bucket as the origin
5. Automated updates using GitHub Actions

## Why I Built This
I built this project to move beyond theory and understand how cloud concepts work in practice. As an educator, I often see learners struggle to connect AWS services with real applications.

## What I Learned
- Using AWS managed services effectively
- Improving performance with CloudFront
- Automating deployments using CI/CD
- Importance of documentation for community learning

## Credits
Frontend inspired by an open-source demo project. All AWS-related work and documentation are my own.
