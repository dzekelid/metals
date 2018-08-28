---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global Metals Get Latest Historical Metal Quote
  description: Get historical metal quote by a given time.
  version: 1.0.0
host: globalmetals.xignite.com
basePath: xGlobalMetals.json/XigniteGlobalMetals
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ListMetals:
    get:
      summary: List Metals
      description: List all Metals.
      operationId: ListMetals
      x-api-path-slug: listmetals-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - List
      - Metals
  /GetRealTimeMetalQuotes:
    get:
      summary: Get Real Time Metal Quotes
      description: Get real time exchange rate.
      operationId: GetRealTimeMetalQuotes
      x-api-path-slug: getrealtimemetalquotes-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Real
      - Time
      - Metal
      - Quotes
  /GetHistoricalMetalQuotes:
    get:
      summary: Get Historical Metal Quotes
      description: Get cross sectional historical metal quotes at a given time.
      operationId: GetHistoricalMetalQuotes
      x-api-path-slug: gethistoricalmetalquotes-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Historical
      - Metal
      - Quotes
  /GetRealTimeMetalQuote:
    get:
      summary: Get Real Time Metal Quote
      description: Get real time metal quote.
      operationId: GetRealTimeMetalQuote
      x-api-path-slug: getrealtimemetalquote-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Real
      - Time
      - Metal
      - Quote
  /GetRealTimeExtendedMetalQuote:
    get:
      summary: Get Real Time Extended Metal Quote
      description: Get real time extended metal quote.
      operationId: GetRealTimeExtendedMetalQuote
      x-api-path-slug: getrealtimeextendedmetalquote-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Real
      - Time
      - Extended
      - Metal
      - Quote
  /GetHistoricalMetalQuote:
    get:
      summary: Get Historical Metal Quote
      description: Get historical metal quote at a given time.
      operationId: GetHistoricalMetalQuote
      x-api-path-slug: gethistoricalmetalquote-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Historical
      - Metal
      - Quote
  /GetLatestHistoricalMetalQuote:
    get:
      summary: Get Latest Historical Metal Quote
      description: Get historical metal quote by a given time.
      operationId: GetLatestHistoricalMetalQuote
      x-api-path-slug: getlatesthistoricalmetalquote-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Latest
      - Historical
      - Metal
      - Quote
  /GetLatestHistoricalMetalQuotes:
    get:
      summary: Get Latest Historical Metal Quotes
      description: Get cross sectional historical metal quotes by a given time.
      operationId: GetLatestHistoricalMetalQuotes
      x-api-path-slug: getlatesthistoricalmetalquotes-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Latest
      - Historical
      - Metal
      - Quotes
  /GetHistoricalMetalQuotesRange:
    get:
      summary: Get Historical Metal Quotes Range
      description: Get historical metal quotes time series.
      operationId: GetHistoricalMetalQuotesRange
      x-api-path-slug: gethistoricalmetalquotesrange-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Historical
      - Metal
      - Quotes
      - Range
  /GetLondonHistoricalMetalQuotesRange:
    get:
      summary: Get London Historical Metal Quotes Range
      description: Get historical metal quotes based on Legacy London spot prices.
      operationId: GetLondonHistoricalMetalQuotesRange
      x-api-path-slug: getlondonhistoricalmetalquotesrange-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - London
      - Historical
      - Metal
      - Quotes
      - Range
  /GetBaseMetalPrice:
    get:
      summary: Get Base Metal Price
      description: Get base metal price.
      operationId: GetBaseMetalPrice
      x-api-path-slug: getbasemetalprice-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Base
      - Metal
      - Price
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