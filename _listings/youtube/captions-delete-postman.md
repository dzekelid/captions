{
  "info": {
    "name": "Youtube Delete Captions",
    "_postman_id": "34a719b3-5af5-448d-b730-7293bdc16ccb",
    "description": "Deletes a specified caption track.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "captions",
      "item": [
        {
          "id": "ebbfba8b-741a-4152-9250-5b89621461cc",
          "name": "deleteCaptions",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/captions?id=%7B%7D&onBehalfOf=%7B%7D&onBehalfOfContentOwner=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specified caption track"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0db8ca14-ed90-407d-95cd-2cf3f2e98ec3"
            }
          ]
        }
      ]
    }
  ]
}