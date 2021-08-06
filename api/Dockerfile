FROM public.ecr.aws/lambda/python:3.8

RUN yum update -y
RUN curl -fsSL https://rpm.nodesource.com/setup_current.x | bash -
RUN yum install -y nodejs
RUN npm install serverless serverless-offline -g
# RUN npm install serverless-offline --save-dev

WORKDIR /var/task
# RUN serverless install -u https://github.com/serverless/examples/tree/master/aws-python-auth0-custom-authorizers-api -n aws-python-auth
