# AthenaWebsiteAnalysis
Using AWS Athena to create data Analysis based on my own personal site held on AWS S3 and using quicksight to generate easy and highly informative data for my website. 

# Setup:
  Website:
  
#  AWS S3:
  In AWS S3 I have a basic static website directory structure, I have also enabled server access logging and static website   hosting on my S3 bucket.
  
 # Athena:
    Create a table which has the location set to the where the logging target bucket is. Try to partition the data, this can keep the costs of Athena down.
    
#  Quicksight:
 Connect Quicksight to the Athena Table and this will generate the graphs for you.
 
 # Goal:
 To have Quicksight automatically generate graphical data for us from live traffic created by our website.
  

# What is AWS Athena?
Please see the AWS documentation here: https://aws.amazon.com/athena/

# What is S3?
Please see the AWS documentation here: https://aws.amazon.com/s3/

# What is QuickSite?
Please see the AWS documentation here: https://aws.amazon.com/quicksight/
