# Scoop - Apps

## Coverage
`index-only`

## Route
- Namespace: `scoop`
- Namespace Name: `Scoop`
- Route Path: `/apps/:query?`
- Route Name: `Apps`
- Example: `/scoop/apps`
- URL: `scoop.sh`
- Language: `en`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `apps.tsx`
- Source Module: `() => import('@/routes/scoop/apps.tsx')`

## Description
::: tip
To subscribe to [Apps](https://scoop.sh/#/apps?s=2&d=1&n=true&dm=true&o=true), where the source URL is `https://scoop.sh/#/apps?s=2&d=1&n=true&dm=true&o=true`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/scoop/apps/s=2&d=1&n=true&dm=true&o=true`](https://rsshub.app/scoop/apps/s=2&d=1&n=true&dm=true&o=true).
:::

## Parameters
- `query`: {"description": "Query, `s=2&d=1&n=true&dm=true&o=true` by default"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `scoop.sh/#/apps`
  - `scoop.sh`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "::: tip\nTo subscribe to [Apps](https://scoop.sh/#/apps?s=2&d=1&n=true&dm=true&o=true), where the source URL is `https://scoop.sh/#/apps?s=2&d=1&n=true&dm=true&o=true`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/scoop/apps/s=2&d=1&n=true&dm=true&o=true`](https://rsshub.app/scoop/apps/s=2&d=1&n=true&dm=true&o=true).\n:::",
  "example": "/scoop/apps",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "apps.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/scoop/apps.tsx')",
  "name": "Apps",
  "parameters": {
    "query": {
      "description": "Query, `s=2&d=1&n=true&dm=true&o=true` by default"
    }
  },
  "path": "/apps/:query?",
  "radar": [
    {
      "source": [
        "scoop.sh/#/apps",
        "scoop.sh"
      ]
    }
  ],
  "url": "scoop.sh",
  "view": 5
}
```
