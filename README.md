# aws-sam-learning
learning aws sam

# Running
`sam build`
`sam deploy --guided` (supply your email when it asks to recieve a password for the API)

# commands
`sam validate` validate sam
`sam build` to build locally
`sam build --use-container` to build locally in a container
`sam local invoke` to invoke an instance and get a response
`sam deploy --guided` deploy (with guide)
`sam list endpoints --region us-east-1 --output json` to get the endpoints
`sam remote invoke HelloWorldFunction --region us-east-1 --stack-name sam-app` invoke the function in the cloud
`sam sync --watch --region us-east-1` sync any local changes to the cloud (deploys local changes in real-time so only do it for development environments)