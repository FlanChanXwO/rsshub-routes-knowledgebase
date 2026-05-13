# 深圳市罗湖区人民政府 - 政府信息公开文件

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `深圳市罗湖区人民政府`
- Route Path: `/gov/suzhou/doc`
- Route Name: `政府信息公开文件`
- Example: `/gov/suzhou/doc`
- URL: `www.suzhou.gov.cn/szxxgk/front/xxgk_right.jsp`
- Language: `_None_`
- Categories: `government`
- Maintainers: `EsuRt`
- Source Location: `suzhou/doc.ts`
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
  - `www.suzhou.gov.cn/szxxgk/front/xxgk_right.jsp`
  - `www.suzhou.gov.cn/`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/suzhou/doc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "suzhou/doc.ts",
  "maintainers": [
    "EsuRt"
  ],
  "name": "政府信息公开文件",
  "parameters": {},
  "path": "/suzhou/doc",
  "radar": [
    {
      "source": [
        "www.suzhou.gov.cn/szxxgk/front/xxgk_right.jsp",
        "www.suzhou.gov.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "苏州市政府 - 政策公开文件 - Powered by RSSHub",
      "errorAt": "2025-11-27T04:24:28.818Z",
      "errorMessage": "[GET] \"https://www.suzhou.gov.cn/szxxgk/front/xxgk_right.jsp\": 404 \n[GET] \"https://www.suzhou.gov.cn/szxxgk/front/xxgk_right.jsp\": 404 \n",
      "id": "73327549478375424",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.suzhou.gov.cn/szxxgk/front/xxgk_right.jsp",
      "title": "苏州市政府 - 政策公开文件",
      "type": "feed",
      "url": "rsshub://gov/suzhou/doc"
    }
  ],
  "url": "www.suzhou.gov.cn/szxxgk/front/xxgk_right.jsp"
}
```
