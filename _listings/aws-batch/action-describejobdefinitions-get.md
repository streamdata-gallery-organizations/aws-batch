---
swagger: "2.0"
info:
  title: AWS Batch API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeJobDefinitions&k=1:
    get:
      summary: ' Describe Job Definitions '
      description: Describes a list of job definitions
      operationId: describeJobDefinitions
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
      - job definitions
definitions: []
x-collection-name: AWS Batch
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