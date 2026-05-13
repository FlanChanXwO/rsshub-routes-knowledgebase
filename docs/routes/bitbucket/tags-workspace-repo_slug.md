# Bitbucket - Tags

## Coverage
`index-only`

## Route
- Namespace: `bitbucket`
- Namespace Name: `Bitbucket`
- Route Path: `/tags/:workspace/:repo_slug`
- Route Name: `Tags`
- Example: `/bitbucket/tags/blaze-lib/blaze`
- URL: `bitbucket.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `AuroraDysis`
- Source Location: `tags.ts`
- Source Module: `() => import('@/routes/bitbucket/tags.ts')`

## Description
_None_

## Parameters
- `workspace`: Workspace
- `repo_slug`: Repository


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
    "programming"
  ],
  "example": "/bitbucket/tags/blaze-lib/blaze",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tags.ts",
  "maintainers": [
    "AuroraDysis"
  ],
  "module": "() => import('@/routes/bitbucket/tags.ts')",
  "name": "Tags",
  "parameters": {
    "repo_slug": "Repository",
    "workspace": "Workspace"
  },
  "path": "/tags/:workspace/:repo_slug"
}
```
