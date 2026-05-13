# LastOrigin - News

## Coverage
`index-only`

## Route
- Namespace: `last-origin`
- Namespace Name: `LastOrigin`
- Route Path: `/news`
- Route Name: `News`
- Example: `/last-origin/news`
- URL: `www.last-origin.com`
- Language: `ja`
- Categories: `game`
- Maintainers: `gudezhi`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/last-origin/news.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.last-origin.com/news.html`
  - `www.last-origin.com`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "",
  "example": "/last-origin/news",
  "features": {
    "supportRadar": true
  },
  "location": "news.ts",
  "maintainers": [
    "gudezhi"
  ],
  "module": "() => import('@/routes/last-origin/news.ts')",
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.last-origin.com/news.html",
        "www.last-origin.com"
      ],
      "target": "/news"
    }
  ],
  "url": "www.last-origin.com"
}
```
