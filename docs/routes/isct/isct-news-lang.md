# Institute of Science Tokyo - News

## Coverage
`index-only`

## Route
- Namespace: `isct`
- Namespace Name: `Institute of Science Tokyo`
- Route Path: `/isct/news/:lang`
- Route Name: `News`
- Example: `/isct/news/ja`
- URL: `isct.ac.jp`
- Language: `_None_`
- Categories: `university`
- Maintainers: `catyyy`
- Source Location: `news.ts`
- Source Module: `_None_`

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
  "heat": 3,
  "location": "news.ts",
  "maintainers": [
    "catyyy"
  ],
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
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "ISCT News - ja - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79365445591242752",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.isct.ac.jp/ja/news",
      "title": "ISCT News - ja",
      "type": "feed",
      "url": "rsshub://isct/news/ja"
    }
  ]
}
```
