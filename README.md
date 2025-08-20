# Static Website on AWS

## Overview
- A simple, secure static website built using S3 and Amplify.

## Live Preview
- [Live Site](https://test.d11dfvv0fsfnmj.amplifyapp.com/)

## Visual Preview
- [Homepage](website-screenshot.png)
- [Error Page](website-error-screenshot.png)
- [Mobile View](website-mobile.jpeg)

## Architecture
- [Diagram](static-website-diagram.png)
- [S3 Versioning](s3-versioning.png)
- [Amplify Deployments](amplify-screenshot.png)

## Tech Stack
- AWS S3
- AWS Amplify
- HTML

## Deployment / Setup
1. Create an S3 bucket, unblock public access, and enable versioning (useful for restoring previous file versions).
2. Upload the website files: index.html, error.html, tokyo.jpg, jerry.gif, and jerry-2.gif.
3. Enable static website hosting and configure the bucket policy for public read access.
4. Deploy the website via AWS Amplify to get HTTPS access automatically.

## Features and Learning
- Hosting static websites in the cloud.
- Configuring bucket policies and managing file versioning during testing and updates.
- Using Amplify to create HTTPS access.

## Future Improvements
- Add a custom domain via Route 53 (Planned for a future personal portfolio site).
- Learn more HTML and website design to give more personality and personal touch to websites.

## Reflection
- As a first official AWS project, creating a static website gave me confidence with permissions, hosting, S3, Amplify and website creation.

This is just the beginning!
