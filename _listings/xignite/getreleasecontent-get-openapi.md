---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Releases Get Release Content
  description: Return detailed information about a release as well as its content.
  version: v1
host: http://www.xignite.com/
basePath: xReleases.xml/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  GetReleaseContent/:
    get:
      summary: Get Release Content
      description: Return detailed information about a release as well as its content.
      operationId: getGetreleasecontent
      x-api-path-slug: getreleasecontent-get
      parameters:
      - in: query
        name: ReleaseID
        description: The press release ID>
      - in: query
        name: _Token
        description: The API Key
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Release
      - Content
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