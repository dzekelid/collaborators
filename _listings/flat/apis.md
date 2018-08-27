---
name: Flat
x-slug: flat
description: Whether youre a beginner or a professional composer, our user-friendly
  music composition software gives you all the tools that you need to make your own
  sheet music. You can write, listen, share and discover music scores right in your
  web browser on any device
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Collaborators
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/flat/apis.md
specificationVersion: "0.14"
apis:
- name: Flat - List the collaborators
  x-api-slug: scoresscorecollaborators-get
  description: |-
    This API call will list the different collaborators of a score and their rights on the document. The returned list will at least contain the owner of the document.

    Collaborators can be a single user (the object `user` will be populated) or a group (the object `group` will be populated).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2
  tags: API Provider, Music, Profiles, Relative Data, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/flat/scoresscorecollaborators-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/flat/scoresscorecollaborators-get-openapi.md
- name: Flat - Add a new collaborator
  x-api-slug: scoresscorecollaborators-post
  description: |-
    Share a score with a single user or a group. This API call allows to add, invite and update the collaborators of a document.
    - To add an existing Flat user to the document, specify its unique identifier in the `user` property.
    - To invite an external user to the document, specify its email in the `userEmail` property.
    - To add a Flat group to the document, specify its unique identifier in the `group` property.
    - To update an existing collaborator, process the same request with different rights.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2
  tags: API Provider, Music, Profiles, Relative Data, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/flat/scoresscorecollaborators-post-openapi.md
- name: Flat - Delete a collaborator
  x-api-slug: scoresscorecollaboratorscollaborator-delete
  description: Remove the specified collaborator from the score
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2
  tags: API Provider, Music, Profiles, Relative Data, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/flat/scoresscorecollaboratorscollaborator-delete-openapi.md
- name: Flat - Get a collaborator
  x-api-slug: scoresscorecollaboratorscollaborator-get
  description: Get the information about a collaborator (User or Group).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2
  tags: API Provider, Music, Profiles, Relative Data, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/flat/scoresscorecollaboratorscollaborator-get-openapi.md
- name: Flat - Add a new collaborator
  x-api-slug: scoresscorecollaborators-post
  description: |-
    Share a score with a single user or a group. This API call allows to add, invite and update the collaborators of a document.
    - To add an existing Flat user to the document, specify its unique identifier in the `user` property.
    - To invite an external user to the document, specify its email in the `userEmail` property.
    - To add a Flat group to the document, specify its unique identifier in the `group` property.
    - To update an existing collaborator, process the same request with different rights.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2
  tags: API Provider, Music, Profiles, Relative Data, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/flat/scoresscorecollaborators-post-openapi.md
- name: Flat - Delete a collaborator
  x-api-slug: scoresscorecollaboratorscollaborator-delete
  description: Remove the specified collaborator from the score
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2
  tags: API Provider, Music, Profiles, Relative Data, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/flat/scoresscorecollaboratorscollaborator-delete-openapi.md
- name: Flat - Get a collaborator
  x-api-slug: scoresscorecollaboratorscollaborator-get
  description: Get the information about a collaborator (User or Group).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2
  tags: API Provider, Music, Profiles, Relative Data, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/flat/scoresscorecollaboratorscollaborator-get-openapi.md
- name: Flat - Get a collaborator
  x-api-slug: scoresscorecollaboratorscollaborator-get
  description: Get the information about a collaborator (User or Group).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2
  tags: API Provider, Music, Profiles, Relative Data, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/flat/scoresscorecollaboratorscollaborator-get-openapi.md
- name: Flat - Delete a collaborator
  x-api-slug: scoresscorecollaboratorscollaborator-delete
  description: Remove the specified collaborator from the score
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2
  tags: API Provider, Music, Profiles, Relative Data, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/flat/scoresscorecollaboratorscollaborator-delete-openapi.md
- name: Flat - Add a new collaborator
  x-api-slug: scoresscorecollaborators-post
  description: |-
    Share a score with a single user or a group. This API call allows to add, invite and update the collaborators of a document.
    - To add an existing Flat user to the document, specify its unique identifier in the `user` property.
    - To invite an external user to the document, specify its email in the `userEmail` property.
    - To add a Flat group to the document, specify its unique identifier in the `group` property.
    - To update an existing collaborator, process the same request with different rights.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2
  tags: API Provider, Music, Profiles, Relative Data, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborators/master/_listings/flat/scoresscorecollaborators-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://fitbit.api.gallery.streamdata.io
- type: x-api-stack
  url: http://flat.stack.network
- type: x-developer
  url: https://flat.io/developers
- type: x-embeddable
  url: https://flat.io/developers/embed
- type: x-github
  url: https://github.com/FlatIO
- type: x-pricing
  url: https://flat.io/pricing
- type: x-privacy-policy
  url: https://flat.io/help/en/policies/#coppa-and-ferpa-compliance
- type: x-support
  url: https://flat.io/help
- type: x-twitter
  url: https://twitter.com/flat_io
- type: x-website
  url: http://flat.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---