---
swagger: "2.0"
x-collection-name: YouTube
x-complete: 0
info:
  title: Youtube Parameters Captions
  description: Parameters captions
  termsOfService: https://developers.google.com/terms/
  contact:
    name: Google
    url: https://google.com
  version: 1.0.0
host: www.googleapis.com
basePath: /youtube/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /captions:
    delete:
      summary: Delete Captions
      description: Deletes a specified caption track.
      operationId: deleteCaptions
      x-api-path-slug: captions-delete
      parameters:
      - in: query
        name: id
        description: The id parameter identifies the caption track that is being deleted
      - in: query
        name: onBehalfOf
        description: ID of the Google+ Page for the channel that the request is be
          on behalf of
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      responses:
        200:
          description: OK
      tags:
      - Captions
    get:
      summary: Get Captions
      description: Returns a list of caption tracks that are associated with a specified
        video. Note that the API response does not contain the actual captions and
        that the captions.download method provides the ability to retrieve a caption
        track.
      operationId: getCaptions
      x-api-path-slug: captions-get
      parameters:
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of IDs that
          identify the caption resources that should be retrieved
      - in: query
        name: onBehalfOf
        description: ID of the Google+ Page for the channel that the request is on
          behalf of
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of one or
          more caption resource parts that the API response will include
      - in: query
        name: videoId
        description: The videoId parameter specifies the YouTube video ID of the video
          for which the API should return caption tracks
      responses:
        200:
          description: OK
      tags:
      - Captions
    parameters:
      summary: Parameters Captions
      description: Parameters captions
      operationId: parametersCaptions
      x-api-path-slug: captions-parameters
      responses:
        200:
          description: OK
      tags:
      - Captions
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