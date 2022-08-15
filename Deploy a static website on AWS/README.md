# Deploy Static Website on AWS

## In this project, you will deploy a static website to AWS using S3, CloudFront, and IAM.

## The files included are: 

* index.html - The Index document for the website.
* /img - The background image file for the website.
* /vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
* /css - CSS files for the website.

## Project Overview

### 1. Create S3 Bucket

![alt text](https://github.com/OmarKhalil10/ALX-Cloud-Developer-ND-Udacity/blob/main/Deploy%20a%20static%20website%20on%20AWS/project%20walk-through%20images/Bucket.png "S3 Bucket")

### 2. Add the website content to the bucket

![alt text](https://github.com/OmarKhalil10/ALX-Cloud-Developer-ND-Udacity/blob/main/Deploy%20a%20static%20website%20on%20AWS/project%20walk-through%20images/Bucket-Content.png "website content inside the s3 bucket")

### 3. Edit the bucket policy

![alt text](https://github.com/OmarKhalil10/ALX-Cloud-Developer-ND-Udacity/blob/main/Deploy%20a%20static%20website%20on%20AWS/project%20walk-through%20images/Bucket-Policy.png "Bucket Policy")

### 4. Enable the Static-Website-Hosting on the s3 Bucket

![alt text](https://github.com/OmarKhalil10/ALX-Cloud-Developer-ND-Udacity/blob/main/Deploy%20a%20static%20website%20on%20AWS/project%20walk-through%20images/Static-Website-Hosting.png "Static-Website-Hosting Enabled")

### 4. Add the index.html & error.html documents

![alt text](https://github.com/OmarKhalil10/ALX-Cloud-Developer-ND-Udacity/blob/main/Deploy%20a%20static%20website%20on%20AWS/project%20walk-through%20images/Static-Website-Hosting-Properties.png "Adding the default html documents")

### 5. Make a CloudFront Distribution for your website

![alt text](https://github.com/OmarKhalil10/ALX-Cloud-Developer-ND-Udacity/blob/main/Deploy%20a%20static%20website%20on%20AWS/project%20walk-through%20images/Website-Distribution.png "CloudFront Distribution")

### 6. Access the website via (Public url, Domain name or Bucket content link)


* `http://my-aws-website-bucket.s3-website-us-east-1.amazonaws.com`

## Thanks!
