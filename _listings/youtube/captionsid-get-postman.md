{
  "info": {
    "name": "Youtube Get Captions",
    "_postman_id": "93a1ce50-4984-44ce-bfa9-91fe6740947b",
    "description": "Downloads a caption track. The caption track is returned in its original format unless the request specifies a value for the tfmt parameter and in its original language unless the request specifies a value for the tlang parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "captions",
      "item": [
        {
          "id": "f9ec13b8-202b-487c-b1af-5832a7e9fffc",
          "name": "getCaptions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "youtube",
                "v1",
                "captions/:id"
              ],
              "query": [
                {
                  "key": "onBehalfOf",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "onBehalfOfContentOwner",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "tfmt",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "tlang",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Downloads a caption track"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c250adc8-6ec2-4823-9f24-f254f80ddd9f"
            }
          ]
        }
      ]
    }
  ]
}