# Load aws key id & secret key in your labtop

### MacOS

```bash
$ brew install awscli

[modify conf --> Developer should generate key in IAM service.]

$ chmod +x load_config

$ ./load_config

$ aws configure get aws_access_key_id

$ aws configure get aws_secret_access_key

$ aws configure get region
