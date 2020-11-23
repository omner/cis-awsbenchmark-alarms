# cis-awsbenchmark-alarms
CloudFormation template to build metric filters for CloudTrail Logs and alarms in CloudWatch in order to meet CIS AWS Foundations Benchmark (3.x requirements).

main-multi-account.json is a template for multi-account environment. Ideal to track activity from Amazon CloudWatch CloudTrail Log Group deployed by Control Tower, send alerts to local SNS Topic and then forward all activity using a Lambda to central location which can be other SNS Topic in Audit account. Same model used by ControTower to centrilize security events.
