# AWS EB RDS & WP

## 🔥 👨‍💻 🔥

## Prerequisites

1.  EB CLI (& IAM user configured)

## Setup

1.  Create RDS instance
    * Note endpoint (host), user, password, and db (not instance) name
1.  Setup VPC
1.  Create EB application
1.  Create EB environment
    * Multi-container Docker
    * Sample app
    * More options > Assign to VPC security group
1.  Rename `Dockerrun.sample.json` -> `Dockerrun.aws.json`
    * Use RDS info from previous step
1.  `$ eb init`
    * Select region, app, and env created through management console
1.  `$ eb deploy`
