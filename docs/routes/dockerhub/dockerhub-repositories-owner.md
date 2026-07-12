# Docker Hub - Owner Repositories

## Coverage
`index-only`

## Route
- Namespace: `dockerhub`
- Namespace Name: `Docker Hub`
- Route Path: `/dockerhub/repositories/:owner`
- Route Name: `Owner Repositories`
- Example: `/dockerhub/repositories/diygod`
- URL: `hub.docker.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `CaoMeiYouRen`
- Source Location: `repositories.ts`
- Source Module: `_None_`

## Description
List of repositories for an image owner

## Parameters
- `owner`: Image owner


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "List of repositories for an image owner",
  "example": "/dockerhub/repositories/diygod",
  "heat": 2,
  "location": "repositories.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "Owner Repositories",
  "parameters": {
    "owner": "Image owner"
  },
  "path": "/repositories/:owner",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "List of repositories for gravityle - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "202356464034565120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hub.docker.com/r/gravityle",
      "title": "gravityle repositories",
      "type": "feed",
      "url": "rsshub://dockerhub/repositories/gravityle"
    },
    {
      "description": "List of repositories for diygod - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83892100612352000",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hub.docker.com/r/diygod",
      "title": "diygod repositories",
      "type": "feed",
      "url": "rsshub://dockerhub/repositories/diygod"
    }
  ],
  "view": 5
}
```
