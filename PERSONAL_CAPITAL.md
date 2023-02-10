# Personal Capital

## Overview

[They (formerly we ;-) ) transform financial lives through technology and people](https://www.personalcapital.com/company). 

This is a rough outline of some of the interesting work I performed while I worked at Personal Capital from 2016 to 2022. Roughly organized in chronological order.

## Categories

### AWS

Some of these projects I plan to reproduce prototype examples in [runamok-aws-lab](https://github.com/mreeves1/runamok-aws-lab).

- Implemented 95% of our AWS IAC in AWS CloudFormation (aka CFn). Previous to my hire in 2016, most AWS resources were created manually va the GUI. Most resources listed below use CFn.
- VPC CFn design that could work with organically created VPCs or create everything depending on parameter settings
- Migrated us from services using key/secret AWS access to ec2 instance profiles
- RDS Aurora Mysql Cluster with replica autoscaling, DBA IAM for self-serve, S3 UNLOAD bucket, etc.
- Elasticache (Redis) Clusters 
- Elasticsearch Clusters
- AWS SFTP Server
- EKS Cluster with Managed Add-ons, Managed Workers (on-demand and spot), IRSA, etc.
- Bidirectional cross-account S3 Replication w/ KMS encryption
- Designed and implemented a Jenkins assume-role pattern model to follow last privilege philosophy.  
  Additionally a k8s service's role (dev only) could be assumed by both users and Jenkins agents to test a given service's AWS resource functionality
- AWS API Gateway V2 with mTLS via S3 Truststore and Oauth using Okta
- NLB in front of ALB design to facilitate having static IP addresses for an IPSEC tunnel access pattern
- Event system using Kinesis, Lambda, Dynamodb, Firehose, Elastic Search, S3, Redshift, etc. (primarily designed by a colleague, but I helped implement it)
- TODO: Add much more

### Kubernetes

- Istio setup with mTLS and istio authorization policies and multiple ingress gateways plus ALB ingress
- Envoy filters to do cookie manipulation and sticky session
- Cluster proportional autoscaler
- Kubernetes Splunk Connect logging
- Security Group Policies
- TODO: Add much more

### Terraform

TODO

### Chef

TODO

## GitHub Contributions

Review my [pc-mreeves Github user](https://github.com/pc-mreeves) that I used during my 6 years at Personal Capital. Most repos are private, but you can see I was quite active at GH. You can see over time I spent a great deal of time mentoring and doing code review as well as committing myself.

![2022 Personal Capital Github Contributions](/images/gh-pc-mreeves-2022.png "2022 Personal Capital Github Contributions")

![2021 Personal Capital Github Contributions](/images/gh-pc-mreeves-2021.png "2021 Personal Capital Github Contributions")

![2020 Personal Capital Github Contributions](/images/gh-pc-mreeves-2020.png "2020 Personal Capital Github Contributions")

![2019 Personal Capital Github Contributions](/images/gh-pc-mreeves-2019.png "2019 Personal Capital Github Contributions")

![2018 Personal Capital Github Contributions](/images/gh-pc-mreeves-2018.png "2018 Personal Capital Github Contributions")

![2017 Personal Capital Github Contributions](/images/gh-pc-mreeves-2017.png "2017 Personal Capital Github Contributions")

![2016 Personal Capital Github Contributions](/images/gh-pc-mreeves-2016.png "2016 Personal Capital Github Contributions")

## RescueTime Final Month

After giving notice of 4 weeks I worked ~260 hours that last month to leave the Devops team (as well as sibling teams) in a good place. Not advisable but I knew where the bodies were buried and wanted to finish some things that only I had good context on to minimize future tech debt.  

![RescueTime Week 1](/images/rescuetime_2022-07-31.jpg "RescueTime Week 1")

TODO: Add missing week

![RescueTime Week 3](/images/rescuetime_2022-08-14.jpg "RescueTime Week 2")

![RescueTime Week 4](/images/rescuetime_2022-08-21.jpg "RescueTime Week 3")

![RescueTime Week 5](/images/rescuetime_2022-08-28.jpg "RescueTime Week 4")