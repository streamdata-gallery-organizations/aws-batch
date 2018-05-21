---
swagger: "2.0"
x-collection-name: AWS Batch
x-complete: 0
info:
  title: AWS Batch API Describe Job Definitions
  version: 1.0.0
  description: Describes a list of job definitions.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CancelJob:
    get:
      summary: Cancel Job
      description: Cancels jobs in an AWS Batch job queue.
      operationId: cancelJob
      x-api-path-slug: actioncanceljob-get
      parameters:
      - in: query
        name: jobId
        description: A list of up to 100 job IDs to cancel
        type: string
      - in: query
        name: reason
        description: A message to attach to the job that explains the reason for cancelling
          it
        type: string
      responses:
        200:
          description: OK
      tags:
      - Jobs
  /?Action=CreateComputeEnvironment:
    get:
      summary: Create Compute Environment
      description: Creates an AWS Batch compute environment.
      operationId: createComputeEnvironment
      x-api-path-slug: actioncreatecomputeenvironment-get
      parameters:
      - in: query
        name: computeEnvironmentName
        description: The name for your compute environment
        type: string
      - in: query
        name: computeResources
        description: Details of the compute resources managed by the compute environment
        type: string
      - in: query
        name: serviceRole
        description: The full Amazon Resource Name (ARN) of the IAM role that allows
          AWS Batch to make calls to other AWS         services on your behalf
        type: string
      - in: query
        name: state
        description: The state of the compute environment
        type: string
      - in: query
        name: type
        description: The type of the compute environment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compute Environment
  /?Action=CreateJobQueue:
    get:
      summary: Create Job Queue
      description: Creates an AWS Batch job queue.
      operationId: createJobQueue
      x-api-path-slug: actioncreatejobqueue-get
      parameters:
      - in: query
        name: computeEnvironmentOrder
        description: The set of compute environments mapped to a job queue and their
          order relative to         each other
        type: string
      - in: query
        name: jobQueueName
        description: The name of the job queue
        type: string
      - in: query
        name: priority
        description: The priority of the job queue
        type: string
      - in: query
        name: state
        description: The state of the job queue
        type: string
      responses:
        200:
          description: OK
      tags:
      - Job Queue
  /?Action=DeleteComputeEnvironment:
    get:
      summary: Delete Compute Environment
      description: Deletes an AWS Batch compute environment.
      operationId: deleteComputeEnvironment
      x-api-path-slug: actiondeletecomputeenvironment-get
      parameters:
      - in: query
        name: computeEnvironment
        description: The name or Amazon Resource Name (ARN) of the compute environment
          to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compute Environment
  /?Action=DeleteJobQueue:
    get:
      summary: Delete Job Queue
      description: Deletes the specified job queue.
      operationId: deleteJobQueue
      x-api-path-slug: actiondeletejobqueue-get
      parameters:
      - in: query
        name: jobQueue
        description: The short name or full Amazon Resource Name (ARN) of the queue
          to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Job Queue
  /?Action=DeregisterJobDefinition:
    get:
      summary: Deregister Job Definition
      description: Deregisters an AWS Batch job definition.
      operationId: deregisterJobDefinition
      x-api-path-slug: actionderegisterjobdefinition-get
      parameters:
      - in: query
        name: jobDefinition
        description: The name and revision (name:revision) or full Amazon Resource
          Name (ARN) of the job         definition to deregister
        type: string
      responses:
        200:
          description: OK
      tags:
      - Job Definitions
  /?Action=DescribeComputeEnvironments:
    get:
      summary: Describe Compute Environments
      description: Describes one or more of your compute environments.
      operationId: describeComputeEnvironments
      x-api-path-slug: actiondescribecomputeenvironments-get
      parameters:
      - in: query
        name: computeEnvironments
        description: A list of up to 100 compute environment names or full Amazon
          Resource Name (ARN) entries
        type: string
      - in: query
        name: maxResults
        description: The maximum number of cluster results returned by            DescribeComputeEnvironments
          in paginated output
        type: string
      - in: query
        name: nextToken
        description: The nextToken value returned from a previous paginated            DescribeComputeEnvironments
          request where maxResults was used         and the results exceeded the value
          of that parameter
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compute Environment
  /?Action=DescribeJobDefinitions:
    get:
      summary: Describe Job Definitions
      description: Describes a list of job definitions.
      operationId: describeJobDefinitions
      x-api-path-slug: actiondescribejobdefinitions-get
      parameters:
      - in: query
        name: jobDefinitionName
        description: The name of the job definition to describe
        type: string
      - in: query
        name: jobDefinitions
        description: A space-separated list of up to 100 job definition names or full
          Amazon Resource Name (ARN)         entries
        type: string
      - in: query
        name: maxResults
        description: The maximum number of results returned by DescribeJobDefinitions
          in         paginated output
        type: string
      - in: query
        name: nextToken
        description: The nextToken value returned from a previous paginated            DescribeJobDefinitions
          request where maxResults was used and         the results exceeded the value
          of that parameter
        type: string
      - in: query
        name: status
        description: The status with which to filter job definitions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Job Definitions
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---