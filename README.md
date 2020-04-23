# hello-world-lambda

## Getting Started

1. Don't forget to make a bucket like `aws s3 mb s3://onemata-deployment-artifacts`
2. Had to update arn:aws:iam::605631505817:policy/service-role/CodeBuildBasePolicy-lambda-pipeline-build-us-east-1 to allow access to our bucket. Use codepipeline-us-east-1-* name convenction to avoid trouble in future.
