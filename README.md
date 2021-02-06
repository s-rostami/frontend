public.ecr.aws/o8f5t9n7/frontend-v1

aws ecr-public get-login-password --region us-east-1 | docker login --username AWS --password-stdin public.ecr.aws/o8f5t9n7

docker tag frontend-v1:latest public.ecr.aws/o8f5t9n7/frontend-v1:latest

docker push public.ecr.aws/o8f5t9n7/frontend-v1:latest
