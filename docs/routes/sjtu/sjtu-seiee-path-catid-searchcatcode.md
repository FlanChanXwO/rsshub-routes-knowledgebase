# 上海交通大学 - 电子信息与电气工程学院

## Coverage
`index-only`

## Route
- Namespace: `sjtu`
- Namespace Name: `上海交通大学`
- Route Path: `/sjtu/seiee/:path/:catID?/:searchCatCode?`
- Route Name: `电子信息与电气工程学院`
- Example: `/sjtu/seiee/xzzx_notice_bks`
- URL: `www.sjtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `dzx-dzx`
- Source Location: `seiee/index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `path`: 不含'.html'的最后一部分路径
- `catID`: '本科生人才培养'与'研究生人才培养'的类别ID
- `searchCatCode`: '本科生人才培养'与'研究生人才培养'下类别名


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.seiee.sjtu.edu.cn/:path.html`
- `target`: `/seiee/:path`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/sjtu/seiee/xzzx_notice_bks",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "seiee/index.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "电子信息与电气工程学院",
  "parameters": {
    "catID": "'本科生人才培养'与'研究生人才培养'的类别ID",
    "path": "不含'.html'的最后一部分路径",
    "searchCatCode": "'本科生人才培养'与'研究生人才培养'下类别名"
  },
  "path": "/seiee/:path/:catID?/:searchCatCode?",
  "radar": [
    {
      "source": [
        "www.seiee.sjtu.edu.cn/:path.html"
      ],
      "target": "/seiee/:path"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "团学工作-上海交通大学电子信息与电气工程学院（学部） - Powered by RSSHub",
      "errorAt": "2025-10-29T13:51:19.494Z",
      "errorMessage": "[GET] \"https://www.seiee.sjtu.edu.cn/xsgz_tzgg_txgz.html\": <no response> fetch failed\n",
      "id": "67550208086553600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.seiee.sjtu.edu.cn/xsgz_tzgg_txgz.html",
      "title": "团学工作-上海交通大学电子信息与电气工程学院（学部）",
      "type": "feed",
      "url": "rsshub://sjtu/seiee/xsgz_tzgg_txgz"
    }
  ]
}
```
