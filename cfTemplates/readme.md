### Deploy the template
- network stack - `aws cloudformation deploy --template-file network.yml --stack-name MenApiNetworkStack  --capabilities CAPABILITY_IAM`

### Deleting the stacks
- network stack - `aws cloudformation delete-stack --stack-name MenApiNetworkStack`
