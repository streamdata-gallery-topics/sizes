swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/collections/{collectionName}/collectionSize:
    get:
      summary: Return the size of a collection.
      description: |-
        Returns the size of the specified collection to decide whether to use the whole collection for spatial query
        or not.
      operationId: returns-the-size-of-the-specified-collection-to-decide-whether-to-use-the-whole-collection-for-spati
      x-api-path-slug: v1collectionscollectionnamecollectionsize-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Return
      - Size
      - Of
      - Collection