# Notes-4-
Cloud Security
//Summary
AWS shared responsibility mode - customers and AWS 
Customers are responsible for data, platform, application, identity and access management 
AWS is responsible for software, compute storeage, database and networking
//Quotes
"EC2 are isolated from another computer" 
Save to know all information uploaded by customer will never be mixed with someone elses data. 
The number one service use is IAM which controls all AWS accounts
Some examples include IAM user, IAM group, IAM policy and IAM role.
To increase security must get a IAM MFA to protect username and password
//Quote
"There are two types of identity and access management policies" 
1. permission policies can attach to principle identity such as IAM user, role and group
2. based policies attach to a resource ( S3 bucket ) 
When creating an new AWS account their are four important steps to protect 
Step 1 - Stop using root user by creating an IAM group and giving admin permission
Step 2 - Enable multi-factor authentication
Step 3 - Use AWS cloudtrail to who what or where of your API interactions
Step 4- Enable billing report such as AWS cost and usage report to a bucket 
