# Docker Hub - Image New Build

## Coverage
`index-only`

## Route
- Namespace: `dockerhub`
- Namespace Name: `Docker Hub`
- Route Path: `/build/:owner/:image/:tag?`
- Route Name: `Image New Build`
- Example: `/dockerhub/build/diygod/rsshub/latest`
- URL: `hub.docker.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `HenryQW`
- Source Location: `build.ts`
- Source Module: `() => import('@/routes/dockerhub/build.ts')`

## Description
_None_

## Parameters
- `owner`: Image owner, the owner of the official image fills in the library, for example: /dockerhub/build/library/mysql
- `image`: Image name
- `tag`: {"default": "latest", "description": "Image tag"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/dockerhub/build/diygod/rsshub/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "build.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/dockerhub/build.ts')",
  "name": "Image New Build",
  "parameters": {
    "image": "Image name",
    "owner": "Image owner, the owner of the official image fills in the library, for example: /dockerhub/build/library/mysql",
    "tag": {
      "default": "latest",
      "description": "Image tag"
    }
  },
  "path": "/build/:owner/:image/:tag?",
  "view": 5
}
```
