{
  "info": {
    "name": "Plentymarkets List all Sets",
    "_postman_id": "3d3769ce-006f-4bce-bd3e-6bed3d46b4a5",
    "description": "Lists all available sets.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "f76e01ac-4601-4ee5-b142-9c52327b208c",
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
              "id": "5da28a58-7b16-4c4e-bc41-9a996dee1fa5"
            }
          ]
        },
        {
          "id": "0654f149-40c2-4b7d-b34f-2f0854ea4c59",
          "name": "getRestPluginSets",
          "request": {
            "url": "http://example.com/rest/plugin_sets",
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
            "description": "Lists all available sets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a07c7837-1dd7-456f-9480-9e3a1734795e"
            }
          ]
        }
      ]
    },
    {
      "name": "Item",
      "item": [
        {
          "id": "d9f48af9-6bce-4533-b573-1ee0b6e16c73",
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
              "id": "26d37fb4-b566-423e-9c7d-f6602d9d0d0f"
            }
          ]
        },
        {
          "id": "b6d9cfa3-e09a-4556-a5c3-ea2695e2f5ec",
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
              "id": "5e94db07-a6d1-4693-b949-3cd6a575d411"
            }
          ]
        },
        {
          "id": "8d0e62f0-5b27-4242-90cd-26250cccb79d",
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
              "id": "4185d379-a410-4029-98c3-b3508b0da26a"
            }
          ]
        }
      ]
    }
  ]
}