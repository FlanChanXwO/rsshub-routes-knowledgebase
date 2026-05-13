# Bitbucket - Commits

## Coverage
`index-only`

## Route
- Namespace: `bitbucket`
- Namespace Name: `Bitbucket`
- Route Path: `/commits/:workspace/:repo_slug`
- Route Name: `Commits`
- Example: `/bitbucket/commits/blaze-lib/blaze`
- URL: `bitbucket.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `AuroraDysis`
- Source Location: `commits.ts`
- Source Module: `() => import('@/routes/bitbucket/commits.ts')`

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
### Rule 1
- `source`:
  - `bitbucket.com/commits/:workspace/:repo_slug`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/bitbucket/commits/blaze-lib/blaze",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "commits.ts",
  "maintainers": [
    "AuroraDysis"
  ],
  "module": "() => import('@/routes/bitbucket/commits.ts')",
  "name": "Commits",
  "parameters": {
    "repo_slug": "Repository",
    "workspace": "Workspace"
  },
  "path": "/commits/:workspace/:repo_slug",
  "radar": [
    {
      "source": [
        "bitbucket.com/commits/:workspace/:repo_slug"
      ]
    }
  ]
}
```
