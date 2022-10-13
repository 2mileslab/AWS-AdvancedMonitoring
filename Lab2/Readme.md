CloudWatch Config 추가 설정 후 아래 명령 실행
```
sudo /opt/aws/amazon-cloudwatch-agent/bin/amazon-cloudwatch-agent-ctl -a fetch-config -m ec2 -c file:./config.json -s
```
