---
name: Heroku
x-slug: heroku
description: Heroku is the first and best multi-language cloud application platform,
  or platform-as-a-service. Heroku allows developers to deploy, scale, and manage
  their apps without needing to think about servers or systems administration. Over
  one million applications have been deployed to Heroku.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/211_logo.png
x-kinRank: "8"
x-alexaRank: ""
tags: Collaborators
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/heroku/apis.md
specificationVersion: "0.14"
apis:
- name: Heroku Parameters Application Collaborators
  x-api-slug: heroku
  description: Parameters application collaborators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/211_logo.png
  humanURL: https://www.heroku.com/
  baseURL: https://api.heroku.com////apps/{app}/collaborators
  tags: Parameters, Application, Collaborators
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/heroku/appsappcollaborators-parameters-openapi.md
- name: Heroku Get Application Collaborators
  x-api-slug: heroku
  description: List collaborators for an app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/211_logo.png
  humanURL: https://www.heroku.com/
  baseURL: https://api.heroku.com////apps/{app}/collaborators
  tags: Application, Collaborators
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/heroku/appsappcollaborators-get-openapi.md
- name: Heroku Parameters Application Collaborators Email
  x-api-slug: heroku
  description: Parameters application collaborators email.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/211_logo.png
  humanURL: https://www.heroku.com/
  baseURL: https://api.heroku.com////apps/{app}/collaborators/{email}
  tags: Parameters, Application, Collaborators, Email
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/heroku/appsappcollaboratorsemail-parameters-openapi.md
- name: Heroku Delete Application Collaborators Email
  x-api-slug: heroku
  description: Delete application collaborators email.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/211_logo.png
  humanURL: https://www.heroku.com/
  baseURL: https://api.heroku.com////apps/{app}/collaborators/{email}
  tags: Application, Collaborators, Email
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/heroku/appsappcollaboratorsemail-delete-openapi.md
- name: Heroku
  x-api-slug: heroku
  description: Learn about building, deploying and managing your apps on Heroku.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/211_logo.png
  humanURL: https://www.heroku.com/
  baseURL: https://api.heroku.com//
  tags: Collaborators
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/heroku/openapi.md
x-common:
- type: x-base
  url: https://api.heroku.com
- type: x-blog
  url: https://blog.heroku.com/
- type: x-blog-rss
  url: http://feeds2.feedburner.com/heroku
- type: x-command-line-interface
  url: https://devcenter.heroku.com/articles/heroku-command
- type: x-crunchbase
  url: http://www.crunchbase.com/company/heroku
- type: x-developer
  url: https://devcenter.heroku.com/
- type: x-getting-started
  url: https://devcenter.heroku.com/start
- type: x-github
  url: https://github.com/heroku
- type: x-issues
  url: https://status.heroku.com/incidents
- type: x-java-library
  url: https://devcenter.heroku.com/categories/java
- type: x-nodejs
  url: https://devcenter.heroku.com/categories/nodejs
- type: x-php-library
  url: https://devcenter.heroku.com/categories/php
- type: x-pricing
  url: https://www.heroku.com/pricing
- type: x-privacy
  url: https://www.heroku.com/policy/privacy
- type: x-python-library
  url: https://devcenter.heroku.com/categories/python
- type: x-ruby-library
  url: https://devcenter.heroku.com/categories/ruby
- type: x-security
  url: https://www.heroku.com/policy/security
- type: x-selfservice-registration
  url: https://signup.heroku.com/dc
- type: x-support
  url: https://www.heroku.com/support
- type: x-terms-of-service
  url: https://www.heroku.com/policy/tos
- type: x-twitter
  url: https://twitter.com/HerokuDevCenter
- type: x-website
  url: https://www.heroku.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---