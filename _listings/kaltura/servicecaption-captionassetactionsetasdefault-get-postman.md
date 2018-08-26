{
  "info": {
    "name": "Kaltura VPaaS Get Service Caption Captionasset Action Setasdefault",
    "_postman_id": "761bb5c7-e4d9-46a2-b0e1-b2e4804b832e",
    "description": "Markss the caption as default and removes that mark from all other caption assets of the entry.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "1c5eaa34-e14d-4dca-9d3b-5e495b61691d",
          "name": "captionAsset.setAsDefault",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/caption_captionasset/action/setAsDefault?captionAssetId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Markss the caption as default and removes that mark from all other caption assets of the entry."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41378a25-7a41-4c98-902d-2cfcc8b1ad65"
            }
          ]
        }
      ]
    }
  ]
}