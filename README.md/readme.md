# ADF-danay Cloud Migration: Static Website to AWS

## Overview
Migrated a local static website (HTML/CSS/JS) to AWS using S3 for storage and CloudFront as a secure CDN layer.

## Architecture
User -> CloudFront (HTTPS) -> Private S3 Bucket (OAC)

## AWS Services Used
- Amazon S3 (object storage)
- Amazon CloudFront (CDN + HTTPS)
- (Optional) Route 53 (custom domain)

## Steps Summary
1. Built website locally in VS Code (`/website`)
2. Created private S3 bucket and uploaded site files
3. Created CloudFront distribution with OAC
4. Updated S3 bucket policy to allow CloudFront access
5. Tested deployment using CloudFront URL

## Screenshots
See `/screenshots`
