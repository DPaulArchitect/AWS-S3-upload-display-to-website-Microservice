Description:
  This template is the a microservice to display information from an S£ bucket after an item is uploaded
  . It will work as follows:
  - Website admin/user uploads a txt file to an S3 bucket.
  - S3 Event notifications trigger a Lambda function which transforms the uploaded text file into an HTML element.
  - Separately, an API endpoint (triggered by refreshing your page) grabs all the 'posts' from S3 and displays them on the page.
