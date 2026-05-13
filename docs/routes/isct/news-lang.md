# Institute of Science Tokyo - News

## Coverage
`index-only`

## Route
- Namespace: `isct`
- Namespace Name: `Institute of Science Tokyo`
- Route Path: `/news/:lang`
- Route Name: `News`
- Example: `/isct/news/ja`
- URL: `isct.ac.jp`
- Language: `ja`
- Categories: `university`
- Maintainers: `catyyy`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/isct/news.ts')`

## Description
_None_

## Parameters
- `lang`: language, could be ja or en


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
  - `www.isct.ac.jp/:lang/news`
- `target`: `/news/:lang`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/isct/news/ja",
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
    "catyyy"
  ],
  "module": "() => import('@/routes/isct/news.ts')",
  "name": "News",
  "parameters": {
    "lang": "language, could be ja or en"
  },
  "path": "/news/:lang",
  "radar": [
    {
      "source": [
        "www.isct.ac.jp/:lang/news"
      ],
      "target": "/news/:lang"
    }
  ]
}
```
