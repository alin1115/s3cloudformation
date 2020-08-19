                Cloudformation S3bucket creation with Versioning Enabled and Encryption Enabled.        

The bucket has the following tags : 
        Team = Dev
        Owner = Alina.
        
        
Versioning enabled on S3 bucket

Publicly not accessible

Prerequisites:
To have Access and Secret key for user with full access to S3 or IAM Role with S3 access

Commands to execute from CLI:

# git clone https://github.com/alin1115/s3cloudformation.git
# aws configure

AWS Access Key ID [None]:
AWS Secret Access Key [None]: 
Default region name [None]:
Default output format [None]:

#  aws cloudformation deploy --no-fail-on-empty-changeset     --template-file s3cloudformation/cloud.yaml     --stack-name s3-cfn-example-stack

Waiting for changeset to be created..
Waiting for stack create/update to complete
Successfully created/updated stack - s3-cfn-example-stack

Now log in to Amazon and check newly created s3 bucket. 
