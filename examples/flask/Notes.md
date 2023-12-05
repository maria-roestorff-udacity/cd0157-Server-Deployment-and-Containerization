


aws s3api  create-bucket --bucket mybucket271120231804 --acl bucket-owner-full-control --region us-east-2 --create-bucket-configuration LocationConstraint=us-east-2

aws s3api put-object --bucket mybucket271120231804 --key sample.html --body sample.html --content-type text/html

aws s3api delete-object --bucket mybucket271120231804 --key sample.html

aws s3api delete-bucket --bucket mybucket271120231804
