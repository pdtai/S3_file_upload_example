# S3_file_upload_example
This repository illustrates one option for file uploads to S3 using the boto3 client.

## Prerequisites
- [Python >= 3.9.7](https://www.python.org/downloads/release/python-397/)
- [Boto3 >= 1.24.74](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)
- Configuration details
    - AWS_ACCESS_KEY
    - AWS_SECRET_ACCESS_KEY
    - S3_BUCKET_NAME

## Setup
1. [Install Python 3.9](https://www.python.org/downloads/)
2. Clone repository
3. Change into repository directory
4. Create virtual environment ```python3 -m venv env```
5. Activate environment ```source env/bin/activate```
6. Install requirements ```pip install -r requirements.txt```
7. Export ephemeral environment variables:
    - ```export AWS_ACCESS_KEY=MY_ACCESS_KEY```
    - ```export AWS_SECRET_KEY=MY_SECRET_KEY```
    - ```export S3_BUCKET_NAME=MY_BUCKET_NAME```


## Run
Execute Python programm:
```python
python upload_image.py
```

## Cleanup
Deactivate virtual environment:
```python
deactivate
```