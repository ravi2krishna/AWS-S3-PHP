### AWS-S3-Uploader Application

Goal: The purpose of this application is to upload the files to S3 bucket.

### Steps to follow

Make sure the file size is less than 1 MB that you want to upload and update the Access & Secret Key info in s3_config.php file
- `$bucket="BucketName";`
- `if (!defined('awsAccessKey')) define('awsAccessKey', 'AWS_ACCESS_KEY');`
- `if (!defined('awsSecretKey')) define('awsSecretKey', 'AWS_SECRET_KEY');`


