# Serverless Framework AWS S3 based website
[![Serverless](http://public.serverless.com/badges/v3.svg)](http://www.serverless.com)
[![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)

Creates a static website on AWS S3.

This will create
* S3 Bucket
* S3 Bucket Policy
* Route53 Record

## Configuration
Anything under `custom` may be altered.  Additionally, take care to replace any values enclosed in `< >`.

All static content should be placed in the `static/` directory.

## Usage
To use, provide the url to this repository when creating a project.

```
sls create -u https://github.com/ServerlessOpsIO/sls-aws-s3-website -p <PATH> -n <NAME>
npm install
```

## Outputs

StaticSiteS3BucketName: Name of S3 bucket.

StaticSiteS3BucketDomainName: Domain under which website resides.

StaticSiteS3BucketWebsiteURL: URL of the static website.
