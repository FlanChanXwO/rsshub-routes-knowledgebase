# Docker Hub - Image New Tag

## Coverage
`index-only`

## Route
- Namespace: `dockerhub`
- Namespace Name: `Docker Hub`
- Route Path: `/tag/:owner/:image/:limits?`
- Route Name: `Image New Tag`
- Example: `/dockerhub/tag/library/mariadb`
- URL: `hub.docker.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `pseudoyu`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/dockerhub/tag.ts')`

## Description
::: warning
  Use `library` as the `owner` for official images, such as [https://rsshub.app/dockerhub/tag/library/mysql](https://rsshub.app/dockerhub/tag/library/mysql)
:::

## Parameters
- `owner`: Image owner
- `image`: Image name
- `limits`: Tag count, 10 by default


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
  "description": "::: warning\n  Use `library` as the `owner` for official images, such as [https://rsshub.app/dockerhub/tag/library/mysql](https://rsshub.app/dockerhub/tag/library/mysql)\n:::",
  "example": "/dockerhub/tag/library/mariadb",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "module": "() => import('@/routes/dockerhub/tag.ts')",
  "name": "Image New Tag",
  "parameters": {
    "image": "Image name",
    "limits": "Tag count, 10 by default",
    "owner": "Image owner"
  },
  "path": "/tag/:owner/:image/:limits?"
}
```
