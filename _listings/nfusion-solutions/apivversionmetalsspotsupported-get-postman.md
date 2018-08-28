{
  "info": {
    "name": "nFusion API Get list of symbols supported by the spot endpoints",
    "_postman_id": "40bbb9a0-d2da-4cbd-ad5d-75ffe381b8a8",
    "description": "Get list of symbols supported by the spot endpoints.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "73612e43-26c5-488d-bf0a-5544108867b8",
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
              "id": "e6ee7137-e99d-4306-9bba-374cbce14b0c"
            }
          ]
        },
        {
          "id": "62bc2409-0ce0-49b5-9d67-dde37fd10790",
          "name": "ApiV{versionMetalsBenchmarkSupportedGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nfusionsolutions.biz",
              "path": [
                "api/v:version/Metals/benchmark/supported"
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
            "description": "Get list of symbols supported by the benchmark endpoints."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6e54479-ca20-4269-b310-984da7363594"
            }
          ]
        },
        {
          "id": "147685c2-5f3e-4ca6-abe2-02de6a2e78ad",
          "name": "ApiV{versionMetalsSpotSupportedGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nfusionsolutions.biz",
              "path": [
                "api/v:version/Metals/spot/supported"
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
            "description": "Get list of symbols supported by the spot endpoints."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69e28eb6-34cb-434b-bb44-70914a03b5be"
            }
          ]
        }
      ]
    },
    {
      "name": "Latest",
      "item": [
        {
          "id": "7114a7e4-3e6e-4d3b-88c8-be278e8b3d39",
          "name": "ApiV{versionMetalsSpotSummaryGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nfusionsolutions.biz",
              "path": [
                "api/v:version/Metals/spot/summary"
              ],
              "query": [
                {
                  "key": "adjust",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "currency",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "metals",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "unitofmeasure",
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
            "description": "Current and daily summary information combined into a single quote"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54242a58-3e46-47e2-b345-ebb974ba31ea"
            }
          ]
        },
        {
          "id": "4d0ff6f9-8fbf-4a85-b365-8a2cead5b02a",
          "name": "ApiV{versionMetalsBenchmarkSummaryGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nfusionsolutions.biz",
              "path": [
                "api/v:version/Metals/benchmark/summary"
              ],
              "query": [
                {
                  "key": "currency",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "metals",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "unitofmeasure",
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
            "description": "Get latest benchmark prices for requested metals."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b5b9c10-f4b0-4901-a1c7-8aa5395fa161"
            }
          ]
        },
        {
          "id": "d18c1fe9-33bd-4619-9ac6-83f1ab6b14a5",
          "name": "ApiV{versionMetalsSpotRatioSummaryGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nfusionsolutions.biz",
              "path": [
                "api/v:version/Metals/spot/ratio/summary"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pairs",
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
            "description": "Get latest spot summary for requested metal ratios."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ccd763d-7f36-4745-9263-2aec46ad1e18"
            }
          ]
        }
      ]
    },
    {
      "name": "Historical",
      "item": [
        {
          "id": "d9c58408-552d-440f-aa6b-260b1449985f",
          "name": "ApiV{versionMetalsSpotHistoryGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nfusionsolutions.biz",
              "path": [
                "api/v:version/Metals/spot/history"
              ],
              "query": [
                {
                  "key": "currency",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "end",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "historicalfx",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "interval",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "metals",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "start",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "unitofmeasure",
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
            "description": "Historical OHLC data for the specified period and interval size\r\n\r\nThe combination of the interval parameter and start and end dates can result in results\r\nbeing truncated to conform to result size limits. See comments on interval parameter for details on valid interval values.\r\n\r\nThe historicalfx flag is used to determine whether to apply today's fx rates to a historical period, or to apply the historical rates from that same time frame."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "280dcb60-7c1b-4cfd-871c-0bd85f70b543"
            }
          ]
        },
        {
          "id": "4a229497-2972-4f0f-8c92-ec7b0f4ea0df",
          "name": "ApiV{versionMetalsSpotRatioHistoryGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nfusionsolutions.biz",
              "path": [
                "api/v:version/Metals/spot/ratio/history"
              ],
              "query": [
                {
                  "key": "end",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "interval",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pairs",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "start",
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
            "description": "Historical data for the specified period and interval size\r\n\r\nThe combination of the interval parameter and start and end dates can result in results\r\nbeing truncated to conform to result size limits. See comments on interval parameter for details on valid interval values."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "82a50c3a-5d79-4f62-856e-d645408b3a9f"
            }
          ]
        },
        {
          "id": "f7067443-2810-4317-88fd-1f6816c2b8e4",
          "name": "ApiV{versionMetalsBenchmarkHistoryGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nfusionsolutions.biz",
              "path": [
                "api/v:version/Metals/benchmark/history"
              ],
              "query": [
                {
                  "key": "currency",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "end",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "historicalfx",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "interval",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "metals",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "start",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "unitofmeasure",
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
            "description": "Historical OHLC data for the specified period and interval size\r\n\r\nThe combination of the interval parameter and start and end dates can result in results\r\nbeing truncated to conform to result size limits. See comments on interval parameter for details on valid interval values.\r\n\r\nThe historicalfx flag is used to determine whether to apply today's fx rates to a historical period, or to apply the historical rates from that same time frame."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea55679f-56b8-44bb-96e9-c47d6e919bed"
            }
          ]
        },
        {
          "id": "2f7cd6a2-64b2-47a6-a6e4-4890ded2e6e8",
          "name": "ApiV{versionMetalsSpotPerformanceAnnualGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nfusionsolutions.biz",
              "path": [
                "api/v:version/Metals/spot/performance/annual"
              ],
              "query": [
                {
                  "key": "currency",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "metals",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "unitofmeasure",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "years",
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
            "description": "Get historical annual performance for requested metals."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cf77f1f0-1f03-4992-9f9a-36982ceb9c91"
            }
          ]
        },
        {
          "id": "1f1fb1cc-6fd7-40ce-a2f2-85753676860a",
          "name": "ApiV{versionMetalsSpotPerformanceGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.nfusionsolutions.biz",
              "path": [
                "api/v:version/Metals/spot/performance"
              ],
              "query": [
                {
                  "key": "currency",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "metals",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "token",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "unitofmeasure",
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
            "description": "Get historical performance for requested metals."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ac60e5ba-53ea-4b5a-9d5a-dbaceac07ee5"
            }
          ]
        }
      ]
    }
  ]
}