# email notifications when my EC2 instance changes states
## Ref https://aws.amazon.com/premiumsupport/knowledge-center/ec2-email-instance-state-change/

Create SNS Topic
Create SNS SUbcription
Create Bus
Create rule 
custom pattern
```
{
  "source": ["aws.ec2"],
  "detail-type": ["EC2 Instance State-change Notification"]
}
```