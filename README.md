# Static Website on AWS

## Overview
- A simple static website built using S3 and Amplify.

## Live Preview
- [Live Site](https://test.d11dfvv0fsfnmj.amplifyapp.com/)

## Visual Preview
- [Homepage](website-screenshot.png)
- [Error Page](website-error-screenshot.png)
- [Mobile View](website-mobile.jpeg)

## Architecture
- <img width="489" height="81" alt="First Static Website" src="https://github.com/user-attachments/assets/ece48446-cd6b-4351-ba9e-276519c872fc" />
- [S3 Versioning](s3-versioning.png)
- [Amplify Deployments](amplify-screenshot.png)

## Tech Stack
- AWS S3
- AWS Amplify
- HTML

## Deployment / Setup
1. Create an S3 bucket, unblock public access settings, enable versioning in case of wanting to update files but have restore as a possibily, and enable 
2. Upload index.html, error.html, tokyo.jpg, jerry.gif and jerry-2.gif.
3. Enable static website hosting and configure bucket policy for public read.
4. Deploy website in Amplify to create HTTPS access.

## Features and Learning
- Hosting static websites in the cloud.
- Configuring bucket policies and versioning files as files were updated from trial and testing code.
- Using Amplify to create HTTPS access.

## Future Improvements
- Add a custom domain via Route 53 (Saving this for when creating my own website to show portfolio).
- Learn more HTML and website design to give more personality and personal touch to websites.

## Reflection
- As a first official AWS project, creating a static website gave me confidence with permissions, hosting, S3, Amplify and website creation.

This is just the beginning!
