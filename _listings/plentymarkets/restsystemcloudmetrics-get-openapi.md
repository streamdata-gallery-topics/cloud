---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Get the cloud metrics for this system
  description: Get the cloud metrics for this system.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/system/cloud/metrics:
    get:
      summary: Get the cloud metrics for this system
      description: Get the cloud metrics for this system.
      operationId: getRestSystemCloudMetrics
      x-api-path-slug: restsystemcloudmetrics-get
      responses:
        2:
          description: Successful response
        200:
          description: OK
      tags:
      - Cloud
      - Metricsthis
      - System
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