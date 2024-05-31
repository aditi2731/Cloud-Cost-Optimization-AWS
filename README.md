# Cloud-Cost-Optimization-AWS
Description:

The Lambda function fetches all EBS snapshots owned by the same account and also retrieves a list of active EC2 instances. For each snapshot, it checks if the associated volume is not associated with any active instance. If it finds a stale snapshot, it deletes it, effectively optimizing storage costs.
