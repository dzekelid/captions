---
name: YouTube
x-slug: youtube
description: Enjoy the videos and music you love, upload original content, and share
  it all with friends, family, and the world on YouTube.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11515-youtube.jpg
x-kinRank: "9"
x-alexaRank: "2"
tags: Captions
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/apis.md
specificationVersion: "0.14"
apis:
- name: YouTube - Delete Captions
  x-api-slug: captions-delete
  description: Deletes a specified caption track.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11515-youtube.jpg
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1
  tags: Videos, Google APIs, Stack Network, Stack, internet, Technology, Mobile, SaaS,
    General Data, Relative Data, Service API, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captions-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captions-delete-openapi.md
- name: YouTube - Get Captions
  x-api-slug: captions-get
  description: Returns a list of caption tracks that are associated with a specified
    video. Note that the API response does not contain the actual captions and that
    the captions.download method provides the ability to retrieve a caption track.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11515-youtube.jpg
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1
  tags: Videos, Google APIs, Stack Network, Stack, internet, Technology, Mobile, SaaS,
    General Data, Relative Data, Service API, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captions-get-openapi.md
- name: YouTube - Add Captions
  x-api-slug: captions-post
  description: Uploads a caption track.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11515-youtube.jpg
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1
  tags: Videos, Google APIs, Stack Network, Stack, internet, Technology, Mobile, SaaS,
    General Data, Relative Data, Service API, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captions-post-openapi.md
- name: YouTube - Put Captions
  x-api-slug: captions-put
  description: Updates a caption track. When updating a caption track, you can change
    the track's draft status, upload a new caption file for the track, or both.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11515-youtube.jpg
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1
  tags: Videos, Google APIs, Stack Network, Stack, internet, Technology, Mobile, SaaS,
    General Data, Relative Data, Service API, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captions-put-openapi.md
- name: YouTube - Get Captions
  x-api-slug: captionsid-get
  description: Downloads a caption track. The caption track is returned in its original
    format unless the request specifies a value for the tfmt parameter and in its
    original language unless the request specifies a value for the tlang parameter.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11515-youtube.jpg
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1
  tags: Videos, Google APIs, Stack Network, Stack, internet, Technology, Mobile, SaaS,
    General Data, Relative Data, Service API, Pedestal, Historical Data API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captionsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captionsid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://yelp.api.gallery.streamdata.io
- type: x-api-stack
  url: http://youtube.stack.network
- type: x-articles
  url: https://developers.google.com/youtube/articles/
- type: x-authentication
  url: https://developers.google.com/youtube/v3/guides/authentication
- type: x-blog
  url: https://youtube-eng.googleblog.com/
- type: x-blog-rss
  url: https://youtube-eng.googleblog.com/feeds/posts/default?alt=rss
- type: x-branding
  url: https://developers.google.com/youtube/branding_guidelines
- type: x-bug-report
  url: https://code.google.com/p/gdata-issues/issues/entry
- type: x-bug-report
  url: https://code.google.com/p/gdata-issues/issues/list?q=label:API-YouTube
- type: x-buttons
  url: https://developers.google.com/youtube/youtube_subscribe_button
- type: x-crunchbase
  url: https://crunchbase.com/organization/youtube
- type: x-deprecation-policy
  url: https://developers.google.com/youtube/youtube-api-list
- type: x-developer
  url: https://developers.google.com/youtube/
- type: x-email
  url: copyright@youtube.com
- type: x-getting-started
  url: https://developers.google.com/youtube/v3/getting-started
- type: x-github
  url: https://github.com/youtube
- type: x-github
  url: https://github.com/youtube/
- type: x-terms-of-service
  url: https://developers.google.com/youtube/terms
- type: x-training
  url: https://developers.google.com/youtube/training/
- type: x-twitter
  url: https://twitter.com/YouTubeDev
- type: x-twitter
  url: https://twitter.com/YouTube
- type: x-website
  url: https://www.youtube.com/
- type: x-widgets
  url: https://developers.google.com/youtube/youtube_upload_widget
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---