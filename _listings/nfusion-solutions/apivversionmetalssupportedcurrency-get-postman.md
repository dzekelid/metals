{
  "info": {
    "name": "nFusion API Get list of currencies supported by metals endpoints for currency conversion",
    "_postman_id": "ec263793-283d-4bf0-814b-1a91caed535a",
    "description": "Get list of currencies supported by metals endpoints for currency conversion.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "08de7f29-0c51-4c0d-a6a4-f1214453370c",
          "name": "ApiV{versionCurrenciesRateSupportedGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nfusionsolutions.biz",
              "path": [
                "api/v:version/Currencies/rate/supported"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "token",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "version",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Any of the currencies in this list can be paired with any other currency in this list when supplied to the Rate endpoint.\r\nFor example: USD/CAD,CAD/USD,USD/EUR,EUR/CAD"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "553fe02f-72ef-4621-9429-d2d97e8e473c"
            }
          ]
        },
        {
          "id": "498e92a1-ff54-4304-bcd8-edb51068ecb5",
          "name": "ApiV{versionMetalsSupportedCurrencyGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nfusionsolutions.biz",
              "path": [
                "api/v:version/Metals/supported/currency"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "token",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "version",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Get list of currencies supported by metals endpoints for currency conversion."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d70b44b2-9801-455f-b85b-9c3f080e04d2"
            }
          ]
        }
      ]
    }
  ]
}