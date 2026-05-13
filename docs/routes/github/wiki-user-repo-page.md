# GitHub - Wiki History

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/wiki/:user/:repo/:page?`
- Route Name: `Wiki History`
- Example: `/github/wiki/flutter/flutter/Roadmap`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `wiki.ts`
- Source Module: `() => import('@/routes/github/wiki.ts')`

## Description
_None_

## Parameters
- `user`: User / Org name
- `repo`: Repo name
- `page`: Page slug, can be found in URL, empty means Home


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
  - `github.com/:user/:repo/wiki/:page/_history`
  - `github.com/:user/:repo/wiki/:page`
  - `github.com/:user/:repo/wiki/_history`
  - `github.com/:user/:repo/wiki`
- `target`: `/wiki/:user/:repo/:page`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/wiki/flutter/flutter/Roadmap",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "wiki.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/github/wiki.ts')",
  "name": "Wiki History",
  "parameters": {
    "page": "Page slug, can be found in URL, empty means Home",
    "repo": "Repo name",
    "user": "User / Org name"
  },
  "path": "/wiki/:user/:repo/:page?",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/wiki/:page/_history",
        "github.com/:user/:repo/wiki/:page",
        "github.com/:user/:repo/wiki/_history",
        "github.com/:user/:repo/wiki"
      ],
      "target": "/wiki/:user/:repo/:page"
    }
  ]
}
```
