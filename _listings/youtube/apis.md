---
name: YouTube
x-slug: youtube
description: YouTube allows billions of people to discover, watch and share originally-created
  videos. YouTube provides a forum for people to connect, inform, and inspire others
  across the globe and acts as a distribution platform for original content creators
  and advertisers large and small.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Captions
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/apis.md
specificationVersion: "0.14"
apis:
- name: Youtube Delete Captions
  x-api-slug: youtube
  description: Deletes a specified caption track.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//captions
  tags: Captions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captions-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captions-delete-openapi.md
- name: Youtube Get Captions
  x-api-slug: youtube
  description: Returns a list of caption tracks that are associated with a specified
    video. Note that the API response does not contain the actual captions and that
    the captions.download method provides the ability to retrieve a caption track.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//captions
  tags: Captions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captions-get-openapi.md
- name: Youtube Add Captions
  x-api-slug: youtube
  description: Uploads a caption track.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//captions
  tags: Captions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captions-post-openapi.md
- name: Youtube Put Captions
  x-api-slug: youtube
  description: Updates a caption track. When updating a caption track, you can change
    the track's draft status, upload a new caption file for the track, or both.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//captions
  tags: Captions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captions-put-openapi.md
- name: Youtube Get Captions
  x-api-slug: youtube
  description: Downloads a caption track. The caption track is returned in its original
    format unless the request specifies a value for the tfmt parameter and in its
    original language unless the request specifies a value for the tlang parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1//captions/{id}
  tags: Captions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captionsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/captionsid-get-openapi.md
- name: Youtube
  x-api-slug: youtube
  description: YouTube allows billions of people to discover, watch and share originally-created
    videos. YouTube provides a forum for people to connect, inform, and inspire others
    across the globe and acts as a distribution platform for original content creators
    and advertisers large and small.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/youtube-logo.png
  humanURL: https://www.youtube.com/
  baseURL: https://www.googleapis.com//youtube/v1
  tags: Captions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/captions/master/_listings/youtube/openapi.md
x-common:
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
- type: x-deprecation-policy
  url: https://developers.google.com/youtube/youtube-api-list
- type: x-developer
  url: https://developers.google.com/youtube/
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