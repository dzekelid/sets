{
  "info": {
    "name": "Plentymarkets Create item sets",
    "_postman_id": "8d4e1228-d357-4d07-b4a3-101f273a4728",
    "description": "Create item sets.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "33f3fc2e-a2ea-430e-b62f-3087dcd77e18",
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
              "id": "9bc61799-b09b-48da-a4b0-b87d5f6a1b0d"
            }
          ]
        }
      ]
    },
    {
      "name": "Item",
      "item": [
        {
          "id": "56f122a6-f399-430d-bcae-9cbf11642047",
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
              "id": "4ae1563c-0ce0-4504-88f5-01a4bcfeed8e"
            }
          ]
        },
        {
          "id": "1ac11f17-826a-46f3-a2e1-4e00f434ce1d",
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
              "id": "b14e5fb7-8c18-431a-ae20-14f75e74c679"
            }
          ]
        }
      ]
    }
  ]
}