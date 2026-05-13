# 得到 - 得到文章

## Coverage
`index-only`

## Route
- Namespace: `dedao`
- Namespace Name: `得到`
- Route Path: `/dedao/articles/:id?`
- Route Name: `得到文章`
- Example: `/articles/9`
- URL: `www.igetget.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Jacky-Chen-Pro`
- Source Location: `articles.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 文章类型 ID，8 为得到头条，9 为得到精选，默认为 8


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
  - `igetget.com`
- `target`: `/articles/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/articles/9",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 487,
  "location": "articles.ts",
  "maintainers": [
    "Jacky-Chen-Pro"
  ],
  "name": "得到文章",
  "parameters": {
    "id": "文章类型 ID，8 为得到头条，9 为得到精选，默认为 8"
  },
  "path": "/articles/:id?",
  "radar": [
    {
      "source": [
        "igetget.com"
      ],
      "target": "/articles/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 404 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "得到文章 - 精选 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74230696245769216",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.igetget.com/",
      "title": "得到文章 - 精选",
      "type": "feed",
      "url": "rsshub://dedao/articles/9"
    },
    {
      "description": "得到文章 - 头条 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74230627866364928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.igetget.com/",
      "title": "得到文章 - 头条",
      "type": "feed",
      "url": "rsshub://dedao/articles/8"
    }
  ],
  "url": "www.igetget.com"
}
```
