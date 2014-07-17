s3-download-sample
==================

This project demonstrates the use of the AWS CLI to download a file from a private S3 bucket. AWS credentials are supplied via two encrypted environment variables named `AWS_ACCESS_KEY` and `AWS_SECRET_ACCESS_KEY`.

*AWS CLI documentation currently states that you should use AWS_ACCESS_KEY and AWS_SECRET_KEY to supply the credentials, but this does NOT work. You must use AWS_SECRET_ACCESS_KEY instead of AWS_SECRET_KEY*
