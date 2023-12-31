## aws-s3-cli :
[![Downloads](https://static.pepy.tech/personalized-badge/aws-s3-cli?period=total&units=international_system&left_color=black&right_color=blue&left_text=Downloads)](https://pepy.tech/project/aws-s3-cli)[![GitHub license](https://img.shields.io/github/license/sujitmandal/aws-s3-cli)](https://github.com/sujitmandal/aws-s3-cli/blob/master/LICENSE) ![PyPI - Python Version](https://img.shields.io/pypi/pyversions/aws-s3-cli) ![PyPI - Wheel](https://img.shields.io/pypi/wheel/aws-s3-cli) ![PyPI](https://img.shields.io/pypi/v/aws-s3-cli) 


```
aws s3 bucket cli

upload, download, check file availability, and get all available list from AWS s3 bucket.
```


## Package Installation : 
```
pip install aws-s3-cli
```
[Pypi Package Link](https://pypi.org/project/aws-s3-cli/)


## How to import the module:
```python
FILE_OBJ = "" # File object
FILE_NAME = "" # File name
S3_FILE_NAME = "" # S3 file name or uploaded file name
BUCKET_NAME = "" # Bucket name
AWS_ACCESS_KYE = "" # Access key ID
AWS_SECRET_ACCESS_KYE = "" # Secret access key
```
## Upload File : 
```python
from aws_s3_cli.aws_s3_cli import upload_file

status = upload_file(BUCKET_NAME, AWS_ACCESS_KYE, AWS_SECRET_ACCESS_KYE, FILE_OBJ, FILE_NAME)

print(status)
```

## Download File : 
```python
from aws_s3_cli.aws_s3_cli import download_file

status = download_file(BUCKET_NAME, AWS_ACCESS_KYE, AWS_SECRET_ACCESS_KYE, S3_FILE_NAME, FILE_NAME)

print(status)
```

## Check File Status : 
```python
from aws_s3_cli.aws_s3_cli import check_file_status

status = check_file_status(BUCKET_NAME, AWS_ACCESS_KYE, AWS_SECRET_ACCESS_KYE, S3_FILE_NAME)

print(status)
```

## Get All File List : 
```python
from aws_s3_cli.aws_s3_cli import get_all_file_list

file_list = get_all_file_list(BUCKET_NAME, AWS_ACCESS_KYE, AWS_SECRET_ACCESS_KYE)

print(file_list)
```

## Get All File Dictionary : 
```python
from aws_s3_cli.aws_s3_cli import get_all_file_dict

file_dict = get_all_file_dict(BUCKET_NAME, AWS_ACCESS_KYE, AWS_SECRET_ACCESS_KYE)

print(file_dict)
```


## Required package’s:
```
• pip install boto3
```
## License:
MIT Licensed

## Author:
Sujit Mandal

[GitHub](https://github.com/sujitmandal)

[PyPi](https://pypi.org/user/sujitmandal/)

[LinkedIn](https://www.linkedin.com/in/sujit-mandal-91215013a/)
