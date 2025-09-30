# aws-cicd-jenkins-and-terraform
I built a production-ready pipeline on AWS using Jenkins + Terraform: CodeBuild for packaging, CodeDeploy (Lambda) for canary traffic shifting, and S3 for artifacts. It publishes new Lambda versions and safely shifts the live alias with automatic rollback.
