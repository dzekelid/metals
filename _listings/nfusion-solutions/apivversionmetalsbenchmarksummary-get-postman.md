{
  "info": {
    "name": "nFusion API Get latest Benchmark prices for requested metals",
    "_postman_id": "9f914173-eeb0-41e0-85f3-cc0997c0ba40",
    "description": "Get latest benchmark prices for requested metals.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "e775307d-f74d-48a4-92fd-4f1c9ccb8572",
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
              "id": "893fdfda-6ac5-4f4b-aec9-da691066115b"
            }
          ]
        },
        {
          "id": "2cbbafca-b4ed-4676-87e3-b2691c1a99b9",
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
              "id": "df72ed37-3b2e-41f4-abcb-640021d9f3b3"
            }
          ]
        },
        {
          "id": "713663ed-c4f5-4b19-89fc-d4d23238f9c7",
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
              "id": "71b2ee5f-34de-4159-b19c-55d84073b365"
            }
          ]
        }
      ]
    },
    {
      "name": "Latest",
      "item": [
        {
          "id": "433a51c8-bded-438b-bc02-16792c53c739",
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
              "id": "bfb00cc1-99c4-4cc9-9c48-d74e5f320675"
            }
          ]
        },
        {
          "id": "68be632b-0db3-48f7-99d6-0f776293d74b",
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
              "id": "c68b0aa2-8828-4087-b2f8-c3d4f19d0212"
            }
          ]
        },
        {
          "id": "c6275bc9-e581-483a-856e-ea7bc0904495",
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
              "id": "c2479cb4-6652-4be0-83cd-cd3af4e0a8f0"
            }
          ]
        }
      ]
    },
    {
      "name": "Historical",
      "item": [
        {
          "id": "f10899d9-4d2c-4487-89c5-d43b24150de1",
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
              "id": "92d22f15-4cd1-4446-912f-16cd0cb15564"
            }
          ]
        },
        {
          "id": "7130723d-4b40-4d69-8192-772ca460cd3f",
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
              "id": "e25e996d-cb15-41ba-a326-604a56b3391a"
            }
          ]
        },
        {
          "id": "caca67c1-b836-4a37-aabb-eebfffe9347a",
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
              "id": "02dfd7d6-36f6-4808-9d42-ecdb79202b15"
            }
          ]
        },
        {
          "id": "c1d558e0-ea1d-44a1-b0cb-f9c003afff51",
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
              "id": "7fb299b5-ca4b-4315-b45c-9b31924ab19c"
            }
          ]
        },
        {
          "id": "d2869192-9770-4610-93b9-c1d4ea6aa928",
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
              "id": "f442d3ad-72f3-4b76-bd84-23c55e343e3b"
            }
          ]
        }
      ]
    }
  ]
}