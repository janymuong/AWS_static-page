Deploy Static Website on AWS

This is a static website deployed to AWS using S3, CloudFront, and IAM.

The files included are: 

index.html - The Index document for the website.
/img - The background image file for the website.
/vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
/css - CSS files for the website.

Request static page:
- cloudfrotn distribution domain name:
https://d29gvtdargjzgj.cloudfront.net

- bucket website-endpoint:
http://static-page-145845390305-bucket.s3-website.us-east-2.amazonaws.com

- Index:
https://static-page-145845390305-bucket.s3.us-east-2.amazonaws.com/index.html


Screenshots Path in zip:
/img
all images in this directory, except travel-blog-bg.png, are snapshots of the 'steps'.

Note:
The endpoints up here in this README file only work for the period when the CloudFront CDN is running, along with other resources. Subsequent request after shutdown will fail.
