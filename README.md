# Wanderlust Travel Blog

A static travel blog website built and deployed on AWS as part of the Accenture LearnVantage x Udacity AWS Cloud Fundamentals course.

## Live Links

CloudFront URL: https://dzuf2g6t6l9w4.cloudfront.net/ 
S3 Website Endpoint: http://wanderlust-travel-blog.s3-website-us-east-1.amazonaws.com

## About the project

Wanderlust is a multi-page travel blog that covers destinations, journal entries, and travel stories from around the world. The site has three pages - a homepage, a destinations page, and a journal page. Everything is built with plain HTML, CSS and JavaScript, no frameworks or libraries involved.

The idea was to build something that actually looks like a real website rather than a basic template, and then deploy it properly on AWS so I could get hands-on experience with cloud hosting.

## Why I built this

This project was made as part of the AWS Cloud Fundamentals course offered through Accenture's LearnVantage program in partnership with Udacity. The course covers core AWS concepts and this was the final hands-on project where you take a static website and deploy it on the cloud using S3 and CloudFront.

## What I learned

Setting up S3 for static website hosting, writing IAM bucket policies for public access, creating a CloudFront distribution and connecting it to an S3 origin, and understanding how a CDN works with static files.

## AWS services used

- Amazon S3 for storing and hosting the static files
- IAM bucket policy for making the content publicly accessible
- Amazon CloudFront as the content delivery network

## File structure
```
wanderlust-travel-blog/
├── index.html
├── destinations.html
├── journal.html
└── README.md
```

## Author

Nishit Dongre
