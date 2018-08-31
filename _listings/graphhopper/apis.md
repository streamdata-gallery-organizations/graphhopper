---
name: GraphHopper
x-slug: graphhopper
description: Use our web services to add route planning, navigation and traffic aware
  route optimization to your application in the food delivery industry or for traveling
  salesmen. We help you to optimize the routes in your logistics, GIS or real estate
  software.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/graphhopper-logo-small-300x51.png
x-kinRank: "7"
x-alexaRank: "0"
tags: GraphHopper
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/graphhopper/master/_listings/graphhopper/apis.md
specificationVersion: "0.14"
apis:
- name: Route Optimization - Solves vehicle routing problems
  x-api-slug: optimize-post
  description: This endpoint for solving vehicle routing problems, i.e. traveling
    salesman or vehicle routing problems, and returns the solution.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/graphhopper-logo-small-300x51.png
  humanURL: https://graphhopper.com
  baseURL: https://graphhopper.com//api/1/vrp
  tags: Travel, Routes, Relative Data, Service API, General Data, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/graphhopper/master/_listings/graphhopper/optimize-post-openapi.md
- name: Route Optimization - Return the solution associated to the jobId
  x-api-slug: solutionjobid-get
  description: This endpoint returns the solution of a large problems. You can fetch
    it with the job_id, you have been sent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/graphhopper-logo-small-300x51.png
  humanURL: https://graphhopper.com
  baseURL: https://graphhopper.com//api/1/vrp
  tags: Travel, Routes, Relative Data, Service API, General Data, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/graphhopper/master/_listings/graphhopper/solutionjobid-get-openapi.md
x-common:
- type: x-website
  url: https://graphhopper.com
- type: x-api-gallery
  url: http://gotomeeting.api.gallery.streamdata.io
- type: x-api-stack
  url: http://graphhopper.stack.network
- type: x-blog
  url: https://www.graphhopper.com/blog/
- type: x-developer
  url: https://www.graphhopper.com/developers/
- type: x-documentation
  url: https://graphhopper.com/api/1/docs/
- type: x-faq
  url: https://graphhopper.com/api/1/docs/FAQ/
- type: x-forum
  url: https://discuss.graphhopper.com/
- type: x-github
  url: https://github.com/graphhopper
- type: x-pricing
  url: https://www.graphhopper.com/pricing/
- type: x-twitter
  url: https://twitter.com/graphhopper
- type: x-website
  url: http://graphhopper.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---