# 中国人民银行 - 广东省内城市预警信号

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `中国人民银行`
- Route Path: `/gov/guangdong/tqyb/sncsyjxh`
- Route Name: `广东省内城市预警信号`
- Example: `/gov/guangdong/tqyb/sncsyjxh`
- URL: `www.tqyb.com.cn/gz/weatherAlarm/otherCity/`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `Fatpandac`
- Source Location: `guangdong/tqyb/sncsyjxh.tsx`
- Source Module: `_None_`

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
  - `www.tqyb.com.cn/gz/weatherAlarm/otherCity/`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/gov/guangdong/tqyb/sncsyjxh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "guangdong/tqyb/sncsyjxh.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "广东省内城市预警信号",
  "parameters": {},
  "path": "/guangdong/tqyb/sncsyjxh",
  "radar": [
    {
      "source": [
        "www.tqyb.com.cn/gz/weatherAlarm/otherCity/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "广东省内城市预警信号 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62330474444404737",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.tqyb.com.cn/gz/weatherAlarm/otherCity/",
      "title": "广东省内城市预警信号",
      "type": "feed",
      "url": "rsshub://gov/guangdong/tqyb/sncsyjxh"
    }
  ],
  "url": "www.tqyb.com.cn/gz/weatherAlarm/otherCity/"
}
```
