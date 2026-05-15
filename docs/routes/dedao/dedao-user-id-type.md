# 得到 - 用户主页

## Coverage
`index-only`

## Route
- Namespace: `dedao`
- Namespace Name: `得到`
- Route Path: `/dedao/user/:id/:type?`
- Route Name: `用户主页`
- Example: `/dedao/user/VkA5OqLX4RyGxmZRNBMlwBrDaJQ9og`
- URL: `dedao.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `user.tsx`
- Source Module: `_None_`

## Description
| 动态 | 书评 | 视频 |
| ---- | ---- | ---- |
| 0    | 7    | 12   |

## Parameters
- `id`: 用户 id，可在对应用户主页 URL 中找到
- `type`: 类型，见下表，默认为`0`，即动态


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 动态 | 书评 | 视频 |\n| ---- | ---- | ---- |\n| 0    | 7    | 12   |",
  "example": "/dedao/user/VkA5OqLX4RyGxmZRNBMlwBrDaJQ9og",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 205,
  "location": "user.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "用户主页",
  "parameters": {
    "id": "用户 id，可在对应用户主页 URL 中找到",
    "type": "类型，见下表，默认为`0`，即动态"
  },
  "path": "/user/:id/:type?",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "《万维钢·精英日课》主理人: - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65325031453147265",
      "image": "https://piccdn2.umiwi.com/avatar/iget/11359683-1493051027.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://m.igetget.com/native/mine/account#/user/detail?enId=vNBaAbwjq5nMoamqzZ1GLKkzgPXy9o",
      "title": "万维钢的得到主页 - 动态",
      "type": "feed",
      "url": "rsshub://dedao/user/vNBaAbwjq5nMoamqzZ1GLKkzgPXy9o"
    },
    {
      "description": "得到联合创始人: 顺风不浪，逆风不投 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "77758485233487872",
      "image": "https://piccdn2.umiwi.com/avatar/iget/19-1531375237.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://m.igetget.com/native/mine/account#/user/detail?enId=VN0Wo2b7GJAYwMWGMdvgePOam4Zjlz",
      "title": "快刀青衣的得到主页 - 动态",
      "type": "feed",
      "url": "rsshub://dedao/user/VN0Wo2b7GJAYwMWGMdvgePOam4Zjlz"
    }
  ]
}
```
