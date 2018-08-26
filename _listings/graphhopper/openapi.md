---
swagger: "2.0"
x-collection-name: GraphHopper
x-complete: 1
info:
  title: Route Optimization
  description: our-route-optimization-api-solves-the-so-called-vehicle-routing-problem-fast--it-calculates-an-optimal-tour-for-a-set-of-vehicles-services-and-constraints
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
  /solution/{jobId}:
    get:
      summary: Return the solution associated to the jobId
      description: This endpoint returns the solution of a large problems. You can
        fetch it with the job_id, you have been sent.
      operationId: getSolution
      x-api-path-slug: solutionjobid-get
      parameters:
      - in: path
        name: jobId
        description: Request solution with jobId
      - in: query
        name: key
        description: your API key
      responses:
        200:
          description: OK
      tags:
      - ""
---