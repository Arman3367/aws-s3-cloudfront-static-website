# AWS Static Website Hosting with S3 and CloudFront

This project demonstrates how to deploy a static website using Amazon S3 and deliver it globally using Amazon CloudFront CDN.

## Architecture

User → CloudFront CDN → S3 Bucket

## Services Used

- Amazon S3
- Amazon CloudFront
- Origin Access Control
- S3 Bucket Policy
- HTTPS via CloudFront

## What This Project Does

- Hosts a static website using Amazon S3
- Uses CloudFront as a CDN for global content delivery
- Secures S3 access using Origin Access Control
- Implements HTTPS access through CloudFront
- Demonstrates cache invalidation during updates

## Deployment Steps

1. Created an S3 bucket configured for static website hosting
2. Uploaded website files (index.html)
3. Configured a CloudFront distribution
4. Enabled Origin Access Control for secure S3 access
5. Set default root object to `index.html`
6. Performed cache invalidation after updates

## Live Demo

CloudFront URL:

https://d2a4b3t8z01apv.cloudfront.net

## Repository Contents

index.html
README.md
