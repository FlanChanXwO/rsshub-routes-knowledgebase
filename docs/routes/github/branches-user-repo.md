# GitHub - Repo Branches

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/branches/:user/:repo`
- Route Name: `Repo Branches`
- Example: `/github/branches/DIYgod/RSSHub`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `max-arnold`
- Source Location: `branches.ts`
- Source Module: `() => import('@/routes/github/branches.ts')`

## Description
_None_

## Parameters
- `user`: User name
- `repo`: Repo name


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
  - `github.com/:user/:repo/branches`
  - `github.com/:user/:repo`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/branches/DIYgod/RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "branches.ts",
  "maintainers": [
    "max-arnold"
  ],
  "module": "() => import('@/routes/github/branches.ts')",
  "name": "Repo Branches",
  "parameters": {
    "repo": "Repo name",
    "user": "User name"
  },
  "path": "/branches/:user/:repo",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/branches",
        "github.com/:user/:repo"
      ]
    }
  ]
}
```
