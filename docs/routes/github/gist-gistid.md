# GitHub - Gist Commits

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/gist/:gistId`
- Route Name: `Gist Commits`
- Example: `/github/gist/d2c152bb7179d07015f336b1a0582679`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `gist.ts`
- Source Module: `() => import('@/routes/github/gist.ts')`

## Description
_None_

## Parameters
- `gistId`: Gist ID


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
  - `gist.github.com/:owner/:gistId/revisions`
  - `gist.github.com/:owner/:gistId/stargazers`
  - `gist.github.com/:owner/:gistId/forks`
  - `gist.github.com/:owner/:gistId`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/gist/d2c152bb7179d07015f336b1a0582679",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gist.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/github/gist.ts')",
  "name": "Gist Commits",
  "parameters": {
    "gistId": "Gist ID"
  },
  "path": "/gist/:gistId",
  "radar": [
    {
      "source": [
        "gist.github.com/:owner/:gistId/revisions",
        "gist.github.com/:owner/:gistId/stargazers",
        "gist.github.com/:owner/:gistId/forks",
        "gist.github.com/:owner/:gistId"
      ]
    }
  ]
}
```
