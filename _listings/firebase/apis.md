---
name: Firebase
x-slug: firebase
description: Firebase is a mobile platform that gives developers the tools and infrastructure
  to build better apps and grow successful businesses.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
x-kinRank: "9"
x-alexaRank: "1"
tags: Rules
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/firebase/apis.md
specificationVersion: "0.14"
apis:
- name: Firebase List Rules
  x-api-slug: firebase
  description: |-
    List `Ruleset` metadata only and optionally filter the results by Ruleset
    name.

    The full `Source` contents of a `Ruleset` may be retrieved with
    GetRuleset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}////v1/{name}/rulesets
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/firebase/v1namerulesets-get-openapi.md
- name: Firebase Create Rules
  x-api-slug: firebase
  description: |-
    Create a `Ruleset` from `Source`.

    The `Ruleset` is given a unique generated name which is returned to the
    caller. `Source` containing syntactic or semantics errors will result in an
    error response indicating the first error encountered. For a detailed view
    of `Source` issues, use TestRuleset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}////v1/{name}/rulesets
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/firebase/v1namerulesets-post-openapi.md
- name: Firebase Test  Rule
  x-api-slug: firebase
  description: |-
    Test `Source` for syntactic and semantic correctness. Issues present in the
    rules, if any, will be returned to the caller with a description, severity,
    and source location.

    The test method will typically be executed with a developer provided
    `Source`, but if regression testing is desired, this method may be
    executed against a `Ruleset` resource name and the `Source` will be
    retrieved from the persisted `Ruleset`.

    The following is an example of `Source` that permits users to upload images
    to a bucket bearing their user id and matching the correct metadata:

    _*Example*_

        // Users are allowed to subscribe and unsubscribe to the blog.
        service firebase.storage {
          match /users/{userId}/images/{imageName} {
              allow write: if userId == request.userId
                  && (imageName.endsWith('.png') || imageName.endsWith('.jpg'))
                  && resource.mimeType.startsWith('image/')
          }
        }
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}////v1/{name}:test
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/firebase/v1nametest-post-openapi.md
- name: Firebase
  x-api-slug: firebase
  description: Firebase is a mobile platform that gives developers the tools and infrastructure
    to build better apps and grow successful businesses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebase-logo.png
  humanURL: https://Firebase.google.com
  baseURL: https://{project_id].firebaseio.co}//
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/firebase/openapi.md
x-common:
- type: x-website
  url: https://Firebase.google.com
- type: x-blog
  url: https://firebase.googleblog.com/
- type: x-blog-rss
  url: http://firebase.googleblog.com/feeds/posts/default?alt=rss
- type: x-case-studies
  url: https://firebase.google.com/customers/
- type: x-change-log
  url: https://firebase.google.com/support/releases
- type: x-code
  url: https://firebase.google.com/docs/libraries/
- type: x-crunchbase
  url: https://crunchbase.com/organization/google
- type: x-documentation
  url: https://firebase.google.com/docs/
- type: x-faq
  url: https://firebase.google.com/support/faq/
- type: x-forum
  url: https://groups.google.com/forum/#!forum/firebase-talk
- type: x-github
  url: https://github.com/firebase
- type: x-pricing
  url: https://firebase.google.com/pricing/
- type: x-pricing
  url: https://adwords.google.com/home/pricing/
- type: x-slack
  url: https://firebase.community/
- type: x-submit-bug
  url: https://firebase.google.com/support/contact/bugs-features
- type: x-support
  url: https://firebase.google.com/support/
- type: x-twitter
  url: https://twitter.com/Google
- type: x-twitter
  url: https://twitter.com/firebase
- type: x-website
  url: https://firebase.google.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---