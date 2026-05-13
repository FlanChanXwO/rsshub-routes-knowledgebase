# 天下雜誌 - 最新上線

## Coverage
`index-only`

## Route
- Namespace: `cw`
- Namespace Name: `天下雜誌`
- Route Path: `/cw/today`
- Route Name: `最新上線`
- Example: `/cw/today`
- URL: `cw.com.tw/today`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `today.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cw.com.tw/today`
  - `cw.com.tw/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/cw/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 38,
  "location": "today.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "最新上線",
  "parameters": {},
  "path": "/today",
  "radar": [
    {
      "source": [
        "cw.com.tw/today",
        "cw.com.tw/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "天下雜誌每日精選財經、國際、管理、教育、經濟學人、評論、時尚，深入解讀世界脈動。 - Powered by RSSHub",
      "errorAt": "2025-05-25T17:41:59.652Z",
      "errorMessage": "page.waitForSelector: Target page, context or browser has been closed\nCall log:\n  - waiting for locator('.caption') to be visible\n  - waiting for locator('.caption')\n    2 × waiting for\" https://www.cw.com.tw/today\" navigation to finish...\n      - navigated to \"https://www.cw.com.tw/today\"\n\n",
      "id": "60230426333120512",
      "image": "https://www.cw.com.tw/assets_new/img/fbshare.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.cw.com.tw/today",
      "title": "今日最新－天下雜誌",
      "type": "feed",
      "url": "rsshub://cw/today"
    }
  ],
  "url": "cw.com.tw/today"
}
```
