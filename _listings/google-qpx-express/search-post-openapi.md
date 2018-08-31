---
swagger: "2.0"
x-collection-name: Google QPX Express
x-complete: 0
info:
  title: Google QPX Express API Search Flights
  description: Returns a list of flights.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /qpxExpress/v1/trips
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /search:
    post:
      summary: Search Flights
      description: Returns a list of flights.
      operationId: qpxExpress.trips.search
      x-api-path-slug: search-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Flights
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