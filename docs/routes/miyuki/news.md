# 中島みゆき Official - News

## Coverage
`index-only`

## Route
- Namespace: `miyuki`
- Namespace Name: `中島みゆき Official`
- Route Path: `/news`
- Route Name: `News`
- Example: `/miyuki/news`
- URL: `www.miyuki.jp/s/y10/news/list`
- Language: `ja`
- Categories: `new-media`
- Maintainers: `KarasuShin`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/miyuki/news.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `miyuki.jp`
  - `miyuki.jp/s/y10/news/list`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/miyuki/news",
  "features": {
    "supportRadar": true
  },
  "location": "news.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/miyuki/news.ts')",
  "name": "News",
  "path": "/news",
  "radar": [
    {
      "source": [
        "miyuki.jp",
        "miyuki.jp/s/y10/news/list"
      ],
      "target": "/news"
    }
  ],
  "url": "www.miyuki.jp/s/y10/news/list"
}
```
