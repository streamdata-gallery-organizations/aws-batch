---
swagger: "2.0"
x-collection-name: AWS Batch
x-complete: 0
info:
  title: AWS Batch API Create Compute Environment
  version: 1.0.0
  description: Creates an AWS Batch compute environment.
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