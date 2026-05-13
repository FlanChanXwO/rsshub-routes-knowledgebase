# X-MOL - News

## Coverage
`index-only`

## Route
- Namespace: `x-mol`
- Namespace Name: `X-MOL`
- Route Path: `/news/:tag?`
- Route Name: `News`
- Example: `/x-mol/news/3`
- URL: `x-mol.com/news/index`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `cssxsh`
- Source Location: `news.tsx`
- Source Module: `() => import('@/routes/x-mol/news.tsx')`

## Description
_None_

## Parameters
- `tag`: Tag number, can be obtained from news list URL. Empty value means news index.


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
  - `x-mol.com/news/index`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/x-mol/news/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.tsx",
  "maintainers": [
    "cssxsh"
  ],
  "module": "() => import('@/routes/x-mol/news.tsx')",
  "name": "News",
  "parameters": {
    "tag": "Tag number, can be obtained from news list URL. Empty value means news index."
  },
  "path": "/news/:tag?",
  "radar": [
    {
      "source": [
        "x-mol.com/news/index"
      ],
      "target": "/news"
    }
  ],
  "url": "x-mol.com/news/index"
}
```
