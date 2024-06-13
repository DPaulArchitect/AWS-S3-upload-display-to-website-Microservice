# AWS-S3-upload-display-to-website-Microservice
Description: >
  This template is the 'blog' microservice. It will work as follows:
  - Website admin uploads a txt file to an S3 bucket.
  - S3 Event notifications trigger a Lambda function which transforms the uploaded text file into an HTML element.
  - Separately, an API endpoint (triggered by refreshing your page) grabs all the 'posts' from S3 and displays them on the page.
