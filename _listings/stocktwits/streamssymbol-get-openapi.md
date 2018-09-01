---
swagger: "2.0"
x-collection-name: StockTwits
x-complete: 0
info:
  title: Stocktwits Streams by Symbol
  version: 1.0.0
  description: Returns the most recent 30 messages for the specified symbol. Includes
    symbol object in response.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  streams/symbol:
    get:
      summary: Streams by Symbol
      description: Returns the most recent 30 messages for the specified symbol. Includes
        symbol object in response.
      operationId: ""
      x-api-path-slug: streamssymbol-get
      responses:
        200:
          description: OK
      tags:
      - ""
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