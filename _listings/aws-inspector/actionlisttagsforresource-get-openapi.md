---
swagger: "2.0"
x-collection-name: AWS Inspector
x-complete: 0
info:
  title: AWS Inspector API List Tags For Resource
  version: 1.0.0
  description: Lists all tags associated with an assessment template.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListTagsForResource:
    get:
      summary: List Tags For Resource
      description: Lists all tags associated with an assessment template.
      operationId: listTagsForResource
      x-api-path-slug: actionlisttagsforresource-get
      parameters:
      - in: query
        name: resourceArn
        description: The ARN that specifies the assessment template whose tags you
          want to list
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags For Resources
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