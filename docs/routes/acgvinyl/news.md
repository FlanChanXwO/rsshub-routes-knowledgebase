# ACG Vinyl - 黑胶 - News

## Coverage
`index-only`

## Route
- Namespace: `acgvinyl`
- Namespace Name: `ACG Vinyl - 黑胶`
- Route Path: `/news`
- Route Name: `News`
- Example: `/news`
- URL: `www.acgvinyl.com/col.jsp?id=103`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `williamgateszhao`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/acgvinyl/news.ts')`

## Description
_None_

## Parameters
_None_


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
  - `www.acgvinyl.com`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "williamgateszhao"
  ],
  "module": "() => import('@/routes/acgvinyl/news.ts')",
  "name": "News",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.acgvinyl.com"
      ],
      "target": "/news"
    }
  ],
  "url": "www.acgvinyl.com/col.jsp?id=103",
  "zh": {
    "name": "黑胶新闻"
  }
}
```
