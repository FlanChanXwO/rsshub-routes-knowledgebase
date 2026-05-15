# 快科技 - 排行

## Coverage
`index-only`

## Route
- Namespace: `mydrivers`
- Namespace Name: `快科技`
- Route Path: `/mydrivers/rank/:range?`
- Route Name: `排行`
- Example: `/mydrivers/rank`
- URL: `m.mydrivers.com/newsclass.aspx`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `rank.ts`
- Source Module: `_None_`

## Description
| 24 小时最热 | 本周最热 | 本月最热 |
| ----------- | -------- | -------- |
| 0           | 1        | 2        |

## Parameters
- `range`: 时间范围，见下表，默认为24小时最热


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
  - `m.mydrivers.com/newsclass.aspx`
- `target`: `/rank`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 24 小时最热 | 本周最热 | 本月最热 |\n| ----------- | -------- | -------- |\n| 0           | 1        | 2        |",
  "example": "/mydrivers/rank",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 39,
  "location": "rank.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "排行",
  "parameters": {
    "range": "时间范围，见下表，默认为24小时最热"
  },
  "path": "/rank/:range?",
  "radar": [
    {
      "source": [
        "m.mydrivers.com/newsclass.aspx"
      ],
      "target": "/rank"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ 'mydrivers.com#1122156' ] to not include 'mydrivers.com#1122156'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "手机驱动之家是驱动之家的手机门户网站，为亿万用户打造一个手机联通世界的超级平台，提供24小时全面及时的中文IT资讯。手机驱动之家触屏版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66732747558908928",
      "image": "https://11.mydrivers.com/m/images/v1/kkj_hearlogo.png",
      "ownerUserId": null,
      "siteUrl": "https://m.mydrivers.com/newsclass.aspx?tid=1001",
      "title": "快科技 - 24小时最热",
      "type": "feed",
      "url": "rsshub://mydrivers/rank"
    },
    {
      "description": "手机驱动之家是驱动之家的手机门户网站，为亿万用户打造一个手机联通世界的超级平台，提供24小时全面及时的中文IT资讯。手机驱动之家触屏版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "122531537836972032",
      "image": "https://11.mydrivers.com/m/images/v1/kkj_hearlogo.png",
      "ownerUserId": null,
      "siteUrl": "https://m.mydrivers.com/newsclass.aspx?tid=1001",
      "title": "快科技 - 24小时最热",
      "type": "feed",
      "url": "rsshub://mydrivers/rank/0"
    }
  ],
  "url": "m.mydrivers.com/newsclass.aspx"
}
```
