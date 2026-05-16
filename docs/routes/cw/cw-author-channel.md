# 天下雜誌 - 作者

## Coverage
`index-only`

## Route
- Namespace: `cw`
- Namespace Name: `天下雜誌`
- Route Path: `/cw/author/:channel`
- Route Name: `作者`
- Example: `/cw/author/57`
- URL: `cw.com.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `author.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `channel`: 作者 ID，可在 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cw.com.tw/author/:channel`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/cw/author/57",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "author.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "作者",
  "parameters": {
    "channel": "作者 ID，可在 URL 中找到"
  },
  "path": "/author/:channel",
  "radar": [
    {
      "source": [
        "cw.com.tw/author/:channel"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "《經濟學人》（The Economist）是一份英國的英文新聞週報，是一本涉及全球政治、經濟、文化、科技等多方面事務的綜合性新聞評論刊物，著重於對這些議題提供深入的分析和評論。 - Powered by RSSHub",
      "errorAt": "2025-05-25T16:19:14.064Z",
      "errorMessage": "page.waitForSelector: Target page, context or browser has been closed\nCall log:\n  - waiting for locator('.caption') to be visible\n  - waiting for locator('.caption')\n    2 × waiting for\" https://www.cw.com.tw/author/57\" navigation to finish...\n      - navigated to \"https://www.cw.com.tw/author/57\"\n\n",
      "id": "69435755254558720",
      "image": "https://cdn-www.cw.com.tw/article/201909/article-5d75f21940867.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.cw.com.tw/author/57",
      "title": "經濟學人｜最新文章｜天下雜誌",
      "type": "feed",
      "url": "rsshub://cw/author/57"
    }
  ]
}
```
