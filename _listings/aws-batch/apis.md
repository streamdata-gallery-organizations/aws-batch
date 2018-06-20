---
name: AWS Batch
x-slug: aws-batch
description: AWS Batch enables developers, scientists, and engineers to easily and
  efficiently run hundreds of thousands of batch computing jobs on AWS. AWS Batch
  dynamically provisions the optimal quantity and type of compute resources (e.g.,
  CPU or memory optimized instances) based on the volume and specific resource requirements
  of the batch jobs submitted. With AWS Batch, there is no need to install and manage
  batch computing software or server clusters that you use to run your jobs, allowing
  you to focus on analyzing results and solving problems. AWS Batch plans, schedules,
  and executes your batch computing workloads across the full range of AWS compute
  services and features, such as Amazon EC2 and Spot Instances.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Batch
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Batch API Cancel Job
  x-api-slug: aws-batch-api
  description: Cancels jobs in an AWS Batch job queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=CancelJob
  tags: Jobs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actioncanceljob-get-openapi.md
- name: AWS Batch API Create Compute Environment
  x-api-slug: aws-batch-api
  description: Creates an AWS Batch compute environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=CreateComputeEnvironment
  tags: Compute Environment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actioncreatecomputeenvironment-get-openapi.md
- name: AWS Batch API Create Job Queue
  x-api-slug: aws-batch-api
  description: Creates an AWS Batch job queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=CreateJobQueue
  tags: Job Queue
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actioncreatejobqueue-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actioncreatejobqueue-get-openapi.md
- name: AWS Batch API Delete Compute Environment
  x-api-slug: aws-batch-api
  description: Deletes an AWS Batch compute environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=DeleteComputeEnvironment
  tags: Compute Environment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actiondeletecomputeenvironment-get-openapi.md
- name: AWS Batch API Delete Job Queue
  x-api-slug: aws-batch-api
  description: Deletes the specified job queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=DeleteJobQueue
  tags: Job Queue
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actiondeletejobqueue-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actiondeletejobqueue-get-openapi.md
- name: AWS Batch API Deregister Job Definition
  x-api-slug: aws-batch-api
  description: Deregisters an AWS Batch job definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=DeregisterJobDefinition
  tags: Job Definitions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actionderegisterjobdefinition-get-openapi.md
- name: AWS Batch API Describe Compute Environments
  x-api-slug: aws-batch-api
  description: Describes one or more of your compute environments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=DescribeComputeEnvironments
  tags: Compute Environment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actiondescribecomputeenvironments-get-openapi.md
- name: AWS Batch API Describe Job Definitions
  x-api-slug: aws-batch-api
  description: Describes a list of job definitions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=DescribeJobDefinitions
  tags: Job Definitions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actiondescribejobdefinitions-get-openapi.md
- name: AWS Batch API Describe Job Queues
  x-api-slug: aws-batch-api
  description: Describes one or more of your job queues.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=DescribeJobQueues
  tags: Job Queue
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actiondescribejobqueues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actiondescribejobqueues-get-openapi.md
- name: AWS Batch API Describe Jobs
  x-api-slug: aws-batch-api
  description: Describes a list of AWS Batch jobs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=DescribeJobs
  tags: Job Definitions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actiondescribejobs-get-openapi.md
- name: AWS Batch API List Jobs
  x-api-slug: aws-batch-api
  description: Returns a list of task jobs for a specified job queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=ListJobs
  tags: Jobs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actionlistjobs-get-openapi.md
- name: AWS Batch API Register Job Definition
  x-api-slug: aws-batch-api
  description: Registers an AWS Batch job definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=RegisterJobDefinition
  tags: Job Definitions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actionregisterjobdefinition-get-openapi.md
- name: AWS Batch API Submit Job
  x-api-slug: aws-batch-api
  description: Submits an AWS Batch job from a job definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=SubmitJob
  tags: Jobs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actionsubmitjob-get-openapi.md
- name: AWS Batch API Terminate Job
  x-api-slug: aws-batch-api
  description: Terminates jobs in a job queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=TerminateJob
  tags: Jobs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actionterminatejob-get-openapi.md
- name: AWS Batch API Update Compute Environment
  x-api-slug: aws-batch-api
  description: Updates an AWS Batch compute environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=UpdateComputeEnvironment
  tags: Compute Environment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actionupdatecomputeenvironment-get-openapi.md
- name: AWS Batch API Update Job Queue
  x-api-slug: aws-batch-api
  description: Updates a job queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: ://///?Action=UpdateJobQueue
  tags: Job Queue
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actionupdatejobqueue-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/actionupdatejobqueue-get-openapi.md
- name: AWS Batch API
  x-api-slug: aws-batch-api
  description: AWS Batch enables developers, scientists, and engineers to easily and
    efficiently run hundreds of thousands of batch computing jobs on AWS. AWS Batch
    dynamically provisions the optimal quantity and type of compute resources (e.g.,
    CPU or memory optimized instances) based on the volume and specific resource requirements
    of the batch jobs submitted. With AWS Batch, there is no need to install and manage
    batch computing software or server clusters that you use to run your jobs, allowing
    you to focus on analyzing results and solving problems. AWS Batch plans, schedules,
    and executes your batch computing workloads across the full range of AWS compute
    services and features, such as Amazon EC2 and Spot Instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-batch.jpg
  humanURL: https://aws.amazon.com/batch/
  baseURL: :///
  tags: AWS Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-batch/master/_listings/aws-batch/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/batch/latest/APIReference/API_Operations.html
- type: x-faq
  url: https://aws.amazon.com/batch/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/batch/pricing/
- type: x-use-cases
  url: https://aws.amazon.com/batch/use-cases/
- type: x-website
  url: https://aws.amazon.com/batch/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---