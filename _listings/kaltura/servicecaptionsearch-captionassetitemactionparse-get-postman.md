{
  "info": {
    "name": "Kaltura VPaaS Get Service Captionsearch Captionassetitem Action Parse",
    "_postman_id": "9b587f54-4574-4822-9ee5-cc0c32ecf4f0",
    "description": "Parse content of caption asset and index it",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "f716ad8d-b6dc-4bc8-b735-bf93ce9d3ffc",
          "name": "captionAssetItem.parse",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/captionsearch_captionassetitem/action/parse?captionAssetId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Parse content of caption asset and index it"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "22077c98-3196-4d9c-90e7-d67114bccf12"
            }
          ]
        }
      ]
    }
  ]
}