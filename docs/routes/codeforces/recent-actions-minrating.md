# Codeforces - Recent actions

## Coverage
`index-only`

## Route
- Namespace: `codeforces`
- Namespace Name: `Codeforces`
- Route Path: `/recent-actions/:minrating?`
- Route Name: `Recent actions`
- Example: `/codeforces/recent-actions`
- URL: `codeforces.com/recent-actions`
- Language: `en`
- Categories: `programming`
- Maintainers: `None`
- Source Location: `recent-actions.ts`
- Source Module: `() => import('@/routes/codeforces/recent-actions.ts')`

## Description
_None_

## Parameters
- `minrating`: The minimum blog/comment rating required. Default: 1


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
  - `codeforces.com/recent-actions`
- `target`: `/recent-actions`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/codeforces/recent-actions",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "recent-actions.ts",
  "maintainers": [],
  "module": "() => import('@/routes/codeforces/recent-actions.ts')",
  "name": "Recent actions",
  "parameters": {
    "minrating": "The minimum blog/comment rating required. Default: 1"
  },
  "path": "/recent-actions/:minrating?",
  "radar": [
    {
      "source": [
        "codeforces.com/recent-actions"
      ],
      "target": "/recent-actions"
    }
  ],
  "url": "codeforces.com/recent-actions"
}
```
