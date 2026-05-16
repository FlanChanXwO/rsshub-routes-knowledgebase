# NL Times - News

## Coverage
`index-only`

## Route
- Namespace: `nltimes`
- Namespace Name: `NL Times`
- Route Path: `/nltimes/news/:category?`
- Route Name: `News`
- Example: `/nltimes/news/top-stories`
- URL: `nltimes.nl`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Hivol`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| Top Stories (default) | Health | Crime | Politics | Business | Tech | Culture | Sports | Weird | 1-1-2 |
| --------------------- | ------ | ----- | -------- | -------- | ---- | ------- | ------ | ----- | ----- |
| top-stories           | health | crime | politics | business | tech | culture | sports | weird | 1-1-2 |

## Parameters
- `category`: category


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
  - `nltimes.nl/categories/:category`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Top Stories (default) | Health | Crime | Politics | Business | Tech | Culture | Sports | Weird | 1-1-2 |\n| --------------------- | ------ | ----- | -------- | -------- | ---- | ------- | ------ | ----- | ----- |\n| top-stories           | health | crime | politics | business | tech | culture | sports | weird | 1-1-2 |",
  "example": "/nltimes/news/top-stories",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "news.ts",
  "maintainers": [
    "Hivol"
  ],
  "name": "News",
  "parameters": {
    "category": "category"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "nltimes.nl/categories/:category"
      ],
      "target": "/news/:category"
    }
  ],
  "topFeeds": [
    {
      "description": "NL Times -- Top Stories - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59769816692412416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nltimes.nl/top-stories",
      "title": "NL Times -- Top Stories",
      "type": "feed",
      "url": "rsshub://nltimes/news/top-stories"
    },
    {
      "description": "NL Times -- Top Stories - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "187417269928465408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nltimes.nl/top-stories",
      "title": "NL Times -- Top Stories",
      "type": "feed",
      "url": "rsshub://nltimes/news"
    }
  ]
}
```
