# 上海市人民政府 - 长沙市人民政府

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `上海市人民政府`
- Route Path: `/gov/hunan/changsha/major-email`
- Route Name: `长沙市人民政府`
- Example: `/gov/hunan/changsha/major-email`
- URL: `wlwz.changsha.gov.cn/webapp/cs2020/email/*`
- Language: `_None_`
- Categories: `government`
- Maintainers: `shansing`
- Source Location: `hunan/changsha/major-email.ts`
- Source Module: `_None_`

## Description
#### 市长信箱 {#hu-nan-sheng-ren-min-zheng-fu-chang-sha-shi-ren-min-zheng-fu-shi-zhang-xin-xiang}

可能仅限中国大陆服务器访问，以实际情况为准。

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
  - `wlwz.changsha.gov.cn/webapp/cs2020/email/*`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "#### 市长信箱 {#hu-nan-sheng-ren-min-zheng-fu-chang-sha-shi-ren-min-zheng-fu-shi-zhang-xin-xiang}\n\n可能仅限中国大陆服务器访问，以实际情况为准。",
  "example": "/gov/hunan/changsha/major-email",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "hunan/changsha/major-email.ts",
  "maintainers": [
    "shansing"
  ],
  "name": "长沙市人民政府",
  "parameters": {},
  "path": "/hunan/changsha/major-email",
  "radar": [
    {
      "source": [
        "wlwz.changsha.gov.cn/webapp/cs2020/email/*"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "wlwz.changsha.gov.cn/webapp/cs2020/email/*"
}
```
