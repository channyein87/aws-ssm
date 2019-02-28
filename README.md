# aws-ssm

### Install-AWSCLI.json
This is template for AWS SSM Document. It installs AWS CLI on Windows. First it creates Installables folder in C:\ and then download the msi installer from S3. After that it checks WMI if AWS CLI is already installed. Final step installs the AWS CLI.
