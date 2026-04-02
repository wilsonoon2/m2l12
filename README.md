# m2l12
#⭐ Final Summary 
1. Execution Role
Defines what the Lambda function is allowed to do inside AWS (e.g., write logs, access S3, call other services).
2. Resource‑Based Policy
Defines who is allowed to invoke the Lambda function (e.g., S3 event trigger, SNS, EventBridge).
3. When Lambda needs to upload to S3:
• 	Execution Role: Add S3 write permissions (e.g., ).
• 	Resource‑Based Policy: No change needed, because S3 is not invoking Lambda.
