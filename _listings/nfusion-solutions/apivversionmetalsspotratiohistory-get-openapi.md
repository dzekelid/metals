---
swagger: "2.0"
x-collection-name: nFusion Solutions
x-complete: 0
info:
  title: nFusion API Get historical Spot Ratio prices for requested metals
  description: "Historical data for the specified period and interval size\r\n\r\nThe
    combination of the interval parameter and start and end dates can result in results\r\nbeing
    truncated to conform to result size limits. See comments on interval parameter
    for details on valid interval values."
  contact:
    name: nFusion Solutions
    url: https://nfusionsolutions.com/contact
    email: support@nfusionsolutions.com
  version: 1.0.0
host: api.nfusionsolutions.biz
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v{version}/Metals/supported/currency:
    get:
      summary: Get list of currencies supported by metals endpoints for currency conversion
      description: Get list of currencies supported by metals endpoints for currency
        conversion.
      operationId: ApiV{versionMetalsSupportedCurrencyGet
      x-api-path-slug: apivversionmetalssupportedcurrency-get
      parameters:
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: token
        description: auth token
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Currencies
      - Supported
      - By
      - Metals
      - Endpointscurrency
      - Conversion
  /api/v{version}/Metals/spot/summary:
    get:
      summary: Get latest Spot Summary for requested metals
      description: Current and daily summary information combined into a single quote
      operationId: ApiV{versionMetalsSpotSummaryGet
      x-api-path-slug: apivversionmetalsspotsummary-get
      parameters:
      - in: query
        name: adjust
        description: apply global and per-tenant spot price adjustments
      - in: query
        name: currency
        description: comma separated list of conversion currencies, defaults to USD
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: metals
        description: comma separated list of metals
      - in: query
        name: token
        description: auth token
      - in: query
        name: unitofmeasure
        description: unit of meaure, defaults to troy ounces
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - Latest
      - Spot
      - Summaryrequested
      - Metals
  /api/v{version}/Metals/spot/history:
    get:
      summary: Get historical Spot prices for requested metals
      description: "Historical OHLC data for the specified period and interval size\r\n\r\nThe
        combination of the interval parameter and start and end dates can result in
        results\r\nbeing truncated to conform to result size limits. See comments
        on interval parameter for details on valid interval values.\r\n\r\nThe historicalfx
        flag is used to determine whether to apply today's fx rates to a historical
        period, or to apply the historical rates from that same time frame."
      operationId: ApiV{versionMetalsSpotHistoryGet
      x-api-path-slug: apivversionmetalsspothistory-get
      parameters:
      - in: query
        name: currency
        description: comma separated list of conversion currencies, defaults to USD
      - in: query
        name: end
        description: end date of time period
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: historicalfx
        description: if true use historical currency rates otherwise current currency
          rates
      - in: query
        name: interval
        description: aggregation interval
      - in: query
        name: metals
        description: comma separated list of metals
      - in: query
        name: start
        description: start date of time period
      - in: query
        name: token
        description: auth token
      - in: query
        name: unitofmeasure
        description: unit of meaure, defaults to troy ounces
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Spot
      - Pricesrequested
      - Metals
  /api/v{version}/Metals/spot/ratio/history:
    get:
      summary: Get historical Spot Ratio prices for requested metals
      description: "Historical data for the specified period and interval size\r\n\r\nThe
        combination of the interval parameter and start and end dates can result in
        results\r\nbeing truncated to conform to result size limits. See comments
        on interval parameter for details on valid interval values."
      operationId: ApiV{versionMetalsSpotRatioHistoryGet
      x-api-path-slug: apivversionmetalsspotratiohistory-get
      parameters:
      - in: query
        name: end
        description: end date of time period
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: interval
        description: aggregation interval
      - in: query
        name: pairs
        description: comma separated list of metals
      - in: query
        name: start
        description: start date of time period
      - in: query
        name: token
        description: auth token
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Spot
      - Ratio
      - Pricesrequested
      - Metals
  /api/v{version}/Metals/benchmark/summary:
    get:
      summary: Get latest Benchmark prices for requested metals
      description: Get latest benchmark prices for requested metals.
      operationId: ApiV{versionMetalsBenchmarkSummaryGet
      x-api-path-slug: apivversionmetalsbenchmarksummary-get
      parameters:
      - in: query
        name: currency
        description: comma separated list of conversion currencies, defaults to USD
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: metals
        description: comma separated list of metals
      - in: query
        name: token
        description: auth token
      - in: query
        name: unitofmeasure
        description: unit of meaure, defaults to troy ounces
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - Latest
      - Benchmark
      - Pricesrequested
      - Metals
  /api/v{version}/Metals/benchmark/history:
    get:
      summary: Get historical benchmark prices for requested metals
      description: "Historical OHLC data for the specified period and interval size\r\n\r\nThe
        combination of the interval parameter and start and end dates can result in
        results\r\nbeing truncated to conform to result size limits. See comments
        on interval parameter for details on valid interval values.\r\n\r\nThe historicalfx
        flag is used to determine whether to apply today's fx rates to a historical
        period, or to apply the historical rates from that same time frame."
      operationId: ApiV{versionMetalsBenchmarkHistoryGet
      x-api-path-slug: apivversionmetalsbenchmarkhistory-get
      parameters:
      - in: query
        name: currency
        description: comma separated list of conversion currencies, defaults to USD
      - in: query
        name: end
        description: end date of time period
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: historicalfx
        description: if true use historical currency rates otherwise current currency
          rates
      - in: query
        name: interval
        description: aggregation interval
      - in: query
        name: metals
        description: comma separated list of metals
      - in: query
        name: start
        description: start date of time period
      - in: query
        name: token
        description: auth token
      - in: query
        name: unitofmeasure
        description: unit of meaure, defaults to troy ounces
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Benchmark
      - Pricesrequested
      - Metals
  /api/v{version}/Metals/spot/performance/annual:
    get:
      summary: Get Historical Annual Performance for requested metals
      description: Get historical annual performance for requested metals.
      operationId: ApiV{versionMetalsSpotPerformanceAnnualGet
      x-api-path-slug: apivversionmetalsspotperformanceannual-get
      parameters:
      - in: query
        name: currency
        description: comma separated list of conversion currencies, defaults to USD
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: metals
        description: comma separated list of metals
      - in: query
        name: token
        description: auth token
      - in: query
        name: unitofmeasure
        description: unit of meaure, defaults to troy ounces
      - in: path
        name: version
        description: The requested API version
      - in: query
        name: years
        description: Number of years of history to return
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Annual
      - Performancerequested
      - Metals
  /api/v{version}/Metals/spot/performance:
    get:
      summary: Get Historical Performance for requested metals
      description: Get historical performance for requested metals.
      operationId: ApiV{versionMetalsSpotPerformanceGet
      x-api-path-slug: apivversionmetalsspotperformance-get
      parameters:
      - in: query
        name: currency
        description: comma separated list of conversion currencies, defaults to USD
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: metals
        description: comma separated list of metals
      - in: query
        name: token
        description: auth token
      - in: query
        name: unitofmeasure
        description: unit of meaure, defaults to troy ounces
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Performancerequested
      - Metals
  /api/v{version}/Metals/benchmark/supported:
    get:
      summary: Get list of symbols supported by the benchmark endpoints
      description: Get list of symbols supported by the benchmark endpoints.
      operationId: ApiV{versionMetalsBenchmarkSupportedGet
      x-api-path-slug: apivversionmetalsbenchmarksupported-get
      parameters:
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: token
        description: auth token
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Symbols
      - Supported
      - By
      - Benchmark
      - Endpoints
  /api/v{version}/Metals/spot/ratio/summary:
    get:
      summary: Get latest Spot Summary for requested metal ratios
      description: Get latest spot summary for requested metal ratios.
      operationId: ApiV{versionMetalsSpotRatioSummaryGet
      x-api-path-slug: apivversionmetalsspotratiosummary-get
      parameters:
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: pairs
        description: comma separated list of metal pairs
      - in: query
        name: token
        description: auth token
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - Latest
      - Spot
      - Summaryrequested
      - Metal
      - Ratios
  /api/v{version}/Metals/spot/supported:
    get:
      summary: Get list of symbols supported by the spot endpoints
      description: Get list of symbols supported by the spot endpoints.
      operationId: ApiV{versionMetalsSpotSupportedGet
      x-api-path-slug: apivversionmetalsspotsupported-get
      parameters:
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: token
        description: auth token
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Symbols
      - Supported
      - By
      - Spot
      - Endpoints
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---