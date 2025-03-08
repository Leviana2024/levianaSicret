# levianaSicret
AmazonAws Public Key✓
                -----BEGIN PUBLIC KEY-----
MFYwEAYHKoZIzj0CAQYFK4EEAAoDQgAEk2L3TZCScr1TrqaPMiKrGqwkMB9e+BnT
fbTZlThYYhJBvyJP1QjtbgvLg1/0xStxBe9WD/LlW6oa0/WcACGuGQ==
                 -----END PUBLIC KEY-----

{
  "Id": "key-consolepolicy-3",
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "Enable IAM User Permissions",
      "Effect": "Allow",
      "Principal": {
        "AWS": "arn:aws:iam::084828583978:root"
      },
      "Action": "kms:*",
      "Resource": "*"
    },
    {
      "Sid": "Allow access for Key Administrators",
      "Effect": "Allow",
      "Principal": {
        "AWS": [
          "arn:aws:iam::084828583978:role/service-role/AWSLambdaBasicExecutionRole",
          "arn:aws:iam::084828583978:role/aws-service-role/mq.amazonaws.com/AWSServiceRoleForAmazonMQ",
          "arn:aws:iam::084828583978:role/aws-service-role/autoscaling.amazonaws.com/AWSServiceRoleForAutoScaling",
          "arn:aws:iam::084828583978:role/aws-service-role/servicecatalog-appregistry.amazonaws.com/AWSServiceRoleForAWSServiceCatalogAppRegistry",
          "arn:aws:iam::084828583978:role/aws-service-role/notifications.amazonaws.com/AWSServiceRoleForAwsUserNotifications",
          "arn:aws:iam::084828583978:role/aws-service-role/pi-db.metrics.cloudwatch.amazonaws.com/AWSServiceRoleForCloudWatchMetrics_DbPerfInsights",
          "arn:aws:iam::084828583978:role/aws-service-role/ecs.amazonaws.com/AWSServiceRoleForECS",
          "arn:aws:iam::084828583978:role/aws-service-role/elasticache.amazonaws.com/AWSServiceRoleForElastiCache",
          "arn:aws:iam::084828583978:role/aws-service-role/resource-explorer-2.amazonaws.com/AWSServiceRoleForResourceExplorer",
          "arn:aws:iam::084828583978:role/aws-service-role/servicequotas.amazonaws.com/AWSServiceRoleForServiceQuotas"
        ]
      },
      "Action": [
        "kms:Create*",
        "kms:Describe*",
        "kms:Enable*",
        "kms:List*",
        "kms:Put*",
        "kms:Update*",
        "kms:Revoke*",
        "kms:Disable*",
        "kms:Get*",
        "kms:Delete*",
        "kms:TagResource",
        "kms:UntagResource",
        "kms:ScheduleKeyDeletion",
        "kms:CancelKeyDeletion",
        "kms:ReplicateKey",
        "kms:UpdatePrimaryRegion"
      ],
      "Resource": "*"
    },
    {
      "Sid": "Allow use of the key",
      "Effect": "Allow",
      "Principal": {
        "AWS": [
          "arn:aws:iam::084828583978:role/service-role/AWSLambdaBasicExecutionRole",
          "arn:aws:iam::084828583978:role/aws-service-role/mq.amazonaws.com/AWSServiceRoleForAmazonMQ",
          "arn:aws:iam::084828583978:role/aws-service-role/autoscaling.amazonaws.com/AWSServiceRoleForAutoScaling",
          "arn:aws:iam::084828583978:role/aws-service-role/servicecatalog-appregistry.amazonaws.com/AWSServiceRoleForAWSServiceCatalogAppRegistry",
          "arn:aws:iam::084828583978:role/aws-service-role/notifications.amazonaws.com/AWSServiceRoleForAwsUserNotifications",
          "arn:aws:iam::084828583978:role/aws-service-role/pi-db.metrics.cloudwatch.amazonaws.com/AWSServiceRoleForCloudWatchMetrics_DbPerfInsights",
          "arn:aws:iam::084828583978:role/aws-service-role/ecs.amazonaws.com/AWSServiceRoleForECS",
          "arn:aws:iam::084828583978:role/aws-service-role/elasticache.amazonaws.com/AWSServiceRoleForElastiCache",
          "arn:aws:iam::084828583978:role/aws-service-role/resource-explorer-2.amazonaws.com/AWSServiceRoleForResourceExplorer",
          "arn:aws:iam::084828583978:role/aws-service-role/servicequotas.amazonaws.com/AWSServiceRoleForServiceQuotas",
          "arn:aws:iam::084828583978:role/aws-service-role/support.amazonaws.com/AWSServiceRoleForSupport",
          "arn:aws:iam::084828583978:role/aws-service-role/trustedadvisor.amazonaws.com/AWSServiceRoleForTrustedAdvisor",
          "arn:aws:iam::084828583978:role/ecsExternalInstanceRole",
          "arn:aws:iam::084828583978:role/ecsInstanceRole"
        ]
      },
      "Action": [
        "kms:DescribeKey",
        "kms:GetPublicKey",
        "kms:Sign",
        "kms:Verify"
      ],
      "Resource": "*"
    },
    {
      "Sid": "Allow attachment of persistent resources",
      "Effect": "Allow",
      "Principal": {
        "AWS": [
          "arn:aws:iam::084828583978:role/service-role/AWSLambdaBasicExecutionRole",
          "arn:aws:iam::084828583978:role/aws-service-role/mq.amazonaws.com/AWSServiceRoleForAmazonMQ",
          "arn:aws:iam::084828583978:role/aws-service-role/autoscaling.amazonaws.com/AWSServiceRoleForAutoScaling",
          "arn:aws:iam::084828583978:role/aws-service-role/servicecatalog-appregistry.amazonaws.com/AWSServiceRoleForAWSServiceCatalogAppRegistry",
          "arn:aws:iam::084828583978:role/aws-service-role/notifications.amazonaws.com/AWSServiceRoleForAwsUserNotifications",
          "arn:aws:iam::084828583978:role/aws-service-role/pi-db.metrics.cloudwatch.amazonaws.com/AWSServiceRoleForCloudWatchMetrics_DbPerfInsights",
          "arn:aws:iam::084828583978:role/aws-service-role/ecs.amazonaws.com/AWSServiceRoleForECS",
          "arn:aws:iam::084828583978:role/aws-service-role/elasticache.amazonaws.com/AWSServiceRoleForElastiCache",
          "arn:aws:iam::084828583978:role/aws-service-role/resource-explorer-2.amazonaws.com/AWSServiceRoleForResourceExplorer",
          "arn:aws:iam::084828583978:role/aws-service-role/servicequotas.amazonaws.com/AWSServiceRoleForServiceQuotas",
          "arn:aws:iam::084828583978:role/aws-service-role/support.amazonaws.com/AWSServiceRoleForSupport",
          "arn:aws:iam::084828583978:role/aws-service-role/trustedadvisor.amazonaws.com/AWSServiceRoleForTrustedAdvisor",
          "arn:aws:iam::084828583978:role/ecsExternalInstanceRole",
          "arn:aws:iam::084828583978:role/ecsInstanceRole"
        ]
      },
      "Action": [
        "kms:CreateGrant",
        "kms:ListGrants",
        "kms:RevokeGrant"
      ],
      "Resource": "*",
      "Condition": {
        "Bool": {
          "kms:GrantIsForAWSResource": "true"
        }
      }
    }
  ]
}

Feedback
© 2025,
