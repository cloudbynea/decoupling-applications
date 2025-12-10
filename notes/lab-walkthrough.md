# Decoupling Applications – Walkthrough Notes

These notes summarize the full hands-on execution of the AWS Cloud Quest lab.

## Steps Completed
1. Created SNS topic `ImageNotification`
2. Created SQS queue `ImageQueue`
3. Edited SQS access policy in Advanced mode
4. Configured Thumbnail UI with queue URL
5. Configured Loader UI with SNS topic ARN
6. Validated full SNS → SQS → Consumer workflow
7. Created second queue `ImageQueueDLQ`
8. Enabled DLQ redrive configuration on `ImageQueue`
9. Final validation completed successfully
