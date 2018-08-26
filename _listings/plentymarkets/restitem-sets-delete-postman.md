{
  "info": {
    "name": "Plentymarkets Delete item sets",
    "_postman_id": "0f4eeb1a-bb46-4109-a53a-777e4d8e3c46",
    "description": "Delete item sets.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Item",
      "item": [
        {
          "id": "330aa14e-f366-4c71-99d7-7c8e9a3b7493",
          "name": "deleteRestItemSets",
          "request": {
            "url": "http://example.com/rest/item_sets",
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Delete item sets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea6e8fe9-26eb-4af5-96a1-b041aa186e3c"
            }
          ]
        }
      ]
    }
  ]
}