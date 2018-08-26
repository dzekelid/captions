{
  "info": {
    "name": "Kaltura VPaaS Get Service Caption Captionasset Action Getremotepaths",
    "_postman_id": "0c900a96-f41d-4d8e-aa40-8f86d5823755",
    "description": "Get remote storage existing paths for the asset",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "6a6552b4-a357-4b01-b1c8-3c7e833c5e69",
          "name": "attachmentAsset.getRemotePaths",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/getRemotePaths?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get remote storage existing paths for the asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd7836af-98ac-407b-8b50-8a490c911db7"
            }
          ]
        },
        {
          "id": "3aeffe7d-455c-4da4-ab46-db6458636bc7",
          "name": "baseEntry.getRemotePaths",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/baseentry/action/getRemotePaths?entryId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get remote storage existing paths for the asset."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b9202ba-76c0-41da-9104-be2318ec5098"
            }
          ]
        },
        {
          "id": "90914b11-2baa-408a-9a8c-888f39a2e473",
          "name": "captionAsset.getRemotePaths",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/caption_captionasset/action/getRemotePaths?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get remote storage existing paths for the asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0e45e10-f206-4239-beb6-b946be157b5e"
            }
          ]
        }
      ]
    }
  ]
}