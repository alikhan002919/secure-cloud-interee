# S3 Cross-Region Replication

1. Enable versioning on source and destination S3 buckets.
2. Create an IAM role with replication permissions.
3. Configure replication rule:
   - Source: `bucket-a` (Region: us-east-1)
   - Destination: `bucket-b` (Region: us-west-2)
4. Enable metrics and logging for replication status.
