{
  "info": {
    "name": "Getty Images Search API Put Asset Changes Change Sets",
    "_postman_id": "588baa90-4ca2-400e-adf1-c4a2bebf1107",
    "description": "Generates asset changes..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Asset",
      "item": [
        {
          "id": "629b5a11-5b82-4752-adbe-5d32a32a697e",
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
              "id": "e3f79072-d0c1-4e27-9401-e5d928142cd9"
            }
          ]
        }
      ]
    }
  ]
}