# cloud-resume-challenge

*Public copy of the private repo. Code may not reflect the current release of the website*.

<h3>A serverless resume website with view counter using AWS. Built to participate in <a href="https://aws.amazon.com/developer/community/heroes/forrest-brazeal">Forrest Brazeal's</a> Cloud Resume <a href="https://cloudresumechallenge.dev/instructions/">Challenge</a>.</h3> 

This <a href="https://cloudresumechallenge.dev/instructions/">16-step challenge</a> requires the creation of a website to showcase my resume with a site view counter. It dives deeper by requiring the use of AWS Lambda, API Gateway, and DynamoDB to operate the view counter, host the site on an S3 bucket, and have the site delivered over HTTPS using CloudFront. Additionally, this all must be automated using the AWS Serverless Application Model (SAM) and a CI/CD pipeline. 

I completed the challenge by breaking the project into groups with similar tasks. 

# Set up AWS account


1- Create an AWS account
2- Set up MFA for root account
3- Create IAM user
  - Create new user
  - Assign permission
4- Set up AWS vault <a href="https://github.com/99designs/aws-vault">AWS Vault</a>
5- Create S3 Bucket

