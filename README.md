### Testando AWS S3
```
aws configure
```

```
aws s3 ls serverless-bucket-pet-007
echo "Hello World" > file-test.txt
aws s3 cp file-test.txt s3://serverless-bucket-pet-007
aws s3 ls serverless-bucket-pet-00
```
