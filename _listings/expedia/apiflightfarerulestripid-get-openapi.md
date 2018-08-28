---
swagger: "2.0"
x-collection-name: Expedia
x-complete: 0
info:
  title: Expedia Fare Rules for the trip
  description: Air Fare Rule information of the trip created
  version: 0.0.1
host: apim.expedia.com
basePath: x/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/flight/fareRules/{tripId}:
    get:
      summary: Fare Rules for the trip
      description: Air Fare Rule information of the trip created
      operationId: flights-fareRules
      x-api-path-slug: apiflightfarerulestripid-get
      parameters:
      - in: path
        name: tripId
        description: The trip ID of an existing trip, from /api/flight/trip/create
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Airports
      - Airplanes
      - Airlines
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