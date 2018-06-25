---
name: GitHub
x-slug: github
description: GitHub brings together the worlds largest community of developers to
  discover, share, and build better software. From open source projects to private
  team repositories, were your all-in-one platform for collaborative development.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
x-kinRank: "10"
x-alexaRank: "64"
tags: Pulls
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/apis.md
specificationVersion: "0.14"
apis:
- name: Github Get Repos Owner Repo Pulls
  x-api-slug: github
  description: List pull requests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls
  tags: Repos, Owner, Repo, Pulls
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopulls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopulls-get-openapi.md
- name: Github Add Repos Owner Repo Pulls
  x-api-slug: github
  description: Create a pull request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls
  tags: Repos, Owner, Repo, Pulls
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopulls-post-openapi.md
- name: Github Get Repos Owner Repo Pulls Comments
  x-api-slug: github
  description: |-
    List comments in a repository.
    By default, Review Comments are ordered by ascending ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/comments
  tags: Repos, Owner, Repo, Pulls, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullscomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullscomments-get-openapi.md
- name: Github Delete Repos Owner Repo Pulls Comments Comment
  x-api-slug: github
  description: Delete a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/comments/{commentId}
  tags: Repos, Owner, Repo, Pulls, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullscommentscommentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullscommentscommentid-delete-openapi.md
- name: Github Get Repos Owner Repo Pulls Comments Comment
  x-api-slug: github
  description: Get a single comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/comments/{commentId}
  tags: Repos, Owner, Repo, Pulls, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullscommentscommentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullscommentscommentid-get-openapi.md
- name: Github Patch Repos Owner Repo Pulls Comments Comment
  x-api-slug: github
  description: Edit a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/comments/{commentId}
  tags: Repos, Owner, Repo, Pulls, Comments, Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullscommentscommentid-patch-openapi.md
- name: Github Get Repos Owner Repo Pulls Number
  x-api-slug: github
  description: Get a single pull request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}
  tags: Repos, Owner, Repo, Pulls, Number
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullsnumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullsnumber-get-openapi.md
- name: Github Patch Repos Owner Repo Pulls Number
  x-api-slug: github
  description: Update a pull request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}
  tags: Repos, Owner, Repo, Pulls, Number
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullsnumber-patch-openapi.md
- name: Github Get Repos Owner Repo Pulls Number Comments
  x-api-slug: github
  description: List comments on a pull request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/comments
  tags: Repos, Owner, Repo, Pulls, Number, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullsnumbercomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullsnumbercomments-get-openapi.md
- name: Github Add Repos Owner Repo Pulls Number Comments
  x-api-slug: github
  description: |-
    Create a comment.
      #TODO Alternative input ( http://developer.github.com/v3/pulls/comments/ )
      description: |
        Alternative Input.
        Instead of passing commit_id, path, and position you can reply to an
        existing Pull Request Comment like this:

            body
               Required string
            in_reply_to
               Required number - Comment id to reply to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/comments
  tags: Repos, Owner, Repo, Pulls, Number, Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullsnumbercomments-post-openapi.md
- name: Github Get Repos Owner Repo Pulls Number Commits
  x-api-slug: github
  description: List commits on a pull request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/commits
  tags: Repos, Owner, Repo, Pulls, Number, Commits
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullsnumbercommits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullsnumbercommits-get-openapi.md
- name: Github Get Repos Owner Repo Pulls Number Files
  x-api-slug: github
  description: List pull requests files.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/files
  tags: Repos, Owner, Repo, Pulls, Number, Files
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullsnumberfiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullsnumberfiles-get-openapi.md
- name: Github Get Repos Owner Repo Pulls Number Merge
  x-api-slug: github
  description: Get if a pull request has been merged.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/merge
  tags: Repos, Owner, Repo, Pulls, Number, Merge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullsnumbermerge-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullsnumbermerge-get-openapi.md
- name: Github Put Repos Owner Repo Pulls Number Merge
  x-api-slug: github
  description: Merge a pull request (Merge Button's)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/merge
  tags: Repos, Owner, Repo, Pulls, Number, Merge
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/reposownerrepopullsnumbermerge-put-openapi.md
- name: Github
  x-api-slug: github
  description: GitHub brings together the worlds largest community of developers to
    discover, share, and build better software. From open source projects to private
    team repositories, were your all-in-one platform for collaborative development.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Pulls
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pulls/master/_listings/github/openapi.md
x-common:
- type: x--net-library
  url: https://github.com/octokit/octokit.net
- type: x-base
  url: https://api.github.com
- type: x-blog
  url: http://github.com/blog
- type: x-blog-rss
  url: https://github.com/blog/subscribe
- type: x-change-log
  url: https://developer.github.com/changes/
- type: x-contact-form
  url: https://github.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/github
- type: x-crunchbase
  url: https://crunchbase.com/organization/github
- type: x-developer
  url: https://developer.github.com/
- type: x-github
  url: https://github.com/github
- type: x-guides
  url: https://developer.github.com/guides/
- type: x-ios-sdk
  url: https://github.com/octokit/octokit.objc
- type: x-pricing
  url: https://github.com/pricing
- type: x-privacy
  url: http://help.github.com/privacy-policy/
- type: x-ruby-library
  url: https://github.com/octokit/octokit.rb
- type: x-security
  url: http://help.github.com/security/
- type: x-status
  url: https://status.github.com/
- type: x-terms-of-service
  url: http://help.github.com/terms-of-service/
- type: x-transparency-report
  url: https://github.com/blog/1987-github-s-2014-transparency-report
- type: x-twitter
  url: https://twitter.com/github
- type: x-webhooks
  url: https://developer.github.com/webhooks/
- type: x-website
  url: https://github.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---