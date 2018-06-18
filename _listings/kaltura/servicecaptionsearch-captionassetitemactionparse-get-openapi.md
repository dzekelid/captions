---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Captionsearch Captionassetitem Action Parse
  description: Parse content of caption asset and index it
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/captionsearch_captionassetitem/action/parse:
    get:
      summary: Get Service Captionsearch Captionassetitem Action Parse
      description: Parse content of caption asset and index it
      operationId: captionAssetItem.parse
      x-api-path-slug: servicecaptionsearch-captionassetitemactionparse-get
      parameters:
      - in: query
        name: captionAssetId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Captionsearch
      - Captionassetitem
      - Action
      - Parse
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