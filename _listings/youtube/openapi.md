---
swagger: "2.0"
x-collection-name: YouTube
x-complete: 1
info:
  title: YouTube
  description: youtube-allows-users-to-upload-view-rate-share-add-to-favorites-report-comment-on-videos-and-subscribe-to-other-users-it-offers-a-wide-variety-of-usergenerated-and-corporate-media-videos-available-content-includes-video-clips-tv-show-clips-music-videos-short-and-documentary-films-audio-recordings-movie-trailers-live-streams-and-other-content-such-as-video-blogging-short-original-videos-and-educational-videos-most-of-the-content-on-youtube-is-uploaded-by-individuals-but-media-corporations-including-cbs-the-bbc-vevo-and-hulu-offer-some-of-their-material-via-youtube-as-part-of-the-youtube-partnership-program-unregistered-users-can-only-watch-videos-on-the-site-while-registered-users-are-permitted-to-upload-an-unlimited-number-of-videos-and-add-comments-to-videos
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
    post:
      summary: Add Captions
      description: Uploads a caption track.
      operationId: postCaptions
      x-api-path-slug: captions-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: onBehalfOf
        description: ID of the Google+ Page for the channel that the request is be
          on behalf of
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: part
        description: The part parameter specifies the caption resource parts that
          the API response will include
      - in: query
        name: sync
        description: The sync parameter indicates whether YouTube should automatically
          synchronize the caption file with the audio track of the video
      responses:
        200:
          description: OK
      tags:
      - Captions
    put:
      summary: Put Captions
      description: Updates a caption track. When updating a caption track, you can
        change the track's draft status, upload a new caption file for the track,
        or both.
      operationId: putCaptions
      x-api-path-slug: captions-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: onBehalfOf
        description: ID of the Google+ Page for the channel that the request is be
          on behalf of
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: part
        description: The part parameter serves two purposes in this operation
      - in: query
        name: sync
        description: 'Note: The API server only processes the parameter value if the
          request contains an updated caption file'
      responses:
        200:
          description: OK
      tags:
      - Captions
  /captions/{id}:
    get:
      summary: Get Captions
      description: Downloads a caption track. The caption track is returned in its
        original format unless the request specifies a value for the tfmt parameter
        and in its original language unless the request specifies a value for the
        tlang parameter.
      operationId: getCaptions
      x-api-path-slug: captionsid-get
      parameters:
      - in: path
        name: id
        description: The id parameter identifies the caption track that is being retrieved
      - in: query
        name: onBehalfOf
        description: ID of the Google+ Page for the channel that the request is be
          on behalf of
      - in: query
        name: onBehalfOfContentOwner
        description: 'Note: This parameter is intended exclusively for YouTube content
          partners'
      - in: query
        name: tfmt
        description: The tfmt parameter specifies that the caption track should be
          returned in a specific format
      - in: query
        name: tlang
        description: The tlang parameter specifies that the API response should return
          a translation of the specified caption track
      responses:
        200:
          description: OK
      tags:
      - Captions
    parameters:
      summary: Parameters Captions
      description: Parameters captions
      operationId: parametersCaptions
      x-api-path-slug: captionsid-parameters
      responses:
        200:
          description: OK
      tags:
      - Captions
---