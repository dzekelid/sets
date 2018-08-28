{
  "info": {
    "name": "Getty Images Search API Delete Asset Changes Change Sets Change Set",
    "_postman_id": "ff5ca4db-f55d-4724-9d4c-cb01c67ee11a",
    "description": "Confirm asset changes acknowledges receipt of asset changes..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Asset",
      "item": [
        {
          "id": "165c1f82-f2b5-4b4d-9aa5-282a5a8b83ec",
          "name": "putV3AssetChangesChangeSets",
          "request": {
            "url": "http://api.gettyimages.com/v3/asset-changes/change-sets?batch_size=%7B%7D&channel_id=%7B%7D",
            "method": "PUT",
            "header": [
              {
                "key": "Accept-Language",
                "value": "{}",
                "description": "Accept-Language parameter optional",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Authorization token required",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Generates asset changes.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "37f9496c-fb14-4242-be99-6517edea5d10"
            }
          ]
        },
        {
          "id": "e99695cb-b76a-42bb-9b27-de62023886cb",
          "name": "deleteV3AssetChangesChangeSetsChangeSet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.gettyimages.com",
              "path": [
                "v3/asset-changes/change-sets/:change-set-id"
              ],
              "variable": [
                {
                  "id": "change-set-id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Accept-Language",
                "value": "{}",
                "description": "Accept-Language parameter optional",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Authorization token required",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Confirm asset changes acknowledges receipt of asset changes.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fbe8c39c-251e-4254-9b2e-92cc46b76c86"
            }
          ]
        }
      ]
    }
  ]
}