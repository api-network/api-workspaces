---
name: Wikipedia
description: Wikipedia is a free online encyclopedia, created and edited by volunteers
  around the world and hosted by the Wikimedia Foundation.
image: http://kinlane-productions2.s3.amazonaws.com/screen-capture-api/144-wikipedia.jpg
tags:
- content
- imports
- wiki
created: "2021-01-03"
modified: "2021-01-03"
url: https://raw.githubusercontent.com/api-evangelist/wikipedia/master/apis.json
specificationVersion: "0.14"
apis:
- name: Wikipedia
  description: ~
  image: http://kinlane-productions2.s3.amazonaws.com/screen-capture-api/144-wikipedia.jpg
  humanURL: http://wikipedia.org
  baseURL: http://wikipedia.org
  tags: []
  properties:
  - type: x-openapi
    url: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/openapis/wikipedia.json
  - type: x-postman-collecction
    url: https://raw.githubusercontent.com/api-evangelist/wikipedia/master/wikipedia-postman-collection.json
include: []
x-common:
- type: Base
  url: http://en.wikipedia.org/w/api.php
- type: Crunchbase
  url: https://crunchbase.com/organization/wikipedia
- type: Crunchbase
  url: http://www.crunchbase.com/company/wikipedia
- type: Developers
  url: http://www.mediawiki.org/wiki/API
- type: Github
  url: https://github.com/Wikipedia
- type: Swagger - Original
  url: http://rest.wikimedia.org/en.wikipedia.org/v1/?spec
- type: Transparency Report
  url: https://transparency.wikimedia.org/
- type: Twitter
  url: https://twitter.com/wikipedia
- type: Website
  url: https://www.wikipedia.org/
- type: Website
  url: http://wikipedia.org
- type: x-screenshot
  url: http://kinlane-productions2.s3.amazonaws.com/wikipedia.jpg
- type: x-workspace
  url: https://www.postman.com/api-evangelist/workspace/wikipedia/overview
...
