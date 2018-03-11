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
  /?Action=DescribeJobs&k=1:
    get:
      summary: ' Describe Jobs '
      description: Describes a list of AWS Batch jobs
      operationId: describeJobs
      parameters:
      - in: query
        name: jobs
        description: A space-separated list of up to 100 job IDs
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