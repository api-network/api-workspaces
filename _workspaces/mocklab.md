---
name: MockLab
description: <p>MockLab helps teams ship better apps faster by mocking APIs that aren't
  ready, don't have a reliable sandbox or have high usage charges. Keep building and
  testing when the APIs you use aren't ready. Ship more robust systems by simulating
  edge cases and faults. Performance testing without large 3rd party bills. Simulate
  stateful behaviour in your mocked API using a simple finite state machine model.
  Dynamically render responses using the Handlebars templating language. Craft your
  simulation using the friendly, no-code UI or go fully automated with the 100% WireMock-compatible
  API. Capture traffic to another API, then play it back from MockLab. Mock the unfinished
  parts of the API and proxy the rest straight through to the real thing. Test your
  app to destruction by injecting delays, dropped connections, drip-drip responses
  and corrupt HTTP payloads. All the power and flexibility you need for pain-free
  testing.</p>
image: http://kinlane-productions2.s3.amazonaws.com/api-evangelist-site/company/logos/Mocklab_Logo_4x.png
tags:
- mocking
- virtualizations
created: "2021-01-03"
modified: "2021-01-03"
url: https://raw.githubusercontent.com/api-evangelist/mocklab/master/apis.json
specificationVersion: "0.14"
apis:
- name: WireMock
  description: ~
  image: http://kinlane-productions2.s3.amazonaws.com/api-evangelist-site/company/logos/Mocklab_Logo_4x.png
  humanURL: http://get.mocklab.io
  baseURL: http://get.mocklab.io
  tags: []
  properties:
  - type: x-openapi
    url: https://raw.githubusercontent.com/api-evangelist/mocklab/master/wiremock-openapi.json
  - type: x-openapi
    url: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/openapis/wiremock.json
  - type: x-postman-collecction
    url: https://raw.githubusercontent.com/api-evangelist/mocklab/master/wiremock-postman-collection.json
include: []
x-common:
- type: Website
  url: http://get.mocklab.io
- type: Crunchbase
  url: https://crunchbase.com/organization/mocklab
- type: Documentation
  url: http://docs.mocklab.io/docs/getting-started/
- type: Pricing
  url: http://get.mocklab.io/pricing/
- type: Twitter
  url: https://twitter.com/TomAkehurst
- type: Website
  url: https://get.mocklab.io
- type: x-screenshot
  url: http://kinlane-productions2.s3.amazonaws.com/mocklab.jpg
- type: x-workspace
  url: https://www.postman.com/api-evangelist/workspace/mocklab/overview
...
