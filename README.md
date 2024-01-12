# aws-sam-learning
learning aws sam


# commands
`sam build` to build locally
`sam build --use-container` to build locally in a container
`sam local invoke` to invoke an instance and get a response
`sam deploy --guided` deploy (with guide)
`sam list endpoints --region us-east-1 --output json` to get the endpoints
`sam remote invoke HelloWorldFunction --region us-east-1 --stack-name sam-app` invoke the function in the cloud
`sam sync --watch` sync any local changes to the cloud (deploys local changes in real-time so only do it for development environments)