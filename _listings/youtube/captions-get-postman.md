{
  "info": {
    "name": "Youtube Get Captions",
    "_postman_id": "c4185f49-ef79-4698-afd0-a9073ab1f88b",
    "description": "Returns a list of caption tracks that are associated with a specified video. Note that the API response does not contain the actual captions and that the captions.download method provides the ability to retrieve a caption track.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "captions",
      "item": [
        {
          "id": "a581265c-a10f-474a-ba7c-fbc1a372a687",
          "name": "getCaptions",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/captions?id=%7B%7D&onBehalfOf=%7B%7D&onBehalfOfContentOwner=%7B%7D&part=%7B%7D&videoId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of caption tracks that are associated with a specified video"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e3f4606-26da-44de-83be-2077dd145034"
            }
          ]
        }
      ]
    }
  ]
}