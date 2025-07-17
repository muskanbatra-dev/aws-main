# EC2 INSTANCE ROLES DEMO

# ping google.com

# aws --version

# aws iam list-users

# aws configure

# if we run aws-configure and enter our personal details on the ec2 instance then anyone else could connect top the ec2 instance and enter our account

# instead use IAM ROLES

# if we go into security you can see there is no IAM role onto our instance

## ACTION -> SECURITY -> MODIFY IAM ROLE

## CHOOSE IAM ROLE -> DEMOROLEOFEC2 -> SAVE

# If we run

# aws iam list-users

## DEATTCH THIS PERMISSION

# we get an access denied

# run => aws iam list-users

# we go back to IAM in the console and add IAMREADONLYACCES
