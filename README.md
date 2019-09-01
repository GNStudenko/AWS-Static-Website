# AWS-Static-Website
An static website deployed to AWS 

The website was published using:
* AWS S3 service for hosting the files
* CloudFront for faster distribution

## Live Website 
Cloudfront URL: 
https://dobdujqi0dm9g.cloudfront.net

Direct S3 Bucket: 
http://george-travel-blog.s3-website.eu-west-3.amazonaws.com/ 

## AWS S3 Bucket configuration

### S3 Bucket configuration
![george-travel-blog S3 Bucket created](AWS_Configuration/S3-Bucket-List.png)
Created the george-travel-blog S3 Bucket

![Files Uploaded](AWS_Configuration/S3-Files-uploaded.png)
Uploaded the website static files

![S3 Bucket Public Access Configuration](AWS_Configuration/S3-Bucket-Public_Access-Conf.png)
S3 Bucket Public Access Configuration

![Set the Bucket Policy](AWS_Configuration/S3-Bucket-Policy.png)
Set the Bucket Policy

![Enable Static website hosting property](AWS_Configuration/S3-Website-Configuration.png)
Enable Static website hosting property

![S3 Static Website Document Configuration](AWS_Configuration/S3-Static-Website-Document-Configuration.png)
S3 Static Website Document Index document configuration

### CloudFront configuration

![Cloudfront Distributions](AWS_Configuration/CloudFront-Conf.png)
Cloudfront Distributions

![CloudFront Configurations](AWS_Configuration/CloudFront-Conf.png)
CloudFront Configurations

![CloudFront Origins configuration](AWS_Configuration/CloudFront-Origins.png)
CloudFront Origins configuration