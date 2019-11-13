## IBM Cloud VPC Migrate from Classic Toolchain

Companion toolchain source code for blog [Create a CI/CD Pipeline for Custom VPC Images](https://www.ibm.com/cloud/blog/create-a-ci-cd-pipeline-for-custom-vpc-images) which includes detailed step by step instructions with screen shots.  Only the highlights are included below


1. Click the **Create Toolchain** button to get started.

      [![VPC Migrate from Classic Toolchain](https://cloud.ibm.com/devops/graphics/create_toolchain_button.png)](https://cloud.ibm.com/devops/setup/deploy/?repository=https://github.com/IBM-Cloud/vpc-migrate-from-classic-toolchain&env_id=ibm:yp:us-south)


1. Notice the `GitHub` and `Delivery Pipeline` configuration panels.  The Delivery Pipeline panel must be configured - the API keys, classic name, and API key are a little tricky but the handy information button will help you locate the values that you need.
1. Click Create to create the toolchain
1. Notice the `GitHub` and `Delivery Pipeline` tool buttons.  The `Delivery Pipeline` tool shows the pipeline.
1. The pipeline will create and verify a VPC on Classic custom image
