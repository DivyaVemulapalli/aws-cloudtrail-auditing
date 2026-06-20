# AWS CloudTrail Auditing Project

##  Project Overview

Implemented AWS CloudTrail to monitor and audit AWS account activity. CloudTrail was configured to record management events and store logs in Amazon S3, enabling tracking of user actions and API activity within the AWS environment.

##  AWS Services Used

* AWS CloudTrail
* Amazon S3

##  Project Objectives

* Monitor AWS account activity
* Track user and API actions
* Understand AWS auditing and governance
* Explore event history and log storage

##  Steps Followed

1. Opened the AWS CloudTrail console
2. Created a new CloudTrail trail
3. Configured Amazon S3 as the log storage location
4. Enabled Management Events logging
5. Selected Read and Write API activity
6. Created the CloudTrail trail
7. Performed AWS actions to generate events
8. Viewed and analyzed events in Event History

##  Events Captured

CloudTrail recorded various AWS account activities, including:

* Console login events
* EC2 actions
* S3 operations
* IAM activities
* API calls performed within the AWS account

##  Outcome

Successfully configured AWS CloudTrail to capture and monitor AWS account activities. Verified that CloudTrail recorded user actions and API events, providing visibility into account activity for auditing and security purposes.

##  Key Learnings

* AWS CloudTrail fundamentals
* AWS auditing and governance
* Event History analysis
* API activity tracking
* Log storage using Amazon S3
* Security monitoring and compliance

##  Future Enhancements

* Integrate CloudTrail with CloudWatch Logs
* Configure SNS notifications for security events
* Enable CloudTrail Insights
* Analyze CloudTrail logs using Amazon Athena
