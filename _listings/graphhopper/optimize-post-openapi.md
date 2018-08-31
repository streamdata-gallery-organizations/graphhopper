---
swagger: "2.0"
x-collection-name: GraphHopper
x-complete: 0
info:
  title: Route Optimization Solves vehicle routing problems
  description: This endpoint for solving vehicle routing problems, i.e. traveling
    salesman or vehicle routing problems, and returns the solution.
  version: "1.0"
host: graphhopper.com
basePath: /api/1/vrp
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /optimize:
    post:
      summary: Solves vehicle routing problems
      description: This endpoint for solving vehicle routing problems, i.e. traveling
        salesman or vehicle routing problems, and returns the solution.
      operationId: postVrp
      x-api-path-slug: optimize-post
      parameters:
      - in: body
        name: body
        description: Request object that contains the problem to be solved
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: key
        description: your API key
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