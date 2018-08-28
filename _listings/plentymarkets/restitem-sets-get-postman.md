{
  "info": {
    "name": "Plentymarkets List item sets",
    "_postman_id": "074f915d-027a-4f00-a8a5-f538641fb483",
    "description": "Lists all item sets.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "e6e26e4f-68c2-4781-8e2b-d84e58b8da5e",
          "name": "getRestItemSets",
          "request": {
            "url": "http://example.com/rest/item_sets",
            "method": "GET",
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
            "description": "Lists all item sets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0aae9020-e1ee-4ace-8253-64f5de164952"
            }
          ]
        }
      ]
    },
    {
      "name": "Item",
      "item": [
        {
          "id": "0145ab3e-2b6e-405d-8714-eba2f8888ee8",
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
              "id": "25177208-bf8e-4480-92a9-54a6234bb04a"
            }
          ]
        }
      ]
    }
  ]
}