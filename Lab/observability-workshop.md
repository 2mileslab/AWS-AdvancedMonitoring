
아래 내용 수정 필요

```
curl -O https://raw.githubusercontent.com/2mileslab/AWS-AdvancedMonitoring/main/Lab/cloud9-cfn.yaml

aws cloudformation create-stack --stack-name user30-C9-Observability-Workshop --template-body file://cloud9-cfn.yaml --capabilities CAPABILITY_NAMED_IAM

aws cloudformation wait stack-create-complete --stack-name user30-C9-Observability-Workshop

echo -e "Cloud9 Instance is Ready!!\n\n"
```
