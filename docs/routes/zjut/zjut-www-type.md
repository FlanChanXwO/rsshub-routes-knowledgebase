# 浙江工业大学 - 浙江工业大学首页

## Coverage
`index-only`

## Route
- Namespace: `zjut`
- Namespace Name: `浙江工业大学`
- Route Path: `/zjut/www/:type`
- Route Name: `浙江工业大学首页`
- Example: `/zjut/www/4528`
- URL: `www.zjut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `zhullyb`
- Source Location: `www/index.ts`
- Source Module: `_None_`

## Description
| 板块       | 参数       |
| ---------- | ---------- |
| 学术动态   | xsdt\_4662 |
| 三创・人物 | 4527       |
| 通知公告   | 4528       |
| 美誉工大   | 5389       |
| 智库工大   | 5390       |
| 工大校历   | 4520       |
| 校区班车   | xqbc       |

## Parameters
- `type`: 分类，见下表


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
  - `www.zjut.edu.cn/:type/list.htm`
- `target`: `/www/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 板块       | 参数       |\n| ---------- | ---------- |\n| 学术动态   | xsdt\\_4662 |\n| 三创・人物 | 4527       |\n| 通知公告   | 4528       |\n| 美誉工大   | 5389       |\n| 智库工大   | 5390       |\n| 工大校历   | 4520       |\n| 校区班车   | xqbc       |",
  "example": "/zjut/www/4528",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "www/index.ts",
  "maintainers": [
    "zhullyb"
  ],
  "name": "浙江工业大学首页",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/www/:type",
  "radar": [
    {
      "source": [
        "www.zjut.edu.cn/:type/list.htm"
      ],
      "target": "/www/:type"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "通知公告 - 浙江工业大学 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72308822252839936",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zjut.edu.cn/4528",
      "title": "通知公告 - 浙江工业大学",
      "type": "feed",
      "url": "rsshub://zjut/www/4528"
    },
    {
      "description": "学术动态 - 浙江工业大学 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76974843415741440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zjut.edu.cn/xsdt_4662",
      "title": "学术动态 - 浙江工业大学",
      "type": "feed",
      "url": "rsshub://zjut/www/xsdt_4662"
    }
  ],
  "url": "www.zjut.edu.cn"
}
```
