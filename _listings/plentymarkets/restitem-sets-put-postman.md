{
  "info": {
    "name": "Plentymarkets Update item sets",
    "_postman_id": "f7c17fd3-5fb7-485c-a258-97666e4a7718",
    "description": "Update item sets.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "20c682a2-ac64-438c-8796-5b3ef083b66e",
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
              "id": "5d242da8-b647-4b9d-abd8-eed854ee7b09"
            }
          ]
        }
      ]
    },
    {
      "name": "Item",
      "item": [
        {
          "id": "728b7fb0-8617-4a84-89a6-8b08d788ff2f",
          "name": "putRestItemSets",
          "request": {
            "url": "http://example.com/rest/item_sets",
            "method": "PUT",
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
            "description": "Update item sets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0cc59f37-c36a-40f2-ac69-5a7816e8dcec"
            }
          ]
        },
        {
          "id": "5c69b240-4f80-4c97-b3a3-ec3315e30dc2",
          "name": "postRestItemSets",
          "request": {
            "url": "http://example.com/rest/item_sets?params=%7B%7D",
            "method": "POST",
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
            "description": "Create item sets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8504e5d5-c2a7-41c7-86e1-214dc25c98fb"
            }
          ]
        },
        {
          "id": "c941f591-c194-4fc3-9493-379d8584fcbf",
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
              "id": "f992b2b1-5508-4daa-a178-0c86ebe0b568"
            }
          ]
        }
      ]
    }
  ]
}