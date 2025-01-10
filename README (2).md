
# AWS SDK for Node.js Sample Project

A simple Node.js application illustrating usage of the AWS SDK for Node.js.


## Requirements
The only requirement of this application is the Node Package Manager. All other dependencies (including the AWS SDK for Node.js) can be installed with:

```bash
  npm install
```

## Basic Configuration

You need to set up your AWS security credentials before the sample code is able to connect to AWS. You can do this by creating a file named "credentials" at ~/.aws/ (C:\Users\USER_NAME.aws\ for Windows users) and saving the following lines in the file:



```bash
[default]
aws_access_key_id = <your access key id>
aws_secret_access_key = <your secret key>
```


## Running the S3 Sample
This sample application connects to Amazon's Simple Storage Service (S3), creates a bucket, and uploads a file to that bucket. The script will automatically create the file to upload. All you need to do is run it:
```bash
node sample.js
```
The S3 documentation has a good overview of the restrictions for bucket names for when you start making your own buckets.


