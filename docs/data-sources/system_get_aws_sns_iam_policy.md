
# snowflake_system_get_aws_sns_iam_policy

<!-- These docs are auto-generated by code in ./docgen, run by with make docs. Manual edits will be overwritten. -->

## properties

|           NAME            |  TYPE  |                           DESCRIPTION                           | OPTIONAL | REQUIRED  | COMPUTED | DEFAULT |
|---------------------------|--------|-----------------------------------------------------------------|----------|-----------|----------|---------|
| aws_sns_topic_arn         | string | Amazon Resource Name (ARN) of the SNS topic for your S3 bucket  | false    | true      | false    |         |
| aws_sns_topic_policy_json | string | IAM policy for Snowflake’s SQS queue to subscribe to this topic | false    | false     | true     |         |