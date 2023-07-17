# Static-Website-Cafe
- Upload to Your S3 Bucket and `Enable Static Website Hosting`
- Json for Access Public

```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::YOUR_NAME_S3_BUCKET/*"
    }
  ]
}
