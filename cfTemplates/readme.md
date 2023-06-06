### Deploy the template
- network stack - `aws cloudformation deploy --template-file network.yaml --stack-name MenApiNetworkStack  --capabilities CAPABILITY_IAM`
- application stack - `aws cloudformation deploy --template-file application.yaml --stack-name MenApiApplicationStack  --capabilities CAPABILITY_IAM`

### Deleting the stacks
- application stack - `aws cloudformation delete-stack --stack-name MenApiApplicationStack`
- network stack - `aws cloudformation delete-stack --stack-name MenApiNetworkStack`

### Creating IAM policy IAM role for private instances
- `aws iam create-policy --policy-name MenApiPrivateInstancePolicy --policy-document private-instance-policy.json`
