# Canadian Broadcasting Corporation - News

## Coverage
`index-only`

## Route
- Namespace: `cbc`
- Namespace Name: `Canadian Broadcasting Corporation`
- Route Path: `/topics/:topic?`
- Route Name: `News`
- Example: `/cbc/topics`
- URL: `cbc.ca/news`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `wb14123`
- Source Location: `topics.ts`
- Source Module: `() => import('@/routes/cbc/topics.ts')`

## Description
_None_

## Parameters
- `topic`: Channel,`Top Stories` by default. For secondary channel like `canada/toronto`, use `-` to replace `/`


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
  - `cbc.ca/news`
- `target`: `/topics`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/cbc/topics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topics.ts",
  "maintainers": [
    "wb14123"
  ],
  "module": "() => import('@/routes/cbc/topics.ts')",
  "name": "News",
  "parameters": {
    "topic": "Channel,`Top Stories` by default. For secondary channel like `canada/toronto`, use `-` to replace `/`"
  },
  "path": "/topics/:topic?",
  "radar": [
    {
      "source": [
        "cbc.ca/news"
      ],
      "target": "/topics"
    }
  ],
  "url": "cbc.ca/news"
}
```
